# 

 Graphical representation



__Diagram__ 





[![Image:Context.-slices-example.jpg](./Context.-slices-example.jpg)](../Image/Context.-slices-example.jpg.md "Image:Context.-slices-example.jpg")





# 

 General information




|  |  |
| --- | --- |
|  Name  |  Context Slices  |
|  Also known as  |  |
|  Author(s)  |  Chris Welty  |
|  SubmittedBy  | [Chris Welty](http://ontologydesignpatterns.org/wiki/index.php?title=User:Chris_Welty&action=edit&redlink=1 "User:Chris Welty (not yet written)")  |



  





# 

 Description




|  |  |
| --- | --- |
|  Motivation  |  Most information on the web is contextualized somehow, for example information may be believed by a person or organization, it may hold only for some time period, it may have been reported/observed by an individual, etc. There are myriad proposals and logics for context, but none are standards and few have even prototype implementations.  In RDF and other binary relation languages (like object oriented languages and description logics), one typical way to represent that a binary relation holds in some context is to "reify" the relation-holding in the context as an node with a binary relations for the subject, object, and property, and a fourth binary relation to the object representing the context itself. The downside to this approach is the expressive ability of the language to describe the binary relation, especially in the case of description logics, is lost. For example, the ancestor relation is transitive. OWL allows one to express transitivity of a binary relation, but this expressiveness is lost if the statements of the relation are reified. The same would be true for symmetry, reflexivity, etc. One can get the effect of cardinality and range/domain restrictions by reifying a relation as an OWL class (instead of using RDF reification), with properties for the _roles_  (as in the n-ary relations W3C note), but not transitivity etc.  The motivation for context slices is to provide a logical pattern for encoding context information in standard RDF graphs that allows some of the expressiveness of OWL to be used in describing the relations that hold in contexts.  This is a generaliztion of the four dimensional ontology for fluents published in [Welty & Fikes, 2006].  |
|  Aim  |  To encode that a binary relation holds in a context.  |
|  Solution description  |  As shown in the example, the idea of the context slices pattern is, rather than reifying the statement itself, to create a projection of the _relation arguments_  in each context for which some binary relation holds between them.  Take for example the statement "Chris believes Sam is CEO of IBM". Say we already have nodes in some graph representing Sam and IBM.  We create, as shown in the diagram, the context c1 corresponding to Chris' belief, and two nodes representing Chris' belief about Sam and Chris' belief about IBM (shown as Sam@c1 and IBM@c1).  This allows us to represent ceoOf as a binary relation, which seems more natural, and it allows us to use the expressivity of OWL in more ways. We can say of the ceoOf relation that it has an inverse, hasCeo. We can express cardinality, e.g. a company may have only one CEO within a context. We can say that a relation is transitive or symmetric. We can express relation taxonomies in the usual way.  While clearly OWL does not support RDF reification, and so none of this is possible if statement reification is used, as mentioned above a more standard way of representing this kind of information (including time, belief, knowledge, etc.) is to create an OWL class that represents the relation holding, with properties for the arguments. This approach makes it possible to express global but not local range and domain constraints, global but not local cardinality, and symmetry.  Note that the ContextualProjection class should be considered disjoint with any of the classes in an ontology that have projections.  |
|  Elements  |  As shown in the diagram, the pattern uses two predefined classes, cs:ContextualProjection and cs:Context. It uses two predefined properties, cs:projectionOf (ContextualProjection x TOP), and cs:hasContext (cs:ContextualProjection x cs:Context). Properties that hold in a context can extend the property cs:contextualProperty.  |
|  Implementation  |  In OWL functional syntax: ```Ontology(<[http://example.org/ContextSlices](http://example.org/ContextSlices "http://example.org/ContextSlices")>  Annotation(owl:versionInfo "1.0"@en)  Annotation(rdfs:label "Context slices ontology logical pattern"@en)  Declaration(Class(cs:Context))  DisjointClasses(cs:Context cs:ContextualProjection)  Declaration(Class(cs:ContextualProjection))  SubClassOf(cs:ContextualProjection ObjectAllValuesFrom(cs:hasContext cs:Context))  SubClassOf(cs:ContextualProjection ObjectExactCardinality(1 cs:hasContext))  SubClassOf(cs:ContextualProjection ObjectExactCardinality(1 cs:projectionOf))  DisjointClasses(cs:ContextualProjection cs:Context)  Declaration(ObjectProperty(cs:contextualProperty))  ObjectPropertyDomain(cs:contextualProperty cs:ContextualProjection)  ObjectPropertyRange(cs:contextualProperty cs:ContextualProjection)  Declaration(ObjectProperty(cs:hasContext))  FunctionalObjectProperty(cs:hasContext)  ObjectPropertyDomain(cs:hasContext cs:ContextualProjection)  Declaration(ObjectProperty(cs:projectionOf))  FunctionalObjectProperty(cs:projectionOf)  ObjectPropertyDomain(cs:projectionOf cs:ContextualProjection) )``` In RDF/XML: ```<?xml version="1.0" encoding="UTF-8"?><!DOCTYPE rdf:RDF [  <!ENTITY owl "[http://www.w3.org/2002/07/owl#](http://www.w3.org/2002/07/owl# "http://www.w3.org/2002/07/owl#")">  <!ENTITY rdf "[http://www.w3.org/1999/02/22-rdf-syntax-ns#](http://www.w3.org/1999/02/22-rdf-syntax-ns# "http://www.w3.org/1999/02/22-rdf-syntax-ns#")">  <!ENTITY rdfs "[http://www.w3.org/2000/01/rdf-schema#](http://www.w3.org/2000/01/rdf-schema# "http://www.w3.org/2000/01/rdf-schema#")">  <!ENTITY xsd "[http://www.w3.org/2001/XMLSchema#](http://www.w3.org/2001/XMLSchema# "http://www.w3.org/2001/XMLSchema#")">]><rdf:RDF xml:base=""         xmlns:owl="&owl;"         xmlns:rdf="&rdf;"         xmlns:rdfs="&rdfs;">   <owl:Ontology rdf:about="">    <rdfs:label xml:lang="en">Context slices ontology logical  pattern</rdfs:label>    <owl:versionInfo xml:lang="en">1.0</owl:versionInfo>  </owl:Ontology>  <owl:Class rdf:about="ContextualProjection">    <rdfs:comment rdf:datatype="&xsd;string">A contextual projection or slice of an entity or event.  The context defines the contextual extent of the slice.  If any relations hold in a context, they must be to other slices of the same context (there is no way to enforce this constraint in OWL).    </rdfs:comment>    <rdfs:subClassOf>      <owl:Restriction>        <owl:cardinality rdf:datatype="&xsd;nonNegativeInteger">1</owl:cardinality>        <owl:onProperty rdf:resource="#hasContext"/>      </owl:Restriction>    </rdfs:subClassOf>    <rdfs:subClassOf>      <owl:Restriction>        <owl:cardinality rdf:datatype="&xsd;nonNegativeInteger">1</owl:cardinality>        <owl:onProperty rdf:resource="#projectionOf"/>      </owl:Restriction>    </rdfs:subClassOf>    <rdfs:subClassOf>      <owl:Restriction>        <owl:allValuesFrom rdf:resource="Context"/>        <owl:onProperty rdf:resource="#hasContext"/>      </owl:Restriction>    </rdfs:subClassOf>    <owl:disjointWith rdf:resource="Context"/>  </owl:Class>  <owl:Class rdf:about="Context">    <rdfs:comment rdf:datatype="&xsd;string">It is intended that this class  should be equatedwith whatever class represents contexts, with possibly subclasses for different kinds such as BeliefContext, TemporalInterval, etc.</rdfs:comment>    <owl:disjointWith rdf:resource="#ContextualProjection"/>  </owl:Class>  <owl:ObjectProperty rdf:about="#contextualProperty">    <rdfs:comment rdf:datatype="&xsd;string">A property that holds in a  context.</rdfs:comment>    <rdfs:domain rdf:resource="#ContextualProjection"/>    <rdfs:range rdf:resource="#ContextualProjection"/>  </owl:ObjectProperty>  <owl:FunctionalProperty rdf:about="#hasContext">    <rdf:type rdf:resource="&owl;ObjectProperty"/>    <rdfs:comment rdf:datatype="&xsd;string">The relation from a  ContextualProjection to the context in which some property holds</rdfs:comment>    <rdfs:domain rdf:resource="#ContextualProjection"/>  </owl:FunctionalProperty>  <owl:FunctionalProperty rdf:about="#projectionOf">    <rdf:type rdf:resource="&owl;ObjectProperty"/>    <rdfs:comment rdf:datatype="&xsd;string">The entity or event that a  context slice is a slice of.</rdfs:comment>    <rdfs:domain rdf:resource="#ContextualProjection"/>  </owl:FunctionalProperty></rdf:RDF>``` |
|  Reusable component  |  |
|  Component type  |  |



  





# 

 Example




|  |  |
| --- | --- |
|  Problem example  |  Here is a simple ontology that extends the logical pattern ontology and represents the statement, "Chris believes Sam is CEO of IBM". ```<?xml version="1.0"?><rdf:RDF    xmlns:rdf="[http://www.w3.org/1999/02/22-rdf-syntax-ns#](http://www.w3.org/1999/02/22-rdf-syntax-ns# "http://www.w3.org/1999/02/22-rdf-syntax-ns#")"    xmlns:xsd="[http://www.w3.org/2001/XMLSchema#](http://www.w3.org/2001/XMLSchema# "http://www.w3.org/2001/XMLSchema#")"    xmlns:rdfs="[http://www.w3.org/2000/01/rdf-schema#](http://www.w3.org/2000/01/rdf-schema# "http://www.w3.org/2000/01/rdf-schema#")"    xmlns:cs="[http://www.example.org/ContextSlices#](http://www.example.org/ContextSlices# "http://www.example.org/ContextSlices#")"    xmlns:owl="[http://www.w3.org/2002/07/owl#](http://www.w3.org/2002/07/owl# "http://www.w3.org/2002/07/owl#")"    xmlns:daml="[http://www.daml.org/2001/03/daml+oil#](http://www.daml.org/2001/03/daml+oil# "http://www.daml.org/2001/03/daml+oil#")"    xmlns:dc="[http://purl.org/dc/elements/1.1/](http://purl.org/dc/elements/1.1/ "http://purl.org/dc/elements/1.1/")"  xml:base="[http://www.example.org/ContextSlicesExample](http://www.example.org/ContextSlicesExample "http://www.example.org/ContextSlicesExample")">  <owl:Ontology rdf:about="">    <rdfs:label xml:lang="en">Example of using context slices</rdfs:label>    <owl:versionInfo xml:lang="en">1.0</owl:versionInfo>  </owl:Ontology>  <owl:Class rdf:ID="Company"/>  <owl:Class rdf:ID="Person"/>  <owl:Class rdf:ID="BeliefContext">    <rdfs:subClassOf rdf:resource="[http://www.example.org/ContextSlices#Context](http://www.example.org/ContextSlices#Context "http://www.example.org/ContextSlices#Context")"/>  </owl:Class>  <owl:ObjectProperty rdf:ID="believedBy"/>  <owl:ObjectProperty rdf:ID="ceoOf">    <rdfs:subPropertyOf>      <owl:ObjectProperty rdf:ID="contextualProperty"/>    </rdfs:subPropertyOf>  </owl:ObjectProperty>  <Person rdf:ID="Sam"/>  <Person rdf:ID="Chris"/>  <Company rdf:ID="IBM"/>  <BeliefContext rdf:ID="c1">    <believedBy rdf:resource="#Chris"/>  </BeliefContext>  <cs:ContextualProjection rdf:about="#IBM$c1">    <cs:hasContext rdf:resource="#c1"/>    <cs:projectionOf rdf:resource="#IBM"/>  </cs:ContextualProjection>  <cs:ContextualProjection rdf:about="#Sam$c1">    <cs:hasContext rdf:resource="#c1"/>    <ceoOf rdf:resource="#IBM$c1"/>    <cs:projectionOf rdf:resource="#Sam"/>  </cs:ContextualProjection></rdf:RDF>``` |
|  Pattern solution example  |  |
|  Consequences  |  |



  





# 

 Pattern reference




|  |  |
| --- | --- |
|  Origin  |  This logical pattern is a generalization of the 4D "Reusable Ontology for Fluents in OWL", presented at FOIS-2006.  Welty, Chris and Richard E. Fikes. 2006. A Reusable Ontology for Fluents in OWL. In Bennet and Fellbaum, eds., _Proceedings of the Fourth International Conference on Formal Ontology in Information Systems_  . IOS Press. See [http://www.booksonline.iospress.nl/Content/View.aspx?piid=2209](http://www.booksonline.iospress.nl/Content/View.aspx?piid=2209 "http://www.booksonline.iospress.nl/Content/View.aspx?piid=2209")  It has been suggestion in [Reviews:ValentinaPresutti\_about\_Context\_Slices](../Reviews/ValentinaPresutti_about_Context_Slices.md "Reviews:ValentinaPresutti about Context Slices")  that this may be a specialization of [Submissions:DescriptionAndSituation](../DescriptionAndSituation/DescriptionAndSituation.md "Submissions:DescriptionAndSituation")  . The DandS pattern is described in a bit of distributed way across four or so patterns, lacks an example, and uses terms like "description" and "concept" in an unfamiliar way, so I am unable to understand it. The main objective of the CS pattern is to form projections of the objects into the contexts, not the relations, which is I think what DandS does.  |
|  Known use  |  |
|  Reference  |  |
|  Related ODP  |  |
|  Used in combination with  |  |
|  Test  |  |



  





# 

 Additional information



# 

 Scenarios




__Scenarios about Context Slices__ 


 No scenario is added to this Content OP.
 




# 

 Reviews




__Reviews about Context Slices__ 



|  Review article  | [Posted on](../Property/CreationDate.md "Property:CreationDate")  | [About revision (current is 10228)](../Property/ReviewAboutVersion.md "Property:ReviewAboutVersion")  |
| --- | --- | --- |
| [VojtechSvatek about Context Slices](../Reviews/VojtechSvatek_about_Context_Slices.md "Reviews:VojtechSvatek about Context Slices")  |  2455456  16 September 2010  |  10058  10,058  |
| [EnricoMotta about Context Slices](../Reviews/EnricoMotta_about_Context_Slices.md "Reviews:EnricoMotta about Context Slices")  |  2455459  19 September 2010  |  10119  10,119  |
| [ValentinaPresutti about Context Slices](../Reviews/ValentinaPresutti_about_Context_Slices.md "Reviews:ValentinaPresutti about Context Slices")  |  2455463  23 September 2010  |  10119  10,119  |



 This revision (revision ID
 __10228__ 
 ) takes in account the reviews:
 [ValentinaPresutti about Context Slices](../Reviews/ValentinaPresutti_about_Context_Slices.md "Reviews:ValentinaPresutti about Context Slices") 




 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Context_Slices&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Context_Slices&action=evaluation") 





  





# 

 Modeling issues




__Modeling issues about Context Slices__ 


 There is no Modeling issue related to this proposal.
 




  





# 

 References



  






|  |  Submission to event [WOP:2010](../WOP/2010.md "WOP:2010")  |
| --- | --- |
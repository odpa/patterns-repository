#  Graphical representation


__Diagram__




[![Image:componency.jpg](./Componency.jpg)](../Image/Componency.jpg.md "Image:componency.jpg")




#  General description




|  |  |
| --- | --- |
|  Name: |  componency |
|  Submitted by: | [ValentinaPresutti](../User/ValentinaPresutti.md "User:ValentinaPresutti") |
|  Also Known As: |  composition |
|  Intent: |  To represent (non-transitively) that objects either are proper parts of other objects, or have properparts. |
|  Domains: | [Parts and Collections](../Community/Parts_and_Collections.md "Community:Parts and Collections") |
|  Competency Questions: | <li> What is this object component of? What are the components of this object?</li> |
|  Solution description: |  - |
|  Reusable OWL Building Block: | [http://www.ontologydesignpatterns.org/cp/owl/componency.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=http://www.ontologydesignpatterns.org/cp/owl/componency.owl&message=OWL building block&from_page_id=271&update=) (877) |
|  Consequences: |  This Content OP allows designers to represent part-whole relations. It allows to distinguish between parts and proper parts. Relation of proper part _is not transitive_, and implies a simple  [part of](../PartOf/PartOf.md "Submissions:PartOf") relation, which is _transitive_. Temporal indexing is not expressible. To solve this issue see the  [time indexed part of](../TimeIndexedPartOf/TimeIndexedPartOf.md "Submissions:TimeIndexedPartOf") Content OP. |
|  Scenarios: |  The turbine is a proper part of the engine, both are parts of a car. Furthermore, the engine and the battery are proper parts of the car. |
|  Known Uses: |  |
|  Web References: |  |
|  Other References: |  |
|  Examples (OWL files): |  |
|  Extracted From: | <li><a class="external free" href="http://www.loa-cnr.it/ontologies/DUL.owl" rel="nofollow" title="http://www.loa-cnr.it/ontologies/DUL.owl">http://www.loa-cnr.it/ontologies/DUL.owl</a></li> |
|  Reengineered From: |  |
|  Has Components: |  |
|  Specialization Of: | <li><a href="../PartOf/PartOf.md" title="Submissions:PartOf">Submissions:PartOf</a></li> |
|  Related CPs: |  |


  




#  Elements


_The __Componency__ Content OP locally defines the following ontology elements:_




[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __Object__ (owl:Class) Any physical, social, or mental object, or a substance. Can be component only of other objects, and can be composed of only other objects. 



 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[Object](../Object/Object.md "Submissions:Componency/Object") page_

[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasComponent__ (owl:ObjectProperty) The  [hasPart](./An_Ontology_Design_Pattern_for_Activity_Reasoning/hasPart.md "Submissions:PartOf/hasPart") relation without transitivity, holding between an  [Object](../Object/Object.md "Submissions:Componency/Object") (the system) and another (the component), and assuming a Design that structures the system Object. 
The componency Content OP uses the transitive reduction  [logical pattern](../Category/LogicalOP.md "Category:LogicalOP") to preserve transitive on the superproperty from the [part of](../PartOf/PartOf.md "Submissions:PartOf") Content OP. In practice, the [part of](../PartOf/PartOf.md "Submissions:PartOf") acts here as the transitive reduction of the  __componency__ Content OP. 



 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasComponent](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/hasComponent.md "Submissions:Componency/hasComponent") page_

[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isComponentOf__ (owl:ObjectProperty) The inverse of the  [hasComponent](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/hasComponent.md "Submissions:Componency/hasComponent")  object property. 



 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isComponentOf](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/isComponentOf.md "Submissions:Componency/isComponentOf") page_
#  Additional information


This Content OP defines the above elements, it also includes the elements of  [part of](../PartOf/PartOf.md "Submissions:PartOf") Content OP.



#  Scenarios



__Scenarios about Componency__
No scenario is added to this Content OP.




#  Reviews



__Reviews about Componency__
There is no review about this proposal.
This revision (revision ID __9077__) takes in account the reviews: none


Other info at [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Componency&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Componency&action=evaluation")




  




#  Modeling issues



__Modeling issues about Componency__
There is no Modeling issue related to this proposal.




  




#  References
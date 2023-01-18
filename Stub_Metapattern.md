# 

 Graphical representation



__Diagram__ 





[![Image:Stub-metapattern.png](../images/c/cd/Stub-metapattern.png)](../Image/Stub-metapattern.png "Image:Stub-metapattern.png")





# 

 General information




|  |  |
| --- | --- |
|  Name  |  Stub Metapattern  |
|  Also known as  |  |
|  Author(s)  |  Adila Krisnadhi, Pascal Hitzler  |
|  SubmittedBy  | [AdilaKrisnadhi](../User/AdilaKrisnadhi "User:AdilaKrisnadhi")  |



  





# 

 Description




|  |  |
| --- | --- |
|  Motivation  |  When modeling an ontology, one of the issues to be addressed is that of granularity: To what detail should the ontology represent the notions it captures? Traditionally, this issue is resolved by looking at a concise definition of the use cases, e.g. by means of competency questions. As a result of this, some parts of the ontology may be modeled in a rather fine-grained manner, while other parts remain relatively coarse.  A straightforward handling of differing granularity requirements in different parts of an ontology can make it more difficult to repurpose or extend the ontology, or to use it in an ontology-driven data integration setting. The reason is that because one is often faced with a situation where (s)he has to decide whether to represent a notion as a string literal value or an ontology entity such as a class. Choosing one over the other introduces a commitment that one may regret later on.  For example, when modeling a location, one could use the location name as a string or model it as a possibly full-blown pattern for the notion of Place. Choosing the former may prevent future use case of data enrichment, e.g., for expressing co-location (as one cannot use owl:sameAs relation between two strings). Choosing the latter means committing to a particular way of modeling Place, which may not necessarily be desirable in the future.  This pattern provides a way to solve this problem is to essentially keep both in the model, i.e., by including the literal value in the model, while employing a very minimalistic pattern for the notion. The latter is realized only as a single class.  |
|  Aim  |  The aim of this metapattern is to act as a type of placeholder for future extensions of an ontology in cases where a more fine-grained modeling would currently be counterproductive, but future extensions may call for more details.  |
|  Solution description  |  The solution is a metapattern. That is, it uses one "variable" class and two "variable" properties. The intention here is that when one wishes to use this metapattern, (s)he needs to instantiate the "variable" class and properties into actual class and properties. See Example section for a more concrete example.  |
|  Elements  |  Entities and variable entities: <li>       owl:Thing      </li><li>       xsd:string      </li><li>       variable class: &lt;ClassName&gt;      </li><li>       variable object property: hasAssociated&lt;ClassName&gt;      </li><li>       variable data property: &lt;ClassName&gt;KnownAs      </li> Axiom patterns (in Manchester Syntax): <li>       hasAssociated&lt;ClassName&gt; Range &lt;ClassName&gt;      </li><li>       &lt;ClassName&gt;KnownAs Range xsd:string      </li><li>       &lt;ClassName&gt;KnownAs some xsd:string SubClassOf: &lt;ClassName&gt;      </li><li>       &lt;ClassName&gt; SubClassOf: &lt;ClassName&gt;KnownAs some xsd:string      </li> |
|  Implementation  |  |
|  Reusable component  |  |
|  Component type  |  |



  





# 

 Example




|  |  |
| --- | --- |
|  Problem example  |  One wishes to instantiate the Stub Metapattern for representing the notion of Place. To do it, the following steps need to be done in all of the axiom patterns. <li>       Replace the variable class &lt;ClassName&gt; with the class Place      </li><li>       Replace the variable object property hasAssociated&lt;ClassName&gt; with hasAssociatedPlace      </li><li>       Replace the variable data property &lt;ClassName&gt;KnownAs with PlaceKnownAs      </li><li>       If desired, the properties may be renamed to something more appropriate with the problem at hand, e.g., rename PlaceKnownAs into placeKnownAs if CamelCase naming convention is used.      </li>[Image:Stub-metapattern-instantiationexample.png](../Image/Stub-metapattern-instantiationexample.png "Image:Stub-metapattern-instantiationexample.png") |
|  Pattern solution example  |  |
|  Consequences  |  A concrete minimalistic pattern for Place is obtained, which already facilitates the use of both URI and literal value to identify a particular place/location.  |



  





# 

 Pattern reference




|  |  |
| --- | --- |
|  Origin  |  Adila Krisnadhi, Pascal Hitzler. The Stub Metapattern. Under review at WOP 2016.  |
|  Known use  |  |
|  Reference  |  |
|  Related ODP  |  |
|  Used in combination with  |  |
|  Test  |  |



# 

 Additional information



# 

 Scenarios




__Scenarios about Stub Metapattern__ 


 No scenario is added to this Content OP.
 




# 

 Reviews




__Reviews about Stub Metapattern__ 


 There is no review about this proposal.
This revision (revision ID
 __12798__ 
 ) takes in account the reviews: none
 



 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Stub_Metapattern&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Stub_Metapattern&action=evaluation") 





  





# 

 Modeling issues




__Modeling issues about Stub Metapattern__ 


 There is no Modeling issue related to this proposal.
 




  





# 

 References



  






|  |  Submission to event [WOP:2016](../WOP/2016.1 "WOP:2016")  |
| --- | --- |
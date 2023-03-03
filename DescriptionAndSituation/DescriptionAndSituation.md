__Diagram__ 
_(this article has no graphical representation)_ 




# 

 General description




|  |  |
| --- | --- |
|  Name:  |  DescriptionAndSituation  |
|  Submitted by:  | [AldoGangemi](../User/AldoGangemi.md "User:AldoGangemi")  |
|  Also Known As:  |  |
|  Intent:  |  |
|  Domains:  |  |
|  Competency Questions:  |  |
|  Solution description:  |  |
|  Reusable OWL Building Block:  | [http://www.ontologydesignpatterns.org/cp/owl/descriptionandsituation.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=http://www.ontologydesignpatterns.org/cp/owl/descriptionandsituation.owl&message=OWL building block&from_page_id=2271&update=)  (836)  |
|  Consequences:  |  |
|  Scenarios:  |  |
|  Known Uses:  |  |
|  Web References:  |  |
|  Other References:  |  |
|  Examples (OWL files):  |  |
|  Extracted From:  | <li><a class="external free" href="http://www.ontologydesignpatterns.org/ont/dul/DUL.owl" rel="nofollow" title="http://www.ontologydesignpatterns.org/ont/dul/DUL.owl">        http://www.ontologydesignpatterns.org/ont/dul/DUL.owl       </a></li> |
|  Reengineered From:  |  |
|  Has Components:  | <li><a href="../Description/Description.md" title="Submissions:Description">        Submissions:Description       </a></li><li><a href="../Classification/Classification.md" title="Submissions:Classification">        Submissions:Classification       </a></li><li><a href="./DescriptionAndSituation.md" title="Submissions:Situation">        Submissions:Situation       </a></li> |
|  Specialization Of:  |  |
|  Related CPs:  |  |



  





# 

 Elements



_The
 __DescriptionAndSituation__ 
 Content OP locally defines the following ontology elements:_ 





[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__describes__ 
 (owl:ObjectProperty) The relation between a Description and an Entity : a Description gives a unity to a Collection of parts (the components), or constituents, by assigning a Role to each of them in the context of a whole Object (the system).
 
 A same Entity can be given different descriptions, for example, an old cradle can be given a unifying Description based on the original aesthetic design, the functionality it was built for, or a new aesthetic functionality in which it can be used as a flower pot.
 



[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[describes](./DescriptionAndSituation/describes.md "Submissions:DescriptionAndSituation/describes") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__isDescribedBy__ 
 (owl:ObjectProperty) The relation between any Thing and a Description: a Description gives a unity to a Collection of parts (the components), or constituents, by assigning a Role to each of them in the context of a whole Object (the system).
 
 A same Thing can be given different descriptions, for example, an old cradle can be given a unifying Description based on the original aesthetic design, the functionality it was built for, or a new aesthetic functionality in which it can be used as a flower pot.
 



[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[isDescribedBy](./DescriptionAndSituation/isDescribedBy.md "Submissions:DescriptionAndSituation/isDescribedBy") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__isSatisfiedBy__ 
 (owl:ObjectProperty) A relation between a Situation and a Description, e.g. the execution of a Plan satisfies that plan.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[isSatisfiedBy](./BasicPlan/isSatisfiedBy.md "Submissions:DescriptionAndSituation/isSatisfiedBy") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__satisfies__ 
 (owl:ObjectProperty) A relation between a Situation and a Description, e.g. the execution of a Plan satisfies that plan.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[satisfies](./BasicPlan/satisfies.md "Submissions:DescriptionAndSituation/satisfies") 
 page_ 


  





# 

 Scenarios




__Scenarios about DescriptionAndSituation__ 


 No scenario is added to this Content OP.
 




# 

 Reviews




__Reviews about DescriptionAndSituation__ 


 There is no review about this proposal.
This revision (revision ID
 __8200__ 
 ) takes in account the reviews: none
 



 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:DescriptionAndSituation&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:DescriptionAndSituation&action=evaluation") 





# 

 Modeling issues




__Modeling issues about DescriptionAndSituation__ 



|  Modeling issue  | [Competency question](../Property/CompetencyQuestion.md "Property:CompetencyQuestion")  | [Domains](../Property/Domain.md "Property:Domain")  |
| --- | --- | --- |
| [Situation classification](../Community/Situation_classification.md "Community:Situation classification")  |  What situations satisfy a certain description? What descriptions can be (partly) satisfied by that situation? What situations (partly) satisfying a certain description can emerge out of this dataset?  |  |




 The Description and Situation content ontology design pattern. This CP represents conceptualizations i.e., descriptions, and corresponding groundings i.e., situations. The pattern is extracted from DOLCE+DnS Ultralite by partial cloning of elements, and is composed of three other CPs: description, situation, and classification.
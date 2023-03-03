# 

 Graphical representation



__Diagram__ 





[![Image:TimeIndexedSituation.png](./TimeIndexedSituation.png)](../Image/TimeIndexedSituation.png.md "Image:TimeIndexedSituation.png")





# 

 General description




|  |  |
| --- | --- |
|  Name:  |  TimeIndexedSituation  |
|  Submitted by:  | [AldoGangemi](../User/AldoGangemi.md "User:AldoGangemi")  |
|  Also Known As:  |  |
|  Intent:  |  To represent time indexed situations.  |
|  Domains:  | [General](../Community/General.md "Community:General")  |
|  Competency Questions:  | <li>       At what time did a certain situation occur?      </li><li>       What situations occurred at a certain time?      </li> |
|  Solution description:  |  This pattern adds a time specification (the [Time interval](../SmartHome_TimeInterval/SmartHome_TimeInterval.md "Submissions:TimeInterval")  pattern) to the [Situation](./TimeIndexedSituation.md "Submissions:Situation")  pattern, in order to provide a handy solution to many cases.  |
|  Reusable OWL Building Block:  | [http://ontologydesignpatterns.org/cp/owl/timeindexedsituation.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=http://ontologydesignpatterns.org/cp/owl/timeindexedsituation.owl&message=OWL building block&from_page_id=2150&update=)  (847)  |
|  Consequences:  |  We can represent situations that have an explicit time parameter.  In principle, this can be done already with the Situation pattern, but this provides a handy composition with the TimeInterval pattern.  |
|  Scenarios:  |  Mustafa's address in 2005 was in Brussels  |
|  Known Uses:  |  |
|  Web References:  |  |
|  Other References:  |  |
|  Examples (OWL files):  |  |
|  Extracted From:  |  |
|  Reengineered From:  |  |
|  Has Components:  | <li><a href="../SmartHome_TimeInterval/SmartHome_TimeInterval.md" title="Submissions:TimeInterval">        Submissions:TimeInterval       </a></li> |
|  Specialization Of:  | <li><a href="./TimeIndexedSituation.md" title="Submissions:Situation">        Submissions:Situation       </a></li> |
|  Related CPs:  | <li><a href="../Time_indexed_participation/Time_indexed_participation.md" title="Submissions:Time indexed participation">        Submissions:Time indexed participation       </a></li><li><a href="../TimeIndexedClassification/TimeIndexedClassification.md" title="Submissions:TimeIndexedClassification">        Submissions:TimeIndexedClassification       </a></li> |



  





# 

 Elements



_The
 __TimeIndexedSituation__ 
 Content OP locally defines the following ontology elements:_ 





[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__atTime__ 
 (owl:ObjectProperty)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[atTime](./Pollution/atTime.md "Submissions:TimeIndexedSituation/atTime") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__forEntity__ 
 (owl:ObjectProperty)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[forEntity](./TimeIndexedSituation/forEntity.md "Submissions:TimeIndexedSituation/forEntity") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__hasTimeIndexedSetting__ 
 (owl:ObjectProperty)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[hasTimeIndexedSetting](./TimeIndexedSituation/hasTimeIndexedSetting.md "Submissions:TimeIndexedSituation/hasTimeIndexedSetting") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__isTimeIndexFor__ 
 (owl:ObjectProperty)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[isTimeIndexFor](./TimeIndexedSituation/isTimeIndexFor.md "Submissions:TimeIndexedSituation/isTimeIndexFor") 
 page_ 



[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__TimeIndexedSituation__ 
 (owl:Class) A Situation that is explicitly indexed at some time for at least one entity.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[TimeIndexedSituation](./TimeIndexedSituation.md "Submissions:TimeIndexedSituation/TimeIndexedSituation") 
 page_ 


# 

 Additional information



 A generic pattern usable for all situations that require a temporal indexing.
 



# 

 Scenarios




__Scenarios about TimeIndexedSituation__ 


 No scenario is added to this Content OP.
 




# 

 Reviews




__Reviews about TimeIndexedSituation__ 


 There is no review about this proposal.
This revision (revision ID
 __9135__ 
 ) takes in account the reviews: none
 



 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:TimeIndexedSituation&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:TimeIndexedSituation&action=evaluation") 





  





# 

 Modeling issues




__Modeling issues about TimeIndexedSituation__ 


 There is no Modeling issue related to this proposal.
 




  





# 

 References
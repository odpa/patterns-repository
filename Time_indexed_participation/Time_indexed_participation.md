# 

 Graphical representation



__Diagram__ 





[![Image:TimeIndexedParticipation.png](./TimeIndexedParticipation.png)](../Image/TimeIndexedParticipation.png.md "Image:TimeIndexedParticipation.png")





# 

 General description




|  |  |
| --- | --- |
|  Name:  |  Time indexed participation  |
|  Submitted by:  | [AldoGangemi](../User/AldoGangemi.md "User:AldoGangemi")  |
|  Also Known As:  |  |
|  Intent:  |  To represent participants in events at some time,To represent participants in parts of events.  |
|  Domains:  | [General](../Community/General.md "Community:General")  |
|  Competency Questions:  | <li>       When something participated in some event?      </li><li>       At what time an event had some participant?      </li> |
|  Solution description:  |  This pattern uses the [Situation](../DescriptionAndSituation/DescriptionAndSituation.md "Submissions:Situation")  pattern to add temporal information to participation of objects into events.  |
|  Reusable OWL Building Block:  | [http://ontologydesignpatterns.org/cp/owl/timeindexedparticipation.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=http://ontologydesignpatterns.org/cp/owl/timeindexedparticipation.owl&message=OWL building block&from_page_id=1151&update=)  (737)  |
|  Consequences:  |  We can represent participation relations with time. This enables participations at different times as well as partial participations in events.  However, this pattern focuses on participation of one entity in one event. If complex events need to be represented (with subevents, more participants and times, etc.), a partonomic structure must be introduced, e.g. by creating a new pattern that composes TimeIndexedParticipation with PartOf.  |
|  Scenarios:  |  This morning I've prepared my coffee and had my fingers burnt, The football match lasted only ten minutes for Totti  |
|  Known Uses:  |  |
|  Web References:  |  |
|  Other References:  |  |
|  Examples (OWL files):  |  |
|  Extracted From:  |  |
|  Reengineered From:  |  |
|  Has Components:  | <li><a href="../Nary_Participation/Nary_Participation.md" title="Submissions:Participation">        Submissions:Participation       </a></li><li><a href="../Region/Region.md" title="Submissions:Region">        Submissions:Region       </a></li> |
|  Specialization Of:  | <li><a href="../TimeIndexedSituation/TimeIndexedSituation.md" title="Submissions:TimeIndexedSituation">        Submissions:TimeIndexedSituation       </a></li> |
|  Related CPs:  | <li><a href="../Nary_Participation/Nary_Participation.md" title="Submissions:Participation">        Submissions:Participation       </a></li><li><a href="../Time_indexed_person_role/Time_indexed_person_role.md" title="Submissions:Time indexed person role">        Submissions:Time indexed person role       </a></li> |



  





# 

 Elements



_The
 __Time indexed participation__ 
 Content OP locally defines the following ontology elements:_ 





[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__includesEvent__ 
 (owl:ObjectProperty) A relation between situations and events, e.g. 'this morning I've prepared my coffee and had my fingers burnt' (i.e.: the preparation of my coffee this morning included a burning of my fingers).
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[includesEvent](./Time_indexed_participation/includesEvent.md "Submissions:Time indexed participation/includesEvent") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__includesObject__ 
 (owl:ObjectProperty) A relation between situations and objects, e.g. 'this morning I've prepared my coffee and had my fingers burnt' (i.e.: the preparation of my coffee this morning included me).
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[includesObject](./BasicPlanExecution/includesObject.md "Submissions:Time indexed participation/includesObject") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__isEventIncludedIn__ 
 (owl:ObjectProperty)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[isEventIncludedIn](./Time_indexed_participation/isEventIncludedIn.md "Submissions:Time indexed participation/isEventIncludedIn") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__isObjectIncludedIn__ 
 (owl:ObjectProperty)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[isObjectIncludedIn](./BasicPlanExecution/isObjectIncludedIn.md "Submissions:Time indexed participation/isObjectIncludedIn") 
 page_ 



[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__TimeIndexedParticipation__ 
 (owl:Class) A Situation that represents participation of Object(s) in Event(s) at some Time.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[TimeIndexedParticipation](./Time_indexed_participation/TimeIndexedParticipation.md "Submissions:Time indexed participation/TimeIndexedParticipation") 
 page_ 


# 

 Additional information



 A time-indexed pattern for participation
 



# 

 Scenarios




__Scenarios about Time indexed participation__ 


 No scenario is added to this Content OP.
 




# 

 Reviews




__Reviews about Time indexed participation__ 


 There is no review about this proposal.
This revision (revision ID
 __9130__ 
 ) takes in account the reviews: none
 



 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Time_indexed_participation&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Time_indexed_participation&action=evaluation") 





  





# 

 Modeling issues




__Modeling issues about Time indexed participation__ 


 There is no Modeling issue related to this proposal.
 




  





# 

 References
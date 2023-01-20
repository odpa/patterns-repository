# 

 Graphical representation



__Diagram__ 





[![Image:TimeIndexedParticipation.png](public/images/7/73/TimeIndexedParticipation.png)](../Image/TimeIndexedParticipation.png "Image:TimeIndexedParticipation.png")





# 

 General description




|  |  |
| --- | --- |
|  Name:  |  Time indexed participation  |
|  Submitted by:  | [AldoGangemi](../User/AldoGangemi "User:AldoGangemi")  |
|  Also Known As:  |  |
|  Intent:  |  To represent participants in events at some time,To represent participants in parts of events.  |
|  Domains:  | [General](../Community/General "Community:General")  |
|  Competency Questions:  | <li>       When something participated in some event?      </li><li>       At what time an event had some participant?      </li> |
|  Solution description:  |  This pattern uses the [Situation](../Submissions/Situation "Submissions:Situation")  pattern to add temporal information to participation of objects into events.  |
|  Reusable OWL Building Block:  | [http://ontologydesignpatterns.org/cp/owl/timeindexedparticipation.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=http://ontologydesignpatterns.org/cp/owl/timeindexedparticipation.owl&message=OWL building block&from_page_id=1151&update=)  (737)  |
|  Consequences:  |  We can represent participation relations with time. This enables participations at different times as well as partial participations in events.  However, this pattern focuses on participation of one entity in one event. If complex events need to be represented (with subevents, more participants and times, etc.), a partonomic structure must be introduced, e.g. by creating a new pattern that composes TimeIndexedParticipation with PartOf.  |
|  Scenarios:  |  This morning I've prepared my coffee and had my fingers burnt, The football match lasted only ten minutes for Totti  |
|  Known Uses:  |  |
|  Web References:  |  |
|  Other References:  |  |
|  Examples (OWL files):  |  |
|  Extracted From:  |  |
|  Reengineered From:  |  |
|  Has Components:  | <li><a href="Submissions%253AParticipation.html" title="Submissions:Participation">        Submissions:Participation       </a></li><li><a href="Submissions%253ARegion.html" title="Submissions:Region">        Submissions:Region       </a></li> |
|  Specialization Of:  | <li><a href="Submissions%253ATimeIndexedSituation.html" title="Submissions:TimeIndexedSituation">        Submissions:TimeIndexedSituation       </a></li> |
|  Related CPs:  | <li><a href="Submissions%253AParticipation.html" title="Submissions:Participation">        Submissions:Participation       </a></li><li><a href="Submissions%253ATime_indexed_person_role.html" title="Submissions:Time indexed person role">        Submissions:Time indexed person role       </a></li> |



  





# 

 Elements



_The
 __Time indexed participation__ 
 Content OP locally defines the following ontology elements:_ 





[![ObjectProperty](public/images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__includesEvent__ 
 (owl:ObjectProperty) A relation between situations and events, e.g. 'this morning I've prepared my coffee and had my fingers burnt' (i.e.: the preparation of my coffee this morning included a burning of my fingers).
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[includesEvent](../Submissions/Time_indexed_participation/includesEvent "Submissions:Time indexed participation/includesEvent") 
 page_ 



[![ObjectProperty](public/images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__includesObject__ 
 (owl:ObjectProperty) A relation between situations and objects, e.g. 'this morning I've prepared my coffee and had my fingers burnt' (i.e.: the preparation of my coffee this morning included me).
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[includesObject](../Submissions/Time_indexed_participation/includesObject "Submissions:Time indexed participation/includesObject") 
 page_ 



[![ObjectProperty](public/images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__isEventIncludedIn__ 
 (owl:ObjectProperty)
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[isEventIncludedIn](../Submissions/Time_indexed_participation/isEventIncludedIn "Submissions:Time indexed participation/isEventIncludedIn") 
 page_ 



[![ObjectProperty](public/images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__isObjectIncludedIn__ 
 (owl:ObjectProperty)
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[isObjectIncludedIn](../Submissions/Time_indexed_participation/isObjectIncludedIn "Submissions:Time indexed participation/isObjectIncludedIn") 
 page_ 



[![Class](public/images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__TimeIndexedParticipation__ 
 (owl:Class) A Situation that represents participation of Object(s) in Event(s) at some Time.
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[TimeIndexedParticipation](../Submissions/Time_indexed_participation/TimeIndexedParticipation "Submissions:Time indexed participation/TimeIndexedParticipation") 
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
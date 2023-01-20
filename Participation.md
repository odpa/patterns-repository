# 

 Graphical representation



__Diagram__ 





[![Image:Participation.jpg](public/images/8/86/Participation.jpg)](../Image/Participation.jpg "Image:Participation.jpg")





# 

 General description




|  |  |
| --- | --- |
|  Name:  |  Participation  |
|  Submitted by:  | [AldoGangemi](../User/AldoGangemi "User:AldoGangemi")  |
|  Also Known As:  |  |
|  Intent:  |  To represent participation of an object in an event.  |
|  Domains:  | [General](../Community/General "Community:General")  |
|  Competency Questions:  | <li>       Which objects do participate in this event? Which events do this object participate in?      </li> |
|  Solution description:  |  This pattern is a basic one, and enables the representation of any simple binary relation between objects and events.  |
|  Reusable OWL Building Block:  | [http://ontologydesignpatterns.org/cp/owl/participation.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=http://ontologydesignpatterns.org/cp/owl/participation.owl&message=OWL building block&from_page_id=434&update=)  (766)  |
|  Consequences:  |  It is possible to model whatever relation between objects and events. Using cardinality restrictions appropriately allows to limit the number of participants, e.g. 'life of' is a specialization of this pattern that requires a functional object property (cardinality 1. . .1).  This is a non-temporal version of the particpation relation. If we need a time-indexed relation, use [http://ontologydesignpatterns.owl/cp/owl/timeindexedparticipation.owl](http://ontologydesignpatterns.owl/cp/owl/timeindexedparticipation.owl "http://ontologydesignpatterns.owl/cp/owl/timeindexedparticipation.owl")  |
|  Scenarios:  |  Aldo Gangemi participated in the premiere of La Dolce Vita.  |
|  Known Uses:  |  |
|  Web References:  |  |
|  Other References:  |  |
|  Examples (OWL files):  |  |
|  Extracted From:  | <li><a class="external free" href="http://ontologydesignpatterns.org/ont/dul/DUL.owl" rel="nofollow" title="http://ontologydesignpatterns.org/ont/dul/DUL.owl">        http://ontologydesignpatterns.org/ont/dul/DUL.owl       </a></li> |
|  Reengineered From:  |  |
|  Has Components:  |  |
|  Specialization Of:  |  |
|  Related CPs:  | <li><a href="Submissions%253ATime_indexed_participation.html" title="Submissions:Time indexed participation">        Submissions:Time indexed participation       </a></li> |



  





# 

 Elements



_The
 __Participation__ 
 Content OP locally defines the following ontology elements:_ 





[![ObjectProperty](public/images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasParticipant__ 
 (owl:ObjectProperty)
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasParticipant](../Submissions/Participation/hasParticipant "Submissions:Participation/hasParticipant") 
 page_ 



[![ObjectProperty](public/images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__isParticipantIn__ 
 (owl:ObjectProperty)
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[isParticipantIn](../Submissions/Participation/isParticipantIn "Submissions:Participation/isParticipantIn") 
 page_ 



[![Class](public/images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__Event__ 
 (owl:Class) Any physical, social, or mental process, event, or state.
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[Event](../Submissions/Participation/Event "Submissions:Participation/Event") 
 page_ 



[![Class](public/images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__Object__ 
 (owl:Class) Any physical, social, or mental object, or substance
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[Object](../Submissions/Participation/Object "Submissions:Participation/Object") 
 page_ 


# 

 Additional information



 The basic participation pattern, without temporal indexing. 
It clones equivalent elements from DOLCE-UltraLite.
 



# 

 Scenarios




__Scenarios about Participation__ 


 No scenario is added to this Content OP.
 




# 

 Reviews




__Reviews about Participation__ 


 There is no review about this proposal.
This revision (revision ID
 __9110__ 
 ) takes in account the reviews: none
 



 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Participation&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Participation&action=evaluation") 





  





# 

 Modeling issues




__Modeling issues about Participation__ 


 There is no Modeling issue related to this proposal.
 




  





# 

 References
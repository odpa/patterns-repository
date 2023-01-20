# 

 Graphical representation



__Diagram__ 





[![Image:ParticipantRole.jpg](public/images/3/34/ParticipantRole.jpg)](../Image/ParticipantRole.jpg "Image:ParticipantRole.jpg")





# 

 General description




|  |  |
| --- | --- |
|  Name:  |  ParticipantRole  |
|  Submitted by:  | [EvaBlomqvist](../User/EvaBlomqvist "User:EvaBlomqvist")  |
|  Also Known As:  |  |
|  Intent:  |  To represent participants in events holding specific roles in that particular event.  |
|  Domains:  | [General](../Community/General "Community:General")  , [Organization](../Community/Organization "Community:Organization")  |
|  Competency Questions:  | <li>       What is the role of this object in this event?      </li><li>       What is the object holding this role in this event?      </li><li>       In what event did this object hold this role?      </li> |
|  Solution description:  |  The pattern introduces a situation that connects the object to its role in a particular event.  |
|  Reusable OWL Building Block:  | [http://www.ontology.se/odp/content/owl/ParticipantRole.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=http://www.ontology.se/odp/content/owl/ParticipantRole.owl&message=OWL building block&from_page_id=2705&update=)  (1082)  |
|  Consequences:  |  This pattern does not take into account time aspects of the participation, for such aspects see the timeindexedparticipation-pattern.  |
|  Scenarios:  |  John was elected the meeting secretary of today's board meeting. During the party we used the blue cup as a vase.  |
|  Known Uses:  |  |
|  Web References:  |  |
|  Other References:  |  |
|  Examples (OWL files):  |  |
|  Extracted From:  |  |
|  Reengineered From:  |  |
|  Has Components:  | <li><a href="Submissions%253ASituation.html" title="Submissions:Situation">        Submissions:Situation       </a></li><li><a href="Submissions%253AParticipation.html" title="Submissions:Participation">        Submissions:Participation       </a></li> |
|  Specialization Of:  | <li><a href="Submissions%253AParticipation.html" title="Submissions:Participation">        Submissions:Participation       </a></li> |
|  Related CPs:  | <li><a href="Submissions%253ATime_indexed_participation.html" title="Submissions:Time indexed participation">        Submissions:Time indexed participation       </a></li> |



  





# 

 Elements



_The
 __ParticipantRole__ 
 Content OP locally defines the following ontology elements:_ 





[![Class](public/images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__Role__ 
 (owl:Class) A concept that classifies an object.
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[Role](../Submissions/ParticipantRole/Role "Submissions:ParticipantRole/Role") 
 page_ 



[![Class](public/images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__ParticipantRole__ 
 (owl:Class) A situation that represents the role(s) of a specific object (or objects) participating in and event (or events).
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[ParticipantRole](../Submissions/ParticipantRole/ParticipantRole "Submissions:ParticipantRole/ParticipantRole") 
 page_ 



[![ObjectProperty](public/images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__participatingInEvent__ 
 (owl:ObjectProperty)
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[participatingInEvent](../Submissions/ParticipantRole/participatingInEvent "Submissions:ParticipantRole/participatingInEvent") 
 page_ 



[![ObjectProperty](public/images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__objectParticipating__ 
 (owl:ObjectProperty)
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[objectParticipating](../Submissions/ParticipantRole/objectParticipating "Submissions:ParticipantRole/objectParticipating") 
 page_ 



[![ObjectProperty](public/images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__roleOfParticipant__ 
 (owl:ObjectProperty)
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[roleOfParticipant](../Submissions/ParticipantRole/roleOfParticipant "Submissions:ParticipantRole/roleOfParticipant") 
 page_ 



[![ObjectProperty](public/images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__objectIncludedIn__ 
 (owl:ObjectProperty)
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[objectIncludedIn](../Submissions/ParticipantRole/objectIncludedIn "Submissions:ParticipantRole/objectIncludedIn") 
 page_ 



[![ObjectProperty](public/images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__roleIncludedIn__ 
 (owl:ObjectProperty)
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[roleIncludedIn](../Submissions/ParticipantRole/roleIncludedIn "Submissions:ParticipantRole/roleIncludedIn") 
 page_ 



[![ObjectProperty](public/images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__eventIncludedIn__ 
 (owl:ObjectProperty)
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[eventIncludedIn](../Submissions/ParticipantRole/eventIncludedIn "Submissions:ParticipantRole/eventIncludedIn") 
 page_ 


# 

 Additional information



# 

 Scenarios




__Scenarios about ParticipantRole__ 


 No scenario is added to this Content OP.
 




# 

 Reviews




__Reviews about ParticipantRole__ 


 There is no review about this proposal.
This revision (revision ID
 __9383__ 
 ) takes in account the reviews: none
 



 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:ParticipantRole&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:ParticipantRole&action=evaluation") 





  





# 

 Modeling issues




__Modeling issues about ParticipantRole__ 


 There is no Modeling issue related to this proposal.
 




  





# 

 References
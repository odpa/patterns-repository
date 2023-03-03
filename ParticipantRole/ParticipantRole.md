# 

 Graphical representation



__Diagram__ 





[![Image:ParticipantRole.jpg](./ParticipantRole.jpg)](../Image/ParticipantRole.jpg.md "Image:ParticipantRole.jpg")





# 

 General description




|  |  |
| --- | --- |
|  Name:  |  ParticipantRole  |
|  Submitted by:  | [EvaBlomqvist](../User/EvaBlomqvist.md "User:EvaBlomqvist")  |
|  Also Known As:  |  |
|  Intent:  |  To represent participants in events holding specific roles in that particular event.  |
|  Domains:  | [General](../Community/General.md "Community:General")  , [Organization](../Community/Organization.md "Community:Organization")  |
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
|  Has Components:  | <li><a href="../DescriptionAndSituation/DescriptionAndSituation.md" title="Submissions:Situation">        Submissions:Situation       </a></li><li><a href="../Nary_Participation/Nary_Participation.md" title="Submissions:Participation">        Submissions:Participation       </a></li> |
|  Specialization Of:  | <li><a href="../Nary_Participation/Nary_Participation.md" title="Submissions:Participation">        Submissions:Participation       </a></li> |
|  Related CPs:  | <li><a href="../Time_indexed_participation/Time_indexed_participation.md" title="Submissions:Time indexed participation">        Submissions:Time indexed participation       </a></li> |



  





# 

 Elements



_The
 __ParticipantRole__ 
 Content OP locally defines the following ontology elements:_ 





[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__Role__ 
 (owl:Class) A concept that classifies an object.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[Role](../AgentRole/AgentRole.md "Submissions:ParticipantRole/Role") 
 page_ 



[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__ParticipantRole__ 
 (owl:Class) A situation that represents the role(s) of a specific object (or objects) participating in and event (or events).
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[ParticipantRole](./ParticipantRole.md "Submissions:ParticipantRole/ParticipantRole") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__participatingInEvent__ 
 (owl:ObjectProperty)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[participatingInEvent](./ParticipantRole/participatingInEvent.md "Submissions:ParticipantRole/participatingInEvent") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__objectParticipating__ 
 (owl:ObjectProperty)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[objectParticipating](./ParticipantRole/objectParticipating.md "Submissions:ParticipantRole/objectParticipating") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__roleOfParticipant__ 
 (owl:ObjectProperty)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[roleOfParticipant](./ParticipantRole/roleOfParticipant.md "Submissions:ParticipantRole/roleOfParticipant") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__objectIncludedIn__ 
 (owl:ObjectProperty)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[objectIncludedIn](./ParticipantRole/objectIncludedIn.md "Submissions:ParticipantRole/objectIncludedIn") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__roleIncludedIn__ 
 (owl:ObjectProperty)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[roleIncludedIn](./ParticipantRole/roleIncludedIn.md "Submissions:ParticipantRole/roleIncludedIn") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__eventIncludedIn__ 
 (owl:ObjectProperty)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[eventIncludedIn](./ParticipantRole/eventIncludedIn.md "Submissions:ParticipantRole/eventIncludedIn") 
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
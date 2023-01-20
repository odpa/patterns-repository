# 

 Graphical representation



__Diagram__ 
_(this article has no graphical representation)_ 




# 

 General description




|  |  |
| --- | --- |
|  Name:  |  time  |
|  Submitted by:  | [MarjanAlirezaie](../User/MarjanAlirezaie "User:MarjanAlirezaie")  |
|  Also Known As:  |  |
|  Intent:  |  This pattern allows us to represent a temporal distance between two timestamps within an observation process in a SmartHome. There are other situations where we need to measure the interval (temporal distance) in the form of time steps regardless of the exact dates indicating the boundaries of the interval. The latter case is used when we want to define a complex event based on the temporal distance with its preconditions.  |
|  Domains:  |  |
|  Competency Questions:  | <li>       What is the time interval between two specific timestamps in the form of dates?      </li><li>       What is the temporal distance between two specific time steps?      </li><li>       What is the starting/ending timestamp?      </li> |
|  Solution description:  |  Specializing the OWL-Time ontology  |
|  Reusable OWL Building Block:  | [http://ecareathome-ontology.mpi.aass.oru.se/patterns/time.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=http://ecareathome-ontology.mpi.aass.oru.se/patterns/time.owl&message=OWL building block&from_page_id=4224&update=)  (498)  |
|  Consequences:  |  We can quantitavely represent temporal distances through an observation process for different purposes . These purposes include  definition of an event in terms of its preconditions whose occurance timestamp is within a specific temporal distance with that of the event.  |
|  Scenarios:  |  |
|  Known Uses:  |  |
|  Web References:  |  |
|  Other References:  |  |
|  Examples (OWL files):  |  |
|  Extracted From:  | <li><a class="external free" href="https://www.w3.org/TR/owl-time/" rel="nofollow" title="https://www.w3.org/TR/owl-time/">        https://www.w3.org/TR/owl-time/       </a></li> |
|  Reengineered From:  | <li><a class="external free" href="https://www.w3.org/TR/owl-time/" rel="nofollow" title="https://www.w3.org/TR/owl-time/">        https://www.w3.org/TR/owl-time/       </a></li> |
|  Has Components:  |  |
|  Specialization Of:  | <li><a class="new" href="http://ontologydesignpatterns.org/wiki/Special:AddData/Content OP Proposal Form/Submissions:Https://www.w3.org/TR/owl-time/?alt_form[0]=Content OP Form" title="Submissions:Https://www.w3.org/TR/owl-time/ (not yet written)">        Submissions:https://www.w3.org/TR/owl-time/       </a></li> |
|  Related CPs:  |  |



  





# 

 Elements



_The
 __SmartHome TimeInterval__ 
 Content OP locally defines the following ontology elements:_ 





[![DatatypeProperty](public/images/thumb/a/a5/DatatypeProperty.gif/20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif "DatatypeProperty")
__hasLowerTimestampValue__ 
 (owl:DatatypeProperty)
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasLowerTimestampValue](../Submissions/SmartHome_TimeInterval/hasLowerTimestampValue "Submissions:SmartHome TimeInterval/hasLowerTimestampValue") 
 page_ 



[![DatatypeProperty](public/images/thumb/a/a5/DatatypeProperty.gif/20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif "DatatypeProperty")
__hasUpperTimestampValue__ 
 (owl:DatatypeProperty)
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasUpperTimestampValue](../Submissions/SmartHome_TimeInterval/hasUpperTimestampValue "Submissions:SmartHome TimeInterval/hasUpperTimestampValue") 
 page_ 



[![Class](public/images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__SmartHomeTemporalDistance__ 
 (owl:Class)
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[SmartHomeTemporalDistance](../Submissions/SmartHome_TimeInterval/SmartHomeTemporalDistance "Submissions:SmartHome TimeInterval/SmartHomeTemporalDistance") 
 page_ 



[![Class](public/images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__SmartHomeTimeInterval__ 
 (owl:Class)
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[SmartHomeTimeInterval](../Submissions/SmartHome_TimeInterval/SmartHomeTimeInterval "Submissions:SmartHome TimeInterval/SmartHomeTimeInterval") 
 page_ 


# 

 Additional information



# 

 Scenarios




__Scenarios about SmartHome TimeInterval__ 


 No scenario is added to this Content OP.
 




# 

 Reviews




__Reviews about SmartHome TimeInterval__ 


 There is no review about this proposal.
This revision (revision ID
 __13366__ 
 ) takes in account the reviews: none
 



 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:SmartHome_TimeInterval&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:SmartHome_TimeInterval&action=evaluation") 





  





# 

 Modeling issues




__Modeling issues about SmartHome TimeInterval__ 


 There is no Modeling issue related to this proposal.
 




  





# 

 References
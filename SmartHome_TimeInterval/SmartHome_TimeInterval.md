# 

 Graphical representation



__Diagram__ 
_(this article has no graphical representation)_ 




# 

 General description




|  |  |
| --- | --- |
|  Name:  |  time  |
|  Submitted by:  | [MarjanAlirezaie](../User/MarjanAlirezaie.md "User:MarjanAlirezaie")  |
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





[![DatatypeProperty](./20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif.md "DatatypeProperty")
__hasLowerTimestampValue__ 
 (owl:DatatypeProperty)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[hasLowerTimestampValue](./SmartHome_TimeInterval/hasLowerTimestampValue.md "Submissions:SmartHome TimeInterval/hasLowerTimestampValue") 
 page_ 



[![DatatypeProperty](./20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif.md "DatatypeProperty")
__hasUpperTimestampValue__ 
 (owl:DatatypeProperty)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[hasUpperTimestampValue](./SmartHome_TimeInterval/hasUpperTimestampValue.md "Submissions:SmartHome TimeInterval/hasUpperTimestampValue") 
 page_ 



[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__SmartHomeTemporalDistance__ 
 (owl:Class)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[SmartHomeTemporalDistance](./SmartHome_TimeInterval/SmartHomeTemporalDistance.md "Submissions:SmartHome TimeInterval/SmartHomeTemporalDistance") 
 page_ 



[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__SmartHomeTimeInterval__ 
 (owl:Class)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[SmartHomeTimeInterval](./SmartHome_TimeInterval/SmartHomeTimeInterval.md "Submissions:SmartHome TimeInterval/SmartHomeTimeInterval") 
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
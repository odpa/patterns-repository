#  Graphical representation


__Diagram__




[![Image:SHEvent.png](./SHEvent.png)](../Image/SHEvent.png.md "Image:SHEvent.png")




#  General description




|  |  |
| --- | --- |
|  Name: |  event |
|  Submitted by: | [MarjanAlirezaie](../User/MarjanAlirezaie.md "User:MarjanAlirezaie") |
|  Also Known As: |  |
|  Intent: |  This pattern is used to represent events in the context of smart environments. An event in this pattern is represented in the form of either a Manifestation or a Complex Event, where a manifestation represents the occurrence of a specific situation of an object which can be directly captured from sensor data ("the TV is switched on"), whereas a complex event is defined based on its preconditions that can involve different events (e.g., "watching TV" happens when "the TV is switched on" and "someone is sitting on the couch").The precondition of a complex event is represented in the form of a situation (DUL:Situation) which indicates proper temporal distances between a complex event and, the events involved in its definition. |
|  Domains: |  |
|  Competency Questions: | <li> What are the preconditions of a comple event? And what is the temporal distance between a complex event and its preconditions?</li><li> Who has participanted in the event? (Dul:Agent)</li><li> Which situation (including object; its property and its state) has been captured in the form of a manifestation event?</li><li> When does an Event occur? (Dul:TimeInterval)</li> |
|  Solution description: |  TBD |
|  Reusable OWL Building Block: | [https://w3id.org/smartenvironment/event.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=https://w3id.org/smartenvironment/event.owl&message=OWL building block&from_page_id=4217&update=) (0) |
|  Consequences: |  |
|  Scenarios: |  |
|  Known Uses: |  |
|  Web References: |  |
|  Other References: |  |
|  Examples (OWL files): |  |
|  Extracted From: |  |
|  Reengineered From: |  |
|  Has Components: |  |
|  Specialization Of: |  |
|  Related CPs: |  |


  




#  Elements


_The __SmartHome Event__ Content OP locally defines the following ontology elements:_



[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __ComplexEvent__ (owl:Class) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[ComplexEvent](./SmartHome_Event/ComplexEvent.md "Submissions:SmartHome Event/ComplexEvent") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __EventCondition__ (owl:Class) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[EventCondition](./SmartHome_Event/EventCondition.md "Submissions:SmartHome Event/EventCondition") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __Manifestation__ (owl:Class) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[Manifestation](./SmartHome_Event/Manifestation.md "Submissions:SmartHome Event/Manifestation") page_
[Submissions:SmartHome Event/event](http://ontologydesignpatterns.org/wiki/Special:AddData/Ontology Element Form/Submissions:SmartHome_Event/event "Submissions:SmartHome Event/event (not yet written)") [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[event](http://ontologydesignpatterns.org/wiki/Special:AddData/Ontology Element Form/Submissions:SmartHome_Event/event "Submissions:SmartHome Event/event (not yet written)") page_
#  Additional information


#  Scenarios



__Scenarios about SmartHome Event__
No scenario is added to this Content OP.




#  Reviews



__Reviews about SmartHome Event__
There is no review about this proposal.
This revision (revision ID __13371__) takes in account the reviews: none


Other info at [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:SmartHome_Event&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:SmartHome_Event&action=evaluation")




  




#  Modeling issues



__Modeling issues about SmartHome Event__
There is no Modeling issue related to this proposal.




  




#  References
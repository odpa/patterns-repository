#  Graphical representation


__Diagram__




[![Image:Transition.png](./Transition.png)](../Image/Transition.png.md "Image:Transition.png")




#  General description




|  |  |
| --- | --- |
|  Name: |  Transition |
|  Submitted by: | [AldoGangemi](../User/AldoGangemi.md "User:AldoGangemi") |
|  Also Known As: |  |
|  Intent: |  To represent basic knowledge about transitions (events, states, processes, objects). |
|  Domains: | [General](../Community/General.md "Community:General"), [Workflow](../Community/Workflow.md "Community:Workflow"), [Manufacturing](../Community/Manufacturing.md "Community:Manufacturing") |
|  Competency Questions: | <li> What states of some object are changed by what event during a transition?</li><li> What is the process that is invariant through the transition?</li><li> What transitions are occurring on what object at what time?</li> |
|  Solution description: |  This pattern composes the [Time-indexed participation](../Time_indexed_participation/Time_indexed_participation.md "Submissions:Time indexed participation"), [Region](../Region/Region.md "Submissions:Region"), and [Sequence](../Sequence/Sequence.md "Submissions:Sequence") patterns in order to represent changing of states for objects, fired by some event, through an underlying process. |
|  Reusable OWL Building Block: | [http://ontologydesignpatterns.org/cp/owl/transition.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=http://ontologydesignpatterns.org/cp/owl/transition.owl&message=OWL building block&from_page_id=1160&update=) (813) |
|  Consequences: |  We are able to represent part of the semantics involved in transitions (e.g. what is implied by Petri Nets): initial and final states, causal events, underlying processes, affected objects, and sequences of time intervals for situations and events.However, it is not possible to define axioms for automatically infer initial and final states from time sequences, because coreference is not allowed in OWL (not even in OWL2). |
|  Scenarios: |  The addition of Bud Powell on piano made the tune jump from a static, aerial comping into a hard driving swing improvisation |
|  Known Uses: |  |
|  Web References: |  |
|  Other References: |  |
|  Examples (OWL files): |  |
|  Extracted From: |  |
|  Reengineered From: |  |
|  Has Components: | <li><a href="../Region/Region.md" title="Submissions:Region">Submissions:Region</a></li><li><a href="../Sequence/Sequence.md" title="Submissions:Sequence">Submissions:Sequence</a></li><li><a href="../Time_indexed_participation/Time_indexed_participation.md" title="Submissions:Time indexed participation">Submissions:Time indexed participation</a></li> |
|  Specialization Of: |  |
|  Related CPs: |  |


  




#  Elements


_The __Transition__ Content OP locally defines the following ontology elements:_



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasEventAtTime__ (owl:ObjectProperty) The time of the event causing the transition. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasEventAtTime](./Transition/hasEventAtTime.md "Submissions:Transition/hasEventAtTime") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasFinalStateAtTime__ (owl:ObjectProperty) The time of the final state of the transition. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasFinalStateAtTime](./Transition/hasFinalStateAtTime.md "Submissions:Transition/hasFinalStateAtTime") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasInitialStateAtTime__ (owl:ObjectProperty) The time of the initial state in the transition. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasInitialStateAtTime](./Transition/hasInitialStateAtTime.md "Submissions:Transition/hasInitialStateAtTime") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __includesFinalSituation__ (owl:ObjectProperty) A relation between a transition situation and the situation resulting from the transition. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[includesFinalSituation](./Transition/includesFinalSituation.md "Submissions:Transition/includesFinalSituation") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __includesInitialSituation__ (owl:ObjectProperty) A relation between a transition situation and the situation existing before the transition event. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[includesInitialSituation](./Transition/includesInitialSituation.md "Submissions:Transition/includesInitialSituation") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __includesProcess__ (owl:ObjectProperty) A relation between a transition situation and the underlying process that is invariant for the object(s) included in the transition. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[includesProcess](./Transition/includesProcess.md "Submissions:Transition/includesProcess") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isFinalSituationIncludedIn__ (owl:ObjectProperty) A relation between a transition situation and the situation resulting from the transition. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isFinalSituationIncludedIn](./Transition/isFinalSituationIncludedIn.md "Submissions:Transition/isFinalSituationIncludedIn") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isInitialSituationIncludedIn__ (owl:ObjectProperty) A relation between a transition situation and the situation existing before the transition event. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isInitialSituationIncludedIn](./Transition/isInitialSituationIncludedIn.md "Submissions:Transition/isInitialSituationIncludedIn") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isProcessIncludedIn__ (owl:ObjectProperty) A relation between a transition situation and the underlying process that is invariant for the object(s) included in the transition. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isProcessIncludedIn](./Transition/isProcessIncludedIn.md "Submissions:Transition/isProcessIncludedIn") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isTimeOf__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isTimeOf](./TimeIndexedPartOf/isTimeOf.md "Submissions:Transition/isTimeOf") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __occursAt__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[occursAt](./Transition/occursAt.md "Submissions:Transition/occursAt") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __Process__ (owl:Class) The invariance under some different transitions (including the one represented here), in which at least one Object is situated. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[Process](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/hasGoalOrProcess.md "Submissions:Transition/Process") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __Transition__ (owl:Class) In this pattern, it is the entity that is invariant across the Process underlying the transition, but is also changed from an initial to a final state by an Event.
  



A transition is a Situation that creates a context for three TimeInterval(s), two additional different Situation(s), one Event, one Process, and at least one Object: the Event is observed as the cause for the transition, one Situation is the state before the transition, the second Situation is the state after the transition, the Process is the invariance under some different transitions (including the one represented here), in which at least one Object is situated. Finally, the time intervals position the situations and the transitional event in time.


This class of situations partly encodes the ontology underlying typical engineering algebras for processes, e.g. Petri Nets. 


A full representation of the transition ontology is outside the expressivity of OWL, because we would need qualified cardinality restrictions, coreference, property equivalence, and property composition. 



 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[Transition](./Transition.md "Submissions:Transition/Transition") page_
#  Additional information


A simple pattern to represent transitions between states.



#  Scenarios



__Scenarios about Transition__
No scenario is added to this Content OP.




#  Reviews



__Reviews about Transition__
There is no review about this proposal.
This revision (revision ID __9137__) takes in account the reviews: none


Other info at [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Transition&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Transition&action=evaluation")




  




#  Modeling issues



__Modeling issues about Transition__
There is no Modeling issue related to this proposal.




  




#  References
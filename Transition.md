# 

 Graphical representation



__Diagram__ 





[![Image:Transition.png](images/7/7a/Transition.png)](../Image/Transition.png "Image:Transition.png")





# 

 General description




|  |  |
| --- | --- |
|  Name:  |  Transition  |
|  Submitted by:  | [AldoGangemi](../User/AldoGangemi "User:AldoGangemi")  |
|  Also Known As:  |  |
|  Intent:  |  To represent basic knowledge about transitions (events, states, processes, objects).  |
|  Domains:  | [General](../Community/General "Community:General")  , [Workflow](../Community/Workflow "Community:Workflow")  , [Manufacturing](../Community/Manufacturing "Community:Manufacturing")  |
|  Competency Questions:  | <li>       What states of some object are changed by what event during a transition?      </li><li>       What is the process that is invariant through the transition?      </li><li>       What transitions are occurring on what object at what time?      </li> |
|  Solution description:  |  This pattern composes the [Time-indexed participation](../Submissions/Time_indexed_participation "Submissions:Time indexed participation")  , [Region](../Submissions/Region "Submissions:Region")  , and [Sequence](../Submissions/Sequence "Submissions:Sequence")  patterns in order to represent changing of states for objects, fired by some event, through an underlying process.  |
|  Reusable OWL Building Block:  | [http://ontologydesignpatterns.org/cp/owl/transition.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=http://ontologydesignpatterns.org/cp/owl/transition.owl&message=OWL building block&from_page_id=1160&update=)  (813)  |
|  Consequences:  |  We are able to represent part of the semantics involved in transitions (e.g. what is implied by Petri Nets): initial and final states, causal events, underlying processes, affected objects, and sequences of time intervals for situations and events.  However, it is not possible to define axioms for automatically infer initial and final states from time sequences, because coreference is not allowed in OWL (not even in OWL2).  |
|  Scenarios:  |  The addition of Bud Powell on piano made the tune jump from a static, aerial comping into a hard driving swing improvisation  |
|  Known Uses:  |  |
|  Web References:  |  |
|  Other References:  |  |
|  Examples (OWL files):  |  |
|  Extracted From:  |  |
|  Reengineered From:  |  |
|  Has Components:  | <li><a href="../Submissions/Region" title="Submissions:Region">        Submissions:Region       </a></li><li><a href="../Submissions/Sequence" title="Submissions:Sequence">        Submissions:Sequence       </a></li><li><a href="../Submissions/Time_indexed_participation" title="Submissions:Time indexed participation">        Submissions:Time indexed participation       </a></li> |
|  Specialization Of:  |  |
|  Related CPs:  |  |



  





# 

 Elements



_The
 __Transition__ 
 Content OP locally defines the following ontology elements:_ 





[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasEventAtTime__ 
 (owl:ObjectProperty) The time of the event causing the transition.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasEventAtTime](../Submissions/Transition/hasEventAtTime "Submissions:Transition/hasEventAtTime") 
 page_ 



[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasFinalStateAtTime__ 
 (owl:ObjectProperty) The time of the final state of the transition.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasFinalStateAtTime](../Submissions/Transition/hasFinalStateAtTime "Submissions:Transition/hasFinalStateAtTime") 
 page_ 



[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasInitialStateAtTime__ 
 (owl:ObjectProperty) The time of the initial state in the transition.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasInitialStateAtTime](../Submissions/Transition/hasInitialStateAtTime "Submissions:Transition/hasInitialStateAtTime") 
 page_ 



[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__includesFinalSituation__ 
 (owl:ObjectProperty) A relation between a transition situation and the situation resulting from the transition.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[includesFinalSituation](../Submissions/Transition/includesFinalSituation "Submissions:Transition/includesFinalSituation") 
 page_ 



[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__includesInitialSituation__ 
 (owl:ObjectProperty) A relation between a transition situation and the situation existing before the transition event.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[includesInitialSituation](../Submissions/Transition/includesInitialSituation "Submissions:Transition/includesInitialSituation") 
 page_ 



[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__includesProcess__ 
 (owl:ObjectProperty) A relation between a transition situation and the underlying process that is invariant for the object(s) included in the transition.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[includesProcess](../Submissions/Transition/includesProcess "Submissions:Transition/includesProcess") 
 page_ 



[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__isFinalSituationIncludedIn__ 
 (owl:ObjectProperty) A relation between a transition situation and the situation resulting from the transition.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[isFinalSituationIncludedIn](../Submissions/Transition/isFinalSituationIncludedIn "Submissions:Transition/isFinalSituationIncludedIn") 
 page_ 



[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__isInitialSituationIncludedIn__ 
 (owl:ObjectProperty) A relation between a transition situation and the situation existing before the transition event.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[isInitialSituationIncludedIn](../Submissions/Transition/isInitialSituationIncludedIn "Submissions:Transition/isInitialSituationIncludedIn") 
 page_ 



[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__isProcessIncludedIn__ 
 (owl:ObjectProperty) A relation between a transition situation and the underlying process that is invariant for the object(s) included in the transition.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[isProcessIncludedIn](../Submissions/Transition/isProcessIncludedIn "Submissions:Transition/isProcessIncludedIn") 
 page_ 



[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__isTimeOf__ 
 (owl:ObjectProperty)
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[isTimeOf](../Submissions/Transition/isTimeOf "Submissions:Transition/isTimeOf") 
 page_ 



[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__occursAt__ 
 (owl:ObjectProperty)
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[occursAt](../Submissions/Transition/occursAt "Submissions:Transition/occursAt") 
 page_ 



[![Class](images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__Process__ 
 (owl:Class) The invariance under some different transitions (including the one represented here), in which at least one Object is situated.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[Process](../Submissions/Transition/Process "Submissions:Transition/Process") 
 page_ 



[![Class](images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__Transition__ 
 (owl:Class) In this pattern, it is the entity that is invariant across the Process underlying the transition, but is also changed from an initial to a final state by an Event.
 
  





 A transition is a Situation that creates a context for three TimeInterval(s), two additional different Situation(s), one Event, one Process, and at least one Object: the Event is observed as the cause for the transition, one Situation is the state before the transition, the second Situation is the state after the transition, the Process is the invariance under some different transitions (including the one represented here), in which at least one Object is situated. Finally, the time intervals position the situations and the transitional event in time.
 



 This class of situations partly encodes the ontology underlying typical engineering algebras for processes, e.g. Petri Nets.
 



 A full representation of the transition ontology is outside the expressivity of OWL, because we would need qualified cardinality restrictions, coreference, property equivalence, and property composition.
 



[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[Transition](../Submissions/Transition/Transition "Submissions:Transition/Transition") 
 page_ 


# 

 Additional information



 A simple pattern to represent transitions between states.
 



# 

 Scenarios




__Scenarios about Transition__ 


 No scenario is added to this Content OP.
 




# 

 Reviews




__Reviews about Transition__ 


 There is no review about this proposal.
This revision (revision ID
 __9137__ 
 ) takes in account the reviews: none
 



 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Transition&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Transition&action=evaluation") 





  





# 

 Modeling issues




__Modeling issues about Transition__ 


 There is no Modeling issue related to this proposal.
 




  





# 

 References
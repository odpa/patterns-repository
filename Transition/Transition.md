___Transition__ 
 has
 [Category:OntologyElement](../../Category/OntologyElement "Category:OntologyElement") 
 and is an
 [element of](../../Property/ElementOf "Property:ElementOf") 
[Transition](../../Submissions/Transition "Submissions:Transition")_




  





[![Class](../public/images/thumb/2/27/Class.gif/45px-Class.gif)](../../Image/Class.gif "Class")


__Name__ 
 : Transition
 



__Type:__ 
 owl:Class
 



__Description__ 
 : In this pattern, it is the entity that is invariant across the Process underlying the transition, but is also changed from an initial to a final state by an Event.
 



  





 A transition is a Situation that creates a context for three TimeInterval(s), two additional different Situation(s), one Event, one Process, and at least one Object: the Event is observed as the cause for the transition, one Situation is the state before the transition, the second Situation is the state after the transition, the Process is the invariance under some different transitions (including the one represented here), in which at least one Object is situated. Finally, the time intervals position the situations and the transitional event in time.
 



 This class of situations partly encodes the ontology underlying typical engineering algebras for processes, e.g. Petri Nets.
 



 A full representation of the transition ontology is outside the expressivity of OWL, because we would need qualified cardinality restrictions, coreference, property equivalence, and property composition.
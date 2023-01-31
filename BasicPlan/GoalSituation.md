___GoalSituation__ 
 has
 [Category:OntologyElement](../../Category/OntologyElement "Category:OntologyElement") 
 and is an
 [element of](../../Property/ElementOf "Property:ElementOf") 
[BasicPlan](../../Submissions/BasicPlan "Submissions:BasicPlan")_




  





[![Class](../images/thumb/2/27/Class.gif/45px-Class.gif)](../../Image/Class.gif "Class")


__Name__ 
 : GoalSituation
 



__Type:__ 
 owl:Class
 



__Description__ 
 : A goal situation is a situation that satisfies a goal.Opposite to the case of subplan executions, a goal situation is not part of a plan execution.In other words, it is not true in general that any situation satisfying a part of a description, is also part of the situation that satisfies the whole description. This helps to account for the following cases: a) Execution of plans containing abort or suspension conditions (the plan would be satisfied even if the goal has not been reached, see below), b) Incidental satisfaction, like when a situation satisfies a goal without being intentionally planned (but anyway desired).
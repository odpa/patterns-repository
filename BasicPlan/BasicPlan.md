#  Graphical representation


__Diagram__
_(this article has no graphical representation)_



#  General description




|  |  |
| --- | --- |
|  Name: |  BasicPlan |
|  Submitted by: | [AldoGangemi](../User/AldoGangemi.md "User:AldoGangemi") |
|  Also Known As: |  |
|  Intent: |  - |
|  Domains: |  |
|  Competency Questions: |  |
|  Solution description: |  - |
|  Reusable OWL Building Block: | [http://www.ontologydesignpatterns.org/cp/owl/basicplan.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=http://www.ontologydesignpatterns.org/cp/owl/basicplan.owl&message=OWL building block&from_page_id=2228&update=) (786) |
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


_The __BasicPlan__ Content OP locally defines the following ontology elements:_



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __conceptualizes__ (owl:ObjectProperty) A relation stating that an Agent is internally representing a SocialObject . E.g., 'John believes in the conspiracy theory'; 'Niels Bohr created the solar-system metaphor for the atomic theory'; 'Jacques assumes all swans are white'; 'the task force members share the attack plan'. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[conceptualizes](./BasicPlan/conceptualizes.md "Submissions:BasicPlan/conceptualizes") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __executesTask__ (owl:ObjectProperty) A relation between an action and a task, e.g. 'putting some water in a pot and putting the pot on a fire until the water starts bubbling' executes the task 'boiling'. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[executesTask](./BasicPlan/executesTask.md "Submissions:BasicPlan/executesTask") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isConceptualizedBy__ (owl:ObjectProperty) A relation stating that an Agent is internally representing a Description . E.g., 'John believes in the conspiracy theory'; 'Niels Bohr created a solar-system metaphor for his atomic theory'; 'Jacques assumes all swans are white'; 'the task force shares the attack plan'. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isConceptualizedBy](./BasicPlan/isConceptualizedBy.md "Submissions:BasicPlan/isConceptualizedBy") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isExecutedIn__ (owl:ObjectProperty) A relation between an action and a task, e.g. 'putting some water in a pot and putting the pot on a fire until the water starts bubbling' executes the task 'boiling'. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isExecutedIn](./BasicPlan/isExecutedIn.md "Submissions:BasicPlan/isExecutedIn") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isParametrizedBy__ (owl:ObjectProperty) The relation between a Parameter, e.g. 'MajorAge', and a Region, e.g. '>17 year'. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isParametrizedBy](./BasicPlan/isParametrizedBy.md "Submissions:BasicPlan/isParametrizedBy") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isSatisfiedBy__ (owl:ObjectProperty) A relation between a Situation and a Description, e.g. the execution of a Plan satisfies that plan. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isSatisfiedBy](./BasicPlan/isSatisfiedBy.md "Submissions:BasicPlan/isSatisfiedBy") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __parametrizes__ (owl:ObjectProperty) The relation between a Parameter, e.g. 'MajorAgeLimit', and a Region, e.g. '18\_year'.
For a more data-oriented relation, see hasDataValue 



 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[parametrizes](./BasicPlan/parametrizes.md "Submissions:BasicPlan/parametrizes") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __satisfies__ (owl:ObjectProperty) A relation between a Situation and a Description, e.g. the execution of a Plan satisfies that plan. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[satisfies](./BasicPlan/satisfies.md "Submissions:BasicPlan/satisfies") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __GoalSituation__ (owl:Class) A goal situation is a situation that satisfies a goal.Opposite to the case of subplan executions, a goal situation is not part of a plan execution.In other words, it is not true in general that any situation satisfying a part of a description, is also part of the situation that satisfies the whole description. This helps to account for the following cases: a) Execution of plans containing abort or suspension conditions (the plan would be satisfied even if the goal has not been reached, see below), b) Incidental satisfaction, like when a situation satisfies a goal without being intentionally planned (but anyway desired). 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[GoalSituation](./BasicPlan/GoalSituation.md "Submissions:BasicPlan/GoalSituation") page_
#  Additional information


The basic plans. This content ontology design patterns represents plans descriptions and their executions. It is defined by combining and expanding other CPs: basic plans description, basic plans execution, and object role. Expansion involves the partial clone of ontology elements from DOLCE Ultra Lite and Plans Lite ontologies.



#  Scenarios



__Scenarios about BasicPlan__
No scenario is added to this Content OP.




#  Reviews



__Reviews about BasicPlan__
There is no review about this proposal.
This revision (revision ID __9066__) takes in account the reviews: none


Other info at [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:BasicPlan&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:BasicPlan&action=evaluation")




  




#  Modeling issues



__Modeling issues about BasicPlan__
There is no Modeling issue related to this proposal.




  




#  References
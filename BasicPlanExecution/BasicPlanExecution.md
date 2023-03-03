#  Graphical representation


__Diagram__
_(this article has no graphical representation)_



#  General description




|  |  |
| --- | --- |
|  Name: |  BasicPlanExecution |
|  Submitted by: | [AldoGangemi](../User/AldoGangemi.md "User:AldoGangemi") |
|  Also Known As: |  |
|  Intent: |  - |
|  Domains: |  |
|  Competency Questions: |  |
|  Solution description: |  - |
|  Reusable OWL Building Block: | [http://www.ontologydesignpatterns.org/cp/owl/basicplanexecution.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=http://www.ontologydesignpatterns.org/cp/owl/basicplanexecution.owl&message=OWL building block&from_page_id=2238&update=) (686) |
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


_The __BasicPlanExecution__ Content OP locally defines the following ontology elements:_



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __actionHasParticipant__ (owl:ObjectProperty) A relation between a Process and an Object, e.g. 'the avalanche hasParticipant a mass of snow', or 'the cooking of a cake hasParticipant an agent, some sugar, flour, etc.'. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[actionHasParticipant](http://ontologydesignpatterns.org/wiki/Submissions:BasicPlanExecution/actionHasParticipant "Submissions:BasicPlanExecution/actionHasParticipant") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __includesAction__ (owl:ObjectProperty) A relation between situations and persons, e.g. 'this morning I've prepared my coffee and had my fingers burnt' (i.e.: the preparation of my coffee this morning included a burning of my fingers). 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[includesAction](./BasicPlanExecution/includesAction.md "Submissions:BasicPlanExecution/includesAction") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __includesAgent__ (owl:ObjectProperty) A relation between situations and persons, e.g. 'this morning I've prepared my coffee and had my fingers burnt' (i.e.: the preparation of my coffee this morning included me). 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[includesAgent](./BasicPlanExecution/includesAgent.md "Submissions:BasicPlanExecution/includesAgent") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __includesObject__ (owl:ObjectProperty) A relation between situations and persons, e.g. 'this morning I've prepared my coffee and had my fingers burnt' (i.e.: the preparation of my coffee this morning included me). 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[includesObject](./BasicPlanExecution/includesObject.md "Submissions:BasicPlanExecution/includesObject") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __includesRegion__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[includesRegion](./BasicPlanExecution/includesRegion.md "Submissions:BasicPlanExecution/includesRegion") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isActionIncludedIn__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isActionIncludedIn](./BasicPlanExecution/isActionIncludedIn.md "Submissions:BasicPlanExecution/isActionIncludedIn") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isAgentIncludedIn__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isAgentIncludedIn](./BasicPlanExecution/isAgentIncludedIn.md "Submissions:BasicPlanExecution/isAgentIncludedIn") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isObjectIncludedIn__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isObjectIncludedIn](./BasicPlanExecution/isObjectIncludedIn.md "Submissions:BasicPlanExecution/isObjectIncludedIn") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isParticipantInAction__ (owl:ObjectProperty) A relation between an object and a process, e.g. 'a mass of snow is partipant in the avalanche', or 'an agent, some sugar, flour, etc. are participant in the cooking of a cake'. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isParticipantInAction](./BasicPlanExecution/isParticipantInAction.md "Submissions:BasicPlanExecution/isParticipantInAction") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isRegionIncludedIn__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isRegionIncludedIn](./BasicPlanExecution/isRegionIncludedIn.md "Submissions:BasicPlanExecution/isRegionIncludedIn") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __Action__ (owl:Class) An Event with at least one Agent that isParticipantIn, and that executes a Task that typically isDefinedIn a Plan, Workflow, Project, etc. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[Action](../Action/Action.md "Submissions:BasicPlanExecution/Action") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __PlanExecution__ (owl:Class) Plan executions are situations that proactively satisfy a plan. Subplan executions are proper parts of the whole plan execution. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[PlanExecution](./BasicPlanExecution.md "Submissions:BasicPlanExecution/PlanExecution") page_
#  Additional information


The basic plans execution content ontology design pattern represents the execution of a plan and the entity that participate in such an execution. This CP is the composition of other CPs: situation and region. Furthermore, it expands such CPs with ontology elements that are partial clones of elements from the DOCLE Ultra Lite and the Plans Lite ontologies.



#  Scenarios



__Scenarios about BasicPlanExecution__
No scenario is added to this Content OP.




#  Reviews



__Reviews about BasicPlanExecution__
There is no review about this proposal.
This revision (revision ID __9067__) takes in account the reviews: none


Other info at [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:BasicPlanExecution&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:BasicPlanExecution&action=evaluation")




  




#  Modeling issues



__Modeling issues about BasicPlanExecution__
There is no Modeling issue related to this proposal.




  




#  References
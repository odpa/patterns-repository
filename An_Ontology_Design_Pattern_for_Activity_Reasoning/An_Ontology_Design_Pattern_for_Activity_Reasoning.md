#  Graphical representation


__Diagram__




[![Image:Activity3_small.png](./Activity3_small.png)](../Image/Activity3_small.png.md "Image:Activity3_small.png")




#  General description




|  |  |
| --- | --- |
|  Name: |  Activity Pattern |
|  Submitted by: | [YingjieHu](../User/YingjieHu.md "User:YingjieHu") |
|  Also Known As: |  |
|  Intent: |  To incorporate the general two perspectives of activities: a workflow perspective, which are often observed in planning-related applications, and a spatiotemporal perspective, which are often found in geographic activity analysis. |
|  Domains: | [Workflow](../Community/Workflow.md "Community:Workflow"), [General](../Community/General.md "Community:General") |
|  Competency Questions: | <li> What are the requirements to complete an activity?</li><li> Which places are involved in the activity?</li><li> Can other planned activities/tasks be combined with this activity?</li><li> Which chained activities are necessary to achieve this activity?</li><li> Which activities are afforded by specific places?</li><li> Where and when to acquire an activity-relevant object?</li> |
|  Solution description: |  Activity is an important concept in many fields, and a number of activity-related ontologies have been developed. While suitable for their designated use cases, these ontologies cannot be easily generalized to other applications. This work aims at providing a generic ontology design pattern to model the common core of activities in different domains. Such a pattern can be used as a building block to construct more specific activity ontologies. |
|  Reusable OWL Building Block: | [http://descartes-core.org/ontologies/activities/1.0/ActivityPattern.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=http://descartes-core.org/ontologies/activities/1.0/ActivityPattern.owl&message=OWL building block&from_page_id=3755&update=) (835) |
|  Consequences: |  Only two perspectives for activities are included in this pattern. While these two perspectives are commonly observed in existing work, other views toward activities may also need to be supported in future work. |
|  Scenarios: |  Activity or task planning. Help find out which activities should be completed before other activities.Activity decomposition. Find out what are the sub-activities that constitute the super activity.Spatiotemporal queries. Find out the activities that happen at particular locations and time. |
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


_The __An Ontology Design Pattern for Activity Reasoning__ Content OP locally defines the following ontology elements:_



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasDependent__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasDependent](./An_Ontology_Design_Pattern_for_Activity_Reasoning/hasDependent.md "Submissions:An Ontology Design Pattern for Activity Reasoning/hasDependent") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasOutcome__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasOutcome](./An_Ontology_Design_Pattern_for_Activity_Reasoning/hasOutcome.md "Submissions:An Ontology Design Pattern for Activity Reasoning/hasOutcome") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasPart__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasPart](./An_Ontology_Design_Pattern_for_Activity_Reasoning/hasPart.md "Submissions:An Ontology Design Pattern for Activity Reasoning/hasPart") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasParticipant__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasParticipant](./An_Ontology_Design_Pattern_for_Activity_Reasoning/hasParticipant.md "Submissions:An Ontology Design Pattern for Activity Reasoning/hasParticipant") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasRequirement__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasRequirement](./An_Ontology_Design_Pattern_for_Activity_Reasoning/hasRequirement.md "Submissions:An Ontology Design Pattern for Activity Reasoning/hasRequirement") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isDependentOf__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isDependentOf](./An_Ontology_Design_Pattern_for_Activity_Reasoning/isDependentOf.md "Submissions:An Ontology Design Pattern for Activity Reasoning/isDependentOf") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isPartOf__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isPartOf](./An_Ontology_Design_Pattern_for_Activity_Reasoning/isPartOf.md "Submissions:An Ontology Design Pattern for Activity Reasoning/isPartOf") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isPrecededBy__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isPrecededBy](./An_Ontology_Design_Pattern_for_Activity_Reasoning/isPrecededBy.md "Submissions:An Ontology Design Pattern for Activity Reasoning/isPrecededBy") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isRequirementOf__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isRequirementOf](./An_Ontology_Design_Pattern_for_Activity_Reasoning/isRequirementOf.md "Submissions:An Ontology Design Pattern for Activity Reasoning/isRequirementOf") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __precedes__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[precedes](./An_Ontology_Design_Pattern_for_Activity_Reasoning/precedes.md "Submissions:An Ontology Design Pattern for Activity Reasoning/precedes") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __produces__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[produces](./An_Ontology_Design_Pattern_for_Activity_Reasoning/produces.md "Submissions:An Ontology Design Pattern for Activity Reasoning/produces") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __supports__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[supports](./An_Ontology_Design_Pattern_for_Activity_Reasoning/supports.md "Submissions:An Ontology Design Pattern for Activity Reasoning/supports") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __takesPlaceAt__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[takesPlaceAt](./An_Ontology_Design_Pattern_for_Activity_Reasoning/takesPlaceAt.md "Submissions:An Ontology Design Pattern for Activity Reasoning/takesPlaceAt") page_
[![DatatypeProperty](./20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif.md "DatatypeProperty") __hasDuration__ (owl:DatatypeProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasDuration](./An_Ontology_Design_Pattern_for_Activity_Reasoning/hasDuration.md "Submissions:An Ontology Design Pattern for Activity Reasoning/hasDuration") page_
[![DatatypeProperty](./20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif.md "DatatypeProperty") __hasEnd__ (owl:DatatypeProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasEnd](./An_Ontology_Design_Pattern_for_Activity_Reasoning/hasEnd.md "Submissions:An Ontology Design Pattern for Activity Reasoning/hasEnd") page_
[![DatatypeProperty](./20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif.md "DatatypeProperty") __hasStart__ (owl:DatatypeProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasStart](./An_Ontology_Design_Pattern_for_Activity_Reasoning/hasStart.md "Submissions:An Ontology Design Pattern for Activity Reasoning/hasStart") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __Activity__ (owl:Class) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[Activity](./An_Ontology_Design_Pattern_for_Activity_Reasoning/Activity.md "Submissions:An Ontology Design Pattern for Activity Reasoning/Activity") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __FixedActivity__ (owl:Class) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[FixedActivity](./An_Ontology_Design_Pattern_for_Activity_Reasoning/FixedActivity.md "Submissions:An Ontology Design Pattern for Activity Reasoning/FixedActivity") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __FlexibleActivity__ (owl:Class) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[FlexibleActivity](./An_Ontology_Design_Pattern_for_Activity_Reasoning/FlexibleActivity.md "Submissions:An Ontology Design Pattern for Activity Reasoning/FlexibleActivity") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __Outcome__ (owl:Class) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[Outcome](./An_Ontology_Design_Pattern_for_Activity_Reasoning/hasOutcome.md "Submissions:An Ontology Design Pattern for Activity Reasoning/Outcome") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __Place__ (owl:Class) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[Place](../Place/Place.md "Submissions:An Ontology Design Pattern for Activity Reasoning/Place") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __Requirement__ (owl:Class) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[Requirement](./An_Ontology_Design_Pattern_for_Activity_Reasoning/hasRequirement.md "Submissions:An Ontology Design Pattern for Activity Reasoning/Requirement") page_
#  Additional information


While this pattern so far focuses on human activities, the agents that are involved in this pattern may also be other autonomous agents, such as animals.



#  Scenarios



__Scenarios about An Ontology Design Pattern for Activity Reasoning__
No scenario is added to this Content OP.




#  Reviews



__Reviews about An Ontology Design Pattern for Activity Reasoning__
There is no review about this proposal.
This revision (revision ID __12001__) takes in account the reviews: none


Other info at [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:An_Ontology_Design_Pattern_for_Activity_Reasoning&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:An_Ontology_Design_Pattern_for_Activity_Reasoning&action=evaluation")




  




#  Modeling issues



__Modeling issues about An Ontology Design Pattern for Activity Reasoning__
There is no Modeling issue related to this proposal.




  




#  References
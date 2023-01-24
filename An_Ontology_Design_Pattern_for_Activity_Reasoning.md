# 

 Graphical representation



__Diagram__ 





[![Image:Activity3_small.png](../images/d/d9/Activity3_small.png)](../Image/Activity3_small.png "Image:Activity3_small.png")





# 

 General description




|  |  |
| --- | --- |
|  Name:  |  Activity Pattern  |
|  Submitted by:  | [YingjieHu](../User/YingjieHu "User:YingjieHu")  |
|  Also Known As:  |  |
|  Intent:  |  To incorporate the general two perspectives of activities: a workflow perspective, which are often observed in planning-related applications, and a spatiotemporal perspective, which are often found in geographic activity analysis.  |
|  Domains:  | [Workflow](../Community/Workflow "Community:Workflow")  , [General](../Community/General "Community:General")  |
|  Competency Questions:  | <li>       What are the requirements to complete an activity?      </li><li>       Which places are involved in the activity?      </li><li>       Can other planned activities/tasks be combined with this activity?      </li><li>       Which chained activities are necessary to achieve this activity?      </li><li>       Which activities are afforded by specific places?      </li><li>       Where and when to acquire an activity-relevant object?      </li> |
|  Solution description:  |  Activity is an important concept in many fields, and a number of activity-related ontologies have been developed. While suitable for their designated use cases, these ontologies cannot be easily generalized to other applications. This work aims at providing a generic ontology design pattern to model the common core of activities in different domains. Such a pattern can be used as a building block to construct more specific activity ontologies.  |
|  Reusable OWL Building Block:  | [http://descartes-core.org/ontologies/activities/1.0/ActivityPattern.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=http://descartes-core.org/ontologies/activities/1.0/ActivityPattern.owl&message=OWL building block&from_page_id=3755&update=)  (835)  |
|  Consequences:  |  Only two perspectives for activities are included in this pattern. While these two perspectives are commonly observed in existing work, other views toward activities may also need to be supported in future work.  |
|  Scenarios:  |  Activity or task planning. Help find out which activities should be completed before other activities.Activity decomposition. Find out what are the sub-activities that constitute the super activity.Spatiotemporal queries. Find out the activities that happen at particular locations and time.  |
|  Known Uses:  |  |
|  Web References:  |  |
|  Other References:  |  |
|  Examples (OWL files):  |  |
|  Extracted From:  |  |
|  Reengineered From:  |  |
|  Has Components:  |  |
|  Specialization Of:  |  |
|  Related CPs:  |  |



  





# 

 Elements



_The
 __An Ontology Design Pattern for Activity Reasoning__ 
 Content OP locally defines the following ontology elements:_ 





[![ObjectProperty](../../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasDependent__ 
 (owl:ObjectProperty)
 
[![](../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasDependent](../Submissions/An_Ontology_Design_Pattern_for_Activity_Reasoning/hasDependent "Submissions:An Ontology Design Pattern for Activity Reasoning/hasDependent") 
 page_ 



[![ObjectProperty](../../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasOutcome__ 
 (owl:ObjectProperty)
 
[![](../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasOutcome](../Submissions/An_Ontology_Design_Pattern_for_Activity_Reasoning/hasOutcome "Submissions:An Ontology Design Pattern for Activity Reasoning/hasOutcome") 
 page_ 



[![ObjectProperty](../../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasPart__ 
 (owl:ObjectProperty)
 
[![](../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasPart](../Submissions/An_Ontology_Design_Pattern_for_Activity_Reasoning/hasPart "Submissions:An Ontology Design Pattern for Activity Reasoning/hasPart") 
 page_ 



[![ObjectProperty](../../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasParticipant__ 
 (owl:ObjectProperty)
 
[![](../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasParticipant](../Submissions/An_Ontology_Design_Pattern_for_Activity_Reasoning/hasParticipant "Submissions:An Ontology Design Pattern for Activity Reasoning/hasParticipant") 
 page_ 



[![ObjectProperty](../../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasRequirement__ 
 (owl:ObjectProperty)
 
[![](../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasRequirement](../Submissions/An_Ontology_Design_Pattern_for_Activity_Reasoning/hasRequirement "Submissions:An Ontology Design Pattern for Activity Reasoning/hasRequirement") 
 page_ 



[![ObjectProperty](../../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__isDependentOf__ 
 (owl:ObjectProperty)
 
[![](../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[isDependentOf](../Submissions/An_Ontology_Design_Pattern_for_Activity_Reasoning/isDependentOf "Submissions:An Ontology Design Pattern for Activity Reasoning/isDependentOf") 
 page_ 



[![ObjectProperty](../../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__isPartOf__ 
 (owl:ObjectProperty)
 
[![](../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[isPartOf](../Submissions/An_Ontology_Design_Pattern_for_Activity_Reasoning/isPartOf "Submissions:An Ontology Design Pattern for Activity Reasoning/isPartOf") 
 page_ 



[![ObjectProperty](../../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__isPrecededBy__ 
 (owl:ObjectProperty)
 
[![](../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[isPrecededBy](../Submissions/An_Ontology_Design_Pattern_for_Activity_Reasoning/isPrecededBy "Submissions:An Ontology Design Pattern for Activity Reasoning/isPrecededBy") 
 page_ 



[![ObjectProperty](../../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__isRequirementOf__ 
 (owl:ObjectProperty)
 
[![](../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[isRequirementOf](../Submissions/An_Ontology_Design_Pattern_for_Activity_Reasoning/isRequirementOf "Submissions:An Ontology Design Pattern for Activity Reasoning/isRequirementOf") 
 page_ 



[![ObjectProperty](../../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__precedes__ 
 (owl:ObjectProperty)
 
[![](../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[precedes](../Submissions/An_Ontology_Design_Pattern_for_Activity_Reasoning/precedes "Submissions:An Ontology Design Pattern for Activity Reasoning/precedes") 
 page_ 



[![ObjectProperty](../../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__produces__ 
 (owl:ObjectProperty)
 
[![](../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[produces](../Submissions/An_Ontology_Design_Pattern_for_Activity_Reasoning/produces "Submissions:An Ontology Design Pattern for Activity Reasoning/produces") 
 page_ 



[![ObjectProperty](../../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__supports__ 
 (owl:ObjectProperty)
 
[![](../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[supports](../Submissions/An_Ontology_Design_Pattern_for_Activity_Reasoning/supports "Submissions:An Ontology Design Pattern for Activity Reasoning/supports") 
 page_ 



[![ObjectProperty](../../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__takesPlaceAt__ 
 (owl:ObjectProperty)
 
[![](../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[takesPlaceAt](../Submissions/An_Ontology_Design_Pattern_for_Activity_Reasoning/takesPlaceAt "Submissions:An Ontology Design Pattern for Activity Reasoning/takesPlaceAt") 
 page_ 



[![DatatypeProperty](../../../images/thumb/a/a5/DatatypeProperty.gif/20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif "DatatypeProperty")
__hasDuration__ 
 (owl:DatatypeProperty)
 
[![](../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasDuration](../Submissions/An_Ontology_Design_Pattern_for_Activity_Reasoning/hasDuration "Submissions:An Ontology Design Pattern for Activity Reasoning/hasDuration") 
 page_ 



[![DatatypeProperty](../../../images/thumb/a/a5/DatatypeProperty.gif/20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif "DatatypeProperty")
__hasEnd__ 
 (owl:DatatypeProperty)
 
[![](../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasEnd](../Submissions/An_Ontology_Design_Pattern_for_Activity_Reasoning/hasEnd "Submissions:An Ontology Design Pattern for Activity Reasoning/hasEnd") 
 page_ 



[![DatatypeProperty](../../../images/thumb/a/a5/DatatypeProperty.gif/20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif "DatatypeProperty")
__hasStart__ 
 (owl:DatatypeProperty)
 
[![](../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasStart](../Submissions/An_Ontology_Design_Pattern_for_Activity_Reasoning/hasStart "Submissions:An Ontology Design Pattern for Activity Reasoning/hasStart") 
 page_ 



[![Class](../../../../../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__Activity__ 
 (owl:Class)
 
[![](../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[Activity](../Submissions/An_Ontology_Design_Pattern_for_Activity_Reasoning/Activity "Submissions:An Ontology Design Pattern for Activity Reasoning/Activity") 
 page_ 



[![Class](../../../../../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__FixedActivity__ 
 (owl:Class)
 
[![](../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[FixedActivity](../Submissions/An_Ontology_Design_Pattern_for_Activity_Reasoning/FixedActivity "Submissions:An Ontology Design Pattern for Activity Reasoning/FixedActivity") 
 page_ 



[![Class](../../../../../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__FlexibleActivity__ 
 (owl:Class)
 
[![](../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[FlexibleActivity](../Submissions/An_Ontology_Design_Pattern_for_Activity_Reasoning/FlexibleActivity "Submissions:An Ontology Design Pattern for Activity Reasoning/FlexibleActivity") 
 page_ 



[![Class](../../../../../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__Outcome__ 
 (owl:Class)
 
[![](../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[Outcome](../Submissions/An_Ontology_Design_Pattern_for_Activity_Reasoning/Outcome "Submissions:An Ontology Design Pattern for Activity Reasoning/Outcome") 
 page_ 



[![Class](../../../../../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__Place__ 
 (owl:Class)
 
[![](../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[Place](../Submissions/An_Ontology_Design_Pattern_for_Activity_Reasoning/Place "Submissions:An Ontology Design Pattern for Activity Reasoning/Place") 
 page_ 



[![Class](../../../../../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__Requirement__ 
 (owl:Class)
 
[![](../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[Requirement](../Submissions/An_Ontology_Design_Pattern_for_Activity_Reasoning/Requirement "Submissions:An Ontology Design Pattern for Activity Reasoning/Requirement") 
 page_ 


# 

 Additional information



 While this pattern so far focuses on human activities, the agents that are involved in this pattern may also be other autonomous agents, such as animals.
 



# 

 Scenarios




__Scenarios about An Ontology Design Pattern for Activity Reasoning__ 


 No scenario is added to this Content OP.
 




# 

 Reviews




__Reviews about An Ontology Design Pattern for Activity Reasoning__ 


 There is no review about this proposal.
This revision (revision ID
 __12001__ 
 ) takes in account the reviews: none
 



 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:An_Ontology_Design_Pattern_for_Activity_Reasoning&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:An_Ontology_Design_Pattern_for_Activity_Reasoning&action=evaluation") 





  





# 

 Modeling issues




__Modeling issues about An Ontology Design Pattern for Activity Reasoning__ 


 There is no Modeling issue related to this proposal.
 




  





# 

 References
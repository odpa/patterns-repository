# 

 Graphical representation



__Diagram__ 





[![Image:ODP_new.png](../images/f/f8/ODP_new.png)](../Image/ODP_new.png "Image:ODP_new.png")





# 

 General description




|  |  |
| --- | --- |
|  Name:  |  Pollution  |
|  Submitted by:  | [SaadAhmad](../User/SaadAhmad "User:SaadAhmad")  |
|  Also Known As:  |  |
|  Intent:  |  The Pollution ontology design pattern (ODP) intends to model the pollution, the pollutants and their observations at various spatio-temporal points. It also captures the information about the various direct and indirect sources of pollution. The Pollution ODP makes use of Trajectory, Observation and Stub-Metapattern ODPs.  |
|  Domains:  |  |
|  Competency Questions:  | <li>       1. What are the contributors of the pollution? 2. What is the pollutant concentration at a particular time and place? 3. What are the carriers that contributed to the pollution? 4. What are the pollutants carried by a carrier? 5. What are the prescribed standards for a particular pollutant? 6. What is the trajectory of a carrier for a pollutant?      </li> |
|  Solution description:  |  The pollution ODP uses Trajectory, Observation and Stub\_Metapattern ODP at its core to represent pollution. Pollution is the core concept in the ODP and is connected to multiple contributors, which can have spatio-temporal characteristics.  |
|  Reusable OWL Building Block:  | [https://github.com/kracr/aq-structured-platform/blob/main/Ontology/PollutionODP/PollutionODP.owl.xml](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=https://github.com/kracr/aq-structured-platform/blob/main/Ontology/PollutionODP/PollutionODP.owl.xml&message=OWL building block&from_page_id=4821&update=)  (0)  |
|  Consequences:  |  This ODP is a first for modelling pollution and is an improvement over some of the ontologies that focus on very specific aspects of pollution. It allows to model pollution sources as well as monitor the pollution at spatio-temporal points.  |
|  Scenarios:  |  1. Which pollutant sources contribute to a wind stream which flows into a place? 2. What was the precipitation level on 23rd April at a particular location? 3. What locations have an AQI beyond a certain threshold in a certain region in a given month?  |
|  Known Uses:  |  |
|  Web References:  |  |
|  Other References:  |  |
|  Examples (OWL files):  |  |
|  Extracted From:  |  |
|  Reengineered From:  |  |
|  Has Components:  | <li><a href="Submissions%253ATrajectory.html" title="Submissions:Trajectory">        Submissions:Trajectory       </a></li><li><a href="Submissions%253AObservation.html" title="Submissions:Observation">        Submissions:Observation       </a></li><li><a href="Submissions%253AStub_Metapattern.html" title="Submissions:Stub Metapattern">        Submissions:Stub_Metapattern       </a></li> |
|  Specialization Of:  |  |
|  Related CPs:  |  |



  





# 

 Elements



_The
 __Pollution__ 
 Content OP locally defines the following ontology elements:_ 





__Authors__ 
 (owl:AnnotationProperty)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[Authors](../Submissions/Pollution/Authors "Submissions:Pollution/Authors") 
 page_ 



[![ObjectProperty](../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__atPlace__ 
 (owl:ObjectProperty)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[atPlace](../Submissions/Pollution/atPlace "Submissions:Pollution/atPlace") 
 page_ 



[![ObjectProperty](../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__atTime__ 
 (owl:ObjectProperty)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[atTime](../Submissions/Pollution/atTime "Submissions:Pollution/atTime") 
 page_ 



[![ObjectProperty](../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__carriesPollutant__ 
 (owl:ObjectProperty)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[carriesPollutant](../Submissions/Pollution/carriesPollutant "Submissions:Pollution/carriesPollutant") 
 page_ 



[![ObjectProperty](../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__endsAt__ 
 (owl:ObjectProperty) Connects a segment to the point it ends at.
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[endsAt](../Submissions/Pollution/endsAt "Submissions:Pollution/endsAt") 
 page_ 



[![ObjectProperty](../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasContributor__ 
 (owl:ObjectProperty)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasContributor](../Submissions/Pollution/hasContributor "Submissions:Pollution/hasContributor") 
 page_ 



[![ObjectProperty](../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasObservation__ 
 (owl:ObjectProperty)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasObservation](../Submissions/Pollution/hasObservation "Submissions:Pollution/hasObservation") 
 page_ 



[![ObjectProperty](../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasPoint__ 
 (owl:ObjectProperty) Relating the trajectory to each of its points.
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasPoint](../Submissions/Pollution/hasPoint "Submissions:Pollution/hasPoint") 
 page_ 



[![ObjectProperty](../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasPrescribedStandard__ 
 (owl:ObjectProperty)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasPrescribedStandard](../Submissions/Pollution/hasPrescribedStandard "Submissions:Pollution/hasPrescribedStandard") 
 page_ 



[![ObjectProperty](../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasSegment__ 
 (owl:ObjectProperty) Relating the trajectory to each of its segments.
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasSegment](../Submissions/Pollution/hasSegment "Submissions:Pollution/hasSegment") 
 page_ 



[![ObjectProperty](../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasTrajectory__ 
 (owl:ObjectProperty) Anything that has a trajectory can use this property to connect it to the trajectory instance
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasTrajectory](../Submissions/Pollution/hasTrajectory "Submissions:Pollution/hasTrajectory") 
 page_ 



[![ObjectProperty](../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__nextPoint__ 
 (owl:ObjectProperty) Relates one point to the immediately following point in the sequence.
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[nextPoint](../Submissions/Pollution/nextPoint "Submissions:Pollution/nextPoint") 
 page_ 



[![ObjectProperty](../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__startsFrom__ 
 (owl:ObjectProperty) Connects a segment to the point it starts from.
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[startsFrom](../Submissions/Pollution/startsFrom "Submissions:Pollution/startsFrom") 
 page_ 



[![Class](../../../../../../../../../../../../../../../../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__Carrier__ 
 (owl:Class) Represents streams which carry pollutants to a particular place.
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[Carrier](../Submissions/Pollution/Carrier "Submissions:Pollution/Carrier") 
 page_ 



[![Class](../../../../../../../../../../../../../../../../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__Contributor__ 
 (owl:Class)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[Contributor](../Submissions/Pollution/Contributor "Submissions:Pollution/Contributor") 
 page_ 



[![Class](../../../../../../../../../../../../../../../../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__DirectContributor__ 
 (owl:Class) Represents concepts which directly represent pollution. For example the concentration of pollutants at a particular spatio-temporal point.
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[DirectContributor](../Submissions/Pollution/DirectContributor "Submissions:Pollution/DirectContributor") 
 page_ 



[![Class](../../../../../../../../../../../../../../../../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__EndingPoint__ 
 (owl:Class)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[EndingPoint](../Submissions/Pollution/EndingPoint "Submissions:Pollution/EndingPoint") 
 page_ 



[![Class](../../../../../../../../../../../../../../../../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__IndirectContributor__ 
 (owl:Class) Represents concepts which indirectly contribute to pollution of a place. These do not directly represent pollution but have properties which can affect the pollution, for example by changing the concentration of pollutants at a spatio-temporal point.
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[IndirectContributor](../Submissions/Pollution/IndirectContributor "Submissions:Pollution/IndirectContributor") 
 page_ 



[![Class](../../../../../../../../../../../../../../../../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__NaturalResourcePollution__ 
 (owl:Class) Represents pollution on natural resources. Which means the pollution that affects natural resources like air, water, land, etc.
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[NaturalResourcePollution](../Submissions/Pollution/NaturalResourcePollution "Submissions:Pollution/NaturalResourcePollution") 
 page_ 



[![Class](../../../../../../../../../../../../../../../../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__NonNaturalResourcePollution__ 
 (owl:Class) Represents pollution which does not represent natural resource. Examples include, sound, light, space debris, radioactive pollution, thermal pollution.
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[NonNaturalResourcePollution](../Submissions/Pollution/NonNaturalResourcePollution "Submissions:Pollution/NonNaturalResourcePollution") 
 page_ 



[![Class](../../../../../../../../../../../../../../../../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__Observation__ 
 (owl:Class) Observation represents a spatio-temporal observation of pollutants under time and place parameters.
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[Observation](../Submissions/Pollution/Observation "Submissions:Pollution/Observation") 
 page_ 



[![Class](../../../../../../../../../../../../../../../../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__PlaceEntity__ 
 (owl:Class)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[PlaceEntity](../Submissions/Pollution/PlaceEntity "Submissions:Pollution/PlaceEntity") 
 page_ 



[![Class](../../../../../../../../../../../../../../../../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__Pollutant__ 
 (owl:Class) Represents various pollutants which contaminate the environment and directly represnt/contribute to pollution. Additionally a carrier's trajecectory point may pick up pollutants from a spatio-temporal point, in which case, it is represented by the sub-property carriesPollutant.
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[Pollutant](../Submissions/Pollution/Pollutant "Submissions:Pollution/Pollutant") 
 page_ 



[![Class](../../../../../../../../../../../../../../../../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__Pollution__ 
 (owl:Class) Represnents the notion of Pollution which includes observation of pollutants at spatio-temporal points or the contributors to the pollution which may be spatio-temporal in nature.
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[Pollution](../Submissions/Pollution/Pollution "Submissions:Pollution/Pollution") 
 page_ 



[![Class](../../../../../../../../../../../../../../../../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__PrescribedStandardForPollutant__ 
 (owl:Class)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[PrescribedStandardForPollutant](../Submissions/Pollution/PrescribedStandardForPollutant "Submissions:Pollution/PrescribedStandardForPollutant") 
 page_ 



[![Class](../../../../../../../../../../../../../../../../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__StartingPoint__ 
 (owl:Class)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[StartingPoint](../Submissions/Pollution/StartingPoint "Submissions:Pollution/StartingPoint") 
 page_ 



[![Class](../../../../../../../../../../../../../../../../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__TimeEntity__ 
 (owl:Class)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[TimeEntity](../Submissions/Pollution/TimeEntity "Submissions:Pollution/TimeEntity") 
 page_ 



[![Class](../../../../../../../../../../../../../../../../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__Trajectory__ 
 (owl:Class) Represents a trajectory of points. Examples include drainage/sewage trajectory or air stream trajectory.
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[Trajectory](../Submissions/Pollution/Trajectory "Submissions:Pollution/Trajectory") 
 page_ 



[![Class](../../../../../../../../../../../../../../../../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__TrajectoryPoint__ 
 (owl:Class) A collection of spatio-temporal points represents a trajectory
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[TrajectoryPoint](../Submissions/Pollution/TrajectoryPoint "Submissions:Pollution/TrajectoryPoint") 
 page_ 



[![Class](../../../../../../../../../../../../../../../../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__TrajectorySegment__ 
 (owl:Class) A subset of spatio-temporal trajectory points represent a TrajectorySegment
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[TrajectorySegment](../Submissions/Pollution/TrajectorySegment "Submissions:Pollution/TrajectorySegment") 
 page_ 


# 

 Additional information



 This ontology is an attempt at a ODP designed to model Pollution. Pollution can be defined as
 



# 

 Scenarios




__Scenarios about Pollution__ 


 No scenario is added to this Content OP.
 




# 

 Reviews




__Reviews about Pollution__ 


 There is no review about this proposal.
This revision (revision ID
 __14244__ 
 ) takes in account the reviews: none
 



 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Pollution&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Pollution&action=evaluation") 





  





# 

 Modeling issues




__Modeling issues about Pollution__ 


 There is no Modeling issue related to this proposal.
 




  





# 

 References
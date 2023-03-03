#  Graphical representation


__Diagram__




[![Image:ODP_new.png](./ODP_new.png)](../Image/ODP_new.png.md "Image:ODP_new.png")




#  General description




|  |  |
| --- | --- |
|  Name: |  Pollution |
|  Submitted by: | [SaadAhmad](../User/SaadAhmad.md "User:SaadAhmad") |
|  Also Known As: |  |
|  Intent: |  The Pollution ontology design pattern (ODP) intends to model the pollution, the pollutants and their observations at various spatio-temporal points. It also captures the information about the various direct and indirect sources of pollution. The Pollution ODP makes use of Trajectory, Observation and Stub-Metapattern ODPs. |
|  Domains: |  |
|  Competency Questions: | <li> 1. What are the contributors of the pollution? 2. What is the pollutant concentration at a particular time and place? 3. What are the carriers that contributed to the pollution? 4. What are the pollutants carried by a carrier? 5. What are the prescribed standards for a particular pollutant? 6. What is the trajectory of a carrier for a pollutant?</li> |
|  Solution description: |  The pollution ODP uses Trajectory, Observation and Stub\_Metapattern ODP at its core to represent pollution. Pollution is the core concept in the ODP and is connected to multiple contributors, which can have spatio-temporal characteristics. |
|  Reusable OWL Building Block: | [https://github.com/kracr/aq-structured-platform/blob/main/Ontology/PollutionODP/PollutionODP.owl.xml](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=https://github.com/kracr/aq-structured-platform/blob/main/Ontology/PollutionODP/PollutionODP.owl.xml&message=OWL building block&from_page_id=4821&update=) (0) |
|  Consequences: |  This ODP is a first for modelling pollution and is an improvement over some of the ontologies that focus on very specific aspects of pollution. It allows to model pollution sources as well as monitor the pollution at spatio-temporal points. |
|  Scenarios: |  1. Which pollutant sources contribute to a wind stream which flows into a place? 2. What was the precipitation level on 23rd April at a particular location? 3. What locations have an AQI beyond a certain threshold in a certain region in a given month? |
|  Known Uses: |  |
|  Web References: |  |
|  Other References: |  |
|  Examples (OWL files): |  |
|  Extracted From: |  |
|  Reengineered From: |  |
|  Has Components: | <li><a href="../Trajectory/Trajectory.md" title="Submissions:Trajectory">Submissions:Trajectory</a></li><li><a href="../AquaticResourceObservation/AquaticResourceObservation.md" title="Submissions:Observation">Submissions:Observation</a></li><li><a href="../Stub_Metapattern/Stub_Metapattern.md" title="Submissions:Stub Metapattern">Submissions:Stub_Metapattern</a></li> |
|  Specialization Of: |  |
|  Related CPs: |  |


  




#  Elements


_The __Pollution__ Content OP locally defines the following ontology elements:_



__Authors__ (owl:AnnotationProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[Authors](./Pollution/Authors.md "Submissions:Pollution/Authors") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __atPlace__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[atPlace](./Pollution/atPlace.md "Submissions:Pollution/atPlace") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __atTime__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[atTime](./Pollution/atTime.md "Submissions:Pollution/atTime") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __carriesPollutant__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[carriesPollutant](./Pollution/carriesPollutant.md "Submissions:Pollution/carriesPollutant") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __endsAt__ (owl:ObjectProperty) Connects a segment to the point it ends at. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[endsAt](./Pollution/endsAt.md "Submissions:Pollution/endsAt") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasContributor__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasContributor](./Pollution/hasContributor.md "Submissions:Pollution/hasContributor") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasObservation__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasObservation](./Observation/hasObservation.md "Submissions:Pollution/hasObservation") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasPoint__ (owl:ObjectProperty) Relating the trajectory to each of its points. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasPoint](./Pollution/hasPoint.md "Submissions:Pollution/hasPoint") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasPrescribedStandard__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasPrescribedStandard](./Pollution/hasPrescribedStandard.md "Submissions:Pollution/hasPrescribedStandard") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasSegment__ (owl:ObjectProperty) Relating the trajectory to each of its segments. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasSegment](./Pollution/hasSegment.md "Submissions:Pollution/hasSegment") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasTrajectory__ (owl:ObjectProperty) Anything that has a trajectory can use this property to connect it to the trajectory instance 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasTrajectory](./Pollution/hasTrajectory.md "Submissions:Pollution/hasTrajectory") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __nextPoint__ (owl:ObjectProperty) Relates one point to the immediately following point in the sequence. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[nextPoint](./Pollution/nextPoint.md "Submissions:Pollution/nextPoint") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __startsFrom__ (owl:ObjectProperty) Connects a segment to the point it starts from. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[startsFrom](./Pollution/startsFrom.md "Submissions:Pollution/startsFrom") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __Carrier__ (owl:Class) Represents streams which carry pollutants to a particular place. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[Carrier](./Pollution/Carrier.md "Submissions:Pollution/Carrier") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __Contributor__ (owl:Class) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[Contributor](./Pollution/Contributor.md "Submissions:Pollution/Contributor") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __DirectContributor__ (owl:Class) Represents concepts which directly represent pollution. For example the concentration of pollutants at a particular spatio-temporal point. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[DirectContributor](./Pollution/DirectContributor.md "Submissions:Pollution/DirectContributor") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __EndingPoint__ (owl:Class) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[EndingPoint](./Pollution/EndingPoint.md "Submissions:Pollution/EndingPoint") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __IndirectContributor__ (owl:Class) Represents concepts which indirectly contribute to pollution of a place. These do not directly represent pollution but have properties which can affect the pollution, for example by changing the concentration of pollutants at a spatio-temporal point. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[IndirectContributor](./Pollution/IndirectContributor.md "Submissions:Pollution/IndirectContributor") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __NaturalResourcePollution__ (owl:Class) Represents pollution on natural resources. Which means the pollution that affects natural resources like air, water, land, etc. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[NaturalResourcePollution](./Pollution/NaturalResourcePollution.md "Submissions:Pollution/NaturalResourcePollution") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __NonNaturalResourcePollution__ (owl:Class) Represents pollution which does not represent natural resource. Examples include, sound, light, space debris, radioactive pollution, thermal pollution. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[NonNaturalResourcePollution](./Pollution/NonNaturalResourcePollution.md "Submissions:Pollution/NonNaturalResourcePollution") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __Observation__ (owl:Class) Observation represents a spatio-temporal observation of pollutants under time and place parameters. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[Observation](./AquaticResourceObservation.md "Submissions:Pollution/Observation") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __PlaceEntity__ (owl:Class) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[PlaceEntity](./Pollution/PlaceEntity.md "Submissions:Pollution/PlaceEntity") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __Pollutant__ (owl:Class) Represents various pollutants which contaminate the environment and directly represnt/contribute to pollution. Additionally a carrier's trajecectory point may pick up pollutants from a spatio-temporal point, in which case, it is represented by the sub-property carriesPollutant. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[Pollutant](./Pollution/carriesPollutant.md "Submissions:Pollution/Pollutant") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __Pollution__ (owl:Class) Represnents the notion of Pollution which includes observation of pollutants at spatio-temporal points or the contributors to the pollution which may be spatio-temporal in nature. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[Pollution](./Pollution.md "Submissions:Pollution/Pollution") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __PrescribedStandardForPollutant__ (owl:Class) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[PrescribedStandardForPollutant](./Pollution/PrescribedStandardForPollutant.md "Submissions:Pollution/PrescribedStandardForPollutant") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __StartingPoint__ (owl:Class) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[StartingPoint](./Pollution/StartingPoint.md "Submissions:Pollution/StartingPoint") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __TimeEntity__ (owl:Class) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[TimeEntity](./Pollution/TimeEntity.md "Submissions:Pollution/TimeEntity") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __Trajectory__ (owl:Class) Represents a trajectory of points. Examples include drainage/sewage trajectory or air stream trajectory. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[Trajectory](../Trajectory/Trajectory.md "Submissions:Pollution/Trajectory") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __TrajectoryPoint__ (owl:Class) A collection of spatio-temporal points represents a trajectory 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[TrajectoryPoint](./Pollution/TrajectoryPoint.md "Submissions:Pollution/TrajectoryPoint") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __TrajectorySegment__ (owl:Class) A subset of spatio-temporal trajectory points represent a TrajectorySegment 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[TrajectorySegment](./Pollution/TrajectorySegment.md "Submissions:Pollution/TrajectorySegment") page_
#  Additional information


This ontology is an attempt at a ODP designed to model Pollution. Pollution can be defined as



#  Scenarios



__Scenarios about Pollution__
No scenario is added to this Content OP.




#  Reviews



__Reviews about Pollution__
There is no review about this proposal.
This revision (revision ID __14244__) takes in account the reviews: none


Other info at [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Pollution&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Pollution&action=evaluation")




  




#  Modeling issues



__Modeling issues about Pollution__
There is no Modeling issue related to this proposal.




  




#  References
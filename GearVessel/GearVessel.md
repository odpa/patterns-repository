#  Graphical representation


__Diagram__
_(this article has no graphical representation)_



#  General description




|  |  |
| --- | --- |
|  Name: |  GearVessel |
|  Submitted by: | [AldoGangemi](../User/AldoGangemi.md "User:AldoGangemi") |
|  Also Known As: |  |
|  Intent: |  to represent types of fishing gear with regard to the types of vessel they can be mounted on |
|  Domains: | [Fishery](../Community/Fishery.md "Community:Fishery") |
|  Competency Questions: | <li> what vessel type can equip what gear type?</li> |
|  Solution description: |  - |
|  Reusable OWL Building Block: | [http://www.ontologydesignpatterns.org/cp/owl/fsdas/gearvessel.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=http://www.ontologydesignpatterns.org/cp/owl/fsdas/gearvessel.owl&message=OWL building block&from_page_id=867&update=) (644) |
|  Consequences: |  This is a straightforward pattern that describes vessel types in terms of the fishing gear they can be equipped with. The original usesGearType object property has been reworked, in that subclass restrictions for affected classes have been replacd with domain and range axiom. This also allows the definition of inverse property usedByVesselType. |
|  Scenarios: |  give me the vesseltypes that use 'trawls' |
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


_The __GearVessel__ Content OP locally defines the following ontology elements:_



[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __VesselType__ (owl:Class) Vessel types are conceptual entities. 
Mappable to fi:VesseltypeRef 



 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[VesselType](./GearVessel/usedByVesselType.md "Submissions:GearVessel/VesselType") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __GearType__ (owl:Class) Gear types are conceptual entities that are characterized together with AquaticSpecies that are either targeted or can be incidentally caught. 
Mappable to fi:GeartypeRef 



 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[GearType](./GearSpecies/GearType.md "Submissions:GearVessel/GearType") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __usesGearType__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[usesGearType](./GearVessel/usesGearType.md "Submissions:GearVessel/usesGearType") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __usedByVesselType__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[usedByVesselType](./GearVessel/usedByVesselType.md "Submissions:GearVessel/usedByVesselType") page_
#  Additional information


(type): [http://www.w3.org/2002/07/owl#Ontology](http://www.w3.org/2002/07/owl#Ontology "http://www.w3.org/2002/07/owl#Ontology")


(versionInfo): 1.0


(imports): [http://www.ontologydesignpatterns.org/schemas/cpannotationschema.owl](http://www.ontologydesignpatterns.org/schemas/cpannotationschema.owl "http://www.ontologydesignpatterns.org/schemas/cpannotationschema.owl")


(versionInfo): Created by Alessandro Adamou



#  Scenarios



__Scenarios about GearVessel__
No scenario is added to this Content OP.




#  Reviews



__Reviews about GearVessel__
There is no review about this proposal.
This revision (revision ID __9090__) takes in account the reviews: none


Other info at [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:GearVessel&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:GearVessel&action=evaluation")




  




#  Modeling issues



__Modeling issues about GearVessel__
There is no Modeling issue related to this proposal.




  




#  References
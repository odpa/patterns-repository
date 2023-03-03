#  Graphical representation


__Diagram__




[![Image:Gearspecies.jpg](./Gearspecies.jpg)](../Image/Gearspecies.jpg.md "Image:Gearspecies.jpg")




#  General description




|  |  |
| --- | --- |
|  Name: |  GearSpecies |
|  Submitted by: | [AlessandroAdamou](../User/AlessandroAdamou.md "User:AlessandroAdamou") |
|  Also Known As: |  |
|  Intent: |  to represent types of fishing gear with respect to the aquatic species they either are targeted to catch or can accidentally catch |
|  Domains: |  |
|  Competency Questions: | <li> what type of fishing gear can catch what aquatic species?</li> |
|  Solution description: |  - |
|  Reusable OWL Building Block: | [http://www.ontologydesignpatterns.org/cp/owl/fsdas/gearspecies.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=http://www.ontologydesignpatterns.org/cp/owl/fsdas/gearspecies.owl&message=OWL building block&from_page_id=859&update=) (633) |
|  Consequences: |  The pattern outlines the relations between aquatic species and types of fishing gear that are suitable for catching exemplars thereof. While we do not make this distinction from the species' viewpoint, we do distinguish what species are gear types targeted to and what can be also incidentally caught. Since the original model does not hint at any other possible use for the three object properties presented herein, restriction superclasses for domains and ranges have been refactored as domain and range axioms for said properties. Note that this pattern can also be combined with :gearvessel.owl for answering what species can be caught using what vessel types. This can be inferred transitively. |
|  Scenarios: |  give me the gears targeting species 'tuna'; give me the gears which incidentally catch species 'dolphins'; give me the species caught using 'bottom gillnets' |
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


_The __GearSpecies__ Content OP locally defines the following ontology elements:_



[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __AquaticSpecies__ (owl:Class) Aquatic species are conceptual entities that are characterized together with resources and water areas. 
Mappable to fi:Species, fi:SpeciesRef, fi:SpeciesFeature, etc.


It has related axioms from FIGIS Schema that are included in the classes linked to the fi:Species class, such as fi:SpeciesRef (holding association with fi:AqResRef, which holds association with fi:WaterAreaRef). 



 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[AquaticSpecies](./AquaticResources/AquaticSpecies.md "Submissions:GearSpecies/AquaticSpecies") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __GearType__ (owl:Class) Gear types are conceptual entities that are characterized together with AquaticSpecies that are either targeted or can be incidentally caught. 
Mappable to fi:GearTypeRef 



 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[GearType](./GearSpecies/GearType.md "Submissions:GearSpecies/GearType") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __incidentallyCatchesSpecies__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[incidentallyCatchesSpecies](./GearSpecies/incidentallyCatchesSpecies.md "Submissions:GearSpecies/incidentallyCatchesSpecies") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __targetsSpecies__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[targetsSpecies](./GearSpecies/targetsSpecies.md "Submissions:GearSpecies/targetsSpecies") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isCaughtByGearType__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isCaughtByGearType](./GearSpecies/isCaughtByGearType.md "Submissions:GearSpecies/isCaughtByGearType") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isCaughtBy__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isCaughtBy](./GearSpecies/isCaughtBy.md "Submissions:GearSpecies/isCaughtBy") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __catchesSpecies__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[catchesSpecies](./GearSpecies/catchesSpecies.md "Submissions:GearSpecies/catchesSpecies") page_
#  Additional information


(type): [http://www.w3.org/2002/07/owl#Ontology](http://www.w3.org/2002/07/owl#Ontology "http://www.w3.org/2002/07/owl#Ontology")


(versionInfo): Created by Alessandro Adamou


(imports): [http://www.ontologydesignpatterns.org/schemas/cpannotationschema.owl](http://www.ontologydesignpatterns.org/schemas/cpannotationschema.owl "http://www.ontologydesignpatterns.org/schemas/cpannotationschema.owl")


(versionInfo): 1.1



#  Scenarios



__Scenarios about GearSpecies__
No scenario is added to this Content OP.




#  Reviews



__Reviews about GearSpecies__
There is no review about this proposal.
This revision (revision ID __9089__) takes in account the reviews: none


Other info at [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:GearSpecies&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:GearSpecies&action=evaluation")




  




#  Modeling issues



__Modeling issues about GearSpecies__
There is no Modeling issue related to this proposal.




  




#  References
# 

 Graphical representation



__Diagram__ 





[![Image:Gearspecies.jpg](../images/9/96/Gearspecies.jpg)](../Image/Gearspecies.jpg "Image:Gearspecies.jpg")





# 

 General description




|  |  |
| --- | --- |
|  Name:  |  GearSpecies  |
|  Submitted by:  | [AlessandroAdamou](../User/AlessandroAdamou "User:AlessandroAdamou")  |
|  Also Known As:  |  |
|  Intent:  |  to represent types of fishing gear with respect to the aquatic species they either are targeted to catch or can accidentally catch  |
|  Domains:  |  |
|  Competency Questions:  | <li>       what type of fishing gear can catch what aquatic species?      </li> |
|  Solution description:  |  -  |
|  Reusable OWL Building Block:  | [http://www.ontologydesignpatterns.org/cp/owl/fsdas/gearspecies.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=http://www.ontologydesignpatterns.org/cp/owl/fsdas/gearspecies.owl&message=OWL building block&from_page_id=859&update=)  (633)  |
|  Consequences:  |  The pattern outlines the relations between aquatic species and types of fishing gear that are suitable for catching exemplars thereof. While we do not make this distinction from the species' viewpoint, we do distinguish what species are gear types targeted to and what can be also incidentally caught. Since the original model does not hint at any other possible use for the three object properties presented herein, restriction superclasses for domains and ranges have been refactored as domain and range axioms for said properties. Note that this pattern can also be combined with :gearvessel.owl for answering what species can be caught using what vessel types. This can be inferred transitively.  |
|  Scenarios:  |  give me the gears targeting species 'tuna'; give me the gears which incidentally catch species 'dolphins'; give me the species caught using 'bottom gillnets'  |
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
 __GearSpecies__ 
 Content OP locally defines the following ontology elements:_ 





[![Class](../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__AquaticSpecies__ 
 (owl:Class) Aquatic species are conceptual entities that are characterized together with resources and water areas.
 
 Mappable to fi:Species, fi:SpeciesRef, fi:SpeciesFeature, etc.
 



 It has related axioms from FIGIS Schema that are included in the classes linked to the fi:Species class, such as fi:SpeciesRef (holding association with fi:AqResRef, which holds association with fi:WaterAreaRef).
 



[![](../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[AquaticSpecies](../Submissions/GearSpecies/AquaticSpecies "Submissions:GearSpecies/AquaticSpecies") 
 page_ 



[![Class](../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__GearType__ 
 (owl:Class) Gear types are conceptual entities that are characterized together with AquaticSpecies that are either targeted or can be incidentally caught.
 
 Mappable to fi:GearTypeRef
 



[![](../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[GearType](../Submissions/GearSpecies/GearType "Submissions:GearSpecies/GearType") 
 page_ 



[![ObjectProperty](../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__incidentallyCatchesSpecies__ 
 (owl:ObjectProperty)
 
[![](../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[incidentallyCatchesSpecies](../Submissions/GearSpecies/incidentallyCatchesSpecies "Submissions:GearSpecies/incidentallyCatchesSpecies") 
 page_ 



[![ObjectProperty](../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__targetsSpecies__ 
 (owl:ObjectProperty)
 
[![](../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[targetsSpecies](../Submissions/GearSpecies/targetsSpecies "Submissions:GearSpecies/targetsSpecies") 
 page_ 



[![ObjectProperty](../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__isCaughtByGearType__ 
 (owl:ObjectProperty)
 
[![](../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[isCaughtByGearType](../Submissions/GearSpecies/isCaughtByGearType "Submissions:GearSpecies/isCaughtByGearType") 
 page_ 



[![ObjectProperty](../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__isCaughtBy__ 
 (owl:ObjectProperty)
 
[![](../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[isCaughtBy](../Submissions/GearSpecies/isCaughtBy "Submissions:GearSpecies/isCaughtBy") 
 page_ 



[![ObjectProperty](../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__catchesSpecies__ 
 (owl:ObjectProperty)
 
[![](../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[catchesSpecies](../Submissions/GearSpecies/catchesSpecies "Submissions:GearSpecies/catchesSpecies") 
 page_ 


# 

 Additional information



 (type):
 [http://www.w3.org/2002/07/owl#Ontology](http://www.w3.org/2002/07/owl#Ontology "http://www.w3.org/2002/07/owl#Ontology") 




 (versionInfo): Created by Alessandro Adamou
 



 (imports):
 [http://www.ontologydesignpatterns.org/schemas/cpannotationschema.owl](http://www.ontologydesignpatterns.org/schemas/cpannotationschema.owl "http://www.ontologydesignpatterns.org/schemas/cpannotationschema.owl") 




 (versionInfo): 1.1
 



# 

 Scenarios




__Scenarios about GearSpecies__ 


 No scenario is added to this Content OP.
 




# 

 Reviews




__Reviews about GearSpecies__ 


 There is no review about this proposal.
This revision (revision ID
 __9089__ 
 ) takes in account the reviews: none
 



 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:GearSpecies&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:GearSpecies&action=evaluation") 





  





# 

 Modeling issues




__Modeling issues about GearSpecies__ 


 There is no Modeling issue related to this proposal.
 




  





# 

 References
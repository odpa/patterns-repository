[![Image:Gearwaterarea.jpg](../images/6/6e/Gearwaterarea.jpg)](../Image/Gearwaterarea.jpg "Image:Gearwaterarea.jpg")





# 

 General description




|  |  |
| --- | --- |
|  Name:  |  GearWaterArea  |
|  Submitted by:  | [AlessandroAdamou](../User/AlessandroAdamou "User:AlessandroAdamou")  |
|  Also Known As:  |  |
|  Intent:  |  to represent gear types in terms of the water areas where they can be employed to collect aquatic resources  |
|  Domains:  |  |
|  Competency Questions:  | <li>       in which water areas are what gear types used?      </li> |
|  Solution description:  |  |
|  Reusable OWL Building Block:  | [http://www.ontologydesignpatterns.org/cp/owl/fsdas/gearwaterarea.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=http://www.ontologydesignpatterns.org/cp/owl/fsdas/gearwaterarea.owl&message=OWL building block&from_page_id=872&update=)  (662)  |
|  Consequences:  |  The relation between gear types and water areas is general, i.e. not expressed in terms of logistics, legal constraints etc. Note that no statement is made as for the domain of the hasWaterArea property, as it applies to both GearType and VesselType in other patterns, and in principle could apply to other entities. Hence the domain is expressed through superclass universal restrictions on the GearType class.  |
|  Scenarios:  |  in which water areas are 'bottom gillnets'?  |
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
 __GearWaterArea__ 
 Content OP locally defines the following ontology elements:_ 





[![Class](../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__GearType__ 
 (owl:Class) Gear types are conceptual entities that are characterized together with AquaticSpecies that are either targeted or can be incidentally caught.
 
 Mappable to fi:GeartypeRef
 



[![](../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[GearType](../Submissions/GearWaterArea/GearType "Submissions:GearWaterArea/GearType") 
 page_ 



[![Class](../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__WaterArea__ 
 (owl:Class) A physical water area. Mappable to fi:WaterAreaRef
 
[![](../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[WaterArea](../Submissions/GearWaterArea/WaterArea "Submissions:GearWaterArea/WaterArea") 
 page_ 



[![ObjectProperty](../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__isUsedInWaterArea__ 
 (owl:ObjectProperty)
 
[![](../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[isUsedInWaterArea](../Submissions/GearWaterArea/isUsedInWaterArea "Submissions:GearWaterArea/isUsedInWaterArea") 
 page_ 



[![ObjectProperty](../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__isSuitableForGearType__ 
 (owl:ObjectProperty)
 
[![](../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[isSuitableForGearType](../Submissions/GearWaterArea/isSuitableForGearType "Submissions:GearWaterArea/isSuitableForGearType") 
 page_ 


 (type):
 [http://www.w3.org/2002/07/owl#Ontology](http://www.w3.org/2002/07/owl#Ontology "http://www.w3.org/2002/07/owl#Ontology") 




# 

 Scenarios




__Scenarios about GearWaterArea__ 


 No scenario is added to this Content OP.
 




# 

 Reviews




__Reviews about GearWaterArea__ 



|  Review article  | [Posted on](../Property/CreationDate "Property:CreationDate")  | [About revision (current is 3659)](../Property/ReviewAboutVersion "Property:ReviewAboutVersion")  |
| --- | --- | --- |
| [AldoGangemi about GearWaterArea](../Reviews/AldoGangemi_about_GearWaterArea "Reviews:AldoGangemi about GearWaterArea")  |  2454908  17 March 2009  |  3659  3,659  |



 This revision (revision ID
 __3659__ 
 ) takes in account the reviews: none
 



 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:GearWaterArea&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:GearWaterArea&action=evaluation")
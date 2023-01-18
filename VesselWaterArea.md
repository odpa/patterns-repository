# 

 Graphical representation



__Diagram__ 





[![Image:Vesselwaterarea.jpg](../images/d/db/Vesselwaterarea.jpg)](../Image/Vesselwaterarea.jpg "Image:Vesselwaterarea.jpg")





# 

 General description




|  |  |
| --- | --- |
|  Name:  |  VesselWaterArea  |
|  Submitted by:  | [AlessandroAdamou](../User/AlessandroAdamou "User:AlessandroAdamou")  |
|  Also Known As:  |  |
|  Intent:  |  to represent a direct relation between vessel types and water areas regardless of what type of fishing gear is fitted  |
|  Domains:  |  |
|  Competency Questions:  | <li>       which vessel types can be used in which water areas?      </li> |
|  Solution description:  |  ---  |
|  Reusable OWL Building Block:  | [http://www.ontologydesignpatterns.org/cp/owl/fsdas/vesselwaterarea.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=http://www.ontologydesignpatterns.org/cp/owl/fsdas/vesselwaterarea.owl&message=OWL building block&from_page_id=931&update=)  (636)  |
|  Consequences:  |  The pattern can be used to represent a water area setting and the vessels that can be used there, no matter whether these constraints are legal or logistic. The hasWaterArea object property is used as in the gearwaterarea pattern. Usage of this property as applied to VesselTypes is related to, but not strictly dependent on the hasWaterArea property as applied to GearTypes.  |
|  Scenarios:  |  in which water areas are 'gillneters' used?  |
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
 __VesselWaterArea__ 
 Content OP locally defines the following ontology elements:_ 





[![Class](../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__VesselType__ 
 (owl:Class) Vessel types are conceptual entities.
 
 Mappable to fi:VesseltypeRef
 



[![](../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[VesselType](../Submissions/VesselWaterArea/VesselType "Submissions:VesselWaterArea/VesselType") 
 page_ 



[![Class](../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__WaterArea__ 
 (owl:Class) A physical water area. Mappable to fi:WaterAreaRef
 
[![](../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[WaterArea](../Submissions/VesselWaterArea/WaterArea "Submissions:VesselWaterArea/WaterArea") 
 page_ 



[![ObjectProperty](../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__canCrossWaterArea__ 
 (owl:ObjectProperty)
 
[![](../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[canCrossWaterArea](../Submissions/VesselWaterArea/canCrossWaterArea "Submissions:VesselWaterArea/canCrossWaterArea") 
 page_ 



[![ObjectProperty](../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__canBeCrossedByVesselType__ 
 (owl:ObjectProperty) A physical water area. Mappable to fi:WaterAreaRef
 
[![](../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[canBeCrossedByVesselType](../Submissions/VesselWaterArea/canBeCrossedByVesselType "Submissions:VesselWaterArea/canBeCrossedByVesselType") 
 page_ 


# 

 Additional information



 (type):
 [http://www.w3.org/2002/07/owl#Ontology](http://www.w3.org/2002/07/owl#Ontology "http://www.w3.org/2002/07/owl#Ontology") 




 (versionInfo): 1.1
 



 (imports):
 [http://www.ontologydesignpatterns.org/schemas/cpannotationschema.owl](http://www.ontologydesignpatterns.org/schemas/cpannotationschema.owl "http://www.ontologydesignpatterns.org/schemas/cpannotationschema.owl") 




 (versionInfo): Created by Alessandro Adamou
 



# 

 Scenarios




__Scenarios about VesselWaterArea__ 


 No scenario is added to this Content OP.
 




# 

 Reviews




__Reviews about VesselWaterArea__ 



|  Review article  | [Posted on](../Property/CreationDate "Property:CreationDate")  | [About revision (current is 9142)](../Property/ReviewAboutVersion "Property:ReviewAboutVersion")  |
| --- | --- | --- |
| [AldoGangemi about VesselWaterArea](../Reviews/AldoGangemi_about_VesselWaterArea "Reviews:AldoGangemi about VesselWaterArea")  |  2454908  17 March 2009  |  3687  3,687  |



 This revision (revision ID
 __9142__ 
 ) takes in account the reviews: none
 



 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:VesselWaterArea&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:VesselWaterArea&action=evaluation") 





  





# 

 Modeling issues




__Modeling issues about VesselWaterArea__ 


 There is no Modeling issue related to this proposal.
 




  





# 

 References
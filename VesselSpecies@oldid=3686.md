[![Image:Vesselspecies.jpg](http://ontologydesignpatterns.org/wiki/images/8/84/Vesselspecies.jpg)](http://ontologydesignpatterns.org/wiki/Image:Vesselspecies.jpg "Image:Vesselspecies.jpg")





# 

 General description




|  |  |
| --- | --- |
|  Name:  |  VesselSpecies  |
|  Submitted by:  | [AlessandroAdamou](../User/AlessandroAdamou "User:AlessandroAdamou")  |
|  Also Known As:  |  |
|  Intent:  |  to provide a direct relation between aquatic species and vessels that are able to catch them, regardless of the fishing gear used.  |
|  Domains:  |  |
|  Competency Questions:  | <li>       what vessel types can catch what species?      </li> |
|  Solution description:  |  |
|  Reusable OWL Building Block:  | [http://www.ontologydesignpatterns.org/cp/owl/fsdas/vesselspecies.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=http://www.ontologydesignpatterns.org/cp/owl/fsdas/vesselspecies.owl&message=OWL building block&from_page_id=925&update=)  (665)  |
|  Consequences:  |  This pattern should be used in scenarios where a VesselType can be deemed suitable for catching some AquaticSpecies for reasons other than mounting some fishing gear of a suitable GearType. It is strictly related to the gearspecies pattern, in that it uses the catchesSpecies and isCaught property pair to define this behaviour. For the sake of reuse, no domain is declared for catchesSpecies, appropriate restrictions having beed applied instead.  |
|  Scenarios:  |  give me the species caught using 'gillneters'  |
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
 __VesselSpecies__ 
 Content OP locally defines the following ontology elements:_ 





[![Class](public/images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__AquaticSpecies__ 
 (owl:Class) Aquatic species are conceptual entities that are characterized together with resources and water areas.
 
 Mappable to fi:Species, fi:SpeciesRef, fi:SpeciesFeature, etc.
 



 It has related axioms from FIGIS Schema that are included in the classes linked to the fi:Species class, such as fi:SpeciesRef (holding association with fi:AqResRef, which holds association with fi:WaterAreaRef).
 



[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[AquaticSpecies](http://ontologydesignpatterns.org/wiki/Submissions:VesselSpecies/AquaticSpecies "Submissions:VesselSpecies/AquaticSpecies") 
 page_ 



[![Class](public/images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__VesselType__ 
 (owl:Class) Vessel types are conceptual entities.
 
 Mappable to fi:VesseltypeRef
 



[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[VesselType](http://ontologydesignpatterns.org/wiki/Submissions:VesselSpecies/VesselType "Submissions:VesselSpecies/VesselType") 
 page_ 



[![ObjectProperty](public/images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__catchesSpecies__ 
 (owl:ObjectProperty) Actually a composed property: this needs either a property chain, a SPARQL query, or a SWRL rule to gather a value. E.g. in SPARQL:
 
  





 CONSTRUCT {?x :catchesSpecies ?y . ?y isCaughtBy ?x}
 



 WHERE {
 



 ?x gearvessel:usesGearType ?z .
 



 ?z gearspecies:catchesSpecies ?y
 



 }
 



[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[catchesSpecies](../Submissions/VesselSpecies/catchesSpecies "Submissions:VesselSpecies/catchesSpecies") 
 page_ 



[![ObjectProperty](public/images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__isCaughtBy__ 
 (owl:ObjectProperty) Actually a composed property: this needs either a property chain, a SPARQL query, or a SWRL rule to gather a value. E.g. in SPARQL:
 
  





 CONSTRUCT {?x :catchesSpecies ?y . ?y isCaughtBy ?x}
 



 WHERE {
 



 ?x gearvessel:usesGearType ?z .
 



 ?z gearspecies:catchesSpecies ?y
 



 }
 



[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[isCaughtBy](../Submissions/VesselSpecies/isCaughtBy "Submissions:VesselSpecies/isCaughtBy") 
 page_ 



[![ObjectProperty](public/images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__isCaughtByVesselType__ 
 (owl:ObjectProperty)
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[isCaughtByVesselType](../Submissions/VesselSpecies/isCaughtByVesselType "Submissions:VesselSpecies/isCaughtByVesselType") 
 page_ 


 (type):
 [http://www.w3.org/2002/07/owl#Ontology](http://www.w3.org/2002/07/owl#Ontology "http://www.w3.org/2002/07/owl#Ontology") 




 (relatedCPs):
 [http://www.ontologydesignpatterns.org/cp/owl/fsdas/gearspecies.owl](http://www.ontologydesignpatterns.org/cp/owl/fsdas/gearspecies.owl "http://www.ontologydesignpatterns.org/cp/owl/fsdas/gearspecies.owl") 




 (imports):
 [http://www.ontologydesignpatterns.org/schemas/cpannotationschema.owl](http://www.ontologydesignpatterns.org/schemas/cpannotationschema.owl "http://www.ontologydesignpatterns.org/schemas/cpannotationschema.owl") 




 (versionInfo): Created by Alessandro Adamou
 



 (versionInfo): 1.0
 



# 

 Scenarios




__Scenarios about VesselSpecies__ 


 No scenario is added to this Content OP.
 




# 

 Reviews




__Reviews about VesselSpecies__ 



|  Review article  | [Posted on](../Property/CreationDate "Property:CreationDate")  | [About revision (current is 3686)](../Property/ReviewAboutVersion "Property:ReviewAboutVersion")  |
| --- | --- | --- |
| [AldoGangemi about VesselSpecies](../Reviews/AldoGangemi_about_VesselSpecies "Reviews:AldoGangemi about VesselSpecies")  |  2454908  17 March 2009  |  3686  3,686  |



 This revision (revision ID
 __3686__ 
 ) takes in account the reviews:
 [AldoGangemi about VesselSpecies](../Reviews/AldoGangemi_about_VesselSpecies "Reviews:AldoGangemi about VesselSpecies") 




 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:VesselSpecies&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:VesselSpecies&action=evaluation")
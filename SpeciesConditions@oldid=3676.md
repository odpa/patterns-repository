[![Image:Speciesconditions.jpg](public/images/8/85/Speciesconditions.jpg)](../Image/Speciesconditions.jpg "Image:Speciesconditions.jpg")





# 

 General description




|  |  |
| --- | --- |
|  Name:  |  SpeciesConditions  |
|  Submitted by:  | [AldoGangemi](../User/AldoGangemi "User:AldoGangemi")  |
|  Also Known As:  |  |
|  Intent:  |  This pattern aims at representing the habitat and bathymetric features that are typical for an aquatic species, in the context of a given water area.  |
|  Domains:  |  |
|  Competency Questions:  | <li>       what are the typical living conditions of a certain aquatic species? what are the aquatic species that live in a certain  habitat/bathymetric range for that water area?      </li> |
|  Solution description:  |  |
|  Reusable OWL Building Block:  | [http://www.ontologydesignpatterns.org/cp/owl/fsdas/speciesconditions.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=http://www.ontologydesignpatterns.org/cp/owl/fsdas/speciesconditions.owl&message=OWL building block&from_page_id=893&update=)  (641)  |
|  Consequences:  |  This pattern allows to represent the contextualized features of an aquatic species. For simpler representation of those features (non-contextualized to a water area), use specieshabitat.owl and speciesbathymetry.owl.  |
|  Scenarios:  |  give me the species found below 200 metres for water area '24'; give me the species having a 'demersal' habitat in water area '24'  |
|  Known Uses:  |  |
|  Web References:  |  |
|  Other References:  |  |
|  Examples (OWL files):  |  |
|  Extracted From:  |  |
|  Reengineered From:  |  |
|  Has Components:  |  |
|  Specialization Of:  |  |
|  Related CPs:  | <li><a class="new" href="http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Submissions:SpeciesHabitat&amp;action=edit&amp;redlink=1" title="Submissions:Submissions:SpeciesHabitat (not yet written)">        Submissions:Submissions:SpeciesHabitat       </a></li> |



  





# 

 Elements



_The
 __SpeciesConditions__ 
 Content OP locally defines the following ontology elements:_ 





[![Class](public/images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__Habitat__ 
 (owl:Class) Habitat is the biological and ecological context of a species in the area of an aquatic resource.
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[Habitat](../Submissions/SpeciesConditions/Habitat "Submissions:SpeciesConditions/Habitat") 
 page_ 



[![Class](public/images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__SpeciesConditions__ 
 (owl:Class) A class that allows to represent the typical physic conditions (bathymetry, habitat) of an aquatic species for a certain water area.
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[SpeciesConditions](../Submissions/SpeciesConditions/SpeciesConditions "Submissions:SpeciesConditions/SpeciesConditions") 
 page_ 



[![Class](public/images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__AquaticSpecies__ 
 (owl:Class) Aquatic species is characterized together with resources and water areas.
 
 Mappable to fi:Species, fi:SpeciesRef, fi:SpeciesFeature, etc.
 



 It has related axioms from FIGIS Schema that are included in the classes linked to the fi:Species class, such as fi:SpeciesRef (holding association with fi:AqResRef, which holds association with fi:WaterAreaRef).
 



[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[AquaticSpecies](../Submissions/SpeciesConditions/AquaticSpecies "Submissions:SpeciesConditions/AquaticSpecies") 
 page_ 



[![Class](public/images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__BathymetricRange__ 
 (owl:Class) This class contains the set of bathymetric ranges. Bathymetry is numeric depth information about the ranges in which an aquatic species is found.
 
 It can be mapped to fi:Bathymetry.
 



[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[BathymetricRange](../Submissions/SpeciesConditions/BathymetricRange "Submissions:SpeciesConditions/BathymetricRange") 
 page_ 



[![Class](public/images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__WaterArea__ 
 (owl:Class)
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[WaterArea](../Submissions/SpeciesConditions/WaterArea "Submissions:SpeciesConditions/WaterArea") 
 page_ 



[![ObjectProperty](public/images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasHabitat__ 
 (owl:ObjectProperty)
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasHabitat](../Submissions/SpeciesConditions/hasHabitat "Submissions:SpeciesConditions/hasHabitat") 
 page_ 



[![ObjectProperty](public/images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__inWaterArea__ 
 (owl:ObjectProperty)
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[inWaterArea](../Submissions/SpeciesConditions/inWaterArea "Submissions:SpeciesConditions/inWaterArea") 
 page_ 



[![ObjectProperty](public/images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasBathymetricRange__ 
 (owl:ObjectProperty)
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasBathymetricRange](../Submissions/SpeciesConditions/hasBathymetricRange "Submissions:SpeciesConditions/hasBathymetricRange") 
 page_ 



[![ObjectProperty](public/images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__forSpecies__ 
 (owl:ObjectProperty)
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[forSpecies](../Submissions/SpeciesConditions/forSpecies "Submissions:SpeciesConditions/forSpecies") 
 page_ 



[![ObjectProperty](public/images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasConditions__ 
 (owl:ObjectProperty)
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasConditions](../Submissions/SpeciesConditions/hasConditions "Submissions:SpeciesConditions/hasConditions") 
 page_ 



[![ObjectProperty](public/images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__isWaterAreaFor__ 
 (owl:ObjectProperty)
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[isWaterAreaFor](../Submissions/SpeciesConditions/isWaterAreaFor "Submissions:SpeciesConditions/isWaterAreaFor") 
 page_ 



[![ObjectProperty](public/images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__isHabitatFor__ 
 (owl:ObjectProperty)
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[isHabitatFor](../Submissions/SpeciesConditions/isHabitatFor "Submissions:SpeciesConditions/isHabitatFor") 
 page_ 



[![ObjectProperty](public/images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__isBathymetricRangeFor__ 
 (owl:ObjectProperty)
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[isBathymetricRangeFor](../Submissions/SpeciesConditions/isBathymetricRangeFor "Submissions:SpeciesConditions/isBathymetricRangeFor") 
 page_ 


 A pattern, based on situation.owl, which allow to express the typical 'conditions' (habitat, bathymetric range) of a species for a certain water area.
 



 (type):
 [http://www.w3.org/2002/07/owl#Ontology](http://www.w3.org/2002/07/owl#Ontology "http://www.w3.org/2002/07/owl#Ontology") 




 (imports):
 [http://www.ontologydesignpatterns.org/cp/owl/situation.owl](http://www.ontologydesignpatterns.org/cp/owl/situation.owl "http://www.ontologydesignpatterns.org/cp/owl/situation.owl") 




 (versionInfo): 1.0
 



 (comment): A pattern, based on situation.owl, which allow to express the typical 'conditions' (habitat, bathymetric range) of a species for a certain water area.
 



 (imports):
 [http://www.ontologydesignpatterns.org/schemas/cpannotationschema.owl](http://www.ontologydesignpatterns.org/schemas/cpannotationschema.owl "http://www.ontologydesignpatterns.org/schemas/cpannotationschema.owl") 




# 

 Scenarios




__Scenarios about SpeciesConditions__ 


 No scenario is added to this Content OP.
 




# 

 Reviews




__Reviews about SpeciesConditions__ 



|  Review article  | [Posted on](../Property/CreationDate "Property:CreationDate")  | [About revision (current is 3676)](../Property/ReviewAboutVersion "Property:ReviewAboutVersion")  |
| --- | --- | --- |
| [AldoGangemi about SpeciesConditions](../Reviews/AldoGangemi_about_SpeciesConditions "Reviews:AldoGangemi about SpeciesConditions")  |  2454908  17 March 2009  |  3676  3,676  |



 This revision (revision ID
 __3676__ 
 ) takes in account the reviews: none
 



 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:SpeciesConditions&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:SpeciesConditions&action=evaluation")
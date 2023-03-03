# 

 Graphical representation



__Diagram__ 





[![Image:Speciesconditions.jpg](./Speciesconditions.jpg)](../Image/Speciesconditions.jpg.md "Image:Speciesconditions.jpg")





# 

 General description




|  |  |
| --- | --- |
|  Name:  |  SpeciesConditions  |
|  Submitted by:  | [AldoGangemi](../User/AldoGangemi.md "User:AldoGangemi")  |
|  Also Known As:  |  |
|  Intent:  |  This pattern aims at representing the habitat and bathymetric features that are typical for an aquatic species, in the context of a given water area.  |
|  Domains:  |  |
|  Competency Questions:  | <li>       what are the typical living conditions of a certain aquatic species? what are the aquatic species that live in a certain  habitat/bathymetric range for that water area?      </li> |
|  Solution description:  |  -  |
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
|  Related CPs:  | <li><a href="../SpeciesHabitat/SpeciesHabitat.md" title="Submissions:SpeciesHabitat">        Submissions:SpeciesHabitat       </a></li> |



  





# 

 Elements



_The
 __SpeciesConditions__ 
 Content OP locally defines the following ontology elements:_ 





[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__Habitat__ 
 (owl:Class) Habitat is the biological and ecological context of a species in the area of an aquatic resource.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[Habitat](../SpeciesHabitat/SpeciesHabitat.md "Submissions:SpeciesConditions/Habitat") 
 page_ 



[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__SpeciesConditions__ 
 (owl:Class) A class that allows to represent the typical physic conditions (bathymetry, habitat) of an aquatic species for a certain water area.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[SpeciesConditions](./SpeciesConditions.md "Submissions:SpeciesConditions/SpeciesConditions") 
 page_ 



[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__AquaticSpecies__ 
 (owl:Class) Aquatic species is characterized together with resources and water areas.
 
 Mappable to fi:Species, fi:SpeciesRef, fi:SpeciesFeature, etc.
 



 It has related axioms from FIGIS Schema that are included in the classes linked to the fi:Species class, such as fi:SpeciesRef (holding association with fi:AqResRef, which holds association with fi:WaterAreaRef).
 



[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[AquaticSpecies](./AquaticResources/AquaticSpecies.md "Submissions:SpeciesConditions/AquaticSpecies") 
 page_ 



[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__BathymetricRange__ 
 (owl:Class) This class contains the set of bathymetric ranges. Bathymetry is numeric depth information about the ranges in which an aquatic species is found.
 
 It can be mapped to fi:Bathymetry.
 



[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[BathymetricRange](./SpeciesBathymetry/BathymetricRange.md "Submissions:SpeciesConditions/BathymetricRange") 
 page_ 



[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__WaterArea__ 
 (owl:Class)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[WaterArea](../GearWaterArea/GearWaterArea.md "Submissions:SpeciesConditions/WaterArea") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__hasHabitat__ 
 (owl:ObjectProperty)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[hasHabitat](./SpeciesConditions/hasHabitat.md "Submissions:SpeciesConditions/hasHabitat") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__inWaterArea__ 
 (owl:ObjectProperty)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[inWaterArea](./SpeciesConditions/inWaterArea.md "Submissions:SpeciesConditions/inWaterArea") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__hasBathymetricRange__ 
 (owl:ObjectProperty)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[hasBathymetricRange](./SpeciesBathymetry/hasBathymetricRange.md "Submissions:SpeciesConditions/hasBathymetricRange") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__forSpecies__ 
 (owl:ObjectProperty)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[forSpecies](./SpeciesConditions/forSpecies.md "Submissions:SpeciesConditions/forSpecies") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__hasConditions__ 
 (owl:ObjectProperty)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[hasConditions](./SpeciesConditions/hasConditions.md "Submissions:SpeciesConditions/hasConditions") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__isWaterAreaFor__ 
 (owl:ObjectProperty)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[isWaterAreaFor](./SpeciesConditions/isWaterAreaFor.md "Submissions:SpeciesConditions/isWaterAreaFor") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__isHabitatFor__ 
 (owl:ObjectProperty)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[isHabitatFor](./SpeciesConditions/isHabitatFor.md "Submissions:SpeciesConditions/isHabitatFor") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__isBathymetricRangeFor__ 
 (owl:ObjectProperty)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[isBathymetricRangeFor](./SpeciesConditions/isBathymetricRangeFor.md "Submissions:SpeciesConditions/isBathymetricRangeFor") 
 page_ 


# 

 Additional information



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



|  Review article  | [Posted on](../Property/CreationDate.md "Property:CreationDate")  | [About revision (current is 9124)](../Property/ReviewAboutVersion.md "Property:ReviewAboutVersion")  |
| --- | --- | --- |
| [AldoGangemi about SpeciesConditions](../Reviews/AldoGangemi_about_SpeciesConditions.md "Reviews:AldoGangemi about SpeciesConditions")  |  2454908  17 March 2009  |  3676  3,676  |



 This revision (revision ID
 __9124__ 
 ) takes in account the reviews: none
 



 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:SpeciesConditions&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:SpeciesConditions&action=evaluation") 





  





# 

 Modeling issues




__Modeling issues about SpeciesConditions__ 


 There is no Modeling issue related to this proposal.
 




  





# 

 References
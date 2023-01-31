# 

 Graphical representation



__Diagram__ 





[![Image:Aquaticresource.jpg](images/c/c0/Aquaticresource.jpg)](../Image/Aquaticresource.jpg "Image:Aquaticresource.jpg")





# 

 General description




|  |  |
| --- | --- |
|  Name:  |  AquaticResources  |
|  Submitted by:  | [AldoGangemi](../User/AldoGangemi "User:AldoGangemi")  |
|  Also Known As:  |  |
|  Intent:  |  To represent aquatic resources or stocks as composed of aquatic organisms from one or more species, and living in a water area.  |
|  Domains:  | [Fishery](../Community/Fishery "Community:Fishery")  |
|  Competency Questions:  | <li>       What species are present in this aquatic resource/stock? In what water area this aquatic resource/stock lives in?      </li> |
|  Solution description:  |  --  |
|  Reusable OWL Building Block:  | [http://www.ontologydesignpatterns.org/cp/owl/fsdas/aquaticresources.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=http://www.ontologydesignpatterns.org/cp/owl/fsdas/aquaticresources.owl&message=OWL building block&from_page_id=827&update=)  (697)  |
|  Consequences:  |  Relations between aquatic resources and either aquatic species or water areas can be represented. In order to infer what species typically live in what water areas however, an application needs to add a SWRL rule, or a SPARQL query that unifies the hasSpecies and hasWaterArea relations.  |
|  Scenarios:  |  give me the Species for water area 24; give me the Water areas for species Gadus morhua.  |
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
 __AquaticResources__ 
 Content OP locally defines the following ontology elements:_ 





[![Class](images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__AquaticSpecies__ 
 (owl:Class) Aquatic species are conceptual entities that are characterized together with resources and water areas.
 
 Mappable to fi:Species, fi:SpeciesRef, fi:SpeciesFeature, etc.
 



 It has related axioms from FIGIS Schema that are included in the classes linked to the fi:Species class, such as fi:SpeciesRef (holding association with fi:AqResRef, which holds association with fi:WaterAreaRef).
 



[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[AquaticSpecies](../Submissions/AquaticResources/AquaticSpecies "Submissions:AquaticResources/AquaticSpecies") 
 page_ 



[![Class](images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__AquaticResource__ 
 (owl:Class) A fishery resource (a collection of actual aquatic organisms) that can include aquatic organisms from different AquaticSpecies, and is localized in some WaterArea.
 
 It can be mapped to fi:AqResRef
 



[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[AquaticResource](../Submissions/AquaticResources/AquaticResource "Submissions:AquaticResources/AquaticResource") 
 page_ 



[![Class](images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__WaterArea__ 
 (owl:Class) A physical water area. Mappable to fi:WaterAreaRef
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[WaterArea](../Submissions/AquaticResources/WaterArea "Submissions:AquaticResources/WaterArea") 
 page_ 



[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasSpecies__ 
 (owl:ObjectProperty) has species
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasSpecies](../Submissions/AquaticResources/hasSpecies "Submissions:AquaticResources/hasSpecies") 
 page_ 



[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasWaterArea__ 
 (owl:ObjectProperty)
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasWaterArea](../Submissions/AquaticResources/hasWaterArea "Submissions:AquaticResources/hasWaterArea") 
 page_ 



[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__isSpeciesPresentIn__ 
 (owl:ObjectProperty)
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[isSpeciesPresentIn](../Submissions/AquaticResources/isSpeciesPresentIn "Submissions:AquaticResources/isSpeciesPresentIn") 
 page_ 



[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__isWaterAreaOf__ 
 (owl:ObjectProperty)
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[isWaterAreaOf](../Submissions/AquaticResources/isWaterAreaOf "Submissions:AquaticResources/isWaterAreaOf") 
 page_ 


# 

 Additional information



 (type):
 [http://www.w3.org/2002/07/owl#Ontology](http://www.w3.org/2002/07/owl#Ontology "http://www.w3.org/2002/07/owl#Ontology") 




 (versionInfo): 1.0
 



 (imports):
 [http://www.ontologydesignpatterns.org/schemas/cpannotationschema.owl](http://www.ontologydesignpatterns.org/schemas/cpannotationschema.owl "http://www.ontologydesignpatterns.org/schemas/cpannotationschema.owl") 




# 

 Scenarios




__Scenarios about AquaticResources__ 


 No scenario is added to this Content OP.
 




# 

 Reviews




__Reviews about AquaticResources__ 


 There is no review about this proposal.
This revision (revision ID
 __9065__ 
 ) takes in account the reviews: none
 



 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:AquaticResources&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:AquaticResources&action=evaluation") 





  





# 

 Modeling issues




__Modeling issues about AquaticResources__ 


 There is no Modeling issue related to this proposal.
 




  





# 

 References
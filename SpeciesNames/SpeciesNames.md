# 

 Graphical representation



__Diagram__ 





[![Image:Speciesnames.jpg](./Speciesnames.jpg)](../Image/Speciesnames.jpg.md "Image:Speciesnames.jpg")





# 

 General description




|  |  |
| --- | --- |
|  Name:  |  SpeciesNames  |
|  Submitted by:  | [AldoGangemi](../User/AldoGangemi.md "User:AldoGangemi")  |
|  Also Known As:  |  |
|  Intent:  |  To express the terminological variants and the conceptual similarity that can be sources of confusion between species.  |
|  Domains:  |  |
|  Competency Questions:  | <li>       what local names are used for that species? what synonyms exist for that species? can that species be confused with some other one?      </li> |
|  Solution description:  |  --  |
|  Reusable OWL Building Block:  | [http://www.ontologydesignpatterns.org/cp/owl/fsdas/speciesnames.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=http://www.ontologydesignpatterns.org/cp/owl/fsdas/speciesnames.owl&message=OWL building block&from_page_id=920&update=)  (603)  |
|  Consequences:  |  Terminological and conceptual similarity between species can be encoded byusing the three properties in this pattern.  |
|  Scenarios:  |  give me the species containing local name 'oyster'; give me the synonyms and localnames for species 'Ostrica gigas'; give me the species with which species 'Ostrica gigas' can be confused  |
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
 __SpeciesNames__ 
 Content OP locally defines the following ontology elements:_ 





[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__AquaticSpecies__ 
 (owl:Class) Aquatic species are conceptual entities that are characterized together with resources and water areas.
 
 Mappable to fi:Species, fi:SpeciesRef, fi:SpeciesFeature, etc.
 



 It has related axioms from FIGIS Schema that are included in the classes linked to the fi:Species class, such as fi:SpeciesRef (holding association with fi:AqResRef, which holds association with fi:WaterAreaRef).
 



[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[AquaticSpecies](./AquaticResources/AquaticSpecies.md "Submissions:SpeciesNames/AquaticSpecies") 
 page_ 



[![DatatypeProperty](./20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif.md "DatatypeProperty")
__hasLocalName__ 
 (owl:DatatypeProperty) Property to express a species' localname , where it is used , and any additional information like the name of the dialect or more detailed geographical information on where exactly the local-common name is used for the aquatic species in a given country.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[hasLocalName](./SpeciesNames/hasLocalName.md "Submissions:SpeciesNames/hasLocalName") 
 page_ 



[![DatatypeProperty](./20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif.md "DatatypeProperty")
__canBeConfusedWith__ 
 (owl:DatatypeProperty) A property for expressing a description of why a species may be confused with another. It may instead/also contain a list of other species with which a species may be confused.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[canBeConfusedWith](./SpeciesNames/canBeConfusedWith.md "Submissions:SpeciesNames/canBeConfusedWith") 
 page_ 



[![DatatypeProperty](./20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif.md "DatatypeProperty")
__hasSynonym__ 
 (owl:DatatypeProperty) Expresses the scientific names that exist for a species but are no longer valid.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[hasSynonym](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/hasSynonym.md "Submissions:SpeciesNames/hasSynonym") 
 page_ 


# 

 Additional information



 (type):
 [http://www.w3.org/2002/07/owl#Ontology](http://www.w3.org/2002/07/owl#Ontology "http://www.w3.org/2002/07/owl#Ontology") 




 (imports):
 [http://www.ontologydesignpatterns.org/schemas/cpannotationschema.owl](http://www.ontologydesignpatterns.org/schemas/cpannotationschema.owl "http://www.ontologydesignpatterns.org/schemas/cpannotationschema.owl") 




 (versionInfo): 1.0
 



# 

 Scenarios




__Scenarios about SpeciesNames__ 


 No scenario is added to this Content OP.
 




# 

 Reviews




__Reviews about SpeciesNames__ 


 There is no review about this proposal.
This revision (revision ID
 __9128__ 
 ) takes in account the reviews: none
 



 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:SpeciesNames&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:SpeciesNames&action=evaluation") 





  





# 

 Modeling issues




__Modeling issues about SpeciesNames__ 


 There is no Modeling issue related to this proposal.
 




  





# 

 References
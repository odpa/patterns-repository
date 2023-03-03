# 

 Graphical representation



__Diagram__ 





[![Image:Specieshabitat.jpg](./Specieshabitat.jpg)](../Image/Specieshabitat.jpg.md "Image:Specieshabitat.jpg")





# 

 General description




|  |  |
| --- | --- |
|  Name:  |  SpeciesHabitat  |
|  Submitted by:  | [AldoGangemi](../User/AldoGangemi.md "User:AldoGangemi")  |
|  Also Known As:  |  |
|  Intent:  |  to represent species together with their typical environment in terms of habitat and water area  |
|  Domains:  |  |
|  Competency Questions:  | <li>       what species have what habitat in what water area?      </li> |
|  Solution description:  |  ---  |
|  Reusable OWL Building Block:  | [http://www.ontologydesignpatterns.org/cp/owl/fsdas/specieshabitat.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=http://www.ontologydesignpatterns.org/cp/owl/fsdas/specieshabitat.owl&message=OWL building block&from_page_id=916&update=)  (642)  |
|  Consequences:  |  The pattern allows to represent species with a typical habitat and a typical water area where the exemplars can be found. However, there is no direct relation between the habitat (type) and the water area; in principle, it is possible that there are no places in the water area that provide the conditions for that habitat.  In order to represent that a species has a habitat within a given water area, the situation pattern should be reused and specialized, as in the speciesconditions.owl pattern.  |
|  Scenarios:  |  give me the species having a 'demersal' habitat in water area '24'  |
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
 __SpeciesHabitat__ 
 Content OP locally defines the following ontology elements:_ 





[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__Habitat__ 
 (owl:Class) Habitat is the biological and ecological context of a species in the area of an aquatic resource.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[Habitat](./SpeciesHabitat.md "Submissions:SpeciesHabitat/Habitat") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__hasHabitat__ 
 (owl:ObjectProperty)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[hasHabitat](./SpeciesConditions/hasHabitat.md "Submissions:SpeciesHabitat/hasHabitat") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__isHabitatFor__ 
 (owl:ObjectProperty)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[isHabitatFor](./SpeciesConditions/isHabitatFor.md "Submissions:SpeciesHabitat/isHabitatFor") 
 page_ 


# 

 Additional information



 This pattern encodes a FSDAS competency question, with an indication to use some Species class, and some hasHabitat property, with range xsd:string.
Since the application task of FSDAS is to jointly query FIGIS factsheet data and RTMS time series data, the pattern must encode elements that can be easily mapped to FIGIS and RTMS schemas/ontologies.
Issue (1) mapping Species to FIGIS schema, since the needed schema elements are two instead of one.
Issue (2) representation of habitats in the pattern is intuitively with objects, since habitats are typically objects, and points in a value space (as the referents of xsd datatypes typically are). The suggestion in the competencey question is to use xsd.string though.
 



 (type):
 [http://www.w3.org/2002/07/owl#Ontology](http://www.w3.org/2002/07/owl#Ontology "http://www.w3.org/2002/07/owl#Ontology") 




 (versionInfo): Created by Aldo Gangemi
 



 (imports):
 [http://www.ontologydesignpatterns.org/cp/owl/fsdas/aquaticresources.owl](http://www.ontologydesignpatterns.org/cp/owl/fsdas/aquaticresources.owl "http://www.ontologydesignpatterns.org/cp/owl/fsdas/aquaticresources.owl") 




 (versionInfo): 1.0
 



 (imports):
 [http://www.ontologydesignpatterns.org/schemas/cpannotationschema.owl](http://www.ontologydesignpatterns.org/schemas/cpannotationschema.owl "http://www.ontologydesignpatterns.org/schemas/cpannotationschema.owl") 




 (comment): This pattern encodes a FSDAS competency question, with an indication to use some Species class, and some hasHabitat property, with range xsd:string.
Since the application task of FSDAS is to jointly query FIGIS factsheet data and RTMS time series data, the pattern must encode elements that can be easily mapped to FIGIS and RTMS schemas/ontologies.
Issue (1) mapping Species to FIGIS schema, since the needed schema elements are two instead of one.
Issue (2) representation of habitats in the pattern is intuitively with objects, since habitats are typically objects, and points in a value space (as the referents of xsd datatypes typically are). The suggestion in the competencey question is to use xsd.string though.
 



# 

 Scenarios




__Scenarios about SpeciesHabitat__ 


 No scenario is added to this Content OP.
 




# 

 Reviews




__Reviews about SpeciesHabitat__ 


 There is no review about this proposal.
This revision (revision ID
 __9127__ 
 ) takes in account the reviews: none
 



 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:SpeciesHabitat&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:SpeciesHabitat&action=evaluation") 





  





# 

 Modeling issues




__Modeling issues about SpeciesHabitat__ 


 There is no Modeling issue related to this proposal.
 




  





# 

 References
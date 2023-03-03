#  Graphical representation


__Diagram__




[![Image:Specieseat.jpg](./Specieseat.jpg)](../Image/Specieseat.jpg.md "Image:Specieseat.jpg")




#  General description




|  |  |
| --- | --- |
|  Name: |  SpeciesEat |
|  Submitted by: | [EvaBlomqvist](../User/EvaBlomqvist.md "User:EvaBlomqvist") |
|  Also Known As: |  |
|  Intent: |  The pattern intends to model the situation that a certain species feed upon other species and that some species are preyed upon by a certain species. |
|  Domains: |  |
|  Competency Questions: | <li> What species feed upon a certain species? What species are eaten by a certain species? What species is preyed upon by a certain species? What species preyes upon a certain species?</li> |
|  Solution description: |  ... |
|  Reusable OWL Building Block: | [http://www.ontologydesignpatterns.org/cp/owl/fsdas/specieseat.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=http://www.ontologydesignpatterns.org/cp/owl/fsdas/specieseat.owl&message=OWL building block&from_page_id=910&update=) (641) |
|  Consequences: |  |
|  Scenarios: |  What species eat 'shrimp'; What species are eaten by 'seals' |
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


_The __SpeciesEat__ Content OP locally defines the following ontology elements:_



[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __AquaticSpecies__ (owl:Class) Aquatic species are conceptual entities that are characterized together with resources and water areas. 
Mappable to fi:Species, fi:SpeciesRef, fi:SpeciesFeature, etc.


It has related axioms from FIGIS Schema that are included in the classes linked to the fi:Species class, such as fi:SpeciesRef (holding association with fi:AqResRef, which holds association with fi:WaterAreaRef). 



 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[AquaticSpecies](./AquaticResources/AquaticSpecies.md "Submissions:SpeciesEat/AquaticSpecies") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __feedsUpon__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[feedsUpon](./SpeciesEat/feedsUpon.md "Submissions:SpeciesEat/feedsUpon") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isPreyedUponBy__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isPreyedUponBy](./SpeciesEat/isPreyedUponBy.md "Submissions:SpeciesEat/isPreyedUponBy") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isFoodOf__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isFoodOf](./SpeciesEat/isFoodOf.md "Submissions:SpeciesEat/isFoodOf") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __preyesUpon__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[preyesUpon](./SpeciesEat/preyesUpon.md "Submissions:SpeciesEat/preyesUpon") page_
#  Additional information


(type): [http://www.w3.org/2002/07/owl#Ontology](http://www.w3.org/2002/07/owl#Ontology "http://www.w3.org/2002/07/owl#Ontology")


(imports): [http://www.ontologydesignpatterns.org/schemas/cpannotationschema.owl](http://www.ontologydesignpatterns.org/schemas/cpannotationschema.owl "http://www.ontologydesignpatterns.org/schemas/cpannotationschema.owl")


(hasUnitTest): SELECT ?x WHERE {?x a :AquaticSpecies.  ?x :feedsUpon :Shrimp. }
SELECT ?x WHERE {?x a :AquaticSpecies.  :Shrimp :isEatenBy ?x. }
SELECT ?x WHERE {?x a :AquaticSpecies.  ?x :isPreyedUponBy :Seals.}
SELECT ?x WHERE {?x a :AquaticSpecies.  :Seals :preyesUpon ?x.}



#  Scenarios



__Scenarios about SpeciesEat__
No scenario is added to this Content OP.




#  Reviews



__Reviews about SpeciesEat__
There is no review about this proposal.
This revision (revision ID __9126__) takes in account the reviews: none


Other info at [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:SpeciesEat&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:SpeciesEat&action=evaluation")




  




#  Modeling issues



__Modeling issues about SpeciesEat__
There is no Modeling issue related to this proposal.




  




#  References
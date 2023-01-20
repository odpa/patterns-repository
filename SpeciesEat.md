# 

 Graphical representation



__Diagram__ 





[![Image:Specieseat.jpg](public/images/1/13/Specieseat.jpg)](../Image/Specieseat.jpg "Image:Specieseat.jpg")





# 

 General description




|  |  |
| --- | --- |
|  Name:  |  SpeciesEat  |
|  Submitted by:  | [EvaBlomqvist](../User/EvaBlomqvist "User:EvaBlomqvist")  |
|  Also Known As:  |  |
|  Intent:  |  The pattern intends to model the situation that a certain species feed upon other species and that some species are preyed upon by a certain species.  |
|  Domains:  |  |
|  Competency Questions:  | <li>       What species feed upon a certain species? What species are eaten by a certain species? What species is preyed upon by a certain species? What species preyes upon a certain species?      </li> |
|  Solution description:  |  ...  |
|  Reusable OWL Building Block:  | [http://www.ontologydesignpatterns.org/cp/owl/fsdas/specieseat.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=http://www.ontologydesignpatterns.org/cp/owl/fsdas/specieseat.owl&message=OWL building block&from_page_id=910&update=)  (641)  |
|  Consequences:  |  |
|  Scenarios:  |  What species eat 'shrimp'; What species are eaten by 'seals'  |
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
 __SpeciesEat__ 
 Content OP locally defines the following ontology elements:_ 





[![Class](public/images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__AquaticSpecies__ 
 (owl:Class) Aquatic species are conceptual entities that are characterized together with resources and water areas.
 
 Mappable to fi:Species, fi:SpeciesRef, fi:SpeciesFeature, etc.
 



 It has related axioms from FIGIS Schema that are included in the classes linked to the fi:Species class, such as fi:SpeciesRef (holding association with fi:AqResRef, which holds association with fi:WaterAreaRef).
 



[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[AquaticSpecies](../Submissions/SpeciesEat/AquaticSpecies "Submissions:SpeciesEat/AquaticSpecies") 
 page_ 



[![ObjectProperty](public/images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__feedsUpon__ 
 (owl:ObjectProperty)
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[feedsUpon](../Submissions/SpeciesEat/feedsUpon "Submissions:SpeciesEat/feedsUpon") 
 page_ 



[![ObjectProperty](public/images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__isPreyedUponBy__ 
 (owl:ObjectProperty)
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[isPreyedUponBy](../Submissions/SpeciesEat/isPreyedUponBy "Submissions:SpeciesEat/isPreyedUponBy") 
 page_ 



[![ObjectProperty](public/images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__isFoodOf__ 
 (owl:ObjectProperty)
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[isFoodOf](../Submissions/SpeciesEat/isFoodOf "Submissions:SpeciesEat/isFoodOf") 
 page_ 



[![ObjectProperty](public/images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__preyesUpon__ 
 (owl:ObjectProperty)
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[preyesUpon](../Submissions/SpeciesEat/preyesUpon "Submissions:SpeciesEat/preyesUpon") 
 page_ 


# 

 Additional information



 (type):
 [http://www.w3.org/2002/07/owl#Ontology](http://www.w3.org/2002/07/owl#Ontology "http://www.w3.org/2002/07/owl#Ontology") 




 (imports):
 [http://www.ontologydesignpatterns.org/schemas/cpannotationschema.owl](http://www.ontologydesignpatterns.org/schemas/cpannotationschema.owl "http://www.ontologydesignpatterns.org/schemas/cpannotationschema.owl") 




 (hasUnitTest): SELECT ?x WHERE {?x a :AquaticSpecies.  ?x :feedsUpon :Shrimp. }
SELECT ?x WHERE {?x a :AquaticSpecies.  :Shrimp :isEatenBy ?x. }
SELECT ?x WHERE {?x a :AquaticSpecies.  ?x :isPreyedUponBy :Seals.}
SELECT ?x WHERE {?x a :AquaticSpecies.  :Seals :preyesUpon ?x.}
 



# 

 Scenarios




__Scenarios about SpeciesEat__ 


 No scenario is added to this Content OP.
 




# 

 Reviews




__Reviews about SpeciesEat__ 


 There is no review about this proposal.
This revision (revision ID
 __9126__ 
 ) takes in account the reviews: none
 



 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:SpeciesEat&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:SpeciesEat&action=evaluation") 





  





# 

 Modeling issues




__Modeling issues about SpeciesEat__ 


 There is no Modeling issue related to this proposal.
 




  





# 

 References
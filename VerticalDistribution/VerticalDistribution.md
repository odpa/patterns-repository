# 

 Graphical representation



__Diagram__ 
_(this article has no graphical representation)_ 




# 

 General description




|  |  |
| --- | --- |
|  Name:  |  VerticalDistribution  |
|  Submitted by:  | [AldoGangemi](../User/AldoGangemi.md "User:AldoGangemi")  , [EvaBlomqvist](../User/EvaBlomqvist.md "User:EvaBlomqvist")  |
|  Also Known As:  |  |
|  Intent:  |  The intent of the pattern is to be able to represent vertical distribution for aquatic resources.  |
|  Domains:  |  |
|  Competency Questions:  | <li>       What resource has what vertical distribution?      </li> |
|  Solution description:  |  ...  |
|  Reusable OWL Building Block:  | [http://www.ontologydesignpatterns.org/cp/owl/fsdas/verticaldistribution.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=http://www.ontologydesignpatterns.org/cp/owl/fsdas/verticaldistribution.owl&message=OWL building block&from_page_id=1206&update=)  (607)  |
|  Consequences:  |  This pattern only allows to query what vertical distribution is typical of an aquatic resource. Whereas such values can be subject to observation, another pattern based on the generic 'observation' pattern should be used.  The vertical distribution is intended to have a fixed set of values (to be defined as nominals) but this is not explicit in the pattern.  |
|  Scenarios:  |  Give me the resource observations where the vertical distribution is 'Pelagic'  |
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
 __VerticalDistribution__ 
 Content OP locally defines the following ontology elements:_ 





[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__hasResource__ 
 (owl:ObjectProperty)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[hasResource](./AquaticResourceObservation/hasResource.md "Submissions:VerticalDistribution/hasResource") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__hasVerticalDistribution__ 
 (owl:ObjectProperty)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[hasVerticalDistribution](./AquaticResourceObservation/hasVerticalDistribution.md "Submissions:VerticalDistribution/hasVerticalDistribution") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__isResourceOf__ 
 (owl:ObjectProperty)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[isResourceOf](./AquaticResourceObservation/isResourceOf.md "Submissions:VerticalDistribution/isResourceOf") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__isVerticalDistributionOf__ 
 (owl:ObjectProperty)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[isVerticalDistributionOf](./AquaticResourceObservation/isVerticalDistributionOf.md "Submissions:VerticalDistribution/isVerticalDistributionOf") 
 page_ 



[![DatatypeProperty](./20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif.md "DatatypeProperty")
__hasReferenceYear__ 
 (owl:DatatypeProperty)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[hasReferenceYear](./AquaticResourceObservation/hasReferenceYear.md "Submissions:VerticalDistribution/hasReferenceYear") 
 page_ 



[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__AquaticResource__ 
 (owl:Class) A fishery resource (a collection of actual aquatic organisms) that can include aquatic organisms from different AquaticSpecies, and is localized in some WaterArea.
 
 It can be mapped to fi:AqResRef
 



[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[AquaticResource](./AquaticResourceObservation/AquaticResource.md "Submissions:VerticalDistribution/AquaticResource") 
 page_ 



[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__AquaticResourceObservation__ 
 (owl:Class) An observation of a resource characterised by different parameters.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[AquaticResourceObservation](../AquaticResourceObservation/AquaticResourceObservation.md "Submissions:VerticalDistribution/AquaticResourceObservation") 
 page_ 



[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__VerticalDistribution__ 
 (owl:Class)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[VerticalDistribution](./VerticalDistribution.md "Submissions:VerticalDistribution/VerticalDistribution") 
 page_ 


# 

 Additional information



 (type):
 [http://www.w3.org/2002/07/owl#Ontology](http://www.w3.org/2002/07/owl#Ontology "http://www.w3.org/2002/07/owl#Ontology") 




 (versionInfo): Created by Eva Blomqvist
 



 (versionInfo): 1.0
 



 (hasUnitTest): SELECT ?x WHERE {?x a :AquaticResourceObservation.  ?x :hasVerticalDistribution :Pelagic}
 



 (imports):
 [http://www.ontologydesignpatterns.org/cp/owl/fsdas/aquaticresources.owl](http://www.ontologydesignpatterns.org/cp/owl/fsdas/aquaticresources.owl "http://www.ontologydesignpatterns.org/cp/owl/fsdas/aquaticresources.owl") 




 (imports):
 [http://www.ontologydesignpatterns.org/cp/owl/observation.owl](http://www.ontologydesignpatterns.org/cp/owl/observation.owl "http://www.ontologydesignpatterns.org/cp/owl/observation.owl") 




 (imports):
 [http://www.ontologydesignpatterns.org/schemas/cpannotationschema.owl](http://www.ontologydesignpatterns.org/schemas/cpannotationschema.owl "http://www.ontologydesignpatterns.org/schemas/cpannotationschema.owl") 




# 

 Scenarios




__Scenarios about VerticalDistribution__ 


 No scenario is added to this Content OP.
 




# 

 Reviews




__Reviews about VerticalDistribution__ 


 There is no review about this proposal.
This revision (revision ID
 __9140__ 
 ) takes in account the reviews: none
 



 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:VerticalDistribution&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:VerticalDistribution&action=evaluation") 





  





# 

 Modeling issues




__Modeling issues about VerticalDistribution__ 


 There is no Modeling issue related to this proposal.
 




  





# 

 References
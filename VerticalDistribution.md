# 

 Graphical representation



__Diagram__ 
_(this article has no graphical representation)_ 




# 

 General description




|  |  |
| --- | --- |
|  Name:  |  VerticalDistribution  |
|  Submitted by:  | [AldoGangemi](../User/AldoGangemi "User:AldoGangemi")  , [EvaBlomqvist](../User/EvaBlomqvist "User:EvaBlomqvist")  |
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





[![ObjectProperty](public/images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasResource__ 
 (owl:ObjectProperty)
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasResource](../Submissions/VerticalDistribution/hasResource "Submissions:VerticalDistribution/hasResource") 
 page_ 



[![ObjectProperty](public/images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasVerticalDistribution__ 
 (owl:ObjectProperty)
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasVerticalDistribution](../Submissions/VerticalDistribution/hasVerticalDistribution "Submissions:VerticalDistribution/hasVerticalDistribution") 
 page_ 



[![ObjectProperty](public/images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__isResourceOf__ 
 (owl:ObjectProperty)
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[isResourceOf](../Submissions/VerticalDistribution/isResourceOf "Submissions:VerticalDistribution/isResourceOf") 
 page_ 



[![ObjectProperty](public/images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__isVerticalDistributionOf__ 
 (owl:ObjectProperty)
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[isVerticalDistributionOf](../Submissions/VerticalDistribution/isVerticalDistributionOf "Submissions:VerticalDistribution/isVerticalDistributionOf") 
 page_ 



[![DatatypeProperty](public/images/thumb/a/a5/DatatypeProperty.gif/20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif "DatatypeProperty")
__hasReferenceYear__ 
 (owl:DatatypeProperty)
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasReferenceYear](../Submissions/VerticalDistribution/hasReferenceYear "Submissions:VerticalDistribution/hasReferenceYear") 
 page_ 



[![Class](public/images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__AquaticResource__ 
 (owl:Class) A fishery resource (a collection of actual aquatic organisms) that can include aquatic organisms from different AquaticSpecies, and is localized in some WaterArea.
 
 It can be mapped to fi:AqResRef
 



[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[AquaticResource](../Submissions/VerticalDistribution/AquaticResource "Submissions:VerticalDistribution/AquaticResource") 
 page_ 



[![Class](public/images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__AquaticResourceObservation__ 
 (owl:Class) An observation of a resource characterised by different parameters.
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[AquaticResourceObservation](../Submissions/VerticalDistribution/AquaticResourceObservation "Submissions:VerticalDistribution/AquaticResourceObservation") 
 page_ 



[![Class](public/images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__VerticalDistribution__ 
 (owl:Class)
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[VerticalDistribution](../Submissions/VerticalDistribution/VerticalDistribution "Submissions:VerticalDistribution/VerticalDistribution") 
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
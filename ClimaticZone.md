# 

 Graphical representation



__Diagram__ 
_(this article has no graphical representation)_ 




# 

 General description




|  |  |
| --- | --- |
|  Name:  |  ClimaticZone  |
|  Submitted by:  | [AldoGangemi](../User/AldoGangemi "User:AldoGangemi")  , [EvaBlomqvist](../User/EvaBlomqvist "User:EvaBlomqvist")  |
|  Also Known As:  |  |
|  Intent:  |  The intent of the pattern is to be able to represent climatic zones for aquatic resources.  |
|  Domains:  | [Fishery](../Community/Fishery "Community:Fishery")  |
|  Competency Questions:  | <li>       What resource has what climatic zone?      </li> |
|  Solution description:  |  --  |
|  Reusable OWL Building Block:  | [http://www.ontologydesignpatterns.org/cp/owl/fsdas/climaticzone.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=http://www.ontologydesignpatterns.org/cp/owl/fsdas/climaticzone.owl&message=OWL building block&from_page_id=1215&update=)  (712)  |
|  Consequences:  |  This pattern only allows to query what climatic zones are typical of an aquatic resource. Whereas such values can be subject to observation, another pattern based on the generic 'observation' pattern should be used.  The climatic zone is intended to have a fixed set of values (to be defined as nominals) but this is not explicit in the pattern.  |
|  Scenarios:  |  Give me the resource observations where the zone is 'Tropical'  |
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
 __ClimaticZone__ 
 Content OP locally defines the following ontology elements:_ 





[![Class](public/images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__ClimaticZone__ 
 (owl:Class)
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[ClimaticZone](../Submissions/ClimaticZone/ClimaticZone "Submissions:ClimaticZone/ClimaticZone") 
 page_ 



[![Class](public/images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__AquaticResource__ 
 (owl:Class) A fishery resource (a collection of actual aquatic organisms) that can include aquatic organisms from different AquaticSpecies, and is localized in some WaterArea.
 
 It can be mapped to fi:AqResRef
 



[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[AquaticResource](../Submissions/ClimaticZone/AquaticResource "Submissions:ClimaticZone/AquaticResource") 
 page_ 



[![Class](public/images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__AquaticResourceObservation__ 
 (owl:Class) An observation of a resource characterised by different parameters.
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[AquaticResourceObservation](../Submissions/ClimaticZone/AquaticResourceObservation "Submissions:ClimaticZone/AquaticResourceObservation") 
 page_ 



[![ObjectProperty](public/images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasResource__ 
 (owl:ObjectProperty)
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasResource](../Submissions/ClimaticZone/hasResource "Submissions:ClimaticZone/hasResource") 
 page_ 



[![ObjectProperty](public/images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasClimaticZone__ 
 (owl:ObjectProperty)
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasClimaticZone](../Submissions/ClimaticZone/hasClimaticZone "Submissions:ClimaticZone/hasClimaticZone") 
 page_ 



[![ObjectProperty](public/images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__isClimaticZoneOf__ 
 (owl:ObjectProperty)
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[isClimaticZoneOf](../Submissions/ClimaticZone/isClimaticZoneOf "Submissions:ClimaticZone/isClimaticZoneOf") 
 page_ 



[![ObjectProperty](public/images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__isResourceOf__ 
 (owl:ObjectProperty)
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[isResourceOf](../Submissions/ClimaticZone/isResourceOf "Submissions:ClimaticZone/isResourceOf") 
 page_ 



[![DatatypeProperty](public/images/thumb/a/a5/DatatypeProperty.gif/20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif "DatatypeProperty")
__hasReferenceYear__ 
 (owl:DatatypeProperty)
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasReferenceYear](../Submissions/ClimaticZone/hasReferenceYear "Submissions:ClimaticZone/hasReferenceYear") 
 page_ 


# 

 Additional information



 (type):
 [http://www.w3.org/2002/07/owl#Ontology](http://www.w3.org/2002/07/owl#Ontology "http://www.w3.org/2002/07/owl#Ontology") 




 (imports):
 [http://www.ontologydesignpatterns.org/cp/owl/observation.owl](http://www.ontologydesignpatterns.org/cp/owl/observation.owl "http://www.ontologydesignpatterns.org/cp/owl/observation.owl") 




 (imports):
 [http://www.ontologydesignpatterns.org/cp/owl/fsdas/aquaticresources.owl](http://www.ontologydesignpatterns.org/cp/owl/fsdas/aquaticresources.owl "http://www.ontologydesignpatterns.org/cp/owl/fsdas/aquaticresources.owl") 




 (versionInfo): Created by Eva Blomqvist
 



 (hasUnitTest): SELECT ?x WHERE {?x a :AquaticResourceObservation.  ?x :hasClimaticZone :Tropical}
 



 (versionInfo): 1.0
 



 (imports):
 [http://www.ontologydesignpatterns.org/schemas/cpannotationschema.owl](http://www.ontologydesignpatterns.org/schemas/cpannotationschema.owl "http://www.ontologydesignpatterns.org/schemas/cpannotationschema.owl") 




# 

 Scenarios




__Scenarios about ClimaticZone__ 


 No scenario is added to this Content OP.
 




# 

 Reviews




__Reviews about ClimaticZone__ 


 There is no review about this proposal.
This revision (revision ID
 __8837__ 
 ) takes in account the reviews: none
 



 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:ClimaticZone&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:ClimaticZone&action=evaluation") 





  





# 

 Modeling issues




__Modeling issues about ClimaticZone__ 


 There is no Modeling issue related to this proposal.
 




  





# 

 References
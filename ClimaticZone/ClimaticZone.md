#  Graphical representation


__Diagram__
_(this article has no graphical representation)_



#  General description




|  |  |
| --- | --- |
|  Name: |  ClimaticZone |
|  Submitted by: | [AldoGangemi](../User/AldoGangemi.md "User:AldoGangemi"), [EvaBlomqvist](../User/EvaBlomqvist.md "User:EvaBlomqvist") |
|  Also Known As: |  |
|  Intent: |  The intent of the pattern is to be able to represent climatic zones for aquatic resources. |
|  Domains: | [Fishery](../Community/Fishery.md "Community:Fishery") |
|  Competency Questions: | <li> What resource has what climatic zone?</li> |
|  Solution description: |  -- |
|  Reusable OWL Building Block: | [http://www.ontologydesignpatterns.org/cp/owl/fsdas/climaticzone.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=http://www.ontologydesignpatterns.org/cp/owl/fsdas/climaticzone.owl&message=OWL building block&from_page_id=1215&update=) (712) |
|  Consequences: |  This pattern only allows to query what climatic zones are typical of an aquatic resource. Whereas such values can be subject to observation, another pattern based on the generic 'observation' pattern should be used.The climatic zone is intended to have a fixed set of values (to be defined as nominals) but this is not explicit in the pattern. |
|  Scenarios: |  Give me the resource observations where the zone is 'Tropical' |
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


_The __ClimaticZone__ Content OP locally defines the following ontology elements:_



[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __ClimaticZone__ (owl:Class) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[ClimaticZone](./ClimaticZone.md "Submissions:ClimaticZone/ClimaticZone") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __AquaticResource__ (owl:Class) A fishery resource (a collection of actual aquatic organisms) that can include aquatic organisms from different AquaticSpecies, and is localized in some WaterArea.
It can be mapped to fi:AqResRef 



 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[AquaticResource](./AquaticResourceObservation/AquaticResource.md "Submissions:ClimaticZone/AquaticResource") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __AquaticResourceObservation__ (owl:Class) An observation of a resource characterised by different parameters. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[AquaticResourceObservation](./AquaticResourceObservation.md "Submissions:ClimaticZone/AquaticResourceObservation") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasResource__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasResource](./AquaticResourceObservation/hasResource.md "Submissions:ClimaticZone/hasResource") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasClimaticZone__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasClimaticZone](./AquaticResourceObservation/hasClimaticZone.md "Submissions:ClimaticZone/hasClimaticZone") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isClimaticZoneOf__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isClimaticZoneOf](./AquaticResourceObservation/isClimaticZoneOf.md "Submissions:ClimaticZone/isClimaticZoneOf") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isResourceOf__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isResourceOf](./AquaticResourceObservation/isResourceOf.md "Submissions:ClimaticZone/isResourceOf") page_
[![DatatypeProperty](./20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif.md "DatatypeProperty") __hasReferenceYear__ (owl:DatatypeProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasReferenceYear](./AquaticResourceObservation/hasReferenceYear.md "Submissions:ClimaticZone/hasReferenceYear") page_
#  Additional information


(type): [http://www.w3.org/2002/07/owl#Ontology](http://www.w3.org/2002/07/owl#Ontology "http://www.w3.org/2002/07/owl#Ontology")


(imports): [http://www.ontologydesignpatterns.org/cp/owl/observation.owl](http://www.ontologydesignpatterns.org/cp/owl/observation.owl "http://www.ontologydesignpatterns.org/cp/owl/observation.owl")


(imports): [http://www.ontologydesignpatterns.org/cp/owl/fsdas/aquaticresources.owl](http://www.ontologydesignpatterns.org/cp/owl/fsdas/aquaticresources.owl "http://www.ontologydesignpatterns.org/cp/owl/fsdas/aquaticresources.owl")


(versionInfo): Created by Eva Blomqvist


(hasUnitTest): SELECT ?x WHERE {?x a :AquaticResourceObservation.  ?x :hasClimaticZone :Tropical}


(versionInfo): 1.0


(imports): [http://www.ontologydesignpatterns.org/schemas/cpannotationschema.owl](http://www.ontologydesignpatterns.org/schemas/cpannotationschema.owl "http://www.ontologydesignpatterns.org/schemas/cpannotationschema.owl")



#  Scenarios



__Scenarios about ClimaticZone__
No scenario is added to this Content OP.




#  Reviews



__Reviews about ClimaticZone__
There is no review about this proposal.
This revision (revision ID __8837__) takes in account the reviews: none


Other info at [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:ClimaticZone&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:ClimaticZone&action=evaluation")




  




#  Modeling issues



__Modeling issues about ClimaticZone__
There is no Modeling issue related to this proposal.




  




#  References
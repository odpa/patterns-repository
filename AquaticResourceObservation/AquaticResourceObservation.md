# 

 Graphical representation



__Diagram__ 





[![Image:AquaticResourceObservation.png](./AquaticResourceObservation.png)](../Image/AquaticResourceObservation.png.md "Image:AquaticResourceObservation.png")





# 

 General description




|  |  |
| --- | --- |
|  Name:  |  AquaticResourceObservation  |
|  Submitted by:  | [AldoGangemi](../User/AldoGangemi.md "User:AldoGangemi")  |
|  Also Known As:  |  |
|  Intent:  |  To represent the aquatic observation data extracted from factsheet application. An aquatic observation refers to a specific year, is about an aquatic resource, and is situated in a given habitat, in which the aquatic species from the resource live. Observations can have a reporting year that is different from the observation time.  |
|  Domains:  | [Fishery](../Community/Fishery.md "Community:Fishery")  |
|  Competency Questions:  | <li>       For an aquatic resource      </li><li>       what species      </li><li>       in what fishing areas      </li><li>       climatic zones      </li><li>       bottom types      </li><li>       depth zones      </li><li>       geo forms      </li><li>       horizontal and vertical distribution      </li><li>       and for what standardized abundance level      </li><li>       exploitation state and rate      </li><li>       have been observed? for what reference year? At what year the observation has been recorded?      </li> |
|  Solution description:  |  This pattern specializes the observation pattern in order to represent situations of aquatic resource features, which contain parameters, time, place, etc. A peculiar difference is the use of two temporal indexes: reference and reporting times. The first is the time, at which the situation represented occurred; the second is the time, at which the observation has been reported.  |
|  Reusable OWL Building Block:  | [http://ontologydesignpatterns.org/cp/owl/fsdas/aquaticresourceobservation.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=http://ontologydesignpatterns.org/cp/owl/fsdas/aquaticresourceobservation.owl&message=OWL building block&from_page_id=2074&update=)  (695)  |
|  Consequences:  |  We are able to query and reason on the data extracted from the FactSheets XML database, concerning the observation of aquatic resources. There are more data in that database, however.  |
|  Scenarios:  |  The aquatic resource for Skipjack tuna in Northern Atlantic in 2004 (as reported in 2008) was observed with low abundance level.  |
|  Known Uses:  |  |
|  Web References:  |  |
|  Other References:  |  |
|  Examples (OWL files):  |  |
|  Extracted From:  |  |
|  Reengineered From:  |  |
|  Has Components:  | <li><a class="new" href="http://ontologydesignpatterns.org/wiki/Special:AddData/Content OP Proposal Form/Submissions:SpeciesFactsheets" title="Submissions:SpeciesFactsheets (not yet written)">        Submissions:SpeciesFactsheets       </a></li><li><a class="new" href="http://ontologydesignpatterns.org/wiki/Special:AddData/Content OP Proposal Form/Submissions:WaterAreasFactsheets" title="Submissions:WaterAreasFactsheets (not yet written)">        Submissions:WaterAreasFactsheets       </a></li> |
|  Specialization Of:  | <li><a href="./AquaticResourceObservation.md" title="Submissions:Observation">        Submissions:Observation       </a></li> |
|  Related CPs:  | <li><a href="../CatchRecord/CatchRecord.md" title="Submissions:CatchRecord">        Submissions:CatchRecord       </a></li> |



  





# 

 Elements



_The
 __AquaticResourceObservation__ 
 Content OP locally defines the following ontology elements:_ 





[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__bottomTypeOfObservation__ 
 (owl:ObjectProperty)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[bottomTypeOfObservation](./AquaticResourceObservation/bottomTypeOfObservation.md "Submissions:AquaticResourceObservation/bottomTypeOfObservation") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__climaticZoneOfObservation__ 
 (owl:ObjectProperty)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[climaticZoneOfObservation](./AquaticResourceObservation/climaticZoneOfObservation.md "Submissions:AquaticResourceObservation/climaticZoneOfObservation") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__depthZoneOfObservation__ 
 (owl:ObjectProperty)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[depthZoneOfObservation](./AquaticResourceObservation/depthZoneOfObservation.md "Submissions:AquaticResourceObservation/depthZoneOfObservation") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__fishingAreaOfObservation__ 
 (owl:ObjectProperty)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[fishingAreaOfObservation](./AquaticResourceObservation/fishingAreaOfObservation.md "Submissions:AquaticResourceObservation/fishingAreaOfObservation") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__geoFormOfObservation__ 
 (owl:ObjectProperty)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[geoFormOfObservation](./AquaticResourceObservation/geoFormOfObservation.md "Submissions:AquaticResourceObservation/geoFormOfObservation") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__horizontalDistributionOfObservation__ 
 (owl:ObjectProperty)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[horizontalDistributionOfObservation](./AquaticResourceObservation/horizontalDistributionOfObservation.md "Submissions:AquaticResourceObservation/horizontalDistributionOfObservation") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__ofBottomType__ 
 (owl:ObjectProperty)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[ofBottomType](./AquaticResourceObservation/ofBottomType.md "Submissions:AquaticResourceObservation/ofBottomType") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__ofClimaticZone__ 
 (owl:ObjectProperty)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[ofClimaticZone](./AquaticResourceObservation/ofClimaticZone.md "Submissions:AquaticResourceObservation/ofClimaticZone") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__ofDepthZone__ 
 (owl:ObjectProperty)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[ofDepthZone](./AquaticResourceObservation/ofDepthZone.md "Submissions:AquaticResourceObservation/ofDepthZone") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__ofFishingArea__ 
 (owl:ObjectProperty)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[ofFishingArea](./AquaticResourceObservation/ofFishingArea.md "Submissions:AquaticResourceObservation/ofFishingArea") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__ofGeoForm__ 
 (owl:ObjectProperty)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[ofGeoForm](./AquaticResourceObservation/ofGeoForm.md "Submissions:AquaticResourceObservation/ofGeoForm") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__ofHorizontalDistribution__ 
 (owl:ObjectProperty)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[ofHorizontalDistribution](./AquaticResourceObservation/ofHorizontalDistribution.md "Submissions:AquaticResourceObservation/ofHorizontalDistribution") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__ofSpecies__ 
 (owl:ObjectProperty)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[ofSpecies](./AquaticResourceObservation/ofSpecies.md "Submissions:AquaticResourceObservation/ofSpecies") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__ofStdAbundanceLevel__ 
 (owl:ObjectProperty)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[ofStdAbundanceLevel](./AquaticResourceObservation/ofStdAbundanceLevel.md "Submissions:AquaticResourceObservation/ofStdAbundanceLevel") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__ofStdExploitationRate__ 
 (owl:ObjectProperty)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[ofStdExploitationRate](./AquaticResourceObservation/ofStdExploitationRate.md "Submissions:AquaticResourceObservation/ofStdExploitationRate") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__ofStdExploitationState__ 
 (owl:ObjectProperty)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[ofStdExploitationState](./AquaticResourceObservation/ofStdExploitationState.md "Submissions:AquaticResourceObservation/ofStdExploitationState") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__ofVerticalDistribution__ 
 (owl:ObjectProperty)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[ofVerticalDistribution](./AquaticResourceObservation/ofVerticalDistribution.md "Submissions:AquaticResourceObservation/ofVerticalDistribution") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__speciesFromObservation__ 
 (owl:ObjectProperty)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[speciesFromObservation](./AquaticResourceObservation/speciesFromObservation.md "Submissions:AquaticResourceObservation/speciesFromObservation") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__stdAbundanceLevelOfObservation__ 
 (owl:ObjectProperty)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[stdAbundanceLevelOfObservation](./AquaticResourceObservation/stdAbundanceLevelOfObservation.md "Submissions:AquaticResourceObservation/stdAbundanceLevelOfObservation") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__stdExploitationRateOfObservation__ 
 (owl:ObjectProperty)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[stdExploitationRateOfObservation](./AquaticResourceObservation/stdExploitationRateOfObservation.md "Submissions:AquaticResourceObservation/stdExploitationRateOfObservation") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__stdExploitationStateOfObservation__ 
 (owl:ObjectProperty)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[stdExploitationStateOfObservation](./AquaticResourceObservation/stdExploitationStateOfObservation.md "Submissions:AquaticResourceObservation/stdExploitationStateOfObservation") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__verticalDistributionOfObservation__ 
 (owl:ObjectProperty)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[verticalDistributionOfObservation](./AquaticResourceObservation/verticalDistributionOfObservation.md "Submissions:AquaticResourceObservation/verticalDistributionOfObservation") 
 page_ 



[![DatatypeProperty](./20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif.md "DatatypeProperty")
__forReferenceYear__ 
 (owl:DatatypeProperty)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[forReferenceYear](./AquaticResourceObservation/forReferenceYear.md "Submissions:AquaticResourceObservation/forReferenceYear") 
 page_ 



[![DatatypeProperty](./20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif.md "DatatypeProperty")
__hasReportingYear__ 
 (owl:DatatypeProperty)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[hasReportingYear](./AquaticResourceObservation/hasReportingYear.md "Submissions:AquaticResourceObservation/hasReportingYear") 
 page_ 



[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__AquaticResource__ 
 (owl:Class) An aquatic resource.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[AquaticResource](./AquaticResourceObservation/AquaticResource.md "Submissions:AquaticResourceObservation/AquaticResource") 
 page_ 



[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__AquaticResourceObservation__ 
 (owl:Class) An observation singled out of reported data, once a year, about an aquatic resource.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[AquaticResourceObservation](./AquaticResourceObservation.md "Submissions:AquaticResourceObservation/AquaticResourceObservation") 
 page_ 



[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__BottomType__ 
 (owl:Class)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[BottomType](./AquaticResourceObservation/BottomType.md "Submissions:AquaticResourceObservation/BottomType") 
 page_ 



[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__ClimaticZone__ 
 (owl:Class)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[ClimaticZone](../ClimaticZone/ClimaticZone.md "Submissions:AquaticResourceObservation/ClimaticZone") 
 page_ 



[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__DepthZone__ 
 (owl:Class)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[DepthZone](./AquaticResourceObservation/DepthZone.md "Submissions:AquaticResourceObservation/DepthZone") 
 page_ 



[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__GeoForm__ 
 (owl:Class)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[GeoForm](./AquaticResourceObservation/GeoForm.md "Submissions:AquaticResourceObservation/GeoForm") 
 page_ 



[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__HorizontalDistribution__ 
 (owl:Class)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[HorizontalDistribution](./AquaticResourceObservation/HorizontalDistribution.md "Submissions:AquaticResourceObservation/HorizontalDistribution") 
 page_ 



[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__StdAbundanceLevel__ 
 (owl:Class)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[StdAbundanceLevel](./AquaticResourceObservation/ofStdAbundanceLevel.md "Submissions:AquaticResourceObservation/StdAbundanceLevel") 
 page_ 



[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__StdExploitationRate__ 
 (owl:Class)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[StdExploitationRate](./AquaticResourceObservation/ofStdExploitationRate.md "Submissions:AquaticResourceObservation/StdExploitationRate") 
 page_ 



[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__StdExploitationState__ 
 (owl:Class)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[StdExploitationState](./AquaticResourceObservation/ofStdExploitationState.md "Submissions:AquaticResourceObservation/StdExploitationState") 
 page_ 



[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__VerticalDistribution__ 
 (owl:Class)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[VerticalDistribution](../VerticalDistribution/VerticalDistribution.md "Submissions:AquaticResourceObservation/VerticalDistribution") 
 page_ 


# 

 Additional information



 An ontology that represents the semantics of a database view about aquatic resources and their related data
 



# 

 Scenarios




__Scenarios about AquaticResourceObservation__ 


 No scenario is added to this Content OP.
 




# 

 Reviews




__Reviews about AquaticResourceObservation__ 



|  Review article  | [Posted on](../Property/CreationDate.md "Property:CreationDate")  | [About revision (current is 9064)](../Property/ReviewAboutVersion.md "Property:ReviewAboutVersion")  |
| --- | --- | --- |
| [AldoGangemi about AquaticResourceObservation](../Community/AldoGangemi_about_AquaticResourceObservation.md "Community:AldoGangemi about AquaticResourceObservation")  |  2454908  17 March 2009  |  3646  3,646  |
| [AldoGangemi about AquaticResourceObservation](../Reviews/AldoGangemi_about_AquaticResourceObservation.md "Reviews:AldoGangemi about AquaticResourceObservation")  |  2454908  17 March 2009  |  3646  3,646  |



 This revision (revision ID
 __9064__ 
 ) takes in account the reviews: none
 



 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:AquaticResourceObservation&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:AquaticResourceObservation&action=evaluation") 





  





# 

 Modeling issues




__Modeling issues about AquaticResourceObservation__ 


 There is no Modeling issue related to this proposal.
 




  





# 

 References
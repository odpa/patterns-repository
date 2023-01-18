# 

 Graphical representation



__Diagram__ 





[![Image:AquaticResourceObservation.png](../images/0/0a/AquaticResourceObservation.png)](../Image/AquaticResourceObservation.png "Image:AquaticResourceObservation.png")





# 

 General description




|  |  |
| --- | --- |
|  Name:  |  AquaticResourceObservation  |
|  Submitted by:  | [AldoGangemi](../User/AldoGangemi "User:AldoGangemi")  |
|  Also Known As:  |  |
|  Intent:  |  To represent the aquatic observation data extracted from factsheet application. An aquatic observation refers to a specific year, is about an aquatic resource, and is situated in a given habitat, in which the aquatic species from the resource live. Observations can have a reporting year that is different from the observation time.  |
|  Domains:  | [Fishery](../Community/Fishery "Community:Fishery")  |
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
|  Specialization Of:  | <li><a href="Submissions%253AObservation.html" title="Submissions:Observation">        Submissions:Observation       </a></li> |
|  Related CPs:  | <li><a href="Submissions%253ACatchRecord.html" title="Submissions:CatchRecord">        Submissions:CatchRecord       </a></li> |



  





# 

 Elements



_The
 __AquaticResourceObservation__ 
 Content OP locally defines the following ontology elements:_ 





[![ObjectProperty](../../../../../../../../../../../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__bottomTypeOfObservation__ 
 (owl:ObjectProperty)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[bottomTypeOfObservation](../Submissions/AquaticResourceObservation/bottomTypeOfObservation "Submissions:AquaticResourceObservation/bottomTypeOfObservation") 
 page_ 



[![ObjectProperty](../../../../../../../../../../../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__climaticZoneOfObservation__ 
 (owl:ObjectProperty)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[climaticZoneOfObservation](../Submissions/AquaticResourceObservation/climaticZoneOfObservation "Submissions:AquaticResourceObservation/climaticZoneOfObservation") 
 page_ 



[![ObjectProperty](../../../../../../../../../../../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__depthZoneOfObservation__ 
 (owl:ObjectProperty)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[depthZoneOfObservation](../Submissions/AquaticResourceObservation/depthZoneOfObservation "Submissions:AquaticResourceObservation/depthZoneOfObservation") 
 page_ 



[![ObjectProperty](../../../../../../../../../../../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__fishingAreaOfObservation__ 
 (owl:ObjectProperty)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[fishingAreaOfObservation](../Submissions/AquaticResourceObservation/fishingAreaOfObservation "Submissions:AquaticResourceObservation/fishingAreaOfObservation") 
 page_ 



[![ObjectProperty](../../../../../../../../../../../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__geoFormOfObservation__ 
 (owl:ObjectProperty)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[geoFormOfObservation](../Submissions/AquaticResourceObservation/geoFormOfObservation "Submissions:AquaticResourceObservation/geoFormOfObservation") 
 page_ 



[![ObjectProperty](../../../../../../../../../../../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__horizontalDistributionOfObservation__ 
 (owl:ObjectProperty)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[horizontalDistributionOfObservation](../Submissions/AquaticResourceObservation/horizontalDistributionOfObservation "Submissions:AquaticResourceObservation/horizontalDistributionOfObservation") 
 page_ 



[![ObjectProperty](../../../../../../../../../../../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__ofBottomType__ 
 (owl:ObjectProperty)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[ofBottomType](../Submissions/AquaticResourceObservation/ofBottomType "Submissions:AquaticResourceObservation/ofBottomType") 
 page_ 



[![ObjectProperty](../../../../../../../../../../../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__ofClimaticZone__ 
 (owl:ObjectProperty)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[ofClimaticZone](../Submissions/AquaticResourceObservation/ofClimaticZone "Submissions:AquaticResourceObservation/ofClimaticZone") 
 page_ 



[![ObjectProperty](../../../../../../../../../../../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__ofDepthZone__ 
 (owl:ObjectProperty)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[ofDepthZone](../Submissions/AquaticResourceObservation/ofDepthZone "Submissions:AquaticResourceObservation/ofDepthZone") 
 page_ 



[![ObjectProperty](../../../../../../../../../../../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__ofFishingArea__ 
 (owl:ObjectProperty)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[ofFishingArea](../Submissions/AquaticResourceObservation/ofFishingArea "Submissions:AquaticResourceObservation/ofFishingArea") 
 page_ 



[![ObjectProperty](../../../../../../../../../../../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__ofGeoForm__ 
 (owl:ObjectProperty)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[ofGeoForm](../Submissions/AquaticResourceObservation/ofGeoForm "Submissions:AquaticResourceObservation/ofGeoForm") 
 page_ 



[![ObjectProperty](../../../../../../../../../../../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__ofHorizontalDistribution__ 
 (owl:ObjectProperty)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[ofHorizontalDistribution](../Submissions/AquaticResourceObservation/ofHorizontalDistribution "Submissions:AquaticResourceObservation/ofHorizontalDistribution") 
 page_ 



[![ObjectProperty](../../../../../../../../../../../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__ofSpecies__ 
 (owl:ObjectProperty)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[ofSpecies](../Submissions/AquaticResourceObservation/ofSpecies "Submissions:AquaticResourceObservation/ofSpecies") 
 page_ 



[![ObjectProperty](../../../../../../../../../../../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__ofStdAbundanceLevel__ 
 (owl:ObjectProperty)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[ofStdAbundanceLevel](../Submissions/AquaticResourceObservation/ofStdAbundanceLevel "Submissions:AquaticResourceObservation/ofStdAbundanceLevel") 
 page_ 



[![ObjectProperty](../../../../../../../../../../../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__ofStdExploitationRate__ 
 (owl:ObjectProperty)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[ofStdExploitationRate](../Submissions/AquaticResourceObservation/ofStdExploitationRate "Submissions:AquaticResourceObservation/ofStdExploitationRate") 
 page_ 



[![ObjectProperty](../../../../../../../../../../../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__ofStdExploitationState__ 
 (owl:ObjectProperty)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[ofStdExploitationState](../Submissions/AquaticResourceObservation/ofStdExploitationState "Submissions:AquaticResourceObservation/ofStdExploitationState") 
 page_ 



[![ObjectProperty](../../../../../../../../../../../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__ofVerticalDistribution__ 
 (owl:ObjectProperty)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[ofVerticalDistribution](../Submissions/AquaticResourceObservation/ofVerticalDistribution "Submissions:AquaticResourceObservation/ofVerticalDistribution") 
 page_ 



[![ObjectProperty](../../../../../../../../../../../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__speciesFromObservation__ 
 (owl:ObjectProperty)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[speciesFromObservation](../Submissions/AquaticResourceObservation/speciesFromObservation "Submissions:AquaticResourceObservation/speciesFromObservation") 
 page_ 



[![ObjectProperty](../../../../../../../../../../../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__stdAbundanceLevelOfObservation__ 
 (owl:ObjectProperty)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[stdAbundanceLevelOfObservation](../Submissions/AquaticResourceObservation/stdAbundanceLevelOfObservation "Submissions:AquaticResourceObservation/stdAbundanceLevelOfObservation") 
 page_ 



[![ObjectProperty](../../../../../../../../../../../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__stdExploitationRateOfObservation__ 
 (owl:ObjectProperty)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[stdExploitationRateOfObservation](../Submissions/AquaticResourceObservation/stdExploitationRateOfObservation "Submissions:AquaticResourceObservation/stdExploitationRateOfObservation") 
 page_ 



[![ObjectProperty](../../../../../../../../../../../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__stdExploitationStateOfObservation__ 
 (owl:ObjectProperty)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[stdExploitationStateOfObservation](../Submissions/AquaticResourceObservation/stdExploitationStateOfObservation "Submissions:AquaticResourceObservation/stdExploitationStateOfObservation") 
 page_ 



[![ObjectProperty](../../../../../../../../../../../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__verticalDistributionOfObservation__ 
 (owl:ObjectProperty)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[verticalDistributionOfObservation](../Submissions/AquaticResourceObservation/verticalDistributionOfObservation "Submissions:AquaticResourceObservation/verticalDistributionOfObservation") 
 page_ 



[![DatatypeProperty](../../images/thumb/a/a5/DatatypeProperty.gif/20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif "DatatypeProperty")
__forReferenceYear__ 
 (owl:DatatypeProperty)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[forReferenceYear](../Submissions/AquaticResourceObservation/forReferenceYear "Submissions:AquaticResourceObservation/forReferenceYear") 
 page_ 



[![DatatypeProperty](../../images/thumb/a/a5/DatatypeProperty.gif/20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif "DatatypeProperty")
__hasReportingYear__ 
 (owl:DatatypeProperty)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasReportingYear](../Submissions/AquaticResourceObservation/hasReportingYear "Submissions:AquaticResourceObservation/hasReportingYear") 
 page_ 



[![Class](../../../../../../../../../../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__AquaticResource__ 
 (owl:Class) An aquatic resource.
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[AquaticResource](../Submissions/AquaticResourceObservation/AquaticResource "Submissions:AquaticResourceObservation/AquaticResource") 
 page_ 



[![Class](../../../../../../../../../../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__AquaticResourceObservation__ 
 (owl:Class) An observation singled out of reported data, once a year, about an aquatic resource.
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[AquaticResourceObservation](../Submissions/AquaticResourceObservation/AquaticResourceObservation "Submissions:AquaticResourceObservation/AquaticResourceObservation") 
 page_ 



[![Class](../../../../../../../../../../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__BottomType__ 
 (owl:Class)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[BottomType](../Submissions/AquaticResourceObservation/BottomType "Submissions:AquaticResourceObservation/BottomType") 
 page_ 



[![Class](../../../../../../../../../../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__ClimaticZone__ 
 (owl:Class)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[ClimaticZone](../Submissions/AquaticResourceObservation/ClimaticZone "Submissions:AquaticResourceObservation/ClimaticZone") 
 page_ 



[![Class](../../../../../../../../../../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__DepthZone__ 
 (owl:Class)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[DepthZone](../Submissions/AquaticResourceObservation/DepthZone "Submissions:AquaticResourceObservation/DepthZone") 
 page_ 



[![Class](../../../../../../../../../../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__GeoForm__ 
 (owl:Class)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[GeoForm](../Submissions/AquaticResourceObservation/GeoForm "Submissions:AquaticResourceObservation/GeoForm") 
 page_ 



[![Class](../../../../../../../../../../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__HorizontalDistribution__ 
 (owl:Class)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[HorizontalDistribution](../Submissions/AquaticResourceObservation/HorizontalDistribution "Submissions:AquaticResourceObservation/HorizontalDistribution") 
 page_ 



[![Class](../../../../../../../../../../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__StdAbundanceLevel__ 
 (owl:Class)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[StdAbundanceLevel](../Submissions/AquaticResourceObservation/StdAbundanceLevel "Submissions:AquaticResourceObservation/StdAbundanceLevel") 
 page_ 



[![Class](../../../../../../../../../../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__StdExploitationRate__ 
 (owl:Class)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[StdExploitationRate](../Submissions/AquaticResourceObservation/StdExploitationRate "Submissions:AquaticResourceObservation/StdExploitationRate") 
 page_ 



[![Class](../../../../../../../../../../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__StdExploitationState__ 
 (owl:Class)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[StdExploitationState](../Submissions/AquaticResourceObservation/StdExploitationState "Submissions:AquaticResourceObservation/StdExploitationState") 
 page_ 



[![Class](../../../../../../../../../../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__VerticalDistribution__ 
 (owl:Class)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[VerticalDistribution](../Submissions/AquaticResourceObservation/VerticalDistribution "Submissions:AquaticResourceObservation/VerticalDistribution") 
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



|  Review article  | [Posted on](../Property/CreationDate "Property:CreationDate")  | [About revision (current is 9064)](../Property/ReviewAboutVersion "Property:ReviewAboutVersion")  |
| --- | --- | --- |
| [AldoGangemi about AquaticResourceObservation](../Community/AldoGangemi_about_AquaticResourceObservation "Community:AldoGangemi about AquaticResourceObservation")  |  2454908  17 March 2009  |  3646  3,646  |
| [AldoGangemi about AquaticResourceObservation](../Reviews/AldoGangemi_about_AquaticResourceObservation "Reviews:AldoGangemi about AquaticResourceObservation")  |  2454908  17 March 2009  |  3646  3,646  |



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
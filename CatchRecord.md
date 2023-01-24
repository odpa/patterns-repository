# 

 Graphical representation



__Diagram__ 





[![Image:CatchRecord.png](../images/b/bb/CatchRecord.png)](../Image/CatchRecord.png "Image:CatchRecord.png")





# 

 General description




|  |  |
| --- | --- |
|  Name:  |  CatchRecord  |
|  Submitted by:  | [AldoGangemi](../User/AldoGangemi "User:AldoGangemi")  |
|  Also Known As:  |  |
|  Intent:  |  To represent the catch records from time series FIGIS application, which contain temporally-indexed aggregated information about aquatic species cacthing.  |
|  Domains:  | [Fishery](../Community/Fishery "Community:Fishery")  |
|  Competency Questions:  | <li>       What species      </li><li>       and what amount of organisms      </li><li>       have been caught from what areas      </li><li>       countries      </li><li>       at what date and fishing year?      </li> |
|  Solution description:  |  This pattern specializes the observation pattern in order to represent situations of aquatic species catching that contain parameters, time, place, etc. A peculiar difference is the use of two temporal indexes: reference and reporting times. The first is the time, at which the situation represented occurred; the second is the time, at which the observation has been reported.  |
|  Reusable OWL Building Block:  | [http://www.ontologydesignpatterns.org/cp/owl/fsdas/catchrecord.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=http://www.ontologydesignpatterns.org/cp/owl/fsdas/catchrecord.owl&message=OWL building block&from_page_id=2106&update=)  (633)  |
|  Consequences:  |  We are able to query time-series data for catches of species in a certain fishing area, by vessels of some country, with anounts and measurement units.  |
|  Scenarios:  |  |
|  Known Uses:  |  |
|  Web References:  |  |
|  Other References:  |  |
|  Examples (OWL files):  |  |
|  Extracted From:  |  |
|  Reengineered From:  |  |
|  Has Components:  | <li><a class="new" href="http://ontologydesignpatterns.org/wiki/Special:AddData/Content OP Proposal Form/Submissions:SpeciesFactsheets" title="Submissions:SpeciesFactsheets (not yet written)">        Submissions:SpeciesFactsheets       </a></li><li><a class="new" href="http://ontologydesignpatterns.org/wiki/Special:AddData/Content OP Proposal Form/Submissions:WaterAreaFactsheets" title="Submissions:WaterAreaFactsheets (not yet written)">        Submissions:WaterAreaFactsheets       </a></li> |
|  Specialization Of:  | <li><a href="Submissions%253AObservation.html" title="Submissions:Observation">        Submissions:Observation       </a></li> |
|  Related CPs:  |  |



  





# 

 Elements



_The
 __CatchRecord__ 
 Content OP locally defines the following ontology elements:_ 





[![ObjectProperty](../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__countryOfRecord__ 
 (owl:ObjectProperty) The country parameter for a species catch record.
 
[![](../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[countryOfRecord](../Submissions/CatchRecord/countryOfRecord "Submissions:CatchRecord/countryOfRecord") 
 page_ 



[![ObjectProperty](../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__fishingAreaOfRecord__ 
 (owl:ObjectProperty) The area parameter for a species catch record.
 
[![](../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[fishingAreaOfRecord](../Submissions/CatchRecord/fishingAreaOfRecord "Submissions:CatchRecord/fishingAreaOfRecord") 
 page_ 



[![ObjectProperty](../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__forCountry__ 
 (owl:ObjectProperty) The country parameter for a species catch record.
 
[![](../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[forCountry](../Submissions/CatchRecord/forCountry "Submissions:CatchRecord/forCountry") 
 page_ 



[![ObjectProperty](../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__fromFishingArea__ 
 (owl:ObjectProperty) The area parameter for a species catch record.
 
[![](../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[fromFishingArea](../Submissions/CatchRecord/fromFishingArea "Submissions:CatchRecord/fromFishingArea") 
 page_ 



[![ObjectProperty](../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasCatchRecord__ 
 (owl:ObjectProperty) The catch record of a species, i.e. its statistical observation over a reference year.
 
[![](../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasCatchRecord](../Submissions/CatchRecord/hasCatchRecord "Submissions:CatchRecord/hasCatchRecord") 
 page_ 



[![ObjectProperty](../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__isCatchRecordFor__ 
 (owl:ObjectProperty) The catch record of a species, i.e. its statistical observation over a reference year.
 
[![](../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[isCatchRecordFor](../Submissions/CatchRecord/isCatchRecordFor "Submissions:CatchRecord/isCatchRecordFor") 
 page_ 



[![ObjectProperty](../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__unitUsedInRecord__ 
 (owl:ObjectProperty) The unit of measure parameter for a species catch record.
 
[![](../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[unitUsedInRecord](../Submissions/CatchRecord/unitUsedInRecord "Submissions:CatchRecord/unitUsedInRecord") 
 page_ 



[![ObjectProperty](../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__withUnit__ 
 (owl:ObjectProperty) The unit of measure parameter for a species catch record.
 
[![](../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[withUnit](../Submissions/CatchRecord/withUnit "Submissions:CatchRecord/withUnit") 
 page_ 



[![DatatypeProperty](../../../images/thumb/a/a5/DatatypeProperty.gif/20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif "DatatypeProperty")
__amount__ 
 (owl:DatatypeProperty)
 
[![](../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[amount](../Submissions/CatchRecord/amount "Submissions:CatchRecord/amount") 
 page_ 



[![DatatypeProperty](../../../images/thumb/a/a5/DatatypeProperty.gif/20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif "DatatypeProperty")
__referenceYear__ 
 (owl:DatatypeProperty) The year for which the status of the target object (e.g. Marine Resource, Fishery...) has been evaluated.
 
[![](../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[referenceYear](../Submissions/CatchRecord/referenceYear "Submissions:CatchRecord/referenceYear") 
 page_ 



[![DatatypeProperty](../../../images/thumb/a/a5/DatatypeProperty.gif/20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif "DatatypeProperty")
__reportingYear__ 
 (owl:DatatypeProperty) The year in which a catch record has been officially reported (different from its reference year, i.e. the year of the actual observation).
 
[![](../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[reportingYear](../Submissions/CatchRecord/reportingYear "Submissions:CatchRecord/reportingYear") 
 page_ 



[![Class](../../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__CatchRecord__ 
 (owl:Class) A design pattern representing the semantics of the data contained in a database view (record) about catches of species in certain fishing areas for a certain reference year.
 
[![](../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[CatchRecord](../Submissions/CatchRecord/CatchRecord "Submissions:CatchRecord/CatchRecord") 
 page_ 



[![Class](../../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__Country__ 
 (owl:Class)
 
[![](../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[Country](../Submissions/CatchRecord/Country "Submissions:CatchRecord/Country") 
 page_ 



[![Class](../../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__UnitOfMeasure__ 
 (owl:Class)
 
[![](../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[UnitOfMeasure](../Submissions/CatchRecord/UnitOfMeasure "Submissions:CatchRecord/UnitOfMeasure") 
 page_ 


# 

 Additional information



 A design pattern for populating an ontology of aquatic species catching records.
 



# 

 Scenarios




__Scenarios about CatchRecord__ 


 No scenario is added to this Content OP.
 




# 

 Reviews




__Reviews about CatchRecord__ 


 There is no review about this proposal.
This revision (revision ID
 __9069__ 
 ) takes in account the reviews: none
 



 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:CatchRecord&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:CatchRecord&action=evaluation") 





  





# 

 Modeling issues




__Modeling issues about CatchRecord__ 


 There is no Modeling issue related to this proposal.
 




  





# 

 References
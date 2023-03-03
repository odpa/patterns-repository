# 

 Graphical representation



__Diagram__ 





[![Image:CatchRecord.png](./CatchRecord.png)](../Image/CatchRecord.png.md "Image:CatchRecord.png")





# 

 General description




|  |  |
| --- | --- |
|  Name:  |  CatchRecord  |
|  Submitted by:  | [AldoGangemi](../User/AldoGangemi.md "User:AldoGangemi")  |
|  Also Known As:  |  |
|  Intent:  |  To represent the catch records from time series FIGIS application, which contain temporally-indexed aggregated information about aquatic species cacthing.  |
|  Domains:  | [Fishery](../Community/Fishery.md "Community:Fishery")  |
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
|  Specialization Of:  | <li><a href="../AquaticResourceObservation/AquaticResourceObservation.md" title="Submissions:Observation">        Submissions:Observation       </a></li> |
|  Related CPs:  |  |



  





# 

 Elements



_The
 __CatchRecord__ 
 Content OP locally defines the following ontology elements:_ 





[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__countryOfRecord__ 
 (owl:ObjectProperty) The country parameter for a species catch record.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[countryOfRecord](./CatchRecord/countryOfRecord.md "Submissions:CatchRecord/countryOfRecord") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__fishingAreaOfRecord__ 
 (owl:ObjectProperty) The area parameter for a species catch record.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[fishingAreaOfRecord](./CatchRecord/fishingAreaOfRecord.md "Submissions:CatchRecord/fishingAreaOfRecord") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__forCountry__ 
 (owl:ObjectProperty) The country parameter for a species catch record.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[forCountry](./CatchRecord/forCountry.md "Submissions:CatchRecord/forCountry") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__fromFishingArea__ 
 (owl:ObjectProperty) The area parameter for a species catch record.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[fromFishingArea](./CatchRecord/fromFishingArea.md "Submissions:CatchRecord/fromFishingArea") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__hasCatchRecord__ 
 (owl:ObjectProperty) The catch record of a species, i.e. its statistical observation over a reference year.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[hasCatchRecord](./CatchRecord/hasCatchRecord.md "Submissions:CatchRecord/hasCatchRecord") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__isCatchRecordFor__ 
 (owl:ObjectProperty) The catch record of a species, i.e. its statistical observation over a reference year.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[isCatchRecordFor](./CatchRecord/isCatchRecordFor.md "Submissions:CatchRecord/isCatchRecordFor") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__unitUsedInRecord__ 
 (owl:ObjectProperty) The unit of measure parameter for a species catch record.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[unitUsedInRecord](./CatchRecord/unitUsedInRecord.md "Submissions:CatchRecord/unitUsedInRecord") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__withUnit__ 
 (owl:ObjectProperty) The unit of measure parameter for a species catch record.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[withUnit](./CatchRecord/withUnit.md "Submissions:CatchRecord/withUnit") 
 page_ 



[![DatatypeProperty](./20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif.md "DatatypeProperty")
__amount__ 
 (owl:DatatypeProperty)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[amount](./CatchRecord/amount.md "Submissions:CatchRecord/amount") 
 page_ 



[![DatatypeProperty](./20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif.md "DatatypeProperty")
__referenceYear__ 
 (owl:DatatypeProperty) The year for which the status of the target object (e.g. Marine Resource, Fishery...) has been evaluated.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[referenceYear](./CatchRecord/referenceYear.md "Submissions:CatchRecord/referenceYear") 
 page_ 



[![DatatypeProperty](./20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif.md "DatatypeProperty")
__reportingYear__ 
 (owl:DatatypeProperty) The year in which a catch record has been officially reported (different from its reference year, i.e. the year of the actual observation).
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[reportingYear](./CatchRecord/reportingYear.md "Submissions:CatchRecord/reportingYear") 
 page_ 



[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__CatchRecord__ 
 (owl:Class) A design pattern representing the semantics of the data contained in a database view (record) about catches of species in certain fishing areas for a certain reference year.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[CatchRecord](./CatchRecord.md "Submissions:CatchRecord/CatchRecord") 
 page_ 



[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__Country__ 
 (owl:Class)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[Country](./CatchRecord/Country.md "Submissions:CatchRecord/Country") 
 page_ 



[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__UnitOfMeasure__ 
 (owl:Class)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[UnitOfMeasure](./CatchRecord/UnitOfMeasure.md "Submissions:CatchRecord/UnitOfMeasure") 
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
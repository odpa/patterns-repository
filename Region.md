# 

 Graphical representation



__Diagram__ 





[![Image:Region.jpg](images/7/73/Region.jpg)](../Image/Region.jpg "Image:Region.jpg")





# 

 General description




|  |  |
| --- | --- |
|  Name:  |  Region  |
|  Submitted by:  | [AldoGangemi](../User/AldoGangemi "User:AldoGangemi")  |
|  Also Known As:  |  |
|  Intent:  |  To represent and reason on values of attributes of things, by explicitly talking about the dimensions ("regions") of the attributes, which include those values.  |
|  Domains:  | [General](../Community/General "Community:General")  |
|  Competency Questions:  | <li>       What is the value for the attribute of that entity?      </li><li>       Which entities have a certain value on that parameter/attribute/feature?      </li> |
|  Solution description:  |  This pattern is a basic one, which allows to talk about attributes/parameters/dimensions, while still referring to their values. It creates a path from things to data values through 'regions' representing attributes.  |
|  Reusable OWL Building Block:  | [http://ontologydesignpatterns.org/cp/owl/region.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=http://ontologydesignpatterns.org/cp/owl/region.owl&message=OWL building block&from_page_id=2157&update=)  (720)  |
|  Consequences:  |  We can represent and reason on \*any\* kind of attributes, parameters, features, etc., which have a given set of values.  With the new OWL2 support for custom and complex datatypes, this pattern should be confronted with possible enrichments, or may be restricted to OWL1. Anyway, since datatypes cannot overlap with classes even in OWL2, it remains useful for the cases where the domain must be kept homogeneous.  |
|  Scenarios:  |  |
|  Known Uses:  |  |
|  Web References:  |  |
|  Other References:  |  |
|  Examples (OWL files):  |  |
|  Extracted From:  | <li><a class="external free" href="http://www.ontologydesignpatterns.org/ont/dul/DUL.owl" rel="nofollow" title="http://www.ontologydesignpatterns.org/ont/dul/DUL.owl">        http://www.ontologydesignpatterns.org/ont/dul/DUL.owl       </a></li> |
|  Reengineered From:  |  |
|  Has Components:  |  |
|  Specialization Of:  |  |
|  Related CPs:  |  |



  





# 

 Elements



_The
 __Region__ 
 Content OP locally defines the following ontology elements:_ 





[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasRegion__ 
 (owl:ObjectProperty) A relation between entities and regions, e.g. 'the number of wheels of that truck is 12'.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasRegion](../Submissions/Region/hasRegion "Submissions:Region/hasRegion") 
 page_ 



[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__isRegionFor__ 
 (owl:ObjectProperty) A relation between entities and regions, e.g. 'the color of my car is red'.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[isRegionFor](../Submissions/Region/isRegionFor "Submissions:Region/isRegionFor") 
 page_ 



[![DatatypeProperty](images/thumb/a/a5/DatatypeProperty.gif/20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif "DatatypeProperty")
__hasRegionDataValue__ 
 (owl:DatatypeProperty) A datatype property that encodes values for a Region, e.g. a float for the Region Height.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasRegionDataValue](../Submissions/Region/hasRegionDataValue "Submissions:Region/hasRegionDataValue") 
 page_ 



[![Class](images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__Region__ 
 (owl:Class) Any region in a dimensional space (a dimensional space is a maximal Region), which can be used as a value for a quality of an Entity . For example, TimeInterval, SpaceRegion, PhysicalAttribute, Amount, SocialAttribute are all subclasses of Region.
 
 Regions are not data values in the ordinary knowledge representation sense; in order to get patterns for modelling data, see the properties: representsDataValue and hasDataValue
 



[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[Region](../Submissions/Region/Region "Submissions:Region/Region") 
 page_ 


# 

 Additional information



 The region content ontology design pattern. This CP represents regions that are portions of a dimensional space which can be used as a value for a quality of an Entity. The CP is extracted from DOLCE + DnS Ultra Lite ontology.
 



# 

 Scenarios




__Scenarios about Region__ 


 No scenario is added to this Content OP.
 




# 

 Reviews




__Reviews about Region__ 


 There is no review about this proposal.
This revision (revision ID
 __9116__ 
 ) takes in account the reviews: none
 



 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Region&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Region&action=evaluation") 





  





# 

 Modeling issues




__Modeling issues about Region__ 


 There is no Modeling issue related to this proposal.
 




  





# 

 References
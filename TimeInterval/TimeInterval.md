# 

 Graphical representation



__Diagram__ 





[![Image:timeinterval.jpg](./Timeinterval.jpg)](../Image/Timeinterval.jpg.md "Image:timeinterval.jpg")





# 

 General description




|  |  |
| --- | --- |
|  Name:  |  time interval  |
|  Submitted by:  | [ValentinaPresutti](../User/ValentinaPresutti.md "User:ValentinaPresutti")  |
|  Also Known As:  |  |
|  Intent:  |  To represent time intervals.  |
|  Domains:  | [Time](../Community/Time.md "Community:Time")  |
|  Competency Questions:  | <li>       What is the end time of this interval?      </li><li>       What is the starting time of this interval?      </li><li>       What is the date of this time interval?      </li> |
|  Solution description:  |  --  |
|  Reusable OWL Building Block:  | [http://www.ontologydesignpatterns.org/cp/owl/timeinterval.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=http://www.ontologydesignpatterns.org/cp/owl/timeinterval.owl&message=OWL building block&from_page_id=284&update=)  (977)  |
|  Consequences:  |  The dates of the time interval are not part of the domain of discourse, they are datatype values. If there is the need of reasoning about dates this Content OP should be used in composition with the [region](../Region/Region.md "Submissions:Region")  Content OP.  |
|  Scenarios:  |  The time interval “January 2008” starts at 2008−01−01 and ends at and ends at 2008−01−31.  |
|  Known Uses:  |  |
|  Web References:  |  |
|  Other References:  |  |
|  Examples (OWL files):  | <li><a class="external free" href="http://www.ontologydesignpatterns.org/cp/examples/timeinterval/january2008.owl" rel="nofollow" title="http://www.ontologydesignpatterns.org/cp/examples/timeinterval/january2008.owl">        http://www.ontologydesignpatterns.org/cp/examples/timeinterval/january2008.owl       </a></li> |
|  Extracted From:  |  |
|  Reengineered From:  |  |
|  Has Components:  |  |
|  Specialization Of:  |  |
|  Related CPs:  |  |



  





# 

 Elements



_The
 __TimeInterval__ 
 Content OP locally defines the following ontology elements:_ 






[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__Time Interval__ 
 (owl:Class) Any region in a dimensional space that represents time.
 



[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[TimeInterval](../SmartHome_TimeInterval/SmartHome_TimeInterval.md "Submissions:TimeInterval/TimeInterval") 
 page_ 




[![DatatypeProperty](./20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif.md "DatatypeProperty")
__has interval date__ 
 (owl:DatatypeProperty) A datatype property that encodes values from xsd:date for a time interval; a 
same time interval can have more than one xsd:date value: begin date, end date, date at which the interval holds, as well as dates expressed in different formats: xsd:gYear, xsd:dateTime, etc.
 



[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[hasIntervalDate](./TimeInterval/hasIntervalDate.md "Submissions:TimeInterval/hasIntervalDate") 
 page_ 




[![DatatypeProperty](./20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif.md "DatatypeProperty")
__has interval start date__ 
 (owl:DatatypeProperty) The start date of a
 [time interval](../SmartHome_TimeInterval/SmartHome_TimeInterval.md "Submissions:TimeInterval/TimeInterval") 
 .
 



[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[hasIntervalStartDate](./TimeInterval/hasIntervalStartDate.md "Submissions:TimeInterval/hasIntervalStartDate") 
 page_ 




[![DatatypeProperty](./20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif.md "DatatypeProperty")
__has interval end date__ 
 (owl:DatatypeProperty) The end date of a
 [time interval](../SmartHome_TimeInterval/SmartHome_TimeInterval.md "Submissions:TimeInterval/TimeInterval") 
 .
 



[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[hasIntervalEndDate](./TimeInterval/hasIntervalEndDate.md "Submissions:TimeInterval/hasIntervalEndDate") 
 page_ 


# 

 Additional information



 This Content OP can be composed with other Content OPs when temporal aspects need to be represented.
 



# 

 Scenarios




__Scenarios about TimeInterval__ 


 No scenario is added to this Content OP.
 




# 

 Reviews




__Reviews about TimeInterval__ 


 There is no review about this proposal.
This revision (revision ID
 __9136__ 
 ) takes in account the reviews: none
 



 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:TimeInterval&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:TimeInterval&action=evaluation") 





  





# 

 Modeling issues




__Modeling issues about TimeInterval__ 


 There is no Modeling issue related to this proposal.
 




  





# 

 References
# 

 Graphical representation



__Diagram__ 





[![Image:PeriodicIntervalv0.jpg](./PeriodicIntervalv0.jpg)](../Image/PeriodicIntervalv0.jpg.md "Image:PeriodicIntervalv0.jpg")





# 

 General description




|  |  |
| --- | --- |
|  Name:  |  PeriodicInterval  |
|  Submitted by:  | [MariaPoveda](../User/MariaPoveda.md "User:MariaPoveda")  , [MariCarmenSuarezFigueroa](../User/MariCarmenSuarezFigueroa.md "User:MariCarmenSuarezFigueroa")  |
|  Also Known As:  |  |
|  Intent:  |  The goal of this pattern is to represent non-convex intervals where the duration of each internal interval and the duration of the gaps between intervals are constant. These intervals are called periodic intervals within the context of this pattern.  |
|  Domains:  | [Time](../Community/Time.md "Community:Time")  |
|  Competency Questions:  | <li>       What is the period of the interval 'every tuesday of 2010'? The period is a week (weekly).      </li> |
|  Solution description:  |  The class “Interval” defined in the OWL-Time ontol-ogy has been extended within this pattern by means of the class “PeriodicInterval”. This concept has been created in order to define periodic intervals. As we have al-ready mentioned, these intervals are defined by four elements, namely, its beginning, its end, the duration of each subinterval and the duration of the period, that is, the gaps between two subintervals. In order to model the beginning and end of the inter-val, we have reused the relationships “hasBeginning” and “hasEnd” already defined in the OWL-Time ontology. By taking advantage of the concepts and relations al-ready defined in the OWL-Time ontology instead of creating new ones we both pro-mote the reuse of existing models and avoid the inclusion of unnecessary complexity within the pattern being developed. The durations of the subintervals and the period between them have been modelled by means of the relationships “hasIntervalDura-tionPerPeriod” and “hasPeriod” respectively. Both relationships are defined between the concepts “PeriodicInterval” and “DurationDescription”.  |
|  Reusable OWL Building Block:  | [http://delicias.dia.fi.upm.es/ontologies/PeriodicInterval.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=http://delicias.dia.fi.upm.es/ontologies/PeriodicInterval.owl&message=OWL building block&from_page_id=3312&update=)  (688)  |
|  Consequences:  |  This content pattern allows designers to represent non-convex intervals where the period between subintervals, that is, the gaps between subintervals, and the duration of the subintervals are constant.  |
|  Scenarios:  |  Sam teaches every monday  |
|  Known Uses:  | [http://www.oeg-upm.net/index.php/en/ontologies/82-mio-ontologies](http://www.oeg-upm.net/index.php/en/ontologies/82-mio-ontologies "http://www.oeg-upm.net/index.php/en/ontologies/82-mio-ontologies")  |
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
 __PeriodicInterval__ 
 Content OP locally defines the following ontology elements:_ 





[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__hasIntervalDurationPerPeriod__ 
 (owl:ObjectProperty)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[hasIntervalDurationPerPeriod](./PeriodicInterval/hasIntervalDurationPerPeriod.md "Submissions:PeriodicInterval/hasIntervalDurationPerPeriod") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__hasPeriod__ 
 (owl:ObjectProperty)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[hasPeriod](./PeriodicInterval/hasPeriod.md "Submissions:PeriodicInterval/hasPeriod") 
 page_ 



[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__PeriodicInterval__ 
 (owl:Class)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[PeriodicInterval](./PeriodicInterval.md "Submissions:PeriodicInterval/PeriodicInterval") 
 page_ 


# 

 Additional information



 This ontology design pattern extends the OWL-Time ontology (
 [http://www.w3.org/TR/owl-time](http://www.w3.org/TR/owl-time "http://www.w3.org/TR/owl-time") 
 ) defining periodic intervals.
 



  





# 

 Scenarios




__Scenarios about PeriodicInterval__ 


 No scenario is added to this Content OP.
 




# 

 Reviews




__Reviews about PeriodicInterval__ 



|  Review article  | [Posted on](../Property/CreationDate.md "Property:CreationDate")  | [About revision (current is 11172)](../Property/ReviewAboutVersion.md "Property:ReviewAboutVersion")  |
| --- | --- | --- |
| [RinkeHoekstra about PeriodicInterval](../Reviews/RinkeHoekstra_about_PeriodicInterval.md "Reviews:RinkeHoekstra about PeriodicInterval")  |  2456161  21 August 2012  |  11152  11,152  |
| [VojtechSvatek about PeriodicInterval](../Reviews/VojtechSvatek_about_PeriodicInterval.md "Reviews:VojtechSvatek about PeriodicInterval")  |  2456171  31 August 2012  |  11172  11,172  |



 This revision (revision ID
 __11172__ 
 ) takes in account the reviews: none
 



 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:PeriodicInterval&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:PeriodicInterval&action=evaluation") 





  





# 

 Modeling issues




__Modeling issues about PeriodicInterval__ 


 There is no Modeling issue related to this proposal.
 




  





# 

 References



  






|  |  Submission to event [WOP:2012](../WOP/2012.md "WOP:2012")  |
| --- | --- |
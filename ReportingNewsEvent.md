# 

 Graphical representation



__Diagram__ 





[![Image:ReportingNewsEvent-scheme.png‎](images/d/d9/ReportingNewsEvent-scheme.png)](../Image/ReportingNewsEvent-scheme.png "Image:ReportingNewsEvent-scheme.png‎")





# 

 General description




|  |  |
| --- | --- |
|  Name:  |  NewsReportingEvent  |
|  Submitted by:  | [EwaKowalczuk](../User/EwaKowalczuk "User:EwaKowalczuk")  |
|  Also Known As:  |  |
|  Intent:  |  The pattern can be used for modelling situations in which we are not certain that a particular actual event has the properties which were described in a news message. We want to define the properties of an actual event which were reported (time, place, actors, subevents, cause, effect etc.), but not to treat them as universal, verified knowledge. The pattern also allows to define who is responsible for a particular description of an event and how this description is dealt with.  |
|  Domains:  | [Event Processing](../Community/Event_Processing "Community:Event Processing")  , [Media](../Community/Media "Community:Media")  , [Social Science](../Community/Social_Science "Community:Social Science")  |
|  Competency Questions:  | <li>       What aspects of an actual event were presented in the news message?      </li><li>       Who reported an actual event? Which news provider they represented?      </li><li>       When was a certain actual event reported for the first time?      </li><li>       What actual events are presented in a certain medium/by media of a certain news provider?      </li><li>       How was an actual event presented?      </li> |
|  Solution description:  |  The pattern extends the ReportingEvent pattern by specifying the primary properties of the specialisation of the ReportingEvent class. The specialisation, NewsEventReportingEvent, denotes the act of providing a unit of information (ReportedNewsEvent) to the general public.  The act utilises a certain Media (TV station, radio station, newspaper, website). A Media is owned by a certain SocialAgent - NewsProvider. This agent takes partial responsibility for the content provided, but its responsibility differs from the one of the NewsEventReporter -- an Agent that directly reports the ActualEvent.Other properties which are very important for NewsEventReportingEvent are time at which the event is reported and the context of presentation.  |
|  Reusable OWL Building Block:  | [http://semantic.cs.put.poznan.pl/ontologies/newsreportingevent.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=http://semantic.cs.put.poznan.pl/ontologies/newsreportingevent.owl&message=OWL building block&from_page_id=4098&update=)  (961)  |
|  Consequences:  |  The pattern is rather complex and should only be used if the circumstances of the events presented in a media  are expected to be uncertain (to differ in different news event reports of different news providers).  |
|  Scenarios:  |  A single actual event, bus drivers protest, is presented in to different media: a TV news station and a news website. John Doe prepared the material for the station Channel 55, owned by Media Corp. This material was presented as first material in a news programme on 16/07/2016, started at 19:30 and ended at 19:35. It was based on correspondent report. The material said that the cause of the protest was malfunction of buses, and that a brutal police intervention took place. The article from website livingintheworld.com also mentioned malfunction of buses, but it also mentioned other cause of protest: planned reduction of social benefits. It did not mention brutal police intervention, but it did mention destruction of public property. The article seems not important for the website authors, it was presented at the page bottom.  |
|  Known Uses:  |  |
|  Web References:  |  |
|  Other References:  |  |
|  Examples (OWL files):  |  |
|  Extracted From:  |  |
|  Reengineered From:  |  |
|  Has Components:  | <li><a href="Submissions%253AIntensionExtension.html" title="Submissions:IntensionExtension">        Submissions:IntensionExtension       </a></li><li><a href="Submissions%253AActingFor.html" title="Submissions:ActingFor">        Submissions:ActingFor       </a></li> |
|  Specialization Of:  | <li><a href="Submissions%253AReportingEvent.html" title="Submissions:ReportingEvent">        Submissions:ReportingEvent       </a></li> |
|  Related CPs:  | <li><a href="Submissions%253AReportingEvent.html" title="Submissions:ReportingEvent">        Submissions:ReportingEvent       </a></li><li><a href="Submissions%253AIntensionExtension.html" title="Submissions:IntensionExtension">        Submissions:IntensionExtension       </a></li><li><a href="Submissions%253AActingFor.html" title="Submissions:ActingFor">        Submissions:ActingFor       </a></li><li><a href="Submissions%253ASituation.html" title="Submissions:Situation">        Submissions:Situation       </a></li> |



  





# 

 Elements



_The
 __ReportingNewsEvent__ 
 Content OP locally defines the following ontology elements:_ 




# 

 Additional information



# 

 Scenarios




__Scenarios about ReportingNewsEvent__ 


 No scenario is added to this Content OP.
 




# 

 Reviews




__Reviews about ReportingNewsEvent__ 


 There is no review about this proposal.
This revision (revision ID
 __12893__ 
 ) takes in account the reviews: none
 



 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:ReportingNewsEvent&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:ReportingNewsEvent&action=evaluation") 





  





# 

 Modeling issues




__Modeling issues about ReportingNewsEvent__ 


 There is no Modeling issue related to this proposal.
 




  





# 

 References
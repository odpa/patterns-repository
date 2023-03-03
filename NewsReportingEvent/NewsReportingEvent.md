# 

 Graphical representation



__Diagram__ 





[![Image:ReportingNewsEvent-scheme.png](./20160826233326!ReportingNewsEvent-scheme.png)](../Image/ReportingNewsEvent-scheme.png.md "Image:ReportingNewsEvent-scheme.png")





# 

 General description




|  |  |
| --- | --- |
|  Name:  |  NewsReportingEvent  |
|  Submitted by:  | [EwaKowalczuk](../User/EwaKowalczuk.md "User:EwaKowalczuk")  |
|  Also Known As:  |  |
|  Intent:  |  The pattern can be used for modelling situations in which we are not certain that a particular actual event has the properties which were described in a news message. We want to define the properties of an actual event which were reported (time, place, actors, subevents, cause, effect etc.), but not to treat them as universal, verified knowledge. The pattern also allows to define who is responsible for a particular  description of an event and how this description is dealt with.  |
|  Domains:  | [Event Processing](../Community/Event_Processing.md "Community:Event Processing")  , [Media](../Community/Media.md "Community:Media")  , [Social Science](../Community/Social_Science.md "Community:Social Science")  |
|  Competency Questions:  | <li>       What aspects of an actual event were presented in the news message?      </li><li>       Who reported an actual event? Which news provider they represented?      </li><li>       When was a certain actual event reported for the first time?      </li><li>       What actual events are presented in a certain medium/by media of a certain news provider?      </li><li>       How was an actual event presented?      </li> |
|  Solution description:  |  The pattern extends the ReportingEvent pattern by specifying the primary properties of the specialisation of the ReportingEvent class. The specialisation, NewsReportingEvent, denotes the act of providing a unit of information (ActualEventView) to the general public.  The act utilises a certain Media (TV station, radio station, newspaper, website). A Media is owned by a certain SocialAgent - NewsProvider. This agent takes partial responsibility for the content provided, but its responsibility differs from the one of the NewsEventReporter, an Agent that directly reports the ActualEvent. Other properties which are very important for a NewsReportingEvent are time at which the event is reported and the context of presentation.  |
|  Reusable OWL Building Block:  | [http://semantic.cs.put.poznan.pl/ontologies/newsreportingevent.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=http://semantic.cs.put.poznan.pl/ontologies/newsreportingevent.owl&message=OWL building block&from_page_id=4177&update=)  (961)  |
|  Consequences:  |  The pattern is rather complex and should only be used if the circumstances of the events presented in a media are expected to be uncertain (to differ in different news event reports of different news providers).  |
|  Scenarios:  |  A single actual event, bus drivers protest, is presented in to different media: a TV news stationand a news website. John Doe prepared the material for the station Channel 55, owned by Media Corp.This material was presented as first material in a news programme on 16/07/2016, started at 19:30 and ended at 19:35.It was based on correspondent report. The material said that the cause of the protest was malfunction of buses, and that a brutal police intervention took place.The article from website livingintheworld.com also mentioned malfunction of buses, but it also mentionedother cause of protest: planned reduction of social benefits. It did not mention brutal police intervention, but it did mention destruction of public property. The article seems not important for the website authors, it was presented at the page bottom.  |
|  Known Uses:  |  |
|  Web References:  |  |
|  Other References:  |  |
|  Examples (OWL files):  |  |
|  Extracted From:  |  |
|  Reengineered From:  |  |
|  Has Components:  | <li><a href="../IntensionExtension/IntensionExtension.md" title="Submissions:IntensionExtension">        Submissions:IntensionExtension       </a></li><li><a href="./NewsReportingEvent.md" title="Submissions:ReportingEvent">        Submissions:ReportingEvent       </a></li><li><a href="../ActingFor/ActingFor.md" title="Submissions:ActingFor">        Submissions:ActingFor       </a></li><li><a href="../TimeIndexedSituation/TimeIndexedSituation.md" title="Submissions:TimeIndexedSituation">        Submissions:TimeIndexedSituation       </a></li> |
|  Specialization Of:  | <li><a href="./NewsReportingEvent.md" title="Submissions:ReportingEvent">        Submissions:ReportingEvent       </a></li> |
|  Related CPs:  | <li><a href="../Types_of_entities/Types_of_entities.md" title="Submissions:Types of entities">        Submissions:Types of entities       </a></li><li><a href="../IntensionExtension/IntensionExtension.md" title="Submissions:IntensionExtension">        Submissions:IntensionExtension       </a></li><li><a href="./NewsReportingEvent.md" title="Submissions:ReportingEvent">        Submissions:ReportingEvent       </a></li><li><a href="../ActingFor/ActingFor.md" title="Submissions:ActingFor">        Submissions:ActingFor       </a></li><li><a href="../TimeIndexedSituation/TimeIndexedSituation.md" title="Submissions:TimeIndexedSituation">        Submissions:TimeIndexedSituation       </a></li> |



  





# 

 Elements



_The
 __NewsReportingEvent__ 
 Content OP locally defines the following ontology elements:_ 





[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__hasPresentationContext__ 
 (owl:ObjectProperty) This property can be used to link NewsReportingEvent to a NewsPresentationContext.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[hasPresentationContext](./NewsReportingEvent/hasPresentationContext.md "Submissions:NewsReportingEvent/hasPresentationContext") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__owns__ 
 (owl:ObjectProperty) This property can be used to link a certain NewsProvider with a Media that the NewsProvider ows, e.g. Fox News Channel is owned by Fox Entertainment Group, which also owns other Media (FXX Channel, etc.).
 
 This is an universal property, it can be also used in different context (e.g. Ruslana owns a Persian cat).
 



[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[owns](./NewsReportingEvent/owns.md "Submissions:NewsReportingEvent/owns") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__presentedAt__ 
 (owl:ObjectProperty) This property can be used to link a NewsReportingEvent to a Media (TV station, radio station, newspaper, webpage) at which a certain ActualEventView was presented.
 
 This is an universal property and can be used in different contexts.
 



[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[presentedAt](./NewsReportingEvent/presentedAt.md "Submissions:NewsReportingEvent/presentedAt") 
 page_ 



[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__Media__ 
 (owl:Class) An entity that allows a communication of news messages, for example a TV station, radio station, newspaper, website, etc.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[Media](./NewsReportingEvent/Media.md "Submissions:NewsReportingEvent/Media") 
 page_ 



[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__NewsEventReporter__ 
 (owl:Class) An Actor (usually a Person) that is an author of a certain ActualEventView.
 
 NewsEventReporter is not linked to an ActualEventView directly, it is connected to NewsReportingEvent, which is designed to document the act of reporting.
 



[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[NewsEventReporter](./NewsReportingEvent/NewsEventReporter.md "Submissions:NewsReportingEvent/NewsEventReporter") 
 page_ 



[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__NewsPresentationContext__ 
 (owl:Class) Class for denoting circumstances of an actual event presentation. For example if an event was presented at the end of website, then end of website is its NewsPresentationContext.
 
 NewsPresentationContext is not directly attached to an ActualEventView, it is attached to NewsReportingEvent, which designates the act of an event reporting.
 



[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[NewsPresentationContext](./NewsReportingEvent/NewsPresentationContext.md "Submissions:NewsReportingEvent/NewsPresentationContext") 
 page_ 



[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__NewsProvider__ 
 (owl:Class) An entity, usually a company, that ows a certain Media. For example Fox Entertainment Group owns the Fox News Channel. Fox Entertainment Group is a NewsProvider.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[NewsProvider](./NewsReportingEvent/NewsProvider.md "Submissions:NewsReportingEvent/NewsProvider") 
 page_ 



[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__NewsReportingEvent__ 
 (owl:Class) This is a subclass of ReportingEvent, designed to represent an act of reporting a certain actual event during a news programme or via other news media.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[NewsReportingEvent](./NewsReportingEvent.md "Submissions:NewsReportingEvent/NewsReportingEvent") 
 page_ 



[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__PresentationContext__ 
 (owl:Class) Class for denoting circumstances of an entity presentation. If a waiter presented a dish with an apologetic smile, then the apologetic smile is a PresentationContext.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[PresentationContext](./NewsReportingEvent/hasPresentationContext.md "Submissions:NewsReportingEvent/PresentationContext") 
 page_ 


# 

 Additional information



 Pattern description is available at:
 [http://ontologydesignpatterns.org/wiki/Submissions:NewsReportingEvent](./NewsReportingEvent.md "http://ontologydesignpatterns.org/wiki/Submissions:NewsReportingEvent") 
 Pattern description is included in: E. Kowalczuk, A. Ławrynowicz,
 



# 

 Scenarios




__Scenarios about NewsReportingEvent__ 


 No scenario is added to this Content OP.
 




# 

 Reviews




__Reviews about NewsReportingEvent__ 


 There is no review about this proposal.
This revision (revision ID
 __12892__ 
 ) takes in account the reviews: none
 



 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:NewsReportingEvent&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:NewsReportingEvent&action=evaluation") 





  





# 

 Modeling issues




__Modeling issues about NewsReportingEvent__ 


 There is no Modeling issue related to this proposal.
 




  





# 

 References



  






|  |  Submission to event [WOP:2016](../WOP/2016.1.md "WOP:2016")  |
| --- | --- |
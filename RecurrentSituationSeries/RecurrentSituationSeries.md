#  Graphical representation


__Diagram__




[![Image:Recurrent-situation-series.jpg](./Recurrent-situation-series.jpg)](../Image/Recurrent-situation-series.jpg.md "Image:Recurrent-situation-series.jpg")




#  General description




|  |  |
| --- | --- |
|  Name: |  RecurrentSituationSeries |
|  Submitted by: | [ValentinaAnitaCarriero](../User/ValentinaAnitaCarriero.md "User:ValentinaAnitaCarriero") |
|  Also Known As: |  |
|  Intent: |  To represent recurrent situation series as situations and collections of consecutive situations, with a regular time period between situations and unifying factors. |
|  Domains: | [General](../Community/General.md "Community:General") |
|  Competency Questions: | <li> What are the situations of a recurrent situation series?</li><li> Which is the time period elapsing between two situations of a recurrent situation series?</li><li> When is the next situation of a recurrent situation series scheduled?</li><li> What are the unifying criteria shared by all the situations in a recurrent situation series?</li><li> Which are the unifying situations shared by a (subset of) the situations member of a recurrent situation series?</li><li> When is a unifying situation valid?</li><li> Which is the (immediate) next situation in a recurrent situation series?</li><li> Which is the (immediate) previous situation in a recurrent situation series?</li> |
|  Solution description: |  A recurrent situation series is modelled as an intersection of a collection and a situation. Indeed, a recurrent situation series is seen as a collection, since it contains entities that share one or more common properties and are unified conceptually (unifying factors). These entities are member of the collection, and are all consecutive situations. At the same time, a recurrent situation series is a situation, intended as a relational context in which the contextualised things are based on a frame: a recurrent situation series is similar to a plan that defines how the things involved in that plan (i.e. the specific events) shall be carried out, e.g. where the situations shall be located, in which time of the year, etc. |
|  Reusable OWL Building Block: | [http://www.ontologydesignpatterns.org/cp/owl/recurrentsituationseries.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=http://www.ontologydesignpatterns.org/cp/owl/recurrentsituationseries.owl&message=OWL building block&from_page_id=4700&update=) (221) |
|  Consequences: |  A series of recurrent situations, its unifying factors and the recurrent time period can be modeled. |
|  Scenarios: |  Umbria Jazz is a collection of situations, which all take place in July and in the Italian region of Umbria, and has the musical genre jazz as a topic. Its situations recur at regular time periods, i.e. annually. |
|  Known Uses: |  |
|  Web References: |  |
|  Other References: |  |
|  Examples (OWL files): |  |
|  Extracted From: |  |
|  Reengineered From: |  |
|  Has Components: |  |
|  Specialization Of: |  |
|  Related CPs: | <li><a href="../Classification/Classification.md" title="Submissions:Classification">Submissions:Classification</a></li><li><a href="../Collection/Collection.md" title="Submissions:Collection">Submissions:Collection</a></li><li><a href="../Description/Description.md" title="Submissions:Description">Submissions:Description</a></li><li><a class="new" href="http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Recurrent_Event_Series&amp;action=edit&amp;redlink=1" title="Submissions:Recurrent Event Series (not yet written)">Submissions:Recurrent Event Series</a></li><li><a href="../Sequence/Sequence.md" title="Submissions:Sequence">Submissions:Sequence</a></li><li><a href="../Situation/Situation.md" title="Submissions:Situation">Submissions:Situation</a></li> |


  




#  Elements


_The __RecurrentSituationSeries__ Content OP locally defines the following ontology elements:_



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasEstimatedTimePeriod__ (owl:ObjectProperty) This property relates a recurrent situation series to an estimated time period. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasEstimatedTimePeriod](./RecurrentSituationSeries/hasEstimatedTimePeriod.md "Submissions:RecurrentSituationSeries/hasEstimatedTimePeriod") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasImmediateNextSituation__ (owl:ObjectProperty) This property relates a situation member of a recurrent situation series to the immediate next situation member of the same recurrent situation series. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasImmediateNextSituation](./RecurrentSituationSeries/hasImmediateNextSituation.md "Submissions:RecurrentSituationSeries/hasImmediateNextSituation") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasImmediatePreviousSituation__ (owl:ObjectProperty) This property relates a situation member of a recurrent situation series to the immediate previous situation member of the same recurrent situation series. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasImmediatePreviousSituation](./RecurrentSituationSeries/hasImmediatePreviousSituation.md "Submissions:RecurrentSituationSeries/hasImmediatePreviousSituation") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasMeasuredTimePeriod__ (owl:ObjectProperty) This property relates a recurrent situation series to a measured time period. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasMeasuredTimePeriod](./RecurrentSituationSeries/hasMeasuredTimePeriod.md "Submissions:RecurrentSituationSeries/hasMeasuredTimePeriod") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasMemberSituation__ (owl:ObjectProperty) This property relates a recurrent situation series to a situation that is member of it. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasMemberSituation](./RecurrentSituationSeries/hasMemberSituation.md "Submissions:RecurrentSituationSeries/hasMemberSituation") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasNextSituation__ (owl:ObjectProperty) This property relates a situation member of a recurrent situation series to a next situation member of the same recurrent situation series. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasNextSituation](./RecurrentSituationSeries/hasNextSituation.md "Submissions:RecurrentSituationSeries/hasNextSituation") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasPreviousSituation__ (owl:ObjectProperty) This property relates a situation member of a recurrent situation series to a previous situation member of the same recurrent situation series. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasPreviousSituation](./RecurrentSituationSeries/hasPreviousSituation.md "Submissions:RecurrentSituationSeries/hasPreviousSituation") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasTimePeriod__ (owl:ObjectProperty) This property relates a recurrent situation series to a time period. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasTimePeriod](./RecurrentSituationSeries/hasTimePeriod.md "Submissions:RecurrentSituationSeries/hasTimePeriod") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasTimePeriodBeforeNextSituation__ (owl:ObjectProperty) This property relates a situation member of a recurrent situation series to the time period elapsing before its next situation. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasTimePeriodBeforeNextSituation](./RecurrentSituationSeries/hasTimePeriodBeforeNextSituation.md "Submissions:RecurrentSituationSeries/hasTimePeriodBeforeNextSituation") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasUnifyingFactor__ (owl:ObjectProperty) This property relates a collection to a unifying factor. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasUnifyingFactor](./RecurrentSituationSeries/hasUnifyingFactor.md "Submissions:RecurrentSituationSeries/hasUnifyingFactor") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasUnifyingSituation__ (owl:ObjectProperty) This property relates a recurrent situation series to a unifying situation. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasUnifyingSituation](./RecurrentSituationSeries/hasUnifyingSituation.md "Submissions:RecurrentSituationSeries/hasUnifyingSituation") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __involvesUnifyingFactor__ (owl:ObjectProperty) This property relates a unifying situation to the involved unifying factor. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[involvesUnifyingFactor](./RecurrentSituationSeries/involvesUnifyingFactor.md "Submissions:RecurrentSituationSeries/involvesUnifyingFactor") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isEstimatedTimePeriodOf__ (owl:ObjectProperty) This property relates an estimated time period to a recurrent situation series. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isEstimatedTimePeriodOf](./RecurrentSituationSeries/isEstimatedTimePeriodOf.md "Submissions:RecurrentSituationSeries/isEstimatedTimePeriodOf") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isInvolvedInUnifyingSituation__ (owl:ObjectProperty) This property relates a unifying factor to the unifying situation it is involved in. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isInvolvedInUnifyingSituation](./RecurrentSituationSeries/isInvolvedInUnifyingSituation.md "Submissions:RecurrentSituationSeries/isInvolvedInUnifyingSituation") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isLocallyInconsistentWith__ (owl:ObjectProperty) This property relates two entities that are considered locally inconsistent. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isLocallyInconsistentWith](./RecurrentSituationSeries/isLocallyInconsistentWith.md "Submissions:RecurrentSituationSeries/isLocallyInconsistentWith") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isMeasuredTimePeriodOf__ (owl:ObjectProperty) This property relates a measured time period to a recurrent situation series. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isMeasuredTimePeriodOf](./RecurrentSituationSeries/isMeasuredTimePeriodOf.md "Submissions:RecurrentSituationSeries/isMeasuredTimePeriodOf") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isSituationMemberOf__ (owl:ObjectProperty) This property relates a situation that is member of a recurrent situation series to the recurrent situation series. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isSituationMemberOf](./RecurrentSituationSeries/isSituationMemberOf.md "Submissions:RecurrentSituationSeries/isSituationMemberOf") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isTimePeriodBeforeNextSituationOf__ (owl:ObjectProperty) This property relates a time period, elapsing before the next situation of a situation member of a recurrent situation series, to one of the member situations. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isTimePeriodBeforeNextSituationOf](./RecurrentSituationSeries/isTimePeriodBeforeNextSituationOf.md "Submissions:RecurrentSituationSeries/isTimePeriodBeforeNextSituationOf") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isTimePeriodOf__ (owl:ObjectProperty) This property relates a time period to a recurrent situation series having that time period. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isTimePeriodOf](./RecurrentSituationSeries/isTimePeriodOf.md "Submissions:RecurrentSituationSeries/isTimePeriodOf") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isUnifyingFactorOf__ (owl:ObjectProperty) This property relates a unifying factor to the collection that is unified by that factor. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isUnifyingFactorOf](./RecurrentSituationSeries/isUnifyingFactorOf.md "Submissions:RecurrentSituationSeries/isUnifyingFactorOf") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isUnifyingSituationOf__ (owl:ObjectProperty) This property relates a unifying situation to the recurrent situation series it unifies. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isUnifyingSituationOf](./RecurrentSituationSeries/isUnifyingSituationOf.md "Submissions:RecurrentSituationSeries/isUnifyingSituationOf") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isValidIn__ (owl:ObjectProperty) This property relates a unifying situation to its temporal validity. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isValidIn](./RecurrentSituationSeries/isValidIn.md "Submissions:RecurrentSituationSeries/isValidIn") page_
[![DatatypeProperty](./20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif.md "DatatypeProperty") __isTheLastSituation__ (owl:DatatypeProperty) This property defines if a situation that is member of a recurrent situation series is the last one or not. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isTheLastSituation](./RecurrentSituationSeries/isTheLastSituation.md "Submissions:RecurrentSituationSeries/isTheLastSituation") page_
[![DatatypeProperty](./20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif.md "DatatypeProperty") __situationNumber__ (owl:DatatypeProperty) This property represents the number of the situation in the recurrent situation series (the first situation, the second situation, etc.) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[situationNumber](./RecurrentSituationSeries/situationNumber.md "Submissions:RecurrentSituationSeries/situationNumber") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __RecurrentSituationSeries__ (owl:Class) Recurrent situation series is modeled as an intersection of the classes Collection and Situation. Indeed, a recurrent situation is seen as a collection, since it contains entities that share one or more common properties and are unified conceptually. These entities are member of the collection, and are all consecutive situations, in such a manner that each situation has either a previous situation, or a next situation, or both, unless the series has never been instantiated. At the same time, a recurrent situation is a situation, intended as a relational context in which the contextualized things are based on a frame: a recurrent situation is similar to a plan that defines how the things involved in that plan (i.e. the specific situations) shall be carried out, e.g. where the situations shall be located, in which time of the year, etc. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[RecurrentSituationSeries](./RecurrentSituationSeries.md "Submissions:RecurrentSituationSeries/RecurrentSituationSeries") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __Situation__ (owl:Class) This class represents a Situation. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[Situation](../DescriptionAndSituation/DescriptionAndSituation.md "Submissions:RecurrentSituationSeries/Situation") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __TimePeriod__ (owl:Class) This class represents a Time Period (e.g. 1 week). 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[TimePeriod](../TimePeriod/TimePeriod.md "Submissions:RecurrentSituationSeries/TimePeriod") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __UnifyingFactor__ (owl:Class) A Unifying Factor is a concept, which classifies an element or property occurring in each situation member of a recurrent situation series, which unifies the collection and makes all the situations attributable to a homogeneous collection. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[UnifyingFactor](./RecurrentSituationSeries/hasUnifyingFactor.md "Submissions:RecurrentSituationSeries/UnifyingFactor") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __UnifyingSituation__ (owl:Class) A Unifying Situation is a situation involving a unifying factor, i.e. a concept classifying an element or property occurring in each situation member of a recurrent situation series, which unifies the collection and makes all the situations attributable to a homogeneous collection, and is valid at a specific time interval. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[UnifyingSituation](./RecurrentSituationSeries/hasUnifyingSituation.md "Submissions:RecurrentSituationSeries/UnifyingSituation") page_
#  Additional information


A pattern for recurrent situation series. This pattern is a new version of the recurrent event series ODP ([http://www.ontologydesignpatterns.org/cp/owl/recurrenteventseries.owl](http://www.ontologydesignpatterns.org/cp/owl/recurrenteventseries.owl "http://www.ontologydesignpatterns.org/cp/owl/recurrenteventseries.owl")), based on new analysis which led to terminological and modelling changes.



#  Scenarios



__Scenarios about RecurrentSituationSeries__
No scenario is added to this Content OP.




#  Reviews



__Reviews about RecurrentSituationSeries__
There is no review about this proposal.
This revision (revision ID __13945__) takes in account the reviews: none


Other info at [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:RecurrentSituationSeries&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:RecurrentSituationSeries&action=evaluation")




  




#  Modeling issues



__Modeling issues about RecurrentSituationSeries__
There is no Modeling issue related to this proposal.




  




#  References
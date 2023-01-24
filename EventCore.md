# 

 Graphical representation



__Diagram__ 





[![Image:EventCore.png](../images/9/98/EventCore.png)](../Image/EventCore.png "Image:EventCore.png")





# 

 General description




|  |  |
| --- | --- |
|  Name:  |  EventCore  |
|  Submitted by:  | [AdilaKrisnadhi](../User/AdilaKrisnadhi "User:AdilaKrisnadhi")  |
|  Also Known As:  |  |
|  Intent:  |  The purpose of this pattern is to provide a minimalistic model of event where it is not always possible to separate its spatial and the temporal aspects, thus can model events that move or possess discontinuous temporal extent. Events according to this model has at least one participant, attached via a participant-role, and may have additional descriptive information through its information object.  |
|  Domains:  | [General](../Community/General "Community:General")  , [Event Processing](../Community/Event_Processing "Community:Event Processing")  |
|  Competency Questions:  | <li>       Where and when did the 1990 World Chess Championship Match take place?      </li><li>       Who were involved in the 1990 World Chess Championship Match?      </li> |
|  Solution description:  |  See Adila Krisnadhi; Pascal Hitzler : A Core Pattern for Events. Under review at WOP 2016  |
|  Reusable OWL Building Block:  | [http://krisnadhi.github.io/onto/event.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=http://krisnadhi.github.io/onto/event.owl&message=OWL building block&from_page_id=4117&update=)  (712)  |
|  Consequences:  |  This pattern can model moving events and events with discontinuous temporal extents, provided an appropriate spatiotemporal extent model is used. This pattern, however, does not facilitate modeling complex relationships between events, such as causality, provenance, or correlation  |
|  Scenarios:  |  The 1990 World Chess Championship Match takes place in New York from October 8 to November 7, 1990, and in Lyons, France, from November 26 to December 30, 1990.  |
|  Known Uses:  |  |
|  Web References:  |  |
|  Other References:  |  |
|  Examples (OWL files):  |  |
|  Extracted From:  |  |
|  Reengineered From:  |  |
|  Has Components:  |  |
|  Specialization Of:  |  |
|  Related CPs:  | <li><a href="Submissions%253ASpatioTemporalExtent.html" title="Submissions:SpatioTemporalExtent">        Submissions:SpatioTemporalExtent       </a></li><li><a href="Submissions%253AParticipantRole.html" title="Submissions:ParticipantRole">        Submissions:ParticipantRole       </a></li><li><a href="Submissions%253AAgentRole.html" title="Submissions:AgentRole">        Submissions:AgentRole       </a></li><li><a href="Submissions%253AObjectrole.html" title="Submissions:Objectrole">        Submissions:Objectrole       </a></li><li><a href="Submissions%253AInformation_realization.html" title="Submissions:Information realization">        Submissions:Information realization       </a></li><li><a href="Submissions%253AInformationObjectsAndRepresentationLanguages.html" title="Submissions:InformationObjectsAndRepresentationLanguages">        Submissions:InformationObjectsAndRepresentationLanguages       </a></li><li><a class="new" href="http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:InformationObject&amp;action=edit&amp;redlink=1" title="Submissions:InformationObject (not yet written)">        Submissions:InformationObject       </a></li><li><a href="Submissions%253AEventProcessing.html" title="Submissions:EventProcessing">        Submissions:EventProcessing       </a></li> |



  





# 

 Elements



_The
 __EventCore__ 
 Content OP locally defines the following ontology elements:_ 





__DASE\_RULE__ 
 (owl:AnnotationProperty) Attached to an axiom, this annotation property provides information on the original (SWRL) rule from which the axiom was obtained through translation.
 
[![](../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[DASE\_RULE](../Submissions/EventCore/DASE_RULE "Submissions:EventCore/DASE RULE") 
 page_ 



[![ObjectProperty](../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__freshProp1__ 
 (owl:ObjectProperty) This property is artificially generated in order to express the following rule in OWL:  :Event(?x) ^ :providesParticipantRole(?x,?p) ^ :subEventOf(?x,?y) -> :providesParticipantRole(?y,?p).
 
 The rule is translated into two axioms:
 



 1. :Event SubClassOf: :freshProp1 some Self
 



 2. inverse (:subEventOf) o :freshProp1 o :providesParticipantRole SubPropertyOf: : :providesParticipantRole
 



[![](../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[freshProp1](../Submissions/EventCore/freshProp1 "Submissions:EventCore/freshProp1") 
 page_ 



[![ObjectProperty](../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__freshProp2__ 
 (owl:ObjectProperty) This property is artificially generated in order to express the following rule in OWL:  :Event(?x) ^ :hasSpatioTemporalExtent(?x,?w) ^ :subEventOf(?x,?y) ^ :Event(?y) ^ :hasSpatioTemporalExtent(?y,?z) -> :subSpatioTemporalExtentOf(?w,?z).
 
 The rule is translated into two axioms:
 



 1. :Event SubClassOf: :freshProp2 some Self
 



 2. inverse (:hasSpatioTemporalExtent) o :freshProp2 o :subEventOf o :freshProp2 o :hasSpatioTemporalExtent SubPropertyOf: :subSpatioTemporalExtentOf
 



[![](../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[freshProp2](../Submissions/EventCore/freshProp2 "Submissions:EventCore/freshProp2") 
 page_ 



[![ObjectProperty](../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasInformationObject__ 
 (owl:ObjectProperty) Property relating Event to InformationObject in this pattern. The domain of this property is not restricted to Event since it is possible that non-event to have an information object. The range is always InformationObject since it makes no sense to have a property named hasInformationObject to point to anything other than information object.
 
[![](../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasInformationObject](../Submissions/EventCore/hasInformationObject "Submissions:EventCore/hasInformationObject") 
 page_ 



[![ObjectProperty](../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasSpatioTemporalExtent__ 
 (owl:ObjectProperty) Property relating Event to SpatioTemporalExtent in this pattern. The range is always SpatioTemporalExtent (globally) since it makes no sense to have a property named hasSpatioTemporalExtent to point to anything other than spatiotemporal extent. Tthe domain is not set to Event as non-Event may also have spatiotemporal extent.
 
[![](../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasSpatioTemporalExtent](../Submissions/EventCore/hasSpatioTemporalExtent "Submissions:EventCore/hasSpatioTemporalExtent") 
 page_ 



[![ObjectProperty](../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__providesParticipantRole__ 
 (owl:ObjectProperty) Property relating Event to ParticipantRole in this pattern. The range is always ParticipantRole since it makes no sense to have a property named as providesParticipantRole not to point to a participant role. The domain is not set to Event as non-Event may also provide a participant role.
 
[![](../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[providesParticipantRole](../Submissions/EventCore/providesParticipantRole "Submissions:EventCore/providesParticipantRole") 
 page_ 



[![ObjectProperty](../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__subEventOf__ 
 (owl:ObjectProperty) Property expressing partonomic relation between two events. Domain and range are always Event.
 
[![](../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[subEventOf](../Submissions/EventCore/subEventOf "Submissions:EventCore/subEventOf") 
 page_ 



[![ObjectProperty](../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__subSpatioTemporalExtentOf__ 
 (owl:ObjectProperty) Property indicating partonomic relation between two spatiotemporal extents. The Event pattern only assumes that this is given by the spatiotemporal extent pattern actually used. Thus, domain and range are not explicitly stated and this property is included in axioms resulted by OWL translation of the following rule: :Event(?x) ^ :hasSpatioTemporalExtent(?x,?w) ^ :subEventOf(?x,?y) ^ :Event(?y) ^ :hasSpatioTemporalExtent(?y,?z) -> :subSpatioTemporalExtentOf(?w,?z)
 
[![](../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[subSpatioTemporalExtentOf](../Submissions/EventCore/subSpatioTemporalExtentOf "Submissions:EventCore/subSpatioTemporalExtentOf") 
 page_ 



[![Class](../../../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__Event__ 
 (owl:Class) Represents any kind of events. An event possesses a spatiotemporal extent, provides at least one participant-role, which is performed by some entity (agents or otherwise), and may be a sub-event of another event. An event may also have additional descriptive information, which is consolidated through an information object.
 
[![](../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[Event](../Submissions/EventCore/Event "Submissions:EventCore/Event") 
 page_ 



[![Class](../../../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__InformationObject__ 
 (owl:Class) An entity that encapsulates all descriptive or non-defining information of the corresponding event, e.g., names, additional identifiers, textual descriptions, etc. Should normally be aligned to a separate Information Object pattern.
 
[![](../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[InformationObject](../Submissions/EventCore/InformationObject "Submissions:EventCore/InformationObject") 
 page_ 



[![Class](../../../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__ParticipantRole__ 
 (owl:Class) Every ParticipantRole represents a reified relationship between an event and one of its participants. Should normally be aligend to a separate Participant-Role pattern.
 
[![](../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[ParticipantRole](../Submissions/EventCore/ParticipantRole "Submissions:EventCore/ParticipantRole") 
 page_ 



[![Class](../../../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__SpatioTemporalExtent__ 
 (owl:Class) Hook to a complex notion representing a unified spatial and temporal extent. Intended to cover non-static or discontinuous spatiotemporal extent. Should be aligned to a separate Spatiotemporal Extent pattern.
 
[![](../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[SpatioTemporalExtent](../Submissions/EventCore/SpatioTemporalExtent "Submissions:EventCore/SpatioTemporalExtent") 
 page_ 


# 

 Additional information



# 

 Scenarios




__Scenarios about EventCore__ 


 No scenario is added to this Content OP.
 




# 

 Reviews




__Reviews about EventCore__ 


 There is no review about this proposal.
This revision (revision ID
 __12751__ 
 ) takes in account the reviews: none
 



 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:EventCore&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:EventCore&action=evaluation") 





  





# 

 Modeling issues




__Modeling issues about EventCore__ 


 There is no Modeling issue related to this proposal.
 




  





# 

 References



  






|  |  Submission to event [WOP:2016](../WOP/2016.1 "WOP:2016")  |
| --- | --- |
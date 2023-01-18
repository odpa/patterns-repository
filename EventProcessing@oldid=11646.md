# 

 Graphical representation



__Diagram__ 





[![Image:Ep.png](../images/2/20/Ep.png)](../Image/Ep.png "Image:Ep.png")





# 

 General description




|  |  |
| --- | --- |
|  Name:  |  EventProcessing  |
|  Submitted by:  | [EvaBlomqvist](../User/EvaBlomqvist "User:EvaBlomqvist")  |
|  Also Known As:  |  ComplexEventProcessing  |
|  Intent:  |  To model event objects (in the context of complex event processing), their attributes, and their relations actual events, and sensor readings producing the events. Different types of event objects, such as complex, composite, and simple events are modelled, preoperties for expressing relations between event objects, such as constituency and componency are expressed, and attributes of event objects, such as timestamps and other data values. This pattern is aligned both to the SSN (Semantic Sensor Network) ontology, and the Event-F model, which in turn both use DUL as an upper layer.  |
|  Domains:  | [Event Processing](../Community/Event_Processing "Community:Event Processing")  , [General](../Community/General "Community:General")  |
|  Competency Questions:  | <li>       What event objects are this complex event object and abstraction of?      </li><li>       What is the header/body of this event object?      </li><li>       What is the timestamp of this event object?      </li><li>       What are the parts of this composite event object?      </li><li>       By what sensor was this event object recorded?      </li><li>       What actual event does this event object document?      </li><li>       What are the attribute values of this event object?      </li> |
|  Solution description:  |  (TBA)  |
|  Reusable OWL Building Block:  | [http://www.ontologydesignpatterns.org/cp/owl/eventprocessing.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=http://www.ontologydesignpatterns.org/cp/owl/eventprocessing.owl&message=OWL building block&from_page_id=3571&update=)  (790)  |
|  Consequences:  |  |
|  Scenarios:  |  |
|  Known Uses:  |  |
|  Web References:  |  |
|  Other References:  |  |
|  Examples (OWL files):  | <li><a class="external free" href="http://www.ontologydesignpatterns.org/cp/examples/eventprocessing/eventexample.owl" rel="nofollow" title="http://www.ontologydesignpatterns.org/cp/examples/eventprocessing/eventexample.owl">        http://www.ontologydesignpatterns.org/cp/examples/eventprocessing/eventexample.owl       </a></li> |
|  Extracted From:  |  |
|  Reengineered From:  |  |
|  Has Components:  |  |
|  Specialization Of:  |  |
|  Related CPs:  |  |



  





# 

 Elements



_The
 __EventProcessing__ 
 Content OP locally defines the following ontology elements:_ 





[![Class](../../../../../../../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__SimpleEvent__ 
 (owl:Class) An event object that is not an abstraction of other event objects, nor is composed of other event objects.
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[SimpleEvent](http://ontologydesignpatterns.org/wiki/Submissions:EventProcessing/SimpleEvent "Submissions:EventProcessing/SimpleEvent") 
 page_ 



[![Class](../../../../../../../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__EventObject__ 
 (owl:Class) An object that represents, encodes, or records an event, generally for the purpose of computer processing.
 
  





 An event object may consist of an event object header and a body, where the header is defined as the part of the event object that can be interpreted by the event processing system, i.e. and event object needs to contain at least some information (e.g. with a known vocabulary) that can be used by the event processing system. Note that the open world assumption allows us to choose not to explicitly specify a header, despite the restriction that it exists.
 



  





 An event object is either a complex event, i.e. an event object that has some relation (either through abstraction or componency) to other event objects, or a simple event.
 



  





 An event object records information about an actual event, which is then by implication a documented event (i.e. participating in an event documentation situation).
 



[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[EventObject](../Submissions/EventProcessing/EventObject "Submissions:EventProcessing/EventObject") 
 page_ 



[![Class](../../../../../../../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__SensorOutput__ 
 (owl:Class) Class representing the alignement to ssn:SensorOutput, expressing the restriction that an ssn:SensorOutput is either a complex event or a simple event, depending on the sensor used.
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[SensorOutput](../Submissions/EventProcessing/SensorOutput "Submissions:EventProcessing/SensorOutput") 
 page_ 



[![Class](../../../../../../../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__ComplexEvent__ 
 (owl:Class) An event that summarizes, represents, or denotes a set of other events, i.e. it is an abstraction over other events. Anything that is not a complex event is instead a simple event.
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[ComplexEvent](http://ontologydesignpatterns.org/wiki/Submissions:EventProcessing/ComplexEvent "Submissions:EventProcessing/ComplexEvent") 
 page_ 



[![Class](../../../../../../../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__CompositeEvent__ 
 (owl:Class) An event object that is composed of a set of other event objects, i.e. its parts.
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[CompositeEvent](http://ontologydesignpatterns.org/wiki/Submissions:EventProcessing/CompositeEvent "Submissions:EventProcessing/CompositeEvent") 
 page_ 



[![ObjectProperty](../../../../../../../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasEventObjectPart__ 
 (owl:TransitiveProperty) This transitive property represents a partonomy relation between event objects. An event object can consist of several "partial events" that together make up the complete event object. The parts of the event object do not exist on their own, but exist to "make up" the whole of the encapsulating event, likewise the encapsulating event is not complete without its parts. Please note the difference between this stronger relation, compared to the "hasSubEvent"-property which merely relates event objects to each other, e.g. expressing the triggering of abstractions, but without implying that the events are parts of each other.
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasEventObjectPart](../Submissions/EventProcessing/hasEventObjectPart "Submissions:EventProcessing/hasEventObjectPart") 
 page_ 



[![Class](../../../../../../../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__EventObjectHeader__ 
 (owl:Class) Some event processing systems need to distinguish between an event object header and its body, where the event object header is the part of the event object with known content (e.g. known vocabulary) that can be directly processed by the event processing system. Although a header is considered mandatory for an event object, if not specified what the header consists of, it can be inferred by the system through the fact that it contains the "known" part, as opposed to the body that may contain a payload that the system cannot interpret.
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[EventObjectHeader](../Submissions/EventProcessing/EventObjectHeader "Submissions:EventProcessing/EventObjectHeader") 
 page_ 



[![ObjectProperty](../../../../../../../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasEventObjectAttributeValue__ 
 (owl:ObjectProperty)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasEventObjectAttributeValue](../Submissions/EventProcessing/hasEventObjectAttributeValue "Submissions:EventProcessing/hasEventObjectAttributeValue") 
 page_ 



[![DatatypeProperty](../../../../../../images/thumb/a/a5/DatatypeProperty.gif/20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif "DatatypeProperty")
__hasEventObjectAttributeDataValue__ 
 (owl:DatatypeProperty)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasEventObjectAttributeDataValue](../Submissions/EventProcessing/hasEventObjectAttributeDataValue "Submissions:EventProcessing/hasEventObjectAttributeDataValue") 
 page_ 



[![DatatypeProperty](../../../../../../images/thumb/a/a5/DatatypeProperty.gif/20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif "DatatypeProperty")
__hasEventObjectTime__ 
 (owl:DatatypeProperty)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasEventObjectTime](../Submissions/EventProcessing/hasEventObjectTime "Submissions:EventProcessing/hasEventObjectTime") 
 page_ 



[![ObjectProperty](../../../../../../../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__isEventObjectHeaderOf__ 
 (owl:ObjectProperty)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[isEventObjectHeaderOf](../Submissions/EventProcessing/isEventObjectHeaderOf "Submissions:EventProcessing/isEventObjectHeaderOf") 
 page_ 



[![Class](../../../../../../../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__EventObjectPart__ 
 (owl:Class)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[EventObjectPart](../Submissions/EventProcessing/EventObjectPart "Submissions:EventProcessing/EventObjectPart") 
 page_ 



[![ObjectProperty](../../../../../../../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasSubEventObject__ 
 (owl:TransitiveProperty) A relation that connects a complex event with the low-level events it is a higher-level representation of. An event object may reference another event, on a lower level of abstraction or granularity, upon which is it is based or from which it was derived or triggered, making that other event a "sub event" of this aggregated or more abstract event object. Note that for modelling instance data, normally, the non-transitive sub-property "hasDirectSubEventObject" should be used, based on which the presence of this transitive relation can be inferred.
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasSubEventObject](../Submissions/EventProcessing/hasSubEventObject "Submissions:EventProcessing/hasSubEventObject") 
 page_ 



[![Class](../../../../../../../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__EventObjectBody__ 
 (owl:Class) Some event processing systems need to distinguish between an event object header and its body, where the event object header is the part of the event object with known content (e.g. known vocabulary) that can be directly processed by the event processing system, and the body is the rest of the event object. The body may always be empty or missing.
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[EventObjectBody](../Submissions/EventProcessing/EventObjectBody "Submissions:EventProcessing/EventObjectBody") 
 page_ 



[![ObjectProperty](../../../../../../../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__isEventObjectBodyOf__ 
 (owl:ObjectProperty)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[isEventObjectBodyOf](../Submissions/EventProcessing/isEventObjectBodyOf "Submissions:EventProcessing/isEventObjectBodyOf") 
 page_ 



[![ObjectProperty](../../../../../../../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasEventObjectHeader__ 
 (owl:ObjectProperty) Some event processing systems need to distinguish between an event object header and its body, where the event object header is the part of the event object with known content (e.g. known vocabulary) that can be directly processed by the event processing system. This property relates an event object to its header part.
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasEventObjectHeader](../Submissions/EventProcessing/hasEventObjectHeader "Submissions:EventProcessing/hasEventObjectHeader") 
 page_ 



[![ObjectProperty](../../../../../../../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__informationAboutEvent__ 
 (owl:ObjectProperty)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[informationAboutEvent](../Submissions/EventProcessing/informationAboutEvent "Submissions:EventProcessing/informationAboutEvent") 
 page_ 



[![ObjectProperty](../../../../../../../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasEventLocation__ 
 (owl:ObjectProperty)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasEventLocation](../Submissions/EventProcessing/hasEventLocation "Submissions:EventProcessing/hasEventLocation") 
 page_ 



[![ObjectProperty](../../../../../../../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasEventObjectBody__ 
 (owl:ObjectProperty) Some event processing systems need to distinguish between an event object header and its body, where the event object header is the part of the event object with known content (e.g. known vocabulary) that can be directly processed by the event processing system. This property relates an event object to its body part.
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasEventObjectBody](../Submissions/EventProcessing/hasEventObjectBody "Submissions:EventProcessing/hasEventObjectBody") 
 page_ 



[![ObjectProperty](../../../../../../../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__refersToEventObjectConstituent__ 
 (owl:ObjectProperty) Event objects that use a header/body structure can use this property to refer to the constituents (i.e. direct sub-events in an abstraction hierarchy) of the event object. Through a property chain axiom, the presence of a "hasDirectSubEventObject" relation can be inferred.
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[refersToEventObjectConstituent](../Submissions/EventProcessing/refersToEventObjectConstituent "Submissions:EventProcessing/refersToEventObjectConstituent") 
 page_ 



[![ObjectProperty](../../../../../../../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__refersToEventObjectComponent__ 
 (owl:ObjectProperty) Event objects that use a header/body structure can use this property to refer to the components (i.e. direct parts) of the event object. Through a property chain axiom, the presence of a "hasEventObjectComponent" relation can be inferred.
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[refersToEventObjectComponent](../Submissions/EventProcessing/refersToEventObjectComponent "Submissions:EventProcessing/refersToEventObjectComponent") 
 page_ 



[![ObjectProperty](../../../../../../../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__isEventObjectComponentOf__ 
 (owl:ObjectProperty)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[isEventObjectComponentOf](../Submissions/EventProcessing/isEventObjectComponentOf "Submissions:EventProcessing/isEventObjectComponentOf") 
 page_ 



[![ObjectProperty](../../../../../../../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasEventObjectComponent__ 
 (owl:ObjectProperty) This non-transitive property expresses the direct relation between an event object and its direct parts, i.e. its components. Using this property a hierarchy of components can be expressed for an event object. The components of the event object do not exist on their own, but exist to "make up" the whole of the encapsulating event, likewise the encapsulating event is not complete without its parts. Please note the difference between this stronger relation, compared to the "hasSubEvent"-property which merely relates event objects to each other, e.g. expressing the triggering of abstractions, but without implying that the events are parts of each other.
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasEventObjectComponent](../Submissions/EventProcessing/hasEventObjectComponent "Submissions:EventProcessing/hasEventObjectComponent") 
 page_ 



[![ObjectProperty](../../../../../../../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__isEventObjectPartOf__ 
 (owl:TransitiveProperty)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[isEventObjectPartOf](../Submissions/EventProcessing/isEventObjectPartOf "Submissions:EventProcessing/isEventObjectPartOf") 
 page_ 



[![ObjectProperty](../../../../../../../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasSensorReadingValue__ 
 (owl:ObjectProperty) Property for expresseing the alignemet to the SSN ontology, equivalent to ssn:hasValue.
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasSensorReadingValue](../Submissions/EventProcessing/hasSensorReadingValue "Submissions:EventProcessing/hasSensorReadingValue") 
 page_ 



[![ObjectProperty](../../../../../../../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasDirectSubEventObject__ 
 (owl:ObjectProperty) A relation that connects a complex event with the low-level events it is a higher-level representation of. This is a non-transitive relation that can be used to create a hierarchy of levels of sub-events, that represents the reasoning/triggering or abstraction process that led up to the creation or detection of a complex event. The transitive superproperty hasSubEventObject allows for direclty querying for the transitive closure of sub-events, regardless of the hierarchy, even if only this non-transitive sub-property is used in the data.
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasDirectSubEventObject](../Submissions/EventProcessing/hasDirectSubEventObject "Submissions:EventProcessing/hasDirectSubEventObject") 
 page_ 



[![ObjectProperty](../../../../../../../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__isDirectSubEventObjectOf__ 
 (owl:ObjectProperty)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[isDirectSubEventObjectOf](../Submissions/EventProcessing/isDirectSubEventObjectOf "Submissions:EventProcessing/isDirectSubEventObjectOf") 
 page_ 



[![ObjectProperty](../../../../../../../../../../../../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__isSubEventObjectOf__ 
 (owl:TransitiveProperty)
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[isSubEventObjectOf](../Submissions/EventProcessing/isSubEventObjectOf "Submissions:EventProcessing/isSubEventObjectOf") 
 page_ 



[![DatatypeProperty](../../../../../../images/thumb/a/a5/DatatypeProperty.gif/20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif "DatatypeProperty")
__hasEventObjectSystemTime__ 
 (owl:DatatypeProperty) The timestamp of the event according to the event processing system (in terms of its internal clock time), i.e. when the event object was received byt the event processing system through the stream.
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasEventObjectSystemTime](../Submissions/EventProcessing/hasEventObjectSystemTime "Submissions:EventProcessing/hasEventObjectSystemTime") 
 page_ 



[![DatatypeProperty](../../../../../../images/thumb/a/a5/DatatypeProperty.gif/20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif "DatatypeProperty")
__hasEventObjectExpirationTime__ 
 (owl:DatatypeProperty) Time limit on the validity of this event object.
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasEventObjectExpirationTime](../Submissions/EventProcessing/hasEventObjectExpirationTime "Submissions:EventProcessing/hasEventObjectExpirationTime") 
 page_ 



[![DatatypeProperty](../../../../../../images/thumb/a/a5/DatatypeProperty.gif/20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif "DatatypeProperty")
__hasEventObjectSamplingTime__ 
 (owl:DatatypeProperty) The time the event was detected and recorded as data, e.g. when it was recorded by a sensor in terms of the sensor's internal clock.
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasEventObjectSamplingTime](../Submissions/EventProcessing/hasEventObjectSamplingTime "Submissions:EventProcessing/hasEventObjectSamplingTime") 
 page_ 



[![DatatypeProperty](../../../../../../images/thumb/a/a5/DatatypeProperty.gif/20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif "DatatypeProperty")
__hasEventObjectApplicationTime__ 
 (owl:DatatypeProperty) The timestamp assigned by the source of the data when it was transmitted, i.e. when it entered the stream.
 
[![](../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasEventObjectApplicationTime](../Submissions/EventProcessing/hasEventObjectApplicationTime "Submissions:EventProcessing/hasEventObjectApplicationTime") 
 page_ 


# 

 Additional information



 Pattern authors: Eva Blomqvist and Mikko Rinne
 



# 

 Scenarios




__Scenarios about EventProcessing__ 


 No scenario is added to this Content OP.
 




# 

 Reviews




__Reviews about EventProcessing__ 



|  Review article  | [Posted on](../Property/CreationDate "Property:CreationDate")  | [About revision (current is 11646)](../Property/ReviewAboutVersion "Property:ReviewAboutVersion")  |
| --- | --- | --- |
| [VojtechSvatek about EventProcessing](../Reviews/VojtechSvatek_about_EventProcessing "Reviews:VojtechSvatek about EventProcessing")  |  2456512  7 August 2013  |  11646  11,646  |



 This revision (revision ID
 __11646__ 
 ) takes in account the reviews:
 [VojtechSvatek about EventProcessing](../Reviews/VojtechSvatek_about_EventProcessing "Reviews:VojtechSvatek about EventProcessing") 




 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:EventProcessing&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:EventProcessing&action=evaluation") 





  





# 

 Modeling issues




__Modeling issues about EventProcessing__ 


 There is no Modeling issue related to this proposal.
 




  





# 

 References



  






|  |  Submission to event [WOP:2013](../WOP/2013 "WOP:2013")  |
| --- | --- |
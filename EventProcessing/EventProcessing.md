# 

 Graphical representation



__Diagram__ 





[![Image:EP_ODP.png](./EP_ODP.png)](../Image/EP_ODP.png.md "Image:EP_ODP.png")





# 

 General description




|  |  |
| --- | --- |
|  Name:  |  EventProcessing  |
|  Submitted by:  | [EvaBlomqvist](../User/EvaBlomqvist.md "User:EvaBlomqvist")  , [MikkoRinne](http://ontologydesignpatterns.org/wiki/index.php?title=User:MikkoRinne&action=edit&redlink=1 "User:MikkoRinne (not yet written)")  |
|  Also Known As:  |  ComplexEventProcessing  |
|  Intent:  |  To model event objects (in the context of complex event processing), their attributes, and their relations actual events, and sensor readings producing the events. Different types of event objects, such as complex, composite, and simple events are modelled, preoperties for expressing relations between event objects, such as constituency and componency are expressed, and attributes of event objects, such as timestamps and other data values. This pattern is aligned both to the SSN (Semantic Sensor Network) ontology, and the Event-F model, which in turn both use DUL as an upper layer.  |
|  Domains:  | [Event Processing](../Community/Event_Processing.md "Community:Event Processing")  , [General](../Community/General.md "Community:General")  |
|  Competency Questions:  | <li>       What event objects are this complex event object and abstraction of?      </li><li>       What is the header/body of this event object?      </li><li>       What are the parts of this composite event object?      </li><li>       What is the timestamp of this event object?      </li><li>       By what sensor was this event object recorded?      </li><li>       What actual event does this event object document?      </li><li>       What are the attribute values of this event object?      </li> |
|  Solution description:  |  See WOP2013 pattern abstract, and full paper.  |
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





[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__SimpleEventObject__ 
 (owl:Class) An event object that is not an abstraction of other event objects, nor is composed of other event objects.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[SimpleEventObject](./EventProcessing/SimpleEventObject.md "Submissions:EventProcessing/SimpleEventObject") 
 page_ 



[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__EventObject__ 
 (owl:Class) An object that represents, encodes, or records an event, generally for the purpose of computer processing.
 
  





 An event object may consist of an event object header and a body, where the header is defined as the part of the event object that can be interpreted by the event processing system, i.e. and event object needs to contain at least some information (e.g. with a known vocabulary) that can be used by the event processing system. Note that the open world assumption allows us to choose not to explicitly specify a header, despite the restriction that it exists.
 



  





 An event object is either a complex event, i.e. an event object that has some relation (either through abstraction or componency) to other event objects, or a simple event.
 



  





 An event object records information about an actual event, which is then by implication a documented event (i.e. participating in an event documentation situation).
 



[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[EventObject](./EventProcessing/ComplexEventObject.md "Submissions:EventProcessing/EventObject") 
 page_ 



[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__CompositeEventObject__ 
 (owl:Class) An event object that is composed of a set of other event objects, i.e. its parts.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[CompositeEventObject](./EventProcessing/CompositeEventObject.md "Submissions:EventProcessing/CompositeEventObject") 
 page_ 



[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__ComplexEventObject__ 
 (owl:Class) An event that summarizes, represents, or denotes a set of other events, i.e. it is an abstraction over other events. Anything that is not a complex event is instead a simple event.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[ComplexEventObject](./EventProcessing/ComplexEventObject.md "Submissions:EventProcessing/ComplexEventObject") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__hasEventObjectPart__ 
 (owl:TransitiveProperty) This transitive property represents a partonomy relation between event objects. An event object can consist of several "partial events" that together make up the complete event object. The parts of the event object do not exist on their own, but exist to "make up" the whole of the encapsulating event, likewise the encapsulating event is not complete without its parts. Please note the difference between this stronger relation, compared to the "hasSubEvent"-property which merely relates event objects to each other, e.g. expressing the triggering of abstractions, but without implying that the events are parts of each other.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[hasEventObjectPart](./EventProcessing/hasEventObjectPart.md "Submissions:EventProcessing/hasEventObjectPart") 
 page_ 



[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__SensorOutput__ 
 (owl:Class) Class representing the alignement to ssn:SensorOutput, expressing the restriction that an ssn:SensorOutput is either a complex event or a simple event, depending on the sensor used.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[SensorOutput](./EventProcessing/SensorOutput.md "Submissions:EventProcessing/SensorOutput") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__hasSubEventObject__ 
 (owl:TransitiveProperty) A relation that connects a complex event with the low-level events it is a higher-level representation of. An event object may reference another event, on a lower level of abstraction or granularity, upon which is it is based or from which it was derived or triggered, making that other event a "sub event" of this aggregated or more abstract event object. Note that for modelling instance data, normally, the non-transitive sub-property "hasDirectSubEventObject" should be used, based on which the presence of this transitive relation can be inferred.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[hasSubEventObject](./EventProcessing/hasSubEventObject.md "Submissions:EventProcessing/hasSubEventObject") 
 page_ 



[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__EventObjectHeader__ 
 (owl:Class) Some event processing systems need to distinguish between an event object header and its body, where the event object header is the part of the event object with known content (e.g. known vocabulary) that can be directly processed by the event processing system. Although a header is considered mandatory for an event object, if not specified what the header consists of, it can be inferred by the system through the fact that it contains the "known" part, as opposed to the body that may contain a payload that the system cannot interpret.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[EventObjectHeader](./EventProcessing/EventObjectHeader.md "Submissions:EventProcessing/EventObjectHeader") 
 page_ 



[![DatatypeProperty](./20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif.md "DatatypeProperty")
__hasEventObjectTime__ 
 (owl:DatatypeProperty)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[hasEventObjectTime](./EventProcessing/hasEventObjectTime.md "Submissions:EventProcessing/hasEventObjectTime") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__hasEventDuration__ 
 (owl:ObjectProperty) Property for represting a time interval of an event object, rather than a time point. Alternative is to define several time points, using the subproperties of the datatype property hasEventObjectTime.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[hasEventDuration](./EventProcessing/hasEventDuration.md "Submissions:EventProcessing/hasEventDuration") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__hasEventObjectAttributeValue__ 
 (owl:ObjectProperty)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[hasEventObjectAttributeValue](./EventProcessing/hasEventObjectAttributeValue.md "Submissions:EventProcessing/hasEventObjectAttributeValue") 
 page_ 



[![DatatypeProperty](./20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif.md "DatatypeProperty")
__hasEventObjectAttributeDataValue__ 
 (owl:DatatypeProperty)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[hasEventObjectAttributeDataValue](./EventProcessing/hasEventObjectAttributeDataValue.md "Submissions:EventProcessing/hasEventObjectAttributeDataValue") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__isEventObjectHeaderOf__ 
 (owl:ObjectProperty)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[isEventObjectHeaderOf](./EventProcessing/isEventObjectHeaderOf.md "Submissions:EventProcessing/isEventObjectHeaderOf") 
 page_ 



[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__EventObjectPart__ 
 (owl:Class)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[EventObjectPart](./EventProcessing/EventObjectPart.md "Submissions:EventProcessing/EventObjectPart") 
 page_ 



[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__EventObjectBody__ 
 (owl:Class) Some event processing systems need to distinguish between an event object header and its body, where the event object header is the part of the event object with known content (e.g. known vocabulary) that can be directly processed by the event processing system, and the body is the rest of the event object. The body may always be empty or missing.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[EventObjectBody](./EventProcessing/EventObjectBody.md "Submissions:EventProcessing/EventObjectBody") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__isEventObjectBodyOf__ 
 (owl:ObjectProperty)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[isEventObjectBodyOf](./EventProcessing/isEventObjectBodyOf.md "Submissions:EventProcessing/isEventObjectBodyOf") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__hasEventObjectHeader__ 
 (owl:ObjectProperty) Some event processing systems need to distinguish between an event object header and its body, where the event object header is the part of the event object with known content (e.g. known vocabulary) that can be directly processed by the event processing system. This property relates an event object to its header part.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[hasEventObjectHeader](./EventProcessing/hasEventObjectHeader.md "Submissions:EventProcessing/hasEventObjectHeader") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__informationAboutEvent__ 
 (owl:ObjectProperty)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[informationAboutEvent](./EventProcessing/informationAboutEvent.md "Submissions:EventProcessing/informationAboutEvent") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__hasEventLocation__ 
 (owl:ObjectProperty)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[hasEventLocation](./EventProcessing/hasEventLocation.md "Submissions:EventProcessing/hasEventLocation") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__hasEventObjectBody__ 
 (owl:ObjectProperty) Some event processing systems need to distinguish between an event object header and its body, where the event object header is the part of the event object with known content (e.g. known vocabulary) that can be directly processed by the event processing system. This property relates an event object to its body part.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[hasEventObjectBody](./EventProcessing/hasEventObjectBody.md "Submissions:EventProcessing/hasEventObjectBody") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__refersToEventObjectConstituent__ 
 (owl:ObjectProperty) Event objects that use a header/body structure can use this property to refer to the constituents (i.e. direct sub-events in an abstraction hierarchy) of the event object. Through a property chain axiom, the presence of a "hasDirectSubEventObject" relation can be inferred.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[refersToEventObjectConstituent](./EventProcessing/refersToEventObjectConstituent.md "Submissions:EventProcessing/refersToEventObjectConstituent") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__refersToEventObjectComponent__ 
 (owl:ObjectProperty) Event objects that use a header/body structure can use this property to refer to the components (i.e. direct parts) of the event object. Through a property chain axiom, the presence of a "hasEventObjectComponent" relation can be inferred.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[refersToEventObjectComponent](./EventProcessing/refersToEventObjectComponent.md "Submissions:EventProcessing/refersToEventObjectComponent") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__isEventObjectComponentOf__ 
 (owl:ObjectProperty)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[isEventObjectComponentOf](./EventProcessing/isEventObjectComponentOf.md "Submissions:EventProcessing/isEventObjectComponentOf") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__hasEventObjectComponent__ 
 (owl:ObjectProperty) This non-transitive property expresses the direct relation between an event object and its direct parts, i.e. its components. Using this property a hierarchy of components can be expressed for an event object. The components of the event object do not exist on their own, but exist to "make up" the whole of the encapsulating event, likewise the encapsulating event is not complete without its parts. Please note the difference between this stronger relation, compared to the "hasSubEvent"-property which merely relates event objects to each other, e.g. expressing the triggering of abstractions, but without implying that the events are parts of each other.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[hasEventObjectComponent](./EventProcessing/hasEventObjectComponent.md "Submissions:EventProcessing/hasEventObjectComponent") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__isEventObjectPartOf__ 
 (owl:TransitiveProperty)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[isEventObjectPartOf](./EventProcessing/isEventObjectPartOf.md "Submissions:EventProcessing/isEventObjectPartOf") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__hasSensorReadingValue__ 
 (owl:ObjectProperty) Property for expresseing the alignemet to the SSN ontology, equivalent to ssn:hasValue.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[hasSensorReadingValue](./EventProcessing/hasSensorReadingValue.md "Submissions:EventProcessing/hasSensorReadingValue") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__hasDirectSubEventObject__ 
 (owl:ObjectProperty) A relation that connects a complex event with the low-level events it is a higher-level representation of. This is a non-transitive relation that can be used to create a hierarchy of levels of sub-events, that represents the reasoning/triggering or abstraction process that led up to the creation or detection of a complex event. The transitive superproperty hasSubEventObject allows for direclty querying for the transitive closure of sub-events, regardless of the hierarchy, even if only this non-transitive sub-property is used in the data.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[hasDirectSubEventObject](./EventProcessing/hasDirectSubEventObject.md "Submissions:EventProcessing/hasDirectSubEventObject") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__isDirectSubEventObjectOf__ 
 (owl:ObjectProperty)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[isDirectSubEventObjectOf](./EventProcessing/isDirectSubEventObjectOf.md "Submissions:EventProcessing/isDirectSubEventObjectOf") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__isSubEventObjectOf__ 
 (owl:TransitiveProperty)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[isSubEventObjectOf](./EventProcessing/isSubEventObjectOf.md "Submissions:EventProcessing/isSubEventObjectOf") 
 page_ 



[![DatatypeProperty](./20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif.md "DatatypeProperty")
__hasEventObjectSystemTime__ 
 (owl:DatatypeProperty) The timestamp of the event according to the event processing system (in terms of its internal clock time), i.e. when the event object was received byt the event processing system through the stream.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[hasEventObjectSystemTime](./EventProcessing/hasEventObjectSystemTime.md "Submissions:EventProcessing/hasEventObjectSystemTime") 
 page_ 



[![DatatypeProperty](./20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif.md "DatatypeProperty")
__hasEventObjectExpirationTime__ 
 (owl:DatatypeProperty) Time limit on the validity of this event object.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[hasEventObjectExpirationTime](./EventProcessing/hasEventObjectExpirationTime.md "Submissions:EventProcessing/hasEventObjectExpirationTime") 
 page_ 



[![DatatypeProperty](./20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif.md "DatatypeProperty")
__hasEventObjectSamplingTime__ 
 (owl:DatatypeProperty) The time the event was detected and recorded as data, e.g. when it was recorded by a sensor in terms of the sensor's internal clock.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[hasEventObjectSamplingTime](./EventProcessing/hasEventObjectSamplingTime.md "Submissions:EventProcessing/hasEventObjectSamplingTime") 
 page_ 



[![DatatypeProperty](./20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif.md "DatatypeProperty")
__hasEventObjectApplicationTime__ 
 (owl:DatatypeProperty) The timestamp assigned by the source of the data when it was transmitted, i.e. when it entered the stream.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[hasEventObjectApplicationTime](./EventProcessing/hasEventObjectApplicationTime.md "Submissions:EventProcessing/hasEventObjectApplicationTime") 
 page_ 


# 

 Additional information



# 

 Scenarios




__Scenarios about EventProcessing__ 


 No scenario is added to this Content OP.
 




# 

 Reviews




__Reviews about EventProcessing__ 



|  Review article  | [Posted on](../Property/CreationDate.md "Property:CreationDate")  | [About revision (current is 11694)](../Property/ReviewAboutVersion.md "Property:ReviewAboutVersion")  |
| --- | --- | --- |
| [VojtechSvatek about EventProcessing](../Reviews/VojtechSvatek_about_EventProcessing.md "Reviews:VojtechSvatek about EventProcessing")  |  2456512  7 August 2013  |  11646  11,646  |



 This revision (revision ID
 __11694__ 
 ) takes in account the reviews:
 [VojtechSvatek about EventProcessing](../Reviews/VojtechSvatek_about_EventProcessing.md "Reviews:VojtechSvatek about EventProcessing") 




 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:EventProcessing&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:EventProcessing&action=evaluation") 





  





# 

 Modeling issues




__Modeling issues about EventProcessing__ 


 There is no Modeling issue related to this proposal.
 




  





# 

 References



  






|  |  Submission to event [WOP:2013](../WOP/2013.md "WOP:2013")  |
| --- | --- |



  






|  |  Submission to event  |
| --- | --- |
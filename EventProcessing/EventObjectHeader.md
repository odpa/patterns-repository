___EventObjectHeader__ 
 has
 [Category:OntologyElement](../../Category/OntologyElement "Category:OntologyElement") 
 and is an
 [element of](../../Property/ElementOf "Property:ElementOf") 
[EventProcessing](../../Submissions/EventProcessing "Submissions:EventProcessing")_




  





[![Class](../../images/thumb/2/27/Class.gif/45px-Class.gif)](../../Image/Class.gif "Class")


__Name__ 
 : EventObjectHeader
 



__Type:__ 
 owl:Class
 



__Description__ 
 : Some event processing systems need to distinguish between an event object header and its body, where the event object header is the part of the event object with known content (e.g. known vocabulary) that can be directly processed by the event processing system. Although a header is considered mandatory for an event object, if not specified what the header consists of, it can be inferred by the system through the fact that it contains the "known" part, as opposed to the body that may contain a payload that the system cannot interpret.
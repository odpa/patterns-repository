___hasEventObjectComponent__ 
 has
 [Category:OntologyElement](../../Category/OntologyElement "Category:OntologyElement") 
 and is an
 [element of](../../Property/ElementOf "Property:ElementOf") 
[EventProcessing](../../Submissions/EventProcessing "Submissions:EventProcessing")_




  





[![ObjectProperty](../public/images/thumb/c/c3/ObjectProperty.gif/45px-ObjectProperty.gif)](../../Image/ObjectProperty.gif "ObjectProperty")


__Name__ 
 : hasEventObjectComponent
 



__Type:__ 
 owl:ObjectProperty
 



__Description__ 
 : This non-transitive property expresses the direct relation between an event object and its direct parts, i.e. its components. Using this property a hierarchy of components can be expressed for an event object. The components of the event object do not exist on their own, but exist to "make up" the whole of the encapsulating event, likewise the encapsulating event is not complete without its parts. Please note the difference between this stronger relation, compared to the "hasSubEvent"-property which merely relates event objects to each other, e.g. expressing the triggering of abstractions, but without implying that the events are parts of each other.
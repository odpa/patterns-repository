___hasSubEventObject__ 
 has
 [Category:OntologyElement](../../Category/OntologyElement "Category:OntologyElement") 
 and is an
 [element of](../../Property/ElementOf "Property:ElementOf") 
[EventProcessing](../../Submissions/EventProcessing "Submissions:EventProcessing")_




  





[![ObjectProperty](../public/images/thumb/c/c3/ObjectProperty.gif/45px-ObjectProperty.gif)](../../Image/ObjectProperty.gif "ObjectProperty")


__Name__ 
 : hasSubEventObject
 



__Type:__ 
 owl:TransitiveProperty
 



__Description__ 
 : A relation that connects a complex event with the low-level events it is a higher-level representation of. An event object may reference another event, on a lower level of abstraction or granularity, upon which is it is based or from which it was derived or triggered, making that other event a "sub event" of this aggregated or more abstract event object. Note that for modelling instance data, normally, the non-transitive sub-property "hasDirectSubEventObject" should be used, based on which the presence of this transitive relation can be inferred.
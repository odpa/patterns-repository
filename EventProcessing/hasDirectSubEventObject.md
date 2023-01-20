___hasDirectSubEventObject__ 
 has
 [Category:OntologyElement](../../Category/OntologyElement "Category:OntologyElement") 
 and is an
 [element of](../../Property/ElementOf "Property:ElementOf") 
[EventProcessing](../../Submissions/EventProcessing "Submissions:EventProcessing")_




  





[![ObjectProperty](../public/images/thumb/c/c3/ObjectProperty.gif/45px-ObjectProperty.gif)](../../Image/ObjectProperty.gif "ObjectProperty")


__Name__ 
 : hasDirectSubEventObject
 



__Type:__ 
 owl:ObjectProperty
 



__Description__ 
 : A relation that connects a complex event with the low-level events it is a higher-level representation of. This is a non-transitive relation that can be used to create a hierarchy of levels of sub-events, that represents the reasoning/triggering or abstraction process that led up to the creation or detection of a complex event. The transitive superproperty hasSubEventObject allows for direclty querying for the transitive closure of sub-events, regardless of the hierarchy, even if only this non-transitive sub-property is used in the data.
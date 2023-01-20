___subSpatioTemporalExtentOf__ 
 has
 [Category:OntologyElement](../../Category/OntologyElement "Category:OntologyElement") 
 and is an
 [element of](../../Property/ElementOf "Property:ElementOf") 
[EventCore](../../Submissions/EventCore "Submissions:EventCore")_




  





[![ObjectProperty](../public/images/thumb/c/c3/ObjectProperty.gif/45px-ObjectProperty.gif)](../../Image/ObjectProperty.gif "ObjectProperty")


__Name__ 
 : subSpatioTemporalExtentOf
 



__Type:__ 
 owl:ObjectProperty
 



__Description__ 
 : Property indicating partonomic relation between two spatiotemporal extents. The Event pattern only assumes that this is given by the spatiotemporal extent pattern actually used. Thus, domain and range are not explicitly stated and this property is included in axioms resulted by OWL translation of the following rule: :Event(?x) ^ :hasSpatioTemporalExtent(?x,?w) ^ :subEventOf(?x,?y) ^ :Event(?y) ^ :hasSpatioTemporalExtent(?y,?z) -> :subSpatioTemporalExtentOf(?w,?z)
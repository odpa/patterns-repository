___freshProp2__ 
 has
 [Category:OntologyElement](../../Category/OntologyElement "Category:OntologyElement") 
 and is an
 [element of](../../Property/ElementOf "Property:ElementOf") 
[EventCore](../../Submissions/EventCore "Submissions:EventCore")_




  





[![ObjectProperty](../../images/thumb/c/c3/ObjectProperty.gif/45px-ObjectProperty.gif)](../../Image/ObjectProperty.gif "ObjectProperty")


__Name__ 
 : freshProp2
 



__Type:__ 
 owl:ObjectProperty
 



__Description__ 
 : This property is artificially generated in order to express the following rule in OWL:  :Event(?x) ^ :hasSpatioTemporalExtent(?x,?w) ^ :subEventOf(?x,?y) ^ :Event(?y) ^ :hasSpatioTemporalExtent(?y,?z) -> :subSpatioTemporalExtentOf(?w,?z).
 



 The rule is translated into two axioms:
 



 1. :Event SubClassOf: :freshProp2 some Self
 



 2. inverse (:hasSpatioTemporalExtent) o :freshProp2 o :subEventOf o :freshProp2 o :hasSpatioTemporalExtent SubPropertyOf: :subSpatioTemporalExtentOf
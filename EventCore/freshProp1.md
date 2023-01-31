___freshProp1__ 
 has
 [Category:OntologyElement](../../Category/OntologyElement "Category:OntologyElement") 
 and is an
 [element of](../../Property/ElementOf "Property:ElementOf") 
[EventCore](../../Submissions/EventCore "Submissions:EventCore")_




  





[![ObjectProperty](../images/thumb/c/c3/ObjectProperty.gif/45px-ObjectProperty.gif)](../../Image/ObjectProperty.gif "ObjectProperty")


__Name__ 
 : freshProp1
 



__Type:__ 
 owl:ObjectProperty
 



__Description__ 
 : This property is artificially generated in order to express the following rule in OWL:  :Event(?x) ^ :providesParticipantRole(?x,?p) ^ :subEventOf(?x,?y) -> :providesParticipantRole(?y,?p).
 



 The rule is translated into two axioms:
 



 1. :Event SubClassOf: :freshProp1 some Self
 



 2. inverse (:subEventOf) o :freshProp1 o :providesParticipantRole SubPropertyOf: : :providesParticipantRole
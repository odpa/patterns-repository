#  Graphical representation


__Diagram__




[![Image:collectionentity.jpg](./Collectionentity.jpg)](../Image/Collectionentity.jpg.md "Image:collectionentity.jpg")




#  General description




|  |  |
| --- | --- |
|  Name: |  collection entity |
|  Submitted by: | [ValentinaPresutti](../User/ValentinaPresutti.md "User:ValentinaPresutti") |
|  Also Known As: |  collections, membership |
|  Intent: |  To represent collections, and their entities, i.e. to represent membership. |
|  Domains: | [Parts and Collections](../Community/Parts_and_Collections.md "Community:Parts and Collections") |
|  Competency Questions: | <li> Which collection this entity is member of?</li><li> Which are the members of this collection?</li> |
|  Solution description: |  This pattern is a basic one: it catches the idea of a collection and its members. |
|  Reusable OWL Building Block: | [http://www.ontologydesignpatterns.org/cp/owl/collectionentity.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=http://www.ontologydesignpatterns.org/cp/owl/collectionentity.owl&message=OWL building block&from_page_id=258&update=) (1538) |
|  Consequences: |  It is possible to put sets in the domain of discourse through the class  [Collection](../Collection/Collection.md "Submissions:CollectionEntity/Collection"), which reifies them.For temporary membership, the TimeIndexedMembership should be used. |
|  Scenarios: |  The Louvre Aegyptian collection. |
|  Known Uses: |  |
|  Web References: |  |
|  Other References: |  |
|  Examples (OWL files): | <li><a class="external free" href="http://www.ontologydesignpatterns.org/cp/examples/collectionentity/ISTC.owl" rel="nofollow" title="http://www.ontologydesignpatterns.org/cp/examples/collectionentity/ISTC.owl">http://www.ontologydesignpatterns.org/cp/examples/collectionentity/ISTC.owl</a></li> |
|  Extracted From: | <li><a class="external free" href="http://www.ontologydesignpatterns.org/ont/dul/DUL.owl" rel="nofollow" title="http://www.ontologydesignpatterns.org/ont/dul/DUL.owl">http://www.ontologydesignpatterns.org/ont/dul/DUL.owl</a></li> |
|  Reengineered From: |  |
|  Has Components: |  |
|  Specialization Of: |  |
|  Related CPs: |  |


  




#  Elements


_The __CollectionEntity__ Content OP locally defines the following ontology elements:_




[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __Collection__ (owl:Class) Any container for entities that share one or more common properties. E.g. _stone objects_, _the nurses_, _the Louvre Aegyptian collection_. A collection is not a logical class: a collection is a first-order entity, while a class is a second-order one. 



 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[Collection](../Collection/Collection.md "Submissions:CollectionEntity/Collection") page_

[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __Entity__ (owl:Class) Anything: real, possible, or imaginary, which some modeller wants to talk about for some purpose. 



 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[Entity](./CollectionEntity.md "Submissions:CollectionEntity/Entity") page_

[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasMember__ (owl:ObjectProperty) A relation between collections and entities, e.g. 'my collection of saxophones includes an old Adolphe Sax original alto' (i.e. my collection has member an Adolphe Sax alto). The object property  [isMemberOf](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/isMemberOf.md "Submissions:CollectionEntity/isMemberOf") is its inverse. 



 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasMember](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/hasMember.md "Submissions:CollectionEntity/hasMember") page_

[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isMemberOf__ (owl:ObjectProperty) The inverse of  [hasMember](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/hasMember.md "Submissions:CollectionEntity/hasMember"). 



 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isMemberOf](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/isMemberOf.md "Submissions:CollectionEntity/isMemberOf") page_
#  Additional information


#  Scenarios



__Scenarios about CollectionEntity__
* Aldo, Alfio and Valentina are members of the STLab. [>>>](./AgentRole/Scenario_1.md "http://ontologydesignpatterns.org/wiki/Submissions:CollectionEntity/Scenario_1")


#  Reviews



__Reviews about CollectionEntity__
There is no review about this proposal.
This revision (revision ID __9075__) takes in account the reviews: [ValentinaPresutti about CollectionEntity](http://ontologydesignpatterns.org/wiki/index.php?title=Reviews:ValentinaPresutti_about_CollectionEntity&action=edit&redlink=1 "Reviews:ValentinaPresutti about CollectionEntity (not yet written)")


Other info at [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:CollectionEntity&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:CollectionEntity&action=evaluation")




  




#  Modeling issues



__Modeling issues about CollectionEntity__
There is no Modeling issue related to this proposal.




  




#  References
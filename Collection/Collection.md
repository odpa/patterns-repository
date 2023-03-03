# 

 Graphical representation



__Diagram__ 





[![Image:Collectionentity.jpg](./Collectionentity.jpg)](../Image/Collectionentity.jpg.md "Image:Collectionentity.jpg")





# 

 General description




|  |  |
| --- | --- |
|  Name:  |  Collection  |
|  Submitted by:  | [AldoGangemi](../User/AldoGangemi.md "User:AldoGangemi")  |
|  Also Known As:  |  membership, collection entity  |
|  Intent:  |  To represent domain (not set theory) membership.  |
|  Domains:  | [General](../Community/General.md "Community:General")  |
|  Competency Questions:  | <li>       What things are contained in this collection (community      </li><li>       collective)? What collections this thing is member of?      </li> |
|  Solution description:  |  A class collection represents the concept of a set of entities (things). Things are members of the collection.  |
|  Reusable OWL Building Block:  | [http://www.ontologydesignpatterns.org/cp/owl/collectionentity.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=http://www.ontologydesignpatterns.org/cp/owl/collectionentity.owl&message=OWL building block&from_page_id=1229&update=)  (1538)  |
|  Consequences:  |  Collections and their members can be associated. Time-indexed membership cannot be represented though (you need a situation-based pattern).  |
|  Scenarios:  |  My saxophone collection includes a Mark VI tenor, a Balanced Action alto, and a Conn Transitional bari.  |
|  Known Uses:  |  |
|  Web References:  |  |
|  Other References:  |  |
|  Examples (OWL files):  |  |
|  Extracted From:  | <li><a class="external free" href="http://www.ontologydesignpatterns.org/ont/dul/DUL.owl" rel="nofollow" title="http://www.ontologydesignpatterns.org/ont/dul/DUL.owl">        http://www.ontologydesignpatterns.org/ont/dul/DUL.owl       </a></li> |
|  Reengineered From:  |  |
|  Has Components:  |  |
|  Specialization Of:  |  |
|  Related CPs:  | <li><a class="new" href="http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:TimeIndexedMembership&amp;action=edit&amp;redlink=1" title="Submissions:TimeIndexedMembership (not yet written)">        Submissions:TimeIndexedMembership       </a></li> |



  





# 

 Elements



_The
 __Collection__ 
 Content OP locally defines the following ontology elements:_ 





[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__hasMember__ 
 (owl:ObjectProperty) A relation between collections and entities, e.g. 'my collection of saxophones includes an old Adolphe Sax original alto' (i.e. my collection has member an Adolphe Sax alto).
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[hasMember](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/hasMember.md "Submissions:Collection/hasMember") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__isMemberOf__ 
 (owl:ObjectProperty)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[isMemberOf](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/isMemberOf.md "Submissions:Collection/isMemberOf") 
 page_ 



[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__Collection__ 
 (owl:Class) Any container for entities that share one or more common properties. E.g. "stone objects", "the nurses", "the Louvre Aegyptian collection". A collection is not a logical class: a collection is a first-order entity, while a class is a second-order one.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[Collection](./Collection.md "Submissions:Collection/Collection") 
 page_ 


# 

 Additional information



 The collection entity pattern. 
It is extracted from DOLCE-UltraLite by partial clone of elements.
 



 (type):
 [http://www.w3.org/2002/07/owl#Ontology](http://www.w3.org/2002/07/owl#Ontology "http://www.w3.org/2002/07/owl#Ontology") 




 (versionInfo): Created by Aldo Gangemi and Valentina Presutti
 



 (comment): The collection entity pattern. 
It is extracted from DOLCE-UltraLite by partial clone of elements.
 



 (imports):
 [http://www.ontologydesignpatterns.org/schemas/cpannotationschema.owl](http://www.ontologydesignpatterns.org/schemas/cpannotationschema.owl "http://www.ontologydesignpatterns.org/schemas/cpannotationschema.owl") 




# 

 Scenarios




__Scenarios about Collection__ 


 No scenario is added to this Content OP.
 




# 

 Reviews




__Reviews about Collection__ 


 There is no review about this proposal.
This revision (revision ID
 __9074__ 
 ) takes in account the reviews: none
 



 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Collection&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Collection&action=evaluation") 





  





# 

 Modeling issues




__Modeling issues about Collection__ 


 There is no Modeling issue related to this proposal.
 




  





# 

 References
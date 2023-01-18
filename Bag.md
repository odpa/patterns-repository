# 

 Graphical representation



__Diagram__ 





[![Image:Bag.jpg](../images/4/47/Bag.jpg)](../Image/Bag.jpg "Image:Bag.jpg")





# 

 General description




|  |  |
| --- | --- |
|  Name:  |  Bag  |
|  Submitted by:  | [EvaBlomqvist](../User/EvaBlomqvist "User:EvaBlomqvist")  |
|  Also Known As:  |  |
|  Intent:  |  To model bags of items (elements). The Bag is characterized by a collection that can have multiple copies of each object.  |
|  Domains:  | [General](../Community/General "Community:General")  , [Parts and Collections](../Community/Parts_and_Collections "Community:Parts and Collections")  |
|  Competency Questions:  | <li>       What bag is this item an element of?      </li><li>       What is the size of this bag?      </li><li>       What resource does this item refer to?      </li><li>       What are the items contained in this bag?      </li> |
|  Solution description:  |  The Bag is characterized by a collection that can have multiple copies of each object. This is performed through the Item entity. The Item is linking exactly one resource through the relationship itemContent.  |
|  Reusable OWL Building Block:  | [http://www.ontologydesignpatterns.org/cp/owl/bag.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=http://www.ontologydesignpatterns.org/cp/owl/bag.owl&message=OWL building block&from_page_id=3047&update=)  (810)  |
|  Consequences:  |  |
|  Scenarios:  |  |
|  Known Uses:  |  |
|  Web References:  |  |
|  Other References:  |  |
|  Examples (OWL files):  |  |
|  Extracted From:  | <li><a class="external free" href="http://swan.mindinformatics.org/ontologies/1.2/collections.owl" rel="nofollow" title="http://swan.mindinformatics.org/ontologies/1.2/collections.owl">        http://swan.mindinformatics.org/ontologies/1.2/collections.owl       </a></li> |
|  Reengineered From:  | <li><a class="external free" href="http://swan.mindinformatics.org/ontologies/1.2/collections.owl" rel="nofollow" title="http://swan.mindinformatics.org/ontologies/1.2/collections.owl">        http://swan.mindinformatics.org/ontologies/1.2/collections.owl       </a></li> |
|  Has Components:  | <li><a href="Submissions%253ACollectionEntity.html" title="Submissions:CollectionEntity">        Submissions:CollectionEntity       </a></li> |
|  Specialization Of:  |  |
|  Related CPs:  | <li><a href="Submissions%253AList.html" title="Submissions:List">        Submissions:List       </a></li> |



  





# 

 Elements



_The
 __Bag__ 
 Content OP locally defines the following ontology elements:_ 





[![Class](../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__Item__ 
 (owl:Class) Item - Element belonging to a Bag
 
[![](../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[Item](../Submissions/Bag/Item "Submissions:Bag/Item") 
 page_ 



[![ObjectProperty](../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__itemContent__ 
 (owl:ObjectProperty) itemContent - The link to the actual resource to which the item refers.
 
[![](../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[itemContent](../Submissions/Bag/itemContent "Submissions:Bag/itemContent") 
 page_ 



[![Class](../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__Bag__ 
 (owl:Class) Bag - Collection that can have a number of copies of each object
 
[![](../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[Bag](../Submissions/Bag/Bag "Submissions:Bag/Bag") 
 page_ 



[![ObjectProperty](../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__itemOf__ 
 (owl:ObjectProperty) item of - The link from an item to the Bag where it is contained
 
[![](../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[itemOf](../Submissions/Bag/itemOf "Submissions:Bag/itemOf") 
 page_ 



[![ObjectProperty](../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasItem__ 
 (owl:ObjectProperty) has item - The link to every item of the Bag
 
[![](../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasItem](../Submissions/Bag/hasItem "Submissions:Bag/hasItem") 
 page_ 



[![DatatypeProperty](../images/thumb/a/a5/DatatypeProperty.gif/20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif "DatatypeProperty")
__size__ 
 (owl:DatatypeProperty) size - The number of items belonging to a collection
 
[![](../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[size](../Submissions/Bag/size "Submissions:Bag/size") 
 page_ 


# 

 Additional information



 The Bag is characterized by a collection that can have multiple copies of each object. This is performed through the Item entity. The Item is linking exaclty one resource through the relationship itemContent.
 



  

 The collections ontology (part of the SWAN ontologies) that this pattern is based on was created by Paolo Ciccarese - Massachusetts General Hospital/Harvard Medical School, and Marco Ocana - Balboa Systems Inc. The original ontologies, and related information, are available under a
 [Creative Commons License](http://creativecommons.org/licenses/by/1.0/ "http://creativecommons.org/licenses/by/1.0/") 
 .
 



# 

 Scenarios




__Scenarios about Bag__ 


 No scenario is added to this Content OP.
 




# 

 Reviews




__Reviews about Bag__ 


 There is no review about this proposal.
This revision (revision ID
 __10367__ 
 ) takes in account the reviews: none
 



 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Bag&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Bag&action=evaluation") 





  





# 

 Modeling issues




__Modeling issues about Bag__ 


 There is no Modeling issue related to this proposal.
 




  





# 

 References
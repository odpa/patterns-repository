# 

 Graphical representation



__Diagram__ 





[![Image:constituency.jpg](../images/2/24/Constituency.jpg)](../Image/Constituency.jpg "Image:constituency.jpg")





# 

 General description




|  |  |
| --- | --- |
|  Name:  |  constituency  |
|  Submitted by:  | [ValentinaPresutti](../User/ValentinaPresutti "User:ValentinaPresutti")  |
|  Also Known As:  |  |
|  Intent:  |  To represent the constituents of a layered structure.  |
|  Domains:  | [Parts and Collections](../Community/Parts_and_Collections "Community:Parts and Collections")  |
|  Competency Questions:  | <li>       Which are the constituents of this entity?      </li><li>       What does this entity is constituent of?      </li> |
|  Solution description:  |  -  |
|  Reusable OWL Building Block:  | [http://www.ontologydesignpatterns.org/cp/owl/constituency.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=http://www.ontologydesignpatterns.org/cp/owl/constituency.owl&message=OWL building block&from_page_id=276&update=)  (732)  |
|  Consequences:  |  A desirable advantage of this CP is that we are able to talk e.g. of physical constituents of  non-physical objects (e.g. systems), while this is typically impossible in terms of parts. This Content OP has to be distinguished from [part of](../Submissions/PartOf "Submissions:PartOf")  , [collection entity](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:CollectionEntiy&action=edit&redlink=1 "Submissions:CollectionEntiy (not yet written)")  , and [componency](../Submissions/Componency "Submissions:Componency")  Content OPs.  |
|  Scenarios:  |  Different types of wood constitute this table.  |
|  Known Uses:  |  |
|  Web References:  |  |
|  Other References:  |  |
|  Examples (OWL files):  |  |
|  Extracted From:  | <li><a class="external free" href="http://www.loa-cnr.it/ontologies/DUL.owl" rel="nofollow" title="http://www.loa-cnr.it/ontologies/DUL.owl">        http://www.loa-cnr.it/ontologies/DUL.owl       </a></li> |
|  Reengineered From:  |  |
|  Has Components:  |  |
|  Specialization Of:  |  |
|  Related CPs:  |  |



  





# 

 Elements



_The
 __Constituency__ 
 Content OP locally defines the following ontology elements:_ 






[![Class](../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__Entity__ 
 (owl:Class) Anything: real, possible, or imaginary, which some modeller wants to talk about for some purpose.
 



[![](../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[Entity](../Submissions/Constituency/Entity "Submissions:Constituency/Entity") 
 page_ 




[![ObjectProperty](../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasConstituent__ 
 (owl:ObjectProperty) Constituency depends on some layering of the world described by the ontology. 
For example, scientiﬁc granularity (e.g. body-organ-tissue-cell) or ontological 'strata' (e.g. social-mental-biological-physical) are typical layerings. Intuitively, a constituent is a part belonging to a lower 
layer. Since layering is actually a partition of the world described by the ontology, constituents are not properly classiﬁed as parts, although this kindship can be intuitive for common sense. Example of constituents include the wood pieces constituting a table, the persons constituting a social system, the 
molecules constituting a person, the atoms constituting a river, etc. In all these examples, we notice a typical discontinuity between the constituted and the constituent object: e.g. a table is conceptualized at a functional layer, while wood pieces are conceptualized at a material layer, a social system is 
conceptualized at a different layer from the persons that constitute it, a person is conceptualized at a different layer from the molecules that constitute them, and a river is conceptualized at a different layer from the atoms that constitute it. The object property
 [isConstituentOf](../Submissions/Constituency/isConstituentOf "Submissions:Constituency/isConstituentOf") 
 is its inverse.
 



[![](../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasConstituent](../Submissions/Constituency/hasConstituent "Submissions:Constituency/hasConstituent") 
 page_ 




[![ObjectProperty](../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__isConstituentOf__ 
 (owl:ObjectProperty) The inverse of the
 [hasConstituent](../Submissions/Constituency/hasConstituent "Submissions:Constituency/hasConstituent") 
 object property.
 



[![](../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[isConstituentOf](../Submissions/Constituency/isConstituentOf "Submissions:Constituency/isConstituentOf") 
 page_ 


# 

 Additional information



# 

 Scenarios




__Scenarios about Constituency__ 


 No scenario is added to this Content OP.
 




# 

 Reviews




__Reviews about Constituency__ 


 There is no review about this proposal.
This revision (revision ID
 __9080__ 
 ) takes in account the reviews: none
 



 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Constituency&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Constituency&action=evaluation") 





  





# 

 Modeling issues




__Modeling issues about Constituency__ 


 There is no Modeling issue related to this proposal.
 




  





# 

 References
[![Image:partof.jpg](images/b/b4/Partof.jpg)](../Image/Partof.jpg "Image:partof.jpg")





# 

 General description




|  |  |
| --- | --- |
|  Name:  |  part of  |
|  Submitted by:  | [User:ValentinaPresutti](http://ontologydesignpatterns.org/wiki/index.php?title=User:User:ValentinaPresutti&action=edit&redlink=1 "User:User:ValentinaPresutti (not yet written)")  |
|  Also Known As:  |  |
|  Intent:  |  To represents entities and their parts.  |
|  Domains:  | [Community:Parts and Collections](http://ontologydesignpatterns.org/wiki/index.php?title=Community:Community:Parts_and_Collections&action=edit&redlink=1 "Community:Community:Parts and Collections (not yet written)")  |
|  Competency Questions:  | <li>       what is this entity part of?      </li><li>       What are the parts of this entity?      </li> |
|  Solution description:  |  |
|  Reusable OWL Building Block:  | [http://www.ontologydesignpatterns.org/cp/owl/partof.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=http://www.ontologydesignpatterns.org/cp/owl/partof.owl&message=OWL building block&from_page_id=266&update=)  (1134)  |
|  Consequences:  |  This Content OP allows designers to represent entities and their parts i.e., part-whole relations,  with transitivity. The temporal aspect of this relations cannot be expressed with this Content OP; in order to solve this issue the [time indexed part of](../Submissions/TimeIndexedPartOf "Submissions:TimeIndexedPartOf")  Content OP can be used. For an intransitive part-of Content OP see [componency](../Submissions/Componency "Submissions:Componency")  .  |
|  Scenarios:  |  Brain and heart are parts of the human body, substantia nigra is part of brain.  |
|  Known Uses:  |  |
|  Web References:  |  |
|  Other References:  |  |
|  Examples (OWL files):  | <li><a class="external free" href="http://www.ontologydesignpatterns.org/cp/examples/partof/humanbodyparts.owl" rel="nofollow" title="http://www.ontologydesignpatterns.org/cp/examples/partof/humanbodyparts.owl">        http://www.ontologydesignpatterns.org/cp/examples/partof/humanbodyparts.owl       </a></li> |
|  Extracted From:  | <li><a class="external free" href="http://www.loa-cnr.it/ontologies/DUL.owl" rel="nofollow" title="http://www.loa-cnr.it/ontologies/DUL.owl">        http://www.loa-cnr.it/ontologies/DUL.owl       </a></li> |
|  Reengineered From:  |  |
|  Has Components:  |  |
|  Specialization Of:  |  |
|  Related CPs:  |  |



  





# 

 Elements



_The
 __PartOf__ 
 Content OP locally defines the following ontology elements:_ 






[![Class](images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__Entity__ 
 (owl:Class) Anything: real, possible, or imaginary, which some modeller wants to talk about for some purpose.
 



[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[Entity](../Submissions/PartOf/Entity "Submissions:PartOf/Entity") 
 page_ 




[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasPart__ 
 (owl:ObjectProperty) A transitive relation expressing parthood between any entities, e.g.
 _the human body has a brain as part_ 
 . When specializing this Content OP, take care of restricting the domain and range appropriately, since it could be counterintuitive to use this relation arbitrarily, e.g. between animals and planets. For an intransitive part-of Content OP, see
 [componency](../Submissions/Componency "Submissions:Componency") 
 .
 



[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasPart](../Submissions/PartOf/hasPart "Submissions:PartOf/hasPart") 
 page_ 




[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__isPartOf__ 
 (owl:ObjectProperty) A transitive relation expressing parthood between any entities, e.g.
 _brain is a part of the human body_ 
 . When specializing this Content OP, take care of restricting the domain and range appropriately, since it could be counterintuitive to use this relation arbitrarily, e.g. between animals and planets. For an intransitive part-of Content OP, see
 [componency](../Submissions/Componency "Submissions:Componency") 
 .
 



[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[isPartOf](../Submissions/PartOf/isPartOf "Submissions:PartOf/isPartOf") 
 page_ 


# 

 Reviews




__Reviews about PartOf__ 



|  Review article  | [Posted on](../Property/CreationDate "Property:CreationDate")  | [About revision (current is 2005)](../Property/ReviewAboutVersion "Property:ReviewAboutVersion")  |
| --- | --- | --- |
| [MargheritaSini about PartOf](../Community/MargheritaSini_about_PartOf "Community:MargheritaSini about PartOf")  |  2454687  8 August 2008  |  2005  2,005  |



 This revision (revision ID
 __2005__ 
 ) takes in account the reviews: none
 



 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:PartOf&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:PartOf&action=evaluation")
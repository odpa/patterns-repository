# 

 Graphical representation



__Diagram__ 





[![Image:partof.jpg](./Partof.jpg)](../Image/Partof.jpg.md "Image:partof.jpg")





# 

 General description




|  |  |
| --- | --- |
|  Name:  |  part of  |
|  Submitted by:  | [ValentinaPresutti](../User/ValentinaPresutti.md "User:ValentinaPresutti")  |
|  Also Known As:  |  part whole  |
|  Intent:  |  To represents entities and their parts.  |
|  Domains:  | [Parts and Collections](../Community/Parts_and_Collections.md "Community:Parts and Collections")  |
|  Competency Questions:  | <li>       what is this entity part of?      </li><li>       What are the parts of this entity?      </li> |
|  Solution description:  |  --  |
|  Reusable OWL Building Block:  | [http://www.ontologydesignpatterns.org/cp/owl/partof.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=http://www.ontologydesignpatterns.org/cp/owl/partof.owl&message=OWL building block&from_page_id=266&update=)  (1134)  |
|  Consequences:  |  This Content OP allows designers to represent entities and their parts i.e., part-whole relations,  with transitivity. The temporal aspect of this relations cannot be expressed with this Content OP; in order to solve this issue the [time indexed part of](../TimeIndexedPartOf/TimeIndexedPartOf.md "Submissions:TimeIndexedPartOf")  Content OP can be used. For an intransitive part-of Content OP see [componency](../Componency/Componency.md "Submissions:Componency")  .  |
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






[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__Entity__ 
 (owl:Class) Anything: real, possible, or imaginary, which some modeller wants to talk about for some purpose.
 



[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[Entity](../CollectionEntity/CollectionEntity.md "Submissions:PartOf/Entity") 
 page_ 




[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__hasPart__ 
 (owl:ObjectProperty) A transitive relation expressing parthood between any entities, e.g.
 _the human body has a brain as part_ 
 . When specializing this Content OP, take care of restricting the domain and range appropriately, since it could be counterintuitive to use this relation arbitrarily, e.g. between animals and planets. For an intransitive part-of Content OP, see
 [componency](../Componency/Componency.md "Submissions:Componency") 
 .
 



[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[hasPart](./An_Ontology_Design_Pattern_for_Activity_Reasoning/hasPart.md "Submissions:PartOf/hasPart") 
 page_ 




[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__isPartOf__ 
 (owl:ObjectProperty) A transitive relation expressing parthood between any entities, e.g.
 _brain is a part of the human body_ 
 . When specializing this Content OP, take care of restricting the domain and range appropriately, since it could be counterintuitive to use this relation arbitrarily, e.g. between animals and planets. For an intransitive part-of Content OP, see
 [componency](../Componency/Componency.md "Submissions:Componency") 
 .
 



[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[isPartOf](./An_Ontology_Design_Pattern_for_Activity_Reasoning/isPartOf.md "Submissions:PartOf/isPartOf") 
 page_ 


# 

 Additional information



# 

 Scenarios




__Scenarios about PartOf__ 


 No scenario is added to this Content OP.
 




# 

 Reviews




__Reviews about PartOf__ 



|  Review article  | [Posted on](../Property/CreationDate.md "Property:CreationDate")  | [About revision (current is 9109)](../Property/ReviewAboutVersion.md "Property:ReviewAboutVersion")  |
| --- | --- | --- |
| [MargheritaSini about PartOf](../Community/MargheritaSini_about_PartOf.md "Community:MargheritaSini about PartOf")  |  2454687  8 August 2008  |  2005  2,005  |



 This revision (revision ID
 __9109__ 
 ) takes in account the reviews: none
 



 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:PartOf&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:PartOf&action=evaluation") 





  





# 

 Modeling issues




__Modeling issues about PartOf__ 



|  Modeling issue  | [Competency question](../Property/CompetencyQuestion.md "Property:CompetencyQuestion")  | [Domains](../Property/Domain.md "Property:Domain")  |
| --- | --- | --- |
| [PharmaceuticalProducts Composition](../Community/PharmaceuticalProducts_Composition.md "Community:PharmaceuticalProducts Composition")  |  Which is the composition of a specific pharmaceutical product?  Which pharmaceutical products are composed by Ibuprofen?  Which pharmaceutical product are composed by less of 1 mg Ibuprofen?  |  |




  





# 

 References
# 

 Graphical representation



__Diagram__ 





[![Image:Description.jpg](./Description.jpg)](../Image/Description.jpg.md "Image:Description.jpg")





# 

 General description




|  |  |
| --- | --- |
|  Name:  |  Description  |
|  Submitted by:  | [ValentinaPresutti](../User/ValentinaPresutti.md "User:ValentinaPresutti")  |
|  Also Known As:  |  |
|  Intent:  |  To formally represent a conceptualization or a descriptive context.  |
|  Domains:  | [General](../Community/General.md "Community:General")  |
|  Competency Questions:  | <li>       Which are the assumptions under which a certain thing is described?      </li><li>       Which are the concepts involved in the description of a certain thing?      </li><li>       What is the interpretation of this case/event/observation?      </li> |
|  Solution description:  |  -  |
|  Reusable OWL Building Block:  | [http://www.ontologydesignpatterns.org/cp/owl/description.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=http://www.ontologydesignpatterns.org/cp/owl/description.owl&message=OWL building block&from_page_id=136&update=)  (820)  |
|  Consequences:  |  This CP allows the designer to represent both a (descriptive) context and the elements that characterize and are involved in that context.  |
|  Scenarios:  |  |
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
 __Description__ 
 Content OP locally defines the following ontology elements:_ 






[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__Description__ 
 (owl:Class) A description represents a conceptualization. It can be thought also as a descriptive
context that defines concepts in order to see a relational context out of a set of data or observations.
For example, a Plan is a description of some actions to be executed by agents in a certain way, with
certain parameters; a diagnosis is a description that provides an interpretation to a set of observed
entities, etc.
 



[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[Description](./Description.md "Submissions:Description/Description") 
 page_ 




[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__Concept__ 
 (owl:Class) A
 __concept__ 
 can be an idea, notion, role, or even a reified class, and is defined in a description.
Once defined, a concept can be used in other descriptions.
 



[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[Concept](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/hasMappedDomainConcept.md "Submissions:Description/Concept") 
 page_ 




[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__is defined in__ 
 (owl:ObjectProperty) A relation between a description and a concept, e.g. a workflow for a governmental
organization defines the role officer, or the Italian Traffic Law defines the role Vehicle. In order to be
used, a concept must be previously defined in another description. The
 [defines](./Description/defines.md "Submissions:Description/defines") 
 object property is its inverse.
 



[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[isDefinedIn](./Description/isDefinedIn.md "Submissions:Description/isDefinedIn") 
 page_ 




[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__is concept used in__ 
 (owl:ObjectProperty) a more generic relation holding between a description and a concept.
The
 [uses concept](./Description/usesConcept.md "Submissions:Description/usesConcept") 
 object property is its inverse.
 



[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[isConceptUsedIn](./Description/isConceptUsedIn.md "Submissions:Description/isConceptUsedIn") 
 page_ 




[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__defines__ 
 (owl:ObjectProperty) A relation between a
 [Description](./Description.md "Submissions:Description/Description") 
 and a
 [Concept](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/hasMappedDomainConcept.md "Submissions:Description/Concept") 
 , e.g. a Workflow for a governmental Organization defines the Role 'officer', or 'the Italian Traffic Law defines the role Vehicle'.
 [isDefinedIn](./Description/isDefinedIn.md "Submissions:Description/isDefinedIn") 
 is its inverse.
 



[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[defines](./Description/defines.md "Submissions:Description/defines") 
 page_ 




[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__uses concept__ 
 (owl:ObjectProperty) A generic relation holding between a
 [Description](./Description.md "Submissions:Description/Description") 
 and a
 [Concept](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/hasMappedDomainConcept.md "Submissions:Description/Concept") 
 . In order to be used, a Concept must be previously
 [defined in](./Description/isDefinedIn.md "Submissions:Description/isDefinedIn") 
 another Description. This last condition cannot be encoded for object properties in OWL.
 



[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[usesConcept](./Description/usesConcept.md "Submissions:Description/usesConcept") 
 page_ 


# 

 Additional information



# 

 Scenarios




__Scenarios about Description__ 


 No scenario is added to this Content OP.
 




# 

 Reviews




__Reviews about Description__ 


 There is no review about this proposal.
This revision (revision ID
 __9087__ 
 ) takes in account the reviews: none
 



 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Description&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Description&action=evaluation") 





  





# 

 Modeling issues




__Modeling issues about Description__ 



|  Modeling issue  | [Competency question](../Property/CompetencyQuestion.md "Property:CompetencyQuestion")  | [Domains](../Property/Domain.md "Property:Domain")  |
| --- | --- | --- |
| [Situation classification](../Community/Situation_classification.md "Community:Situation classification")  |  What situations satisfy a certain description? What descriptions can be (partly) satisfied by that situation? What situations (partly) satisfying a certain description can emerge out of this dataset?  |  |




  





# 

 References
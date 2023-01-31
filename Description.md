# 

 Graphical representation



__Diagram__ 





[![Image:Description.jpg](images/6/61/Description.jpg)](../Image/Description.jpg "Image:Description.jpg")





# 

 General description




|  |  |
| --- | --- |
|  Name:  |  Description  |
|  Submitted by:  | [ValentinaPresutti](../User/ValentinaPresutti "User:ValentinaPresutti")  |
|  Also Known As:  |  |
|  Intent:  |  To formally represent a conceptualization or a descriptive context.  |
|  Domains:  | [General](../Community/General "Community:General")  |
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






[![Class](images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__Description__ 
 (owl:Class) A description represents a conceptualization. It can be thought also as a descriptive
context that defines concepts in order to see a relational context out of a set of data or observations.
For example, a Plan is a description of some actions to be executed by agents in a certain way, with
certain parameters; a diagnosis is a description that provides an interpretation to a set of observed
entities, etc.
 



[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[Description](../Submissions/Description/Description "Submissions:Description/Description") 
 page_ 




[![Class](images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__Concept__ 
 (owl:Class) A
 __concept__ 
 can be an idea, notion, role, or even a reified class, and is defined in a description.
Once defined, a concept can be used in other descriptions.
 



[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[Concept](../Submissions/Description/Concept "Submissions:Description/Concept") 
 page_ 




[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__is defined in__ 
 (owl:ObjectProperty) A relation between a description and a concept, e.g. a workflow for a governmental
organization defines the role officer, or the Italian Traffic Law defines the role Vehicle. In order to be
used, a concept must be previously defined in another description. The
 [defines](../Submissions/Description/defines "Submissions:Description/defines") 
 object property is its inverse.
 



[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[isDefinedIn](../Submissions/Description/isDefinedIn "Submissions:Description/isDefinedIn") 
 page_ 




[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__is concept used in__ 
 (owl:ObjectProperty) a more generic relation holding between a description and a concept.
The
 [uses concept](../Submissions/Description/usesConcept "Submissions:Description/usesConcept") 
 object property is its inverse.
 



[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[isConceptUsedIn](../Submissions/Description/isConceptUsedIn "Submissions:Description/isConceptUsedIn") 
 page_ 




[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__defines__ 
 (owl:ObjectProperty) A relation between a
 [Description](../Submissions/Description/Description "Submissions:Description/Description") 
 and a
 [Concept](../Submissions/Description/Concept "Submissions:Description/Concept") 
 , e.g. a Workflow for a governmental Organization defines the Role 'officer', or 'the Italian Traffic Law defines the role Vehicle'.
 [isDefinedIn](../Submissions/Description/isDefinedIn "Submissions:Description/isDefinedIn") 
 is its inverse.
 



[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[defines](../Submissions/Description/defines "Submissions:Description/defines") 
 page_ 




[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__uses concept__ 
 (owl:ObjectProperty) A generic relation holding between a
 [Description](../Submissions/Description/Description "Submissions:Description/Description") 
 and a
 [Concept](../Submissions/Description/Concept "Submissions:Description/Concept") 
 . In order to be used, a Concept must be previously
 [defined in](../Submissions/Description/isDefinedIn "Submissions:Description/isDefinedIn") 
 another Description. This last condition cannot be encoded for object properties in OWL.
 



[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[usesConcept](../Submissions/Description/usesConcept "Submissions:Description/usesConcept") 
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



|  Modeling issue  | [Competency question](../Property/CompetencyQuestion "Property:CompetencyQuestion")  | [Domains](../Property/Domain "Property:Domain")  |
| --- | --- | --- |
| [Situation classification](../Community/Situation_classification "Community:Situation classification")  |  What situations satisfy a certain description? What descriptions can be (partly) satisfied by that situation? What situations (partly) satisfying a certain description can emerge out of this dataset?  |  |




  





# 

 References
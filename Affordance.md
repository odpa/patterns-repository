# 

 Graphical representation



__Diagram__ 





[![Image:Affordance.png](public/images/b/b3/Affordance.png)](../Image/Affordance.png "Image:Affordance.png")





# 

 General description




|  |  |
| --- | --- |
|  Name:  |  Affordance  |
|  Submitted by:  | [AndreaNuzzolese](../User/AndreaNuzzolese "User:AndreaNuzzolese")  |
|  Also Known As:  |  |
|  Intent:  |  To represent the model for supporting the action selection mechanism.  |
|  Domains:  |  |
|  Competency Questions:  | <li>       Which is the strength of an Affordance?      </li> Which tasks are afforded in a certain situation?How should an agent behave in a certain situation?Which are the parameters involved in certain task?  |
|  Solution description:  |  The Afforndance ODP relies on the descriptions and situations ODP, and is combined with a frame-based representation scheme. This allows to extend the notion of affordance not only to physical objects, but also complex situations afford actions.  |
|  Reusable OWL Building Block:  | [http://www.ontologydesignpatterns.org/ont/mario/affordance.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=http://www.ontologydesignpatterns.org/ont/mario/affordance.owl&message=OWL building block&from_page_id=4130&update=)  (581)  |
|  Consequences:  |  |
|  Scenarios:  |  |
|  Known Uses:  |  |
|  Web References:  |  |
|  Other References:  |  |
|  Examples (OWL files):  |  |
|  Extracted From:  | <li><a class="external free" href="http://www.ontologydesignpatterns.org/ont/dul/DUL.owl" rel="nofollow" title="http://www.ontologydesignpatterns.org/ont/dul/DUL.owl">        http://www.ontologydesignpatterns.org/ont/dul/DUL.owl       </a></li> |
|  Reengineered From:  |  |
|  Has Components:  |  |
|  Specialization Of:  |  |
|  Related CPs:  |  |



  





# 

 Elements



_The
 __Affordance__ 
 Content OP locally defines the following ontology elements:_ 





[![ObjectProperty](public/images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasParameter__ 
 (owl:ObjectProperty) It associates the Task with its parameters.
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasParameter](../Submissions/Affordance/hasParameter "Submissions:Affordance/hasParameter") 
 page_ 



[![ObjectProperty](public/images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasTask__ 
 (owl:ObjectProperty) It associates an Affordance to the Task it refers to.
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasTask](../Submissions/Affordance/hasTask "Submissions:Affordance/hasTask") 
 page_ 



[![ObjectProperty](public/images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__holds__ 
 (owl:ObjectProperty) It associates an Affordance with the Frame in which it holds.
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[holds](../Submissions/Affordance/holds "Submissions:Affordance/holds") 
 page_ 



[![ObjectProperty](public/images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__isHeldBy__ 
 (owl:ObjectProperty) It associates a Frame with the Affordance it enables.
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[isHeldBy](../Submissions/Affordance/isHeldBy "Submissions:Affordance/isHeldBy") 
 page_ 



[![DatatypeProperty](public/images/thumb/a/a5/DatatypeProperty.gif/20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif "DatatypeProperty")
__affordanceStrength__ 
 (owl:DatatypeProperty) It encodes the strength of the Affordance.
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[affordanceStrength](../Submissions/Affordance/affordanceStrength "Submissions:Affordance/affordanceStrength") 
 page_ 



[![Class](public/images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__Affordance__ 
 (owl:Class) An affordance is modelled in DnS fashion and is an n-ary that relates state of the world (i.e., situations) to tasks according to specific weights or affordance strengths.
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[Affordance](../Submissions/Affordance/Affordance "Submissions:Affordance/Affordance") 
 page_ 



[![Class](public/images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__Frame__ 
 (owl:Class)
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[Frame](../Submissions/Affordance/Frame "Submissions:Affordance/Frame") 
 page_ 



[![Class](public/images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__Situation__ 
 (owl:Class) A state of the world.
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[Situation](../Submissions/Affordance/Situation "Submissions:Affordance/Situation") 
 page_ 



[![Class](public/images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__TaskParameter__ 
 (owl:Class) A parameter of a task.
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[TaskParameter](../Submissions/Affordance/TaskParameter "Submissions:Affordance/TaskParameter") 
 page_ 


# 

 Additional information



# 

 Scenarios




__Scenarios about Affordance__ 


 No scenario is added to this Content OP.
 




# 

 Reviews




__Reviews about Affordance__ 


 There is no review about this proposal.
This revision (revision ID
 __12749__ 
 ) takes in account the reviews: none
 



 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Affordance&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Affordance&action=evaluation") 





  





# 

 Modeling issues




__Modeling issues about Affordance__ 


 There is no Modeling issue related to this proposal.
 




  





# 

 References
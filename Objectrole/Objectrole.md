# 

 Graphical representation



__Diagram__ 





[![Image:objectrole.jpg](./Objectrole.jpg)](../Image/Objectrole.jpg.md "Image:objectrole.jpg")





# 

 General description




|  |  |
| --- | --- |
|  Name:  |  object role  |
|  Submitted by:  | [ValentinaPresutti](../User/ValentinaPresutti.md "User:ValentinaPresutti")  |
|  Also Known As:  |  |
|  Intent:  |  To represents objects and the roles they play.  |
|  Domains:  | [General](../Community/General.md "Community:General")  |
|  Competency Questions:  | <li>       what role does this object play?      </li><li>       which objects do play that role?      </li> |
|  Solution description:  |  -  |
|  Reusable OWL Building Block:  | [http://ontologydesignpatterns.org/cp/owl/objectrole.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=http://ontologydesignpatterns.org/cp/owl/objectrole.owl&message=OWL building block&from_page_id=222&update=)  (884)  |
|  Consequences:  |  it is possible to make assertions about roles, which are typically considered at the meta-  level of an ontology. Instances of [Submissions:Objectrole/Role](../AgentRole/AgentRole.md "Submissions:Objectrole/Role")  reify such elements, which are therefore put in the ordinary domain of an ontology. It is not possible to parametrize the classiﬁcation over different dimensions e.g., time, space, etc.  |
|  Scenarios:  |  This old glass is used as a ﬂower pot.  |
|  Known Uses:  |  |
|  Web References:  |  |
|  Other References:  |  |
|  Examples (OWL files):  |  |
|  Extracted From:  | <li><a class="external free" href="http://www.loa-cnr.it/ontologies/DUL.owl" rel="nofollow" title="http://www.loa-cnr.it/ontologies/DUL.owl">        http://www.loa-cnr.it/ontologies/DUL.owl       </a></li> |
|  Reengineered From:  |  |
|  Has Components:  |  |
|  Specialization Of:  | <li><a href="../Classification/Classification.md" title="Submissions:Classification">        Submissions:Classification       </a></li> |
|  Related CPs:  |  |



  





# 

 Elements



_The
 __Objectrole__ 
 Content OP locally defines the following ontology elements:_ 






[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__Role__ 
 (owl:Class) A
 [Concept](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/hasMappedDomainConcept.md "Submissions:Classification/Concept") 
 that classifies an
 [Object](../Object/Object.md "Submissions:Objectrole/Object") 
 .
 



[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[Role](../AgentRole/AgentRole.md "Submissions:Objectrole/Role") 
 page_ 




[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__Object__ 
 (owl:Class) Any physical, social, or mental object, or a substance.
 



[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[Object](../Object/Object.md "Submissions:Objectrole/Object") 
 page_ 




[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__isRoleOf__ 
 (owl:ObjectProperty) A relation between an
 [Object](../Object/Object.md "Submissions:Objectrole/Object") 
 and a
 [Role](../AgentRole/AgentRole.md "Submissions:Objectrole/Role") 
 , e.g. the 'student' is the role of 'John'.
 [hasRole](./Objectrole/hasRole.md "Submissions:Objectrole/hasRole") 
 is its inverse.
 



[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[isRoleOf](./Objectrole/isRoleOf.md "Submissions:Objectrole/isRoleOf") 
 page_ 




[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__hasRole__ 
 (owl:ObjectProperty) A relation between an
 [Object](../Object/Object.md "Submissions:Objectrole/Object") 
 and a
 [Role](../AgentRole/AgentRole.md "Submissions:Objectrole/Role") 
 , e.g. the person 'John' has role 'student'.
 [isRoleOf](./Objectrole/isRoleOf.md "Submissions:Objectrole/isRoleOf") 
 is its inverse.
 



[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[hasRole](./Objectrole/hasRole.md "Submissions:Objectrole/hasRole") 
 page_ 


# 

 Additional information



 The elements of this Content OP are added with the elements of its components and/or the elements of the Content OPs it is a specialization of.
 



# 

 Scenarios




__Scenarios about Objectrole__ 


 No scenario is added to this Content OP.
 




# 

 Reviews




__Reviews about Objectrole__ 


 There is no review about this proposal.
This revision (revision ID
 __9106__ 
 ) takes in account the reviews: none
 



 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Objectrole&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Objectrole&action=evaluation") 





  





# 

 Modeling issues




__Modeling issues about Objectrole__ 



|  Modeling issue  | [Competency question](../Property/CompetencyQuestion.md "Property:CompetencyQuestion")  | [Domains](../Property/Domain.md "Property:Domain")  |
| --- | --- | --- |
| [AcademicRoles](../Community/AcademicRoles.md "Community:AcademicRoles")  |  who plays a certain role within that project?  |  |




  





# 

 References
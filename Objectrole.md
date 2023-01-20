# 

 Graphical representation



__Diagram__ 





[![Image:objectrole.jpg](public/images/a/a4/Objectrole.jpg)](../Image/Objectrole.jpg "Image:objectrole.jpg")





# 

 General description




|  |  |
| --- | --- |
|  Name:  |  object role  |
|  Submitted by:  | [ValentinaPresutti](../User/ValentinaPresutti "User:ValentinaPresutti")  |
|  Also Known As:  |  |
|  Intent:  |  To represents objects and the roles they play.  |
|  Domains:  | [General](../Community/General "Community:General")  |
|  Competency Questions:  | <li>       what role does this object play?      </li><li>       which objects do play that role?      </li> |
|  Solution description:  |  -  |
|  Reusable OWL Building Block:  | [http://ontologydesignpatterns.org/cp/owl/objectrole.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=http://ontologydesignpatterns.org/cp/owl/objectrole.owl&message=OWL building block&from_page_id=222&update=)  (884)  |
|  Consequences:  |  it is possible to make assertions about roles, which are typically considered at the meta-  level of an ontology. Instances of [Submissions:Objectrole/Role](../Submissions/Objectrole/Role "Submissions:Objectrole/Role")  reify such elements, which are therefore put in the ordinary domain of an ontology. It is not possible to parametrize the classiﬁcation over different dimensions e.g., time, space, etc.  |
|  Scenarios:  |  This old glass is used as a ﬂower pot.  |
|  Known Uses:  |  |
|  Web References:  |  |
|  Other References:  |  |
|  Examples (OWL files):  |  |
|  Extracted From:  | <li><a class="external free" href="http://www.loa-cnr.it/ontologies/DUL.owl" rel="nofollow" title="http://www.loa-cnr.it/ontologies/DUL.owl">        http://www.loa-cnr.it/ontologies/DUL.owl       </a></li> |
|  Reengineered From:  |  |
|  Has Components:  |  |
|  Specialization Of:  | <li><a href="Submissions%253AClassification.html" title="Submissions:Classification">        Submissions:Classification       </a></li> |
|  Related CPs:  |  |



  





# 

 Elements



_The
 __Objectrole__ 
 Content OP locally defines the following ontology elements:_ 






[![Class](public/images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__Role__ 
 (owl:Class) A
 [Concept](../Submissions/Classification/Concept "Submissions:Classification/Concept") 
 that classifies an
 [Object](../Submissions/Objectrole/Object "Submissions:Objectrole/Object") 
 .
 



[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[Role](../Submissions/Objectrole/Role "Submissions:Objectrole/Role") 
 page_ 




[![Class](public/images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__Object__ 
 (owl:Class) Any physical, social, or mental object, or a substance.
 



[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[Object](../Submissions/Objectrole/Object "Submissions:Objectrole/Object") 
 page_ 




[![ObjectProperty](public/images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__isRoleOf__ 
 (owl:ObjectProperty) A relation between an
 [Object](../Submissions/Objectrole/Object "Submissions:Objectrole/Object") 
 and a
 [Role](../Submissions/Objectrole/Role "Submissions:Objectrole/Role") 
 , e.g. the 'student' is the role of 'John'.
 [hasRole](../Submissions/Objectrole/hasRole "Submissions:Objectrole/hasRole") 
 is its inverse.
 



[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[isRoleOf](../Submissions/Objectrole/isRoleOf "Submissions:Objectrole/isRoleOf") 
 page_ 




[![ObjectProperty](public/images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasRole__ 
 (owl:ObjectProperty) A relation between an
 [Object](../Submissions/Objectrole/Object "Submissions:Objectrole/Object") 
 and a
 [Role](../Submissions/Objectrole/Role "Submissions:Objectrole/Role") 
 , e.g. the person 'John' has role 'student'.
 [isRoleOf](../Submissions/Objectrole/isRoleOf "Submissions:Objectrole/isRoleOf") 
 is its inverse.
 



[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasRole](../Submissions/Objectrole/hasRole "Submissions:Objectrole/hasRole") 
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



|  Modeling issue  | [Competency question](../Property/CompetencyQuestion "Property:CompetencyQuestion")  | [Domains](../Property/Domain "Property:Domain")  |
| --- | --- | --- |
| [AcademicRoles](../Community/AcademicRoles "Community:AcademicRoles")  |  who plays a certain role within that project?  |  |




  





# 

 References
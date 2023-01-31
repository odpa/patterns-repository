# 

 Graphical representation



__Diagram__ 





[![Image:taskrole.jpg](images/0/0c/Taskrole.jpg)](../Image/Taskrole.jpg "Image:taskrole.jpg")





# 

 General description




|  |  |
| --- | --- |
|  Name:  |  role task  |
|  Submitted by:  | [ValentinaPresutti](../User/ValentinaPresutti "User:ValentinaPresutti")  |
|  Also Known As:  |  task role  |
|  Intent:  |  To represent the assignment of tasks to roles  |
|  Domains:  | [Organization](../Community/Organization "Community:Organization")  , [Management](../Community/Management "Community:Management")  , [Scheduling](../Community/Scheduling "Community:Scheduling")  |
|  Competency Questions:  | <li>       What roles are this task of?      </li><li>       What tasks do have this role?      </li> |
|  Solution description:  |  This pattern is basic, and is used to connect intensional descriptions of actions (tasks) and objects (roles).  |
|  Reusable OWL Building Block:  | [http://www.ontologydesignpatterns.org/cp/owl/taskrole.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=http://www.ontologydesignpatterns.org/cp/owl/taskrole.owl&message=OWL building block&from_page_id=445&update=)  (730)  |
|  Consequences:  |  This pattern allows to put roles in the domain of discourse. It does not allow to model time indexed task assignement.  |
|  Scenarios:  |  Students have the duty of giving exams  |
|  Known Uses:  |  |
|  Web References:  |  |
|  Other References:  |  |
|  Examples (OWL files):  | <li><a class="external free" href="http://www.ontologydesignpatterns.org/cp/examples/taskrole/ex1.owl" rel="nofollow" title="http://www.ontologydesignpatterns.org/cp/examples/taskrole/ex1.owl">        http://www.ontologydesignpatterns.org/cp/examples/taskrole/ex1.owl       </a></li> |
|  Extracted From:  | <li><a class="external free" href="http://www.ontologydesignpatterns.org/ont/dul/DUL.owl" rel="nofollow" title="http://www.ontologydesignpatterns.org/ont/dul/DUL.owl">        http://www.ontologydesignpatterns.org/ont/dul/DUL.owl       </a></li> |
|  Reengineered From:  |  |
|  Has Components:  |  |
|  Specialization Of:  |  |
|  Related CPs:  | <li><a href="../Submissions/AgentRole" title="Submissions:AgentRole">        Submissions:AgentRole       </a></li><li><a href="../Submissions/Description" title="Submissions:Description">        Submissions:Description       </a></li><li><a href="../Submissions/Objectrole" title="Submissions:Objectrole">        Submissions:Objectrole       </a></li> |



  





# 

 Elements



_The
 __Role task__ 
 Content OP locally defines the following ontology elements:_ 






[![Class](images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__role__ 
 (owl:Class) A concept that classifies an object. For example, the role developer classifies a person, the role server classifies a computer machine. A hasTask only Tasks. It is disjoint with Task.
 



[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[Role](../Submissions/Role_task/Role "Submissions:Role task/Role") 
 page_ 




[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__has task__ 
 (owl:ObjectProperty) A relation between roles and tasks, e.g. 'students have the duty of giving exams' (i.e. the Role 'student' hasTask the Task 'giving exams'). It is the inverse of
 [isTaskOf](../Submissions/Role_task/isTaskOf "Submissions:Role task/isTaskOf") 
 .
 



[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasTask](../Submissions/Role_task/hasTask "Submissions:Role task/hasTask") 
 page_ 




[![Class](images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__Task__ 
 (owl:Class) A piece of work to be done or undertaken. A Task is assigned to only
 [Roles](../Submissions/Role_task/Role "Submissions:Role task/Role") 
 through the property
 [isTaskOf](../Submissions/Role_task/isTaskOf "Submissions:Role task/isTaskOf") 
 .
 



[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[Task](../Submissions/Role_task/Task "Submissions:Role task/Task") 
 page_ 




[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__is task ok__ 
 (owl:ObjectProperty) A relation between
 [roles](../Submissions/Role_task/Role "Submissions:Role task/Role") 
 and
 [tasks](../Submissions/Role_task/Task "Submissions:Role task/Task") 
 , e.g. 'students have the duty of giving exams' (i.e. the Role 'student' hasTask the Task 'giving exams'). It is the inverse of
 [hasTask](../Submissions/Role_task/hasTask "Submissions:Role task/hasTask") 
 .
 



[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[isTaskOf](../Submissions/Role_task/isTaskOf "Submissions:Role task/isTaskOf") 
 page_ 


# 

 Additional information



 This CP is typically used in composition with the
 [agent role](../Submissions/AgentRole "Submissions:AgentRole") 
 CP, or
 [object role](../Submissions/Objectrole "Submissions:Objectrole") 
 CP. It can be also used with the
 [description](../Submissions/Description "Submissions:Description") 
 CP, when used for representing e.g., plans, workflows.
 



# 

 Scenarios




__Scenarios about Role task__ 


 No scenario is added to this Content OP.
 




# 

 Reviews




__Reviews about Role task__ 


 There is no review about this proposal.
This revision (revision ID
 __9119__ 
 ) takes in account the reviews: none
 



 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Role_task&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Role_task&action=evaluation") 





  





# 

 Modeling issues




__Modeling issues about Role task__ 


 There is no Modeling issue related to this proposal.
 




  





# 

 References
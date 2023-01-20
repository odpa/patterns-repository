# 

 Graphical representation



__Diagram__ 





[![Image:Taskexecution.jpg](public/images/d/db/Taskexecution.jpg)](../Image/Taskexecution.jpg "Image:Taskexecution.jpg")





# 

 General description




|  |  |
| --- | --- |
|  Name:  |  TaskExecution  |
|  Submitted by:  | [AldoGangemi](../User/AldoGangemi "User:AldoGangemi")  |
|  Also Known As:  |  |
|  Intent:  |  To represent actions through which tasks are executed.  |
|  Domains:  | [Organization](../Community/Organization "Community:Organization")  , [Management](../Community/Management "Community:Management")  , [Scheduling](../Community/Scheduling "Community:Scheduling")  , [Workflow](../Community/Workflow "Community:Workflow")  |
|  Competency Questions:  | <li>       which task is executed through this action?      </li> what actions can done in order to execute that task?  |
|  Solution description:  |  ----  |
|  Reusable OWL Building Block:  | [http://www.ontologydesignpatterns.org/cp/owl/taskexecution.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=http://www.ontologydesignpatterns.org/cp/owl/taskexecution.owl&message=OWL building block&from_page_id=766&update=)  (755)  |
|  Consequences:  |  This CP allows designers to make assertions on roles played by agents without involving the agents that play that roles, and vice versa. It allows to express neither the context type in which tasks are defined, not the particular context in which the action is carried out. Moreover, it does not allow to express the time at which the task is executed through the action (for actions that do not solely execute that certain task).  |
|  Scenarios:  |  She smiled at us, so obtaining the effect of making us feeling positive.  |
|  Known Uses:  |  |
|  Web References:  |  |
|  Other References:  |  |
|  Examples (OWL files):  |  |
|  Extracted From:  | <li><a class="external free" href="http://www.loa-cnr./ontologies/DUL.owl" rel="nofollow" title="http://www.loa-cnr./ontologies/DUL.owl">        http://www.loa-cnr./ontologies/DUL.owl       </a></li> |
|  Reengineered From:  |  |
|  Has Components:  | <li><a class="new" href="http://ontologydesignpatterns.org/wiki/Special:AddData/Content OP Proposal Form/Submissions:Submissions:AgentRole" title="Submissions:Submissions:AgentRole (not yet written)">        Submissions:Submissions:AgentRole       </a></li> |
|  Specialization Of:  |  |
|  Related CPs:  |  |



  





# 

 Elements



_The
 __TaskExecution__ 
 Content OP locally defines the following ontology elements:_ 





[![Class](public/images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__Action__ 
 (owl:Class) An Event with at least one Agent that isParticipantIn it, and that executes a Task that typically isDefinedIn a Plan, Workflow, Project, etc.
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[Action](../Submissions/TaskExecution/Action "Submissions:TaskExecution/Action") 
 page_ 



[![ObjectProperty](public/images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__executesTask__ 
 (owl:ObjectProperty) A relation between an action and a task, e.g. 'putting some water in a pot and putting the pot on a fire until the water starts bubbling' executes the task 'boiling'.
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[executesTask](../Submissions/TaskExecution/executesTask "Submissions:TaskExecution/executesTask") 
 page_ 



[![ObjectProperty](public/images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__isExecutedIn__ 
 (owl:ObjectProperty) A relation between an action and a task, e.g. 'putting some water in a pot and putting the pot on a fire until the water starts bubbling' executes the task 'boiling'.
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[isExecutedIn](../Submissions/TaskExecution/isExecutedIn "Submissions:TaskExecution/isExecutedIn") 
 page_ 


# 

 Additional information



 (type):
 [http://www.w3.org/2002/07/owl#Ontology](http://www.w3.org/2002/07/owl#Ontology "http://www.w3.org/2002/07/owl#Ontology") 




 (relatedCPs): The Nary Classification CP available at
 [http://www.ontologydesignpatterns.org/cp/owl/naryclassification.owl](http://www.ontologydesignpatterns.org/cp/owl/naryclassification.owl "http://www.ontologydesignpatterns.org/cp/owl/naryclassification.owl") 
 allows to represent temporariness of concepts that classify objects. By specializing naryclassification, it is possible to create a temporally-indexed version of taskexecution.
Its imported component taskrole.owl allows to express also the dependence between tasks and roles.
 



 (imports):
 [http://www.ontologydesignpatterns.org/cp/owl/taskrole.owl](http://www.ontologydesignpatterns.org/cp/owl/taskrole.owl "http://www.ontologydesignpatterns.org/cp/owl/taskrole.owl") 




 (imports):
 [http://www.ontologydesignpatterns.org/cp/owl/participation.owl](http://www.ontologydesignpatterns.org/cp/owl/participation.owl "http://www.ontologydesignpatterns.org/cp/owl/participation.owl") 




 (scenarios): She smiled at us, so obtaining the effect of making us feeling positive.
 



 (imports):
 [http://www.ontologydesignpatterns.org/cp/owl/agentrole.owl](http://www.ontologydesignpatterns.org/cp/owl/agentrole.owl "http://www.ontologydesignpatterns.org/cp/owl/agentrole.owl") 




 (versionInfo): Created by Aldo Gangemi
 



# 

 Scenarios




__Scenarios about TaskExecution__ 


 No scenario is added to this Content OP.
 




# 

 Reviews




__Reviews about TaskExecution__ 


 There is no review about this proposal.
This revision (revision ID
 __9131__ 
 ) takes in account the reviews: none
 



 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:TaskExecution&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:TaskExecution&action=evaluation") 





  





# 

 Modeling issues




__Modeling issues about TaskExecution__ 


 There is no Modeling issue related to this proposal.
 




  





# 

 References
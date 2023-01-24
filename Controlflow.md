# 

 Graphical representation



__Diagram__ 
_(this article has no graphical representation)_ 




# 

 General description




|  |  |
| --- | --- |
|  Name:  |  Controlflow  |
|  Submitted by:  | [AldoGangemi](../User/AldoGangemi "User:AldoGangemi")  |
|  Also Known As:  |  |
|  Intent:  |  To represent control flows: activation, branching, decisions, concurrency, etc.  |
|  Domains:  |  |
|  Competency Questions:  |  |
|  Solution description:  |  -  |
|  Reusable OWL Building Block:  | [http://www.ontologydesignpatterns.org/cp/owl/controlflow.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=http://www.ontologydesignpatterns.org/cp/owl/controlflow.owl&message=OWL building block&from_page_id=2253&update=)  (699)  |
|  Consequences:  |  |
|  Scenarios:  |  |
|  Known Uses:  |  |
|  Web References:  |  |
|  Other References:  |  |
|  Examples (OWL files):  |  |
|  Extracted From:  | <li><a class="external free" href="http://www.loa-cnr.it/ontologies/PlansLite.owl" rel="nofollow" title="http://www.loa-cnr.it/ontologies/PlansLite.owl">        http://www.loa-cnr.it/ontologies/PlansLite.owl       </a></li> |
|  Reengineered From:  |  |
|  Has Components:  |  |
|  Specialization Of:  |  |
|  Related CPs:  |  |



  





# 

 Elements



_The
 __Controlflow__ 
 Content OP locally defines the following ontology elements:_ 





[![Class](../../../../../../../../../../../../../../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__AbstractMergingTask__ 
 (owl:Class) An abstract merging task is a merging aimed at 'formally' joining the tasks that are direct successor to a case task.
 
 Differently from synchronization tasks, which are expected to be executed, abstract mergings only provide abstract boundaries to a task structure, because in a case task, only one action task is supposed to be executed.
 



[![](../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[AbstractMergingTask](../Submissions/Controlflow/AbstractMergingTask "Submissions:Controlflow/AbstractMergingTask") 
 page_ 



[![Class](../../../../../../../../../../../../../../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__ActionTask__ 
 (owl:Class) An action task is an elementary task that sequences non-planning activities, like: moving, exercising forces, gathering information, etc. Planning activites are mental events involving some rational event.
 
[![](../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[ActionTask](../Submissions/Controlflow/ActionTask "Submissions:Controlflow/ActionTask") 
 page_ 



[![Class](../../../../../../../../../../../../../../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__ActivationTask__ 
 (owl:Class) A control task aimed at starting an activity. It is specialized either by a beginning task or a reactivation task.
 
[![](../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[ActivationTask](../Submissions/Controlflow/ActivationTask "Submissions:Controlflow/ActivationTask") 
 page_ 



[![Class](../../../../../../../../../../../../../../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__BooleanCaseTask__ 
 (owl:Class) E.g. a yes-or-no case task, requiring exactly two deliberation tasks.
 
[![](../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[BooleanCaseTask](../Submissions/Controlflow/BooleanCaseTask "Submissions:Controlflow/BooleanCaseTask") 
 page_ 



[![Class](../../../../../../../../../../../../../../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__BranchingTask__ 
 (owl:Class) A task that articulates the plan into an ordered set of tasks.
 
[![](../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[BranchingTask](../Submissions/Controlflow/BranchingTask "Submissions:Controlflow/BranchingTask") 
 page_ 



[![Class](../../../../../../../../../../../../../../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__CaseTask__ 
 (owl:Class) A case task is a control task branched to a set of tasks that are not executable concurrently. In order to choose which task has to be undertaken, preliminary deliberation tasks should be executed, possibly based on information-gathering and decision rationales.
 
[![](../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[CaseTask](../Submissions/Controlflow/CaseTask "Submissions:Controlflow/CaseTask") 
 page_ 



[![Class](../../../../../../../../../../../../../../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__ConcurrencyTask__ 
 (owl:Class) A concurrent task is a task branched to a set of tasks executable concurrently -the sequenced perdurants can overlap-, which means that no deliberation task is performed in order to choose among them. A concurrent task has at least one successor synchronization task, which is aimed at waiting for the execution of all -except the optional ones- tasks direct successor to the concurrent -or any order, see below- one.The axioms cannot be expressed fully in OWL-DL (no value mapping available).
 
[![](../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[ConcurrencyTask](../Submissions/Controlflow/ConcurrencyTask "Submissions:Controlflow/ConcurrencyTask") 
 page_ 



[![Class](../../../../../../../../../../../../../../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__ControlTask__ 
 (owl:Class) A control task is a task executed during a planning activity, e.g. an activity aimed at (cognitively or via simulation) anticipating other activities. Therefore, control tasks have usually at least one direct successor task (the controlled one), with the exception of ending tasks.The reification of control constructs allows to represent procedural knowledge into the same ontology including controlled action. Besides conceptual transparency and independency from a particular grounding system, a further advantage is enabling the representation of coordination tasks. For example, a manager that coordinates the execution of several related activities can be represented as a role with a responsibility (duty+right) towards some complex task.
 
[![](../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[ControlTask](../Submissions/Controlflow/ControlTask "Submissions:Controlflow/ControlTask") 
 page_ 



[![Class](../../../../../../../../../../../../../../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__DecisionActivity__ 
 (owl:Class) An activity related to planning. It is supposed to execute a 'case task', and can contain an information gathering activity.
 
[![](../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[DecisionActivity](../Submissions/Controlflow/DecisionActivity "Submissions:Controlflow/DecisionActivity") 
 page_ 



[![Class](../../../../../../../../../../../../../../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__DeliberationState__ 
 (owl:Class) A state related to planning. It finalizes the execution of a 'deliberation task', and is preceded by a decision activity.
 
[![](../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[DeliberationState](../Submissions/Controlflow/DeliberationState "Submissions:Controlflow/DeliberationState") 
 page_ 



[![Class](../../../../../../../../../../../../../../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__DeliberationTask__ 
 (owl:Class) A deliberation task is a control task that is executed in a deliberation state (a decision taken during a case task execution, e.g. a yes or a no, or a known value, etc.).
 
[![](../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[DeliberationTask](../Submissions/Controlflow/DeliberationTask "Submissions:Controlflow/DeliberationTask") 
 page_ 



[![Class](../../../../../../../../../../../../../../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__EndingTask__ 
 (owl:Class) An ending task is a control task that has no successor tasks defined in the plan.
 
[![](../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[EndingTask](../Submissions/Controlflow/EndingTask "Submissions:Controlflow/EndingTask") 
 page_ 



[![Class](../../../../../../../../../../../../../../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__LoopTask__ 
 (owl:Class) A loop task is a control task that has as successor an action -or complex- task that sequences at least two distinct activities sharing a minimal common set of properties -they have a MinimalCommonType. Notice that MinimalCommonType cannot be formalised as a first-order predicate, and then neither in OWL-DL. It can be considered a trivial guideline: when sequencing looped actions, choose a definite action class from the ground ontology.
 
 Some relations typically hold for loop tasks. Exit condition can be used to state what deliberation task causes to exit the cycle; iteration interval can be used to state how much time should be taken by each iteration of the looped activity; iteration cardinality can be used to state how many times the action should be repeated.
 



[![](../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[LoopTask](../Submissions/Controlflow/LoopTask "Submissions:Controlflow/LoopTask") 
 page_ 



[![Class](../../../../../../../../../../../../../../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__MergingTask__ 
 (owl:Class) A task that joins a set of tasks after a branching.
 
[![](../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[MergingTask](../Submissions/Controlflow/MergingTask "Submissions:Controlflow/MergingTask") 
 page_ 



[![Class](../../../../../../../../../../../../../../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__SynchroTask__ 
 (owl:Class) A synchronization task is a merging aimed at waiting for the execution of all (except the optional ones) tasks that are direct successor to a concurrent or any order task.
 
[![](../../../../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[SynchroTask](../Submissions/Controlflow/SynchroTask "Submissions:Controlflow/SynchroTask") 
 page_ 


# 

 Additional information



# 

 Scenarios




__Scenarios about Controlflow__ 


 No scenario is added to this Content OP.
 




# 

 Reviews




__Reviews about Controlflow__ 


 There is no review about this proposal.
This revision (revision ID
 __9085__ 
 ) takes in account the reviews: none
 



 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Controlflow&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Controlflow&action=evaluation") 





  





# 

 Modeling issues




__Modeling issues about Controlflow__ 


 There is no Modeling issue related to this proposal.
 




  





# 

 References
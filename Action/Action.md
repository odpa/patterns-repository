# 

 Graphical representation



__Diagram__ 





[![Image:Action.jpg](./Action.jpg)](../Image/Action.jpg.md "Image:Action.jpg")





# 

 General description




|  |  |
| --- | --- |
|  Name:  |  Action  |
|  Submitted by:  | [EvaBlomqvist](../User/EvaBlomqvist.md "User:EvaBlomqvist")  |
|  Also Known As:  |  |
|  Intent:  |  The purpose of the pattern is to model actions that are proposed, planned, and performed or abandoned, together with their status and durations in time.  |
|  Domains:  | [Product development](../Community/Product_development.md "Community:Product development")  , [Business](../Community/Business.md "Community:Business")  , [General](../Community/General.md "Community:General")  |
|  Competency Questions:  | <li>       What actions is this action dependent on?      </li><li>       When was this action started?      </li><li>       What are the actions contained in this plan?      </li><li>       What are the consequences of this action?      </li><li>       What is the status of this action?      </li><li>       When was this action completed?      </li><li>       What is the suspension time of this action?      </li> |
|  Solution description:  |  This pattern models an action class, and subclasses that represents different kinds of actions depending on their properties. It also includes properties of actions such as status and duration.  |
|  Reusable OWL Building Block:  | [http://www.ontology.se/odp/content/owl/Action.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=http://www.ontology.se/odp/content/owl/Action.owl&message=OWL building block&from_page_id=2522&update=)  (1211)  |
|  Consequences:  |  The pattern allows to represent different types of actions, e.g. implemented actions or suspended actions, but does not enforce any rules such as "if an action is an instance of the class of completed actions it has to have the status 'completed' ".  |
|  Scenarios:  |  The action of making coffee is dependent on the action of buying coffee., The action of making coffee is 'completed'., The consequence of making coffee is drinking coffee., I performed the action of making coffee between 9 and 9:05am this morning., I plan to make coffee tomorrow, and then I plan to have breakfast.  |
|  Known Uses:  |  |
|  Web References:  |  |
|  Other References:  |  |
|  Examples (OWL files):  |  |
|  Extracted From:  |  |
|  Reengineered From:  | <li>       'action' data model pattern      </li> |
|  Has Components:  |  |
|  Specialization Of:  | <li><a href="../Sequence/Sequence.md" title="Submissions:Sequence">        Submissions:Sequence       </a></li><li><a href="../SmartHome_TimeInterval/SmartHome_TimeInterval.md" title="Submissions:TimeInterval">        Submissions:TimeInterval       </a></li> |
|  Related CPs:  |  |



  





# 

 Elements



_The
 __Action__ 
 Content OP locally defines the following ontology elements:_ 





[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__Action__ 
 (owl:Class) The process of doing something. An action is performed by an agent. An action can be proposed (proposed actions make up a plan), implemented or abandoned, and it has a status and possibly one or more suspension periods. Actions can have consequences and can be dependent on other actions, e.g. the action of pouring water from a cup is dependent on the action to first fill the cup with water.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[Action](./Action.md "Submissions:Action/Action") 
 page_ 



[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__Action\_status__ 
 (owl:Class) The different values the status of an action can take. A possible set of status values could be {proposed, ongoing, completed, abandoned}.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[Action\_status](./Action/Action_status.md "Submissions:Action/Action status") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__has\_status__ 
 (owl:ObjectProperty) A property that can be used to relate an action instance to its current status. For example, we could represent the fact that "I finished making coffee".
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[has\_status](./Action/has_status.md "Submissions:Action/has status") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__is\_consequence\_of__ 
 (owl:TransitiveProperty) A causal relation between actions, i.e. one action is the cause of another action. For example, the action of "swimming" is a consequence of "jumping into deep water".
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[is\_consequence\_of](./Action/is_consequence_of.md "Submissions:Action/is consequence of") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__is\_dependent\_on__ 
 (owl:TransitiveProperty) A transitive property for representing other types of dependencies between actions (other than the consequence one). For example, "swimming" is dependent on the action "getting into the water", but it is not necessarily a consequence (we may be able to also walk if the water is shallow).
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[is\_dependent\_on](./Action/is_dependent_on.md "Submissions:Action/is dependent on") 
 page_ 



[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__Plan__ 
 (owl:Class) A set of proposed actions and the sequence in which to perform them.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[Plan](../BasicPlan/BasicPlan.md "Submissions:Action/Plan") 
 page_ 



[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__Suspension__ 
 (owl:Class) The time interval within which an action is (temporarily or permanently) suspended.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[Suspension](./Action/Suspension.md "Submissions:Action/Suspension") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__has\_suspension__ 
 (owl:ObjectProperty) Property that can be used to relate an action instance to periods of suspension of that action. For example, we could represent that I took a lunch break between 1 and 2pm while preparing slides for a particular lecture.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[has\_suspension](./Action/has_suspension.md "Submissions:Action/has suspension") 
 page_ 



[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__Performance\_duration__ 
 (owl:Class) The time interval within which an action is performed.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[Performance\_duration](./Action/Performance_duration.md "Submissions:Action/Performance duration") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__is\_duration\_of__ 
 (owl:ObjectProperty) Property relating a time interval (a duration) to implemented actions, representing their execution time. For example, the property could be used to represent the fact that I started to make coffee at 9am this morning and finished 5 minutes later.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[is\_duration\_of](./Action/is_duration_of.md "Submissions:Action/is duration of") 
 page_ 



[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__Implemented\_action__ 
 (owl:Class) An implemented action is an action that has been started.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[Implemented\_action](http://ontologydesignpatterns.org/wiki/Submissions:Action/Implemented_action "Submissions:Action/Implemented action") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__is\_suspension\_of__ 
 (owl:ObjectProperty) Property that can be used to relate a suspension period of suspension to an action. For example, we could represent that I took a lunch break between 1 and 2pm while preparing slides for a particular lecture.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[is\_suspension\_of](./Action/is_suspension_of.md "Submissions:Action/is suspension of") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__plan\_composed\_of__ 
 (owl:ObjectProperty) Property relating a plan to the action(s) (proposed action) that it contains. For example, the plan for making coffee contains the actions "filling up the water container", "adding coffee", and "turning on the coffee machine".
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[plan\_composed\_of](./Action/plan_composed_of.md "Submissions:Action/plan composed of") 
 page_ 



[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__Proposed\_action__ 
 (owl:Class) A proposed action is an action that is in some plan, whether the plan is accepted or shared between agents or not. Proposed actions can be abandoned or implemented.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[Proposed\_action](http://ontologydesignpatterns.org/wiki/Submissions:Action/Proposed_action "Submissions:Action/Proposed action") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__is\_status\_of__ 
 (owl:ObjectProperty) A property that can be used to relate a status to instances of actions. For example, we could represent the fact that "I finished making coffee".
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[is\_status\_of](./Action/is_status_of.md "Submissions:Action/is status of") 
 page_ 



[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__Abandoned\_action__ 
 (owl:Class) An abandoned action is an action which is no longer going to be performed, regardless if it was previously just proposed or actually partly implemented. An abandoned action could be seen as an action that is permanently suspended.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[Abandoned\_action](http://ontologydesignpatterns.org/wiki/Submissions:Action/Abandoned_action "Submissions:Action/Abandoned action") 
 page_ 



[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__Completed\_action__ 
 (owl:Class) A completed action is an implemented action that has also been finalized.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[Completed\_action](http://ontologydesignpatterns.org/wiki/Submissions:Action/Completed_action "Submissions:Action/Completed action") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__has\_duration__ 
 (owl:ObjectProperty) Property relating implemented actions (actions that have been started) to their duration, which is a (possibly open-ended) time interval. For example, the property could be used to represent the fact that I started to make coffee at 9am this morning and finished 5 minutes later.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[has\_duration](./Action/has_duration.md "Submissions:Action/has duration") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__action\_proposed\_in__ 
 (owl:ObjectProperty) Property relating an action (proposed action) to the plan(s) in which it is contained. For example, the plan for making coffee contains the actions "filling up the water container", "adding coffee", and "turning on the coffee machine".
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[action\_proposed\_in](http://ontologydesignpatterns.org/wiki/Submissions:Action/action_proposed_in "Submissions:Action/action proposed in") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__has\_direct\_consequence__ 
 (owl:ObjectProperty) An intransitive subproperty of the causal consequence property, for representing direct consequences.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[has\_direct\_consequence](./Action/has_direct_consequence.md "Submissions:Action/has direct consequence") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__has\_consequence__ 
 (owl:TransitiveProperty) A causal relation between actions, i.e. one action is the cause of another action. For example, the action of "swimming" is a consequence of "jumping into deep water". The property is transitive.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[has\_consequence](./Action/has_consequence.md "Submissions:Action/has consequence") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__is\_direct\_consequence\_of__ 
 (owl:ObjectProperty) An intransitive subproperty of the causal consequence property, for representing direct consequences.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[is\_direct\_consequence\_of](./Action/is_direct_consequence_of.md "Submissions:Action/is direct consequence of") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__is\_directly\_dependent\_on__ 
 (owl:TransitiveProperty) Intransitive version of the dependency property, for representing direct dependency relations.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[is\_directly\_dependent\_on](./Action/is_directly_dependent_on.md "Submissions:Action/is directly dependent on") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__has\_direct\_dependent__ 
 (owl:TransitiveProperty) Intransitive version of the dependency property, for representing direct dependency relations.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[has\_direct\_dependent](./Action/has_direct_dependent.md "Submissions:Action/has direct dependent") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__has\_dependent__ 
 (owl:TransitiveProperty) A transitive property for representing other types of dependencies between actions (other than the consequence one). For example, "swimming" is dependent on the action "getting into the water", but it is not necessarily a consequence (we may be able to also walk if the water is shallow).
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[has\_dependent](./Action/has_dependent.md "Submissions:Action/has dependent") 
 page_ 


# 

 Additional information



# 

 Scenarios




__Scenarios about Action__ 


 No scenario is added to this Content OP.
 




# 

 Reviews




__Reviews about Action__ 


 There is no review about this proposal.
This revision (revision ID
 __9806__ 
 ) takes in account the reviews: none
 



 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Action&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Action&action=evaluation") 





  





# 

 Modeling issues




__Modeling issues about Action__ 


 There is no Modeling issue related to this proposal.
 




  





# 

 References
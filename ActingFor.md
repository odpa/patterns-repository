# 

 Graphical representation



__Diagram__ 
_(this article has no graphical representation)_ 




# 

 General description




|  |  |
| --- | --- |
|  Name:  |  ActingFor  |
|  Submitted by:  | [AldoGangemi](../User/AldoGangemi "User:AldoGangemi")  |
|  Also Known As:  |  |
|  Intent:  |  To represent that some agent is acting in order to forward the action of a social (non-physical) agent.  |
|  Domains:  |  |
|  Competency Questions:  | <li>       Who is working for which organization? Who is representing the company?      </li> |
|  Solution description:  |  -  |
|  Reusable OWL Building Block:  | [http://www.ontologydesignpatterns.org/cp/owl/actingfor.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=http://www.ontologydesignpatterns.org/cp/owl/actingfor.owl&message=OWL building block&from_page_id=2223&update=)  (907)  |
|  Consequences:  |  An ontology designer is able to express relations like delegation, working for, etc. It is not possible to express either time indexing (the situation pattern should be specialized to that purpose), nor the role or task, under which the social action is carried out by the physical agent (the descriptionandsituation pattern should be used instead).  |
|  Scenarios:  |  Matteo Sanvitale is working as an officer for CEMA s.r.l.  |
|  Known Uses:  |  |
|  Web References:  |  |
|  Other References:  |  |
|  Examples (OWL files):  |  |
|  Extracted From:  |  |
|  Reengineered From:  | <li><a class="external free" href="http://www.ontologydesignpatterns.org/ont/dul/DUL.owl" rel="nofollow" title="http://www.ontologydesignpatterns.org/ont/dul/DUL.owl">        http://www.ontologydesignpatterns.org/ont/dul/DUL.owl       </a></li> |
|  Has Components:  |  |
|  Specialization Of:  |  |
|  Related CPs:  |  |



  





# 

 Elements



_The
 __ActingFor__ 
 Content OP locally defines the following ontology elements:_ 





[![ObjectProperty](public/images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__actsFor__ 
 (owl:ObjectProperty) The relation holding between any Agent, and a SocialAgent. In principle, a SocialAgent requires at least one PhysicalAgent in order to act, but this dependency can be 'delegated'; e.g. a university can be acted for by a department, which on its turm is acted for by physical agents.
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[actsFor](../Submissions/ActingFor/actsFor "Submissions:ActingFor/actsFor") 
 page_ 



[![ObjectProperty](public/images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__actsThrough__ 
 (owl:ObjectProperty) The relation holding between a PhysicalAgent and a SocialAgent. In principle, a SocialAgent requires at least one PhysicalAgent in order to act, but this dependency can be 'delegated', e.g. a university can be acted for by a department, which is acted for by physical agents.
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[actsThrough](../Submissions/ActingFor/actsThrough "Submissions:ActingFor/actsThrough") 
 page_ 



[![Class](public/images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__Agent__ 
 (owl:Class) Any agentive Object , either physical (e.g. a whale, a robot, an oak), or social (e.g. a corporation, an institution, a community).
 
  





 Additional comment: a computational agent can be considered as a PhysicalAgent that realizes a certain class of algorithms (that can be considered as instances of InformationObject) that allow to obtain some behaviors that are considered typical of agents in general. For an ontology of computational objects based on DOLCE see e.g. and
 [http://www.loa-cnr.it/COS/COS.owl](http://www.loa-cnr.it/COS/COS.owl "http://www.loa-cnr.it/COS/COS.owl") 
 , and
 [http://www.loa-cnr.it/KCO/KCO.owl](http://www.loa-cnr.it/KCO/KCO.owl "http://www.loa-cnr.it/KCO/KCO.owl") 
 .
 



[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[Agent](../Submissions/ActingFor/Agent "Submissions:ActingFor/Agent") 
 page_ 



[![Class](public/images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__SocialAgent__ 
 (owl:Class) Any individual whose existence is granted simply by its social communicability and capability of action (through some PhysicalAgent).
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[SocialAgent](../Submissions/ActingFor/SocialAgent "Submissions:ActingFor/SocialAgent") 
 page_ 


# 

 Additional information



# 

 Scenarios




__Scenarios about ActingFor__ 


 No scenario is added to this Content OP.
 




# 

 Reviews




__Reviews about ActingFor__ 


 There is no review about this proposal.
This revision (revision ID
 __10789__ 
 ) takes in account the reviews: none
 



 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:ActingFor&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:ActingFor&action=evaluation") 





  





# 

 Modeling issues




__Modeling issues about ActingFor__ 


 There is no Modeling issue related to this proposal.
 




  





# 

 References
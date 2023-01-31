# 

 Graphical representation



__Diagram__ 





[![Image:Policies_ODP.png](images/8/8b/Policies_ODP.png)](../Image/Policies_ODP.png "Image:Policies_ODP.png")





# 

 General description




|  |  |
| --- | --- |
|  Name:  |  Policy  |
|  Submitted by:  | [PanagiotisMitzias](../User/PanagiotisMitzias "User:PanagiotisMitzias")  , [FabioCorubolo](../User/FabioCorubolo "User:FabioCorubolo")  , [EfstratiosKontopoulos](../User/EfstratiosKontopoulos "User:EfstratiosKontopoulos")  , [MarinaRiga](../User/MarinaRiga "User:MarinaRiga")  |
|  Also Known As:  |  |
|  Intent:  |  The pattern intends to model policies, their characteristics and their associated entities, such as processes and agents. This pattern has been developed by [MKLab](http://mklab.iti.gr/ "http://mklab.iti.gr/")  at CERTH/ITI and the University of Liverpool for the [PERICLES](http://www.pericles-project.eu/ "http://www.pericles-project.eu/")  FP7 project.  |
|  Domains:  | [General](../Community/General "Community:General")  |
|  Competency Questions:  | <li><p><i>         What are the main entities associated with a policy?        </i>        A policy is usually associated with:        <ul><li>          super/sub-policies         </li><li>          processes         </li><li>          agents         </li><li>          other entities         </li></ul></p></li>* _What are the main attributes of a policy?_  They are:	+ version+ language+ policy type+ requirement level+ implementation status+ automation status* _Where is a policy described?_  Statements are detailed text (formal or non- formal) definitions of the policy contents. |
|  Solution description:  |  The pattern’s main entity is a policy. Appropriate object properties connect the policy with significant attributes and other entities.  |
|  Reusable OWL Building Block:  | [http://mklab.iti.gr/pericles/Policy\_ODP.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=http://mklab.iti.gr/pericles/Policy_ODP.owl&message=OWL building block&from_page_id=4273&update=)  (565)  |
|  Consequences:  |  The Policy ODP is expected to facilitate the representation of the policy notion, which can be exploited in various domains. A well-established, comprehensible pattern will prove to be advantageous.  |
|  Scenarios:  | <li>       The policy has two subpolicies.      </li><li>       The policy is implemented by a certain process.      </li><li>       The policy is validated by a certain process.      </li><li>       The policy is assigned to John Smith.      </li><li>       The policy is fully automated.      </li> |
|  Known Uses:  |  |
|  Web References:  |  |
|  Other References:  |  |
|  Examples (OWL files):  |  |
|  Extracted From:  |  |
|  Reengineered From:  |  |
|  Has Components:  |  |
|  Specialization Of:  |  |
|  Related CPs:  |  |



  





# 

 Elements



_The
 __Policy__ 
 Content OP locally defines the following ontology elements:_ 





[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__assignedTo__ 
 (owl:ObjectProperty) Associates a policy to the agent that is responsible for the application of the policy (person or role).
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[assignedTo](../Submissions/Policy/assignedTo "Submissions:Policy/assignedTo") 
 page_ 



[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasAutomationStatus__ 
 (owl:ObjectProperty) Associates a policy with an automation level.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasAutomationStatus](../Submissions/Policy/hasAutomationStatus "Submissions:Policy/hasAutomationStatus") 
 page_ 



[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasImplementationStatus__ 
 (owl:ObjectProperty) Associates a policy with an implementation level.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasImplementationStatus](../Submissions/Policy/hasImplementationStatus "Submissions:Policy/hasImplementationStatus") 
 page_ 



[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasLanguage__ 
 (owl:ObjectProperty) Associates a policy with the language used for the policy definition.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasLanguage](../Submissions/Policy/hasLanguage "Submissions:Policy/hasLanguage") 
 page_ 



[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasPolicyType__ 
 (owl:ObjectProperty) Associates a policy with a policy type.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasPolicyType](../Submissions/Policy/hasPolicyType "Submissions:Policy/hasPolicyType") 
 page_ 



[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasRequirementLevel__ 
 (owl:ObjectProperty) Associates a policy with an requirement level.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasRequirementLevel](../Submissions/Policy/hasRequirementLevel "Submissions:Policy/hasRequirementLevel") 
 page_ 



[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasStatement__ 
 (owl:ObjectProperty) Associates a policy with a statement, which is a detailed definition of the policy contents.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasStatement](../Submissions/Policy/hasStatement "Submissions:Policy/hasStatement") 
 page_ 



[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasSubPolicy__ 
 (owl:ObjectProperty) Associates a policy to another policy that is contained in the initial.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasSubPolicy](../Submissions/Policy/hasSubPolicy "Submissions:Policy/hasSubPolicy") 
 page_ 



[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasValidationProcess__ 
 (owl:ObjectProperty) Associates a policy with a process that is used to validate the policy.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasValidationProcess](../Submissions/Policy/hasValidationProcess "Submissions:Policy/hasValidationProcess") 
 page_ 



[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasVersion__ 
 (owl:ObjectProperty) Defines a policy's version.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasVersion](../Submissions/Policy/hasVersion "Submissions:Policy/hasVersion") 
 page_ 



[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__implementedBy__ 
 (owl:ObjectProperty) Associates a policy with a process that is used to implement the policy.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[implementedBy](../Submissions/Policy/implementedBy "Submissions:Policy/implementedBy") 
 page_ 



[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__targetsEntity__ 
 (owl:ObjectProperty) Associates a policy with an entity that is subject to the policy.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[targetsEntity](../Submissions/Policy/targetsEntity "Submissions:Policy/targetsEntity") 
 page_ 



[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__targetsUsers__ 
 (owl:ObjectProperty) Associates a policy to the user community the policy has been designed for.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[targetsUsers](../Submissions/Policy/targetsUsers "Submissions:Policy/targetsUsers") 
 page_ 



[![Class](images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__AutomationStatus__ 
 (owl:Class) The level of automation of a policy. Specifies if a policy implementation requires human intervention. E.g. manual, automated with human intervention, automated with human validation, fully automated, etc.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[AutomationStatus](../Submissions/Policy/AutomationStatus "Submissions:Policy/AutomationStatus") 
 page_ 



[![Class](images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__Descriptor__ 
 (owl:Class) The various elements describing a policy.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[Descriptor](../Submissions/Policy/Descriptor "Submissions:Policy/Descriptor") 
 page_ 



[![Class](images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__ImplementationStatus__ 
 (owl:Class) The level of implementation of a policy. E.g. implemented, partially implemented, unimplemented, not-implementable, etc.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[ImplementationStatus](../Submissions/Policy/ImplementationStatus "Submissions:Policy/ImplementationStatus") 
 page_ 



[![Class](images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__Language__ 
 (owl:Class) The language used for the policy definition. E.g. natural language, ReAL, SPIN, etc.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[Language](../Submissions/Policy/Language "Submissions:Policy/Language") 
 page_ 



[![Class](images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__Policy__ 
 (owl:Class) A deliberate system of principles to guide decisions and achieve rational outcomes. A policy is a statement of intent, and is implemented as a procedure or protocol.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[Policy](../Submissions/Policy/Policy "Submissions:Policy/Policy") 
 page_ 



[![Class](images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__PolicyType__ 
 (owl:Class) The type of policy. Not all policies are equal; mandatory ones must be implemented to satisfy law or other requirements, others are aspirational, and most are met with the best possible effort. E.g. mandatory, legal requirement, aspirational, business driven, etc.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[PolicyType](../Submissions/Policy/PolicyType "Submissions:Policy/PolicyType") 
 page_ 



[![Class](images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__Process__ 
 (owl:Class) A sequence of interdependent and linked procedures which, at every stage, consume one or more resources (time, energy, machines, money) to convert inputs (data, material, parts, etc.) into outputs.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[Process](../Submissions/Policy/Process "Submissions:Policy/Process") 
 page_ 



[![Class](images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__RequirementLevel__ 
 (owl:Class) The level of a policy's compliance. E.g. must, must not, should, shoud not, may, etc.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[RequirementLevel](../Submissions/Policy/RequirementLevel "Submissions:Policy/RequirementLevel") 
 page_ 



[![Class](images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__Statement__ 
 (owl:Class) Detailed definition of the policy contents.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[Statement](../Submissions/Policy/Statement "Submissions:Policy/Statement") 
 page_ 



[![Class](images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__Version__ 
 (owl:Class) A policy's version
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[Version](../Submissions/Policy/Version "Submissions:Policy/Version") 
 page_ 


# 

 Additional information



# 

 Scenarios




__Scenarios about Policy__ 


 No scenario is added to this Content OP.
 




# 

 Reviews




__Reviews about Policy__ 


 There is no review about this proposal.
This revision (revision ID
 __13090__ 
 ) takes in account the reviews: none
 



 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Policy&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Policy&action=evaluation") 





  





# 

 Modeling issues




__Modeling issues about Policy__ 


 There is no Modeling issue related to this proposal.
 




  





# 

 References
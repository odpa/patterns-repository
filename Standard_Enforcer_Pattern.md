# 

 Graphical representation



__Diagram__ 





[![Image:Standard-enforcer-pattern.png](images/d/df/Standard-enforcer-pattern.png)](../Image/Standard-enforcer-pattern.png "Image:Standard-enforcer-pattern.png")





# 

 General description




|  |  |
| --- | --- |
|  Name:  |  Standard Enforcer Pattern  |
|  Submitted by:  | [MonikaSolanki](../User/MonikaSolanki "User:MonikaSolanki")  |
|  Also Known As:  |  SEP  |
|  Intent:  |  The remit of the SEP content pattern is to represent the relation between standards and the processes, operations, activities and services that enforce them, the domains they cater to and the scope of that specific process, operation, activity, service within the context of the domain.  |
|  Domains:  |  |
|  Competency Questions:  | <li>       1. Which are the standards enforced by this process?      </li><li>       2. Which processes enforce these standards ?      </li><li>       3. What is/are the domain level scope(s) of the standard?      </li><li>       4. Within the context of the domain what is the scope of the process to which the standard is applicable?      </li><li>       5. What are the prescribed guidelines for a standard?      </li><li>       6. Which prescribed guideline(s) of a standard does a specific process conform to?      </li> |
|  Solution description:  |  SEP provides a mechanism to ontologically declare the conformance of a  process with one or more standards. The pattern is flexible andcompositional. It can be exploited to include few or more guidelinesfrom multiple standards and can be easily combined with otherpatterns.  |
|  Reusable OWL Building Block:  | [http://windermere.aston.ac.uk/~monika/ontologies/Standards-Enforcer-Pattern.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=http://windermere.aston.ac.uk/~monika/ontologies/Standards-Enforcer-Pattern.owl&message=OWL building block&from_page_id=3343&update=)  (861)  |
|  Consequences:  |  The pattern can be applied to use cases in all those domains where a standard is enforced to regulate processes. The main advantage of this pattern is that it provides the capability to link processes, operations, activities and services to their governing standards in a generic and compositional manner. In some scenarios it is possible that a process or an operation does not enforce all prescribed guidelines but enforces atleast some. The pattern accounts for that through the definition of the process enforcing the standard.  |
|  Scenarios:  |  As an exemplifier for SEP, we present a use case from the domain of algal biomass production which depicts the application of SEP to an ontology that models algal biomass production. The Minimum Descriptive Language (MDL) standard proposed by the Algal Biomass Association is enforced by the production operation. MDL recommends a set of descriptive metrics to uniformly characterise the analysis of large scale algal operations. In this use case, the ontology defines the concepts and relationships for the operation and incorporates SEP by enforcing a guideline for measuring Carbon input to the operation.  |
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
 __Standard Enforcer Pattern__ 
 Content OP locally defines the following ontology elements:_ 





[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__enforcesGuideline__ 
 (owl:ObjectProperty)
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[enforcesGuideline](../Submissions/Standard_Enforcer_Pattern/enforcesGuideline "Submissions:Standard Enforcer Pattern/enforcesGuideline") 
 page_ 



[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__enforcesStandard__ 
 (owl:ObjectProperty)
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[enforcesStandard](../Submissions/Standard_Enforcer_Pattern/enforcesStandard "Submissions:Standard Enforcer Pattern/enforcesStandard") 
 page_ 



[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__guidelinePrescribedIn__ 
 (owl:ObjectProperty)
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[guidelinePrescribedIn](../Submissions/Standard_Enforcer_Pattern/guidelinePrescribedIn "Submissions:Standard Enforcer Pattern/guidelinePrescribedIn") 
 page_ 



[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasDomainScope__ 
 (owl:ObjectProperty)
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasDomainScope](../Submissions/Standard_Enforcer_Pattern/hasDomainScope "Submissions:Standard Enforcer Pattern/hasDomainScope") 
 page_ 



[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasProcessScope__ 
 (owl:ObjectProperty)
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasProcessScope](../Submissions/Standard_Enforcer_Pattern/hasProcessScope "Submissions:Standard Enforcer Pattern/hasProcessScope") 
 page_ 



[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__isEnforcedBy__ 
 (owl:ObjectProperty)
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[isEnforcedBy](../Submissions/Standard_Enforcer_Pattern/isEnforcedBy "Submissions:Standard Enforcer Pattern/isEnforcedBy") 
 page_ 



[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__prescribesGuideline__ 
 (owl:ObjectProperty)
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[prescribesGuideline](../Submissions/Standard_Enforcer_Pattern/prescribesGuideline "Submissions:Standard Enforcer Pattern/prescribesGuideline") 
 page_ 



[![Class](images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__DomainScope__ 
 (owl:Class) An entity that identifies the domain level scope of the standard
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[DomainScope](../Submissions/Standard_Enforcer_Pattern/DomainScope "Submissions:Standard Enforcer Pattern/DomainScope") 
 page_ 



[![Class](images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__Guideline__ 
 (owl:Class) An entity that defines the guideline that is part of a standard
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[Guideline](../Submissions/Standard_Enforcer_Pattern/Guideline "Submissions:Standard Enforcer Pattern/Guideline") 
 page_ 



[![Class](images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__Process__ 
 (owl:Class) An entity that defines a workflow, operation, activity or a service
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[Process](../Submissions/Standard_Enforcer_Pattern/Process "Submissions:Standard Enforcer Pattern/Process") 
 page_ 



[![Class](images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__ProcessEnforcingStandard__ 
 (owl:Class) A process/operation/activity or serrvice that enforces one or more standard.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[ProcessEnforcingStandard](../Submissions/Standard_Enforcer_Pattern/ProcessEnforcingStandard "Submissions:Standard Enforcer Pattern/ProcessEnforcingStandard") 
 page_ 



[![Class](images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__ProcessScope__ 
 (owl:Class) An entity that defines the scope of a process
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[ProcessScope](../Submissions/Standard_Enforcer_Pattern/ProcessScope "Submissions:Standard Enforcer Pattern/ProcessScope") 
 page_ 



[![Class](images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__Standard__ 
 (owl:Class) An entity that identifies a specification established through domain expert consensus that prescribes a set of rules and guidelines for a given context within the domain.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[Standard](../Submissions/Standard_Enforcer_Pattern/Standard "Submissions:Standard Enforcer Pattern/Standard") 
 page_ 


# 

 Additional information



 This ontology models the standards enforcer pattern (SEP). The main advantage of this pattern is that it provides the capability
to link processes operation and activities to their governing
standards in a generic way. The pattern can be applied to all those
use cases where a standard is enforced.
 



# 

 Scenarios




__Scenarios about Standard Enforcer Pattern__ 


 No scenario is added to this Content OP.
 




# 

 Reviews




__Reviews about Standard Enforcer Pattern__ 



|  Review article  | [Posted on](../Property/CreationDate "Property:CreationDate")  | [About revision (current is 11210)](../Property/ReviewAboutVersion "Property:ReviewAboutVersion")  |
| --- | --- | --- |
| [GerdGroener about Standard Enforcer Pattern](../Reviews/GerdGroener_about_Standard_Enforcer_Pattern "Reviews:GerdGroener about Standard Enforcer Pattern")  |  2456170  30 August 2012  |  11149  11,149  |
| [IonelVirgilPop about Standard Enforcer Pattern](../Community/IonelVirgilPop_about_Standard_Enforcer_Pattern "Community:IonelVirgilPop about Standard Enforcer Pattern")  |  2456164  24 August 2012  |  11149  11,149  |
| [BorisVillazón-Terrazas about Standard Enforcer Pattern](../Reviews/BorisVillazón-Terrazas_about_Standard_Enforcer_Pattern "Reviews:BorisVillazón-Terrazas about Standard Enforcer Pattern")  |  2456170  30 August 2012  |  11210  11,210  |



 This revision (revision ID
 __11210__ 
 ) takes in account the reviews: none
 



 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Standard_Enforcer_Pattern&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Standard_Enforcer_Pattern&action=evaluation") 





  





# 

 Modeling issues




__Modeling issues about Standard Enforcer Pattern__ 


 There is no Modeling issue related to this proposal.
 




  





# 

 References



  






|  |  Submission to event [WOP:2012](../WOP/2012 "WOP:2012")  |
| --- | --- |
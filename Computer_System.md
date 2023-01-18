# 

 Graphical representation



__Diagram__ 





[![Image:ComputerSystemODP Diagram.png](../images/a/ab/ComputerSystemODP_Diagram.png)](../Image/ComputerSystemODP_Diagram.png "Image:ComputerSystemODP Diagram.png")





# 

 General description




|  |  |
| --- | --- |
|  Name:  |  Computer System  |
|  Submitted by:  | [PanagiotisMitzias](../User/PanagiotisMitzias "User:PanagiotisMitzias")  , [EfstratiosKontopoulos](../User/EfstratiosKontopoulos "User:EfstratiosKontopoulos")  , [MarinaRiga](../User/MarinaRiga "User:MarinaRiga")  |
|  Also Known As:  |  |
|  Intent:  |  The pattern intends to model computer systems based on a hardware/software approach. This pattern has been developed by [MKLab](http://mklab.iti.gr/ "http://mklab.iti.gr/")  at CERTH/ITI and [Tate](http://www.tate.org.uk/ "http://www.tate.org.uk/")  for the [PERICLES](http://www.pericles-project.eu/ "http://www.pericles-project.eu/")  FP7 project.  |
|  Domains:  | [General](../Community/General "Community:General")  |
|  Competency Questions:  | <li><p><i>         What is currently installed in a computer?        </i>        A computer uses specific pieces of hardware and software.       </p></li>* _What software or hardware is required so that some other software or hardware can operate properly?_  This relationship is represented with properties requiresSoftware and requiresHardware.* _What software or hardware is compatible with other software or hardware?_  This is expressed via the isCompatibleWith relationship. |
|  Solution description:  |  The pattern represents a computer system, along with the involved software and hardware components. It also includes significant properties between these main entities.  |
|  Reusable OWL Building Block:  | [http://mklab.iti.gr/pericles/ComputerSystem\_ODP.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=http://mklab.iti.gr/pericles/ComputerSystem_ODP.owl&message=OWL building block&from_page_id=4312&update=)  (603)  |
|  Consequences:  |  The design pattern is expected to facilitate the creation of computer system domain ontologies that can be exploited in numerous fields. A well-established, comprehensible pattern will prove to be advantageous.  |
|  Scenarios:  | <li>       The computer uses Ubuntu 16.04.      </li><li>       The graphics card requires driver A.      </li><li>       The software is compatible with Windows 10.      </li><li>       The processor is compatible with motherboard B.      </li> |
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
 __Computer System__ 
 Content OP locally defines the following ontology elements:_ 





[![ObjectProperty](../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__isCompatibleWith__ 
 (owl:ObjectProperty) Represents the relationship of compatibility between two components.
 
[![](../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[isCompatibleWith](../Submissions/Computer_System/isCompatibleWith "Submissions:Computer System/isCompatibleWith") 
 page_ 



[![ObjectProperty](../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__requiresHardware__ 
 (owl:ObjectProperty) Indicates that an entity requires a certain piece of hardware to operate.
 
[![](../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[requiresHardware](../Submissions/Computer_System/requiresHardware "Submissions:Computer System/requiresHardware") 
 page_ 



[![ObjectProperty](../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__requiresSoftware__ 
 (owl:ObjectProperty) Indicates that an entity requires a certain piece of software to operate.
 
[![](../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[requiresSoftware](../Submissions/Computer_System/requiresSoftware "Submissions:Computer System/requiresSoftware") 
 page_ 



[![ObjectProperty](../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__usesDriver__ 
 (owl:ObjectProperty) Indicates the usage of a specific driver.
 
[![](../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[usesDriver](../Submissions/Computer_System/usesDriver "Submissions:Computer System/usesDriver") 
 page_ 



[![ObjectProperty](../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__usesHardware__ 
 (owl:ObjectProperty) Indicates the usage of a specific piece of hardware.
 
[![](../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[usesHardware](../Submissions/Computer_System/usesHardware "Submissions:Computer System/usesHardware") 
 page_ 



[![ObjectProperty](../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__usesOperatingSystem__ 
 (owl:ObjectProperty) Indicates the usage of a certain Operating System.
 
[![](../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[usesOperatingSystem](../Submissions/Computer_System/usesOperatingSystem "Submissions:Computer System/usesOperatingSystem") 
 page_ 



[![ObjectProperty](../../../../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__usesSoftware__ 
 (owl:ObjectProperty) Indicates the usage of a specific piece of software.
 
[![](../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[usesSoftware](../Submissions/Computer_System/usesSoftware "Submissions:Computer System/usesSoftware") 
 page_ 



[![Class](../../../../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__Computer__ 
 (owl:Class) This entity represents computers of any type, size, cost and application.
 
[![](../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[Computer](../Submissions/Computer_System/Computer "Submissions:Computer System/Computer") 
 page_ 



[![Class](../../../../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__Driver__ 
 (owl:Class) A computer program that operates or controls a particular type of device that is attached to a computer.
 
[![](../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[Driver](../Submissions/Computer_System/Driver "Submissions:Computer System/Driver") 
 page_ 



[![Class](../../../../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__Hardware__ 
 (owl:Class) A physical component or a collection of physical components used by (or within or aside) a computer.
 
[![](../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[Hardware](../Submissions/Computer_System/Hardware "Submissions:Computer System/Hardware") 
 page_ 



[![Class](../../../../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__OperatingSystem__ 
 (owl:Class) A system software that manages computer hardware and software resources and provides common services for computer programs.
 
[![](../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[OperatingSystem](../Submissions/Computer_System/OperatingSystem "Submissions:Computer System/OperatingSystem") 
 page_ 



[![Class](../../../../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__Software__ 
 (owl:Class) Part of a computer system that consists of encoded information or computer instructions.
 
[![](../../../../../../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[Software](../Submissions/Computer_System/Software "Submissions:Computer System/Software") 
 page_ 


# 

 Additional information



# 

 Scenarios




__Scenarios about Computer System__ 


 No scenario is added to this Content OP.
 




# 

 Reviews




__Reviews about Computer System__ 


 There is no review about this proposal.
This revision (revision ID
 __13196__ 
 ) takes in account the reviews: none
 



 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Computer_System&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Computer_System&action=evaluation") 





  





# 

 Modeling issues




__Modeling issues about Computer System__ 


 There is no Modeling issue related to this proposal.
 




  





# 

 References
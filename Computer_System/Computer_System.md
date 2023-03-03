#  Graphical representation


__Diagram__




[![Image:ComputerSystemODP Diagram.png](./ComputerSystemODP_Diagram.png)](../Image/ComputerSystemODP_Diagram.png.md "Image:ComputerSystemODP Diagram.png")




#  General description




|  |  |
| --- | --- |
|  Name: |  Computer System |
|  Submitted by: | [PanagiotisMitzias](../User/PanagiotisMitzias.md "User:PanagiotisMitzias"), [EfstratiosKontopoulos](../User/EfstratiosKontopoulos.md "User:EfstratiosKontopoulos"), [MarinaRiga](../User/MarinaRiga.md "User:MarinaRiga") |
|  Also Known As: |  |
|  Intent: |  The pattern intends to model computer systems based on a hardware/software approach. This pattern has been developed by [MKLab](http://mklab.iti.gr/ "http://mklab.iti.gr/") at CERTH/ITI and [Tate](http://www.tate.org.uk/ "http://www.tate.org.uk/") for the [PERICLES](http://www.pericles-project.eu/ "http://www.pericles-project.eu/") FP7 project. |
|  Domains: | [General](../Community/General.md "Community:General") |
|  Competency Questions: | <li><p><i>What is currently installed in a computer?</i> A computer uses specific pieces of hardware and software.</p></li>* _What software or hardware is required so that some other software or hardware can operate properly?_ This relationship is represented with properties requiresSoftware and requiresHardware.* _What software or hardware is compatible with other software or hardware?_ This is expressed via the isCompatibleWith relationship. |
|  Solution description: |  The pattern represents a computer system, along with the involved software and hardware components. It also includes significant properties between these main entities. |
|  Reusable OWL Building Block: | [http://mklab.iti.gr/pericles/ComputerSystem\_ODP.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=http://mklab.iti.gr/pericles/ComputerSystem_ODP.owl&message=OWL building block&from_page_id=4312&update=) (603) |
|  Consequences: |  The design pattern is expected to facilitate the creation of computer system domain ontologies that can be exploited in numerous fields. A well-established, comprehensible pattern will prove to be advantageous. |
|  Scenarios: | <li>The computer uses Ubuntu 16.04.</li><li>The graphics card requires driver A.</li><li>The software is compatible with Windows 10.</li><li>The processor is compatible with motherboard B.</li> |
|  Known Uses: |  |
|  Web References: |  |
|  Other References: |  |
|  Examples (OWL files): |  |
|  Extracted From: |  |
|  Reengineered From: |  |
|  Has Components: |  |
|  Specialization Of: |  |
|  Related CPs: |  |


  




#  Elements


_The __Computer System__ Content OP locally defines the following ontology elements:_



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isCompatibleWith__ (owl:ObjectProperty) Represents the relationship of compatibility between two components. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isCompatibleWith](./Computer_System/isCompatibleWith.md "Submissions:Computer System/isCompatibleWith") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __requiresHardware__ (owl:ObjectProperty) Indicates that an entity requires a certain piece of hardware to operate. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[requiresHardware](./Computer_System/requiresHardware.md "Submissions:Computer System/requiresHardware") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __requiresSoftware__ (owl:ObjectProperty) Indicates that an entity requires a certain piece of software to operate. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[requiresSoftware](./Computer_System/requiresSoftware.md "Submissions:Computer System/requiresSoftware") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __usesDriver__ (owl:ObjectProperty) Indicates the usage of a specific driver. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[usesDriver](./Computer_System/usesDriver.md "Submissions:Computer System/usesDriver") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __usesHardware__ (owl:ObjectProperty) Indicates the usage of a specific piece of hardware. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[usesHardware](./Computer_System/usesHardware.md "Submissions:Computer System/usesHardware") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __usesOperatingSystem__ (owl:ObjectProperty) Indicates the usage of a certain Operating System. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[usesOperatingSystem](./Computer_System/usesOperatingSystem.md "Submissions:Computer System/usesOperatingSystem") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __usesSoftware__ (owl:ObjectProperty) Indicates the usage of a specific piece of software. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[usesSoftware](./Computer_System/usesSoftware.md "Submissions:Computer System/usesSoftware") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __Computer__ (owl:Class) This entity represents computers of any type, size, cost and application. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[Computer](./Computer_System/Computer.md "Submissions:Computer System/Computer") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __Driver__ (owl:Class) A computer program that operates or controls a particular type of device that is attached to a computer. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[Driver](./Computer_System/Driver.md "Submissions:Computer System/Driver") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __Hardware__ (owl:Class) A physical component or a collection of physical components used by (or within or aside) a computer. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[Hardware](./Computer_System/Hardware.md "Submissions:Computer System/Hardware") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __OperatingSystem__ (owl:Class) A system software that manages computer hardware and software resources and provides common services for computer programs. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[OperatingSystem](./Computer_System/OperatingSystem.md "Submissions:Computer System/OperatingSystem") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __Software__ (owl:Class) Part of a computer system that consists of encoded information or computer instructions. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[Software](./Computer_System/requiresSoftware.md "Submissions:Computer System/Software") page_
#  Additional information


#  Scenarios



__Scenarios about Computer System__
No scenario is added to this Content OP.




#  Reviews



__Reviews about Computer System__
There is no review about this proposal.
This revision (revision ID __13196__) takes in account the reviews: none


Other info at [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Computer_System&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Computer_System&action=evaluation")




  




#  Modeling issues



__Modeling issues about Computer System__
There is no Modeling issue related to this proposal.




  




#  References
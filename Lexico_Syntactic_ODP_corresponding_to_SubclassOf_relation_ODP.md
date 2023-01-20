# 

 Description




|  |  |
| --- | --- |
|  Name  |  Lexico Syntactic ODPs corresponding to SubclassOf relation ODP  |
|  Language  |  English  |
|  Also known as  |  LSP-SC-EN  |
|  Intent  |  Recurrent expressions in English to state the relation holding between a class and its sublclasses  |
|  Solution description  |  The set of Lexico-Syntactic ODPs included here have a direct correspondence to the Logical ODP for modelling "SubclassOf relation", described in the Technical report D5.1.1, NeOn project Deliverable (see Web Reference below).  |
|  Description of the correspondence relation between the LSPs and the ODPs  |  one LSP to one ODP  |
|  Related ODP(s)  |  |
|  Web reference  | [http://www.neon-project.org/nw/Deliverables](http://www.neon-project.org/nw/Deliverables "http://www.neon-project.org/nw/Deliverables")  |
|  Author(s)  |  Elena Montiel-Ponsoda, Guadalupe Aguado de Cea, Mari Carmen Suárez-Figueroa, Asunción Gómez-Pérez  |
|  Submitted by  | [Elena Montiel-Ponsoda](http://ontologydesignpatterns.org/wiki/index.php?title=User:Elena_Montiel-Ponsoda&action=edit&redlink=1 "User:Elena Montiel-Ponsoda (not yet written)")  |



  





# 

 Cases



_The
 __Lexico Syntactic ODP corresponding to SubclassOf relation ODP__ 
 Lexico-Syntactic ODP includes the following cases (see also
 [abbreviations and symbols used in LSP Formalization](../Community/LSPSymbols "Community:LSPSymbols") 
 ):_ 




  







__NL Formulation__ 



* An orphan drug is a type of drug.* Odometry, speedometry and GPS are types of sensors.


__LSP Formalization__ 




```
[(NP<subclass>,)* and] NP<subclass> be [CN-CATV] NP<superclass>

```


__Reusable JAPE code__ 
 :
 [SC\_1\_2.jape](public/images/c/c1/SC_1_2.jape "SC 1 2.jape") 






[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[1](../Submissions/Lexico_Syntactic_ODP_corresponding_to_SubclassOf_relation_ODP/1 "Submissions:Lexico Syntactic ODP corresponding to SubclassOf relation ODP/1") 
 page_ 






__NL Formulation__ 



* Prefixes and suffixes are classified as affixes.


__LSP Formalization__ 




```
[(NP<subclass>,)* and] NP<subclass> classify as NP<superclass>

```


__Reusable JAPE code__ 
 :
 [SC\_3.jape](public/images/9/90/SC_3.jape "SC 3.jape") 






[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[2](../Submissions/Lexico_Syntactic_ODP_corresponding_to_SubclassOf_relation_ODP/2 "Submissions:Lexico Syntactic ODP corresponding to SubclassOf relation ODP/2") 
 page_ 






__NL Formulation__ 



* Thyroid medicines belong to the general group of hormone medicines.* Starfish fall into the class Asteroidea.


__LSP Formalization__ 




```
[(NP<subclass>,)* and] NP<subclass> (belong to)\(fall into) CN-CATV NP<superclass>

```


__Reusable JAPE code__ 
 :
 [SC\_3.jape](public/images/9/90/SC_3.jape "SC 3.jape") 






[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[3](../Submissions/Lexico_Syntactic_ODP_corresponding_to_SubclassOf_relation_ODP/3 "Submissions:Lexico Syntactic ODP corresponding to SubclassOf relation ODP/3") 
 page_ 






__NL Formulation__ 



* There are several kinds of memory: fast, expensive, short term memory, and long-term memory.


__LSP Formalization__ 




```
There are QUAN CN-CATV NP<superclass> PARA [(NP<subclass>,)* and] NP<subclass>

```


__Reusable JAPE code__ 
 :
 [SC\_4.jape](public/images/5/5f/SC_4.jape "SC 4.jape") 






[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[4](../Submissions/Lexico_Syntactic_ODP_corresponding_to_SubclassOf_relation_ODP/4 "Submissions:Lexico Syntactic ODP corresponding to SubclassOf relation ODP/4") 
 page_ 






__NL Formulation__ 



* Some examples of peripherals are keyboards, mice, monitors, printers, scanners, disk and tape drives, microphones, speakers, joysticks, plotters and cameras.* Types of criteria for assessing applications are: quality, safety and efficacy.


__LSP Formalization__ 




```
[A(n)/QUAN] example of/CN-CATV NP<superclass> be/include [PARA] [(NP<subclass>,)* and] NP<subclass>

```


__Reusable JAPE code__ 
 :
 [SC\_5.jape](public/images/d/d5/SC_5.jape "SC 5.jape") 






[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[5](../Submissions/Lexico_Syntactic_ODP_corresponding_to_SubclassOf_relation_ODP/5 "Submissions:Lexico Syntactic ODP corresponding to SubclassOf relation ODP/5") 
 page_ 




# 

 Additional information



# 

 Reviews




__Reviews about Lexico Syntactic ODP corresponding to SubclassOf relation ODP__ 


 There is no review about this proposal.
This revision (revision ID
 __8973__ 
 ) takes in account the reviews: none
 



 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Lexico_Syntactic_ODP_corresponding_to_SubclassOf_relation_ODP&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Lexico_Syntactic_ODP_corresponding_to_SubclassOf_relation_ODP&action=evaluation") 





  





# 

 Modeling issues




__Modeling issues about Lexico Syntactic ODP corresponding to SubclassOf relation ODP__ 


 There is no Modeling issue related to this proposal.
 




  





# 

 References
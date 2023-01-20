# 

 Description




|  |  |
| --- | --- |
|  Name  |  Lexico Syntactic ODPs corresponding to Simple Part-Whole relation "or" Constituency "or" Componency "or" Collection-Entity ODPs  |
|  Language  |  English  |
|  Also known as  |  LSP-PW-CONS-COM-CE-EN  |
|  Intent  |  Ambiguous (or polisemic) expressions in English that can state for different types of relations of meronymy: (1) the relation between an object and its parts, (2) the relation between an object and the material it is made of, (3) the relation between an objects and its proper parts, or (4) the relations between a collection and the members that belong it.  |
|  Solution description  |  The set of Lexico-Syntactic ODPs included here have a correspondence to four Content ODPs for modelling "Simple Part-Whole relation", "Constituency", "Componency" or "Collection-Entity".  |
|  Description of the correspondence relation between the LSPs and the ODPs  |  one LSP to pair-wise disjoint ODPs  |
|  Related ODP(s)  | [Submissions:http://ontologydesignpatterns.org/wiki/Submissions:ContentOPs](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Http://ontologydesignpatterns.org/wiki/Submissions:ContentOPs&action=edit&redlink=1 "Submissions:Http://ontologydesignpatterns.org/wiki/Submissions:ContentOPs (not yet written)")  |
|  Web reference  | [http://www.neon-project.org/web-content/images/Publications/neon\_2008\_d2.5.1.pdf](http://www.neon-project.org/web-content/images/Publications/neon_2008_d2.5.1.pdf "http://www.neon-project.org/web-content/images/Publications/neon_2008_d2.5.1.pdf")  |
|  Author(s)  |  Elena Montiel-Ponsoda, Guadalupe Aguado de Cea, Mari Carmen Suárez-Figueroa, Asunción Gómez-Pérez  |
|  Submitted by  | [ElenaMontiel-Ponsoda](../User/ElenaMontiel-Ponsoda "User:ElenaMontiel-Ponsoda")  |



  





# 

 Cases



_The
 __Lexico Syntactic ODPs corresponding to Simple Part-Whole relation "or" Constituency "or" Componency "or" Collection-Entity ODPs__ 
 Lexico-Syntactic ODP includes the following cases (see also
 [abbreviations and symbols used in LSP Formalization](../Community/LSPSymbols "Community:LSPSymbols") 
 ):_ 




  







__NL Formulation__ 



* Proteins form part of the cell membrane.


__LSP Formalization__ 




```
[(NP<part>,)* and] NP<part> PART NP<whole>

```


__Reusable JAPE code__ 
 :
 [PW\_1.jape](public/images/d/db/PW_1.jape "PW 1.jape") 






[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[1](Submissions%253ALexico_Syntactic_ODPs_corresponding_to_Simple_Part-Whole_relation_%2522or%2522_Constituency_%2522or%2522_Componency_%2522or%2522_Collection-Entity_ODPs/1.html "Submissions:Lexico Syntactic ODPs corresponding to Simple Part-Whole relation \"or\" Constituency \"or\" Componency \"or\" Collection-Entity ODPs/1") 
 page_ 






__NL Formulation__ 



* Most clays consist of flat particles.* Water is made up of hydrogen and oxygen.* The United Arab Emirates is a country composed of seven emirates or sheikdoms.


__LSP Formalization__ 




```
NP<whole> PART [(NP<part>,)* and] NP<part>

```


__Reusable JAPE code__ 
 :
 [PW\_2.jape](public/images/8/89/PW_2.jape "PW 2.jape") 






[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[2](Submissions%253ALexico_Syntactic_ODPs_corresponding_to_Simple_Part-Whole_relation_%2522or%2522_Constituency_%2522or%2522_Componency_%2522or%2522_Collection-Entity_ODPs/2.html "Submissions:Lexico Syntactic ODPs corresponding to Simple Part-Whole relation \"or\" Constituency \"or\" Componency \"or\" Collection-Entity ODPs/2") 
 page_ 






__NL Formulation__ 



* A state machine workflow is made up of a set of states, transitions, and actions.


__LSP Formalization__ 




```
NP<whole> be PART [CD] CN-PART [PARA] [(NP<part>,)* and] NP<part>

```


__Reusable JAPE code__ 
 : -
 





[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[3](Submissions%253ALexico_Syntactic_ODPs_corresponding_to_Simple_Part-Whole_relation_%2522or%2522_Constituency_%2522or%2522_Componency_%2522or%2522_Collection-Entity_ODPs/3.html "Submissions:Lexico Syntactic ODPs corresponding to Simple Part-Whole relation \"or\" Constituency \"or\" Componency \"or\" Collection-Entity ODPs/3") 
 page_ 






__NL Formulation__ 



* The parts of a tree are the root, trunk(s), branches, twigs and leaves.


__LSP Formalization__ 




```
CN-PART  NP<whole> be [PARA] [(NP<part>,)* and] NP<part>

```


__Reusable JAPE code__ 
 :
 [PW\_3.jape](public/images/4/48/PW_3.jape "PW 3.jape") 






[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[4](Submissions%253ALexico_Syntactic_ODPs_corresponding_to_Simple_Part-Whole_relation_%2522or%2522_Constituency_%2522or%2522_Componency_%2522or%2522_Collection-Entity_ODPs/4.html "Submissions:Lexico Syntactic ODPs corresponding to Simple Part-Whole relation \"or\" Constituency \"or\" Componency \"or\" Collection-Entity ODPs/4") 
 page_ 






__NL Formulation__ 



* The cerebrum is divided into two major parts: the right cerebral hemisphere and left cerebral hemisphere.


__LSP Formalization__ 




```
NP<whole> include/(be divide in/into)/(be separate in/into)CD CN-PART [PARA] [(NP<part>,)* and] NP<part

```


__Reusable JAPE code__ 
 :
 [PW\_5.jape](public/images/7/7a/PW_5.jape "PW 5.jape") 






[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[5](Submissions%253ALexico_Syntactic_ODPs_corresponding_to_Simple_Part-Whole_relation_%2522or%2522_Constituency_%2522or%2522_Componency_%2522or%2522_Collection-Entity_ODPs/5.html "Submissions:Lexico Syntactic ODPs corresponding to Simple Part-Whole relation \"or\" Constituency \"or\" Componency \"or\" Collection-Entity ODPs/5") 
 page_ 




# 

 Additional information



# 

 Reviews




__Reviews about Lexico Syntactic ODPs corresponding to Simple Part-Whole relation "or" Constituency "or" Componency "or" Collection-Entity ODPs__ 


 There is no review about this proposal.
This revision (revision ID
 __8984__ 
 ) takes in account the reviews: none
 



 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Lexico_Syntactic_ODPs_corresponding_to_Simple_Part-Whole_relation_%22or%22_Constituency_%22or%22_Componency_%22or%22_Collection-Entity_ODPs&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Lexico_Syntactic_ODPs_corresponding_to_Simple_Part-Whole_relation_%22or%22_Constituency_%22or%22_Componency_%22or%22_Collection-Entity_ODPs&action=evaluation") 





  





# 

 Modeling issues




__Modeling issues about Lexico Syntactic ODPs corresponding to Simple Part-Whole relation "or" Constituency "or" Componency "or" Collection-Entity ODPs__ 


 There is no Modeling issue related to this proposal.
 




  





# 

 References
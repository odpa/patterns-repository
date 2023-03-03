#  Description




|  |  |
| --- | --- |
|  Name |  Lexico Syntactic ODPs corresponding to SubclassOf relation, Disjoint Classes, and Exhaustive Classes ODPs |
|  Language |  English |
|  Also known as |  LSP-SC-Di-EC-EN |
|  Intent |  Recurrent expressions in English that state a relation between a (super)class and all the distinct (sub)classes that belong to the superclass. |
|  Solution description |  The set of Lexico-Syntactic ODPs included here have a direct correspondence to the Logical ODPs for modelling "SubclassOf relation", "Disjoint Classes", and "Exhaustive Classes" described in the Technical report D5.1.1, NeOn project Deliverable (see Web Reference below). |
|  Description of the correspondence relation between the LSPs and the ODPs |  one LSP to the combination of several ODPs |
|  Related ODP(s) |  |
|  Web reference | [http://www.neon-project.org/nw/Deliverables](http://www.neon-project.org/nw/Deliverables "http://www.neon-project.org/nw/Deliverables") |
|  Author(s) |  Elena Montiel-Ponsoda, Guadalupe Aguado de Cea, Mari Carmen Suárez-Figueroa, Asunción Gómez-Pérez |
|  Submitted by | [ElenaMontiel-Ponsoda](../User/ElenaMontiel-Ponsoda.md "User:ElenaMontiel-Ponsoda") |


  




#  Cases


_The __Lexico Syntactic ODPs corresponding to SubclassOf relation, Disjoint Classes, and Exhaustive Classes ODPs__ Lexico-Syntactic ODP includes the following cases (see also [abbreviations and symbols used in LSP Formalization](../Community/LSPSymbols.md "Community:LSPSymbols")):_


  






__NL Formulation__



* Animals are either vertebrates or invertebrates.

__LSP Formalization__




```
NP<superclass> be/CATV [either] NP<subclass> or/and NP<subclass>

```

__Reusable JAPE code__: [SC\_Di\_EC\_3.jape](./SC_Di_EC_3.jape "SC Di EC 3.jape")





[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[1](./Normalization@oldid=10071.md "Submissions:Lexico Syntactic ODPs corresponding to SubclassOf relation, Disjoint Classes, and Exhaustive Classes ODPs/1") page_





__NL Formulation__



* Membrane proteins are classified into two major categories, integral proteins and peripheral proteins.

__LSP Formalization__




```
NP<superclass> CATV CD CN-CATV [PARA] [(NP<subclass>,)*and] NP <subclass>

```

__Reusable JAPE code__: [SC\_Di\_EC\_4\_5.jape](./SC_Di_EC_4_5.jape "SC Di EC 4 5.jape")





[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[2](../Adrian_Walker_2/Adrian_Walker_2.md "Submissions:Lexico Syntactic ODPs corresponding to SubclassOf relation, Disjoint Classes, and Exhaustive Classes ODPs/2") page_





__NL Formulation__



* There are CD CN-CATV NP<superclass> [PARA] [(NP<subclass>,)\* and] NP<subclass>

__LSP Formalization__




```
There are two types of narcotic analgesics: the opiates and the opioids.

```

__Reusable JAPE code__: -





[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[3](./NegativePropertyAssertions@oldid=5903.md "Submissions:Lexico Syntactic ODPs corresponding to SubclassOf relation, Disjoint Classes, and Exhaustive Classes ODPs/3") page_





__NL Formulation__



* Marine mammals are divided into three orders: Carnivora, Sirenia and Cetacea.

__LSP Formalization__




```
NP<superclass> be divided/separate in/into CD CN-CATV [PARA] [(NP<subclass >,)* and] NP<subclass>

```

__Reusable JAPE code__: [SC\_Di\_EC\_2.jape](./SC_Di_EC_2.jape "SC Di EC 2.jape")





[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[4](./ConceptTerms@oldid=5714.md "Submissions:Lexico Syntactic ODPs corresponding to SubclassOf relation, Disjoint Classes, and Exhaustive Classes ODPs/4") page_



#  Additional information


#  Reviews



__Reviews about Lexico Syntactic ODPs corresponding to SubclassOf relation, Disjoint Classes, and Exhaustive Classes ODPs__
There is no review about this proposal.
This revision (revision ID __8987__) takes in account the reviews: none


Other info at [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Lexico_Syntactic_ODPs_corresponding_to_SubclassOf_relation%2C_Disjoint_Classes%2C_and_Exhaustive_Classes_ODPs&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Lexico_Syntactic_ODPs_corresponding_to_SubclassOf_relation%2C_Disjoint_Classes%2C_and_Exhaustive_Classes_ODPs&action=evaluation")




  




#  Modeling issues



__Modeling issues about Lexico Syntactic ODPs corresponding to SubclassOf relation, Disjoint Classes, and Exhaustive Classes ODPs__
There is no Modeling issue related to this proposal.




  




#  References
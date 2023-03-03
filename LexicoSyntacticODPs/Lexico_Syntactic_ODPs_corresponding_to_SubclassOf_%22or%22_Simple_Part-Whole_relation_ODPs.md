#  Description




|  |  |
| --- | --- |
|  Name |  Lexico Syntactic ODPs corresponding to SubclassOf "or" Simple Part-Whole relation ODPs |
|  Language |  English |
|  Also known as |  LSP-SC-PW-EN |
|  Intent |  Ambiguous (or polisemic) expressions in English that can either state the relation holding between a class and its sublclasses, or a whole and its parts. |
|  Solution description |  The set of Lexico-Syntactic ODPs included here have a direct correspondence to both patterns: the Logical ODP for modelling "SubclassOf relation" or the Content ODP for modelling "Simple Part-Whole" relations, as described in the Technical report D5.1.1, NeOn project Deliverable (see Web Reference below). |
|  Description of the correspondence relation between the LSPs and the ODPs |  one LSP to pair-wise disjoint ODPs |
|  Related ODP(s) | [Submissions:http://ontologydesignpatterns.org/wiki/Submissions:PartOf](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Http://ontologydesignpatterns.org/wiki/Submissions:PartOf&action=edit&redlink=1 "Submissions:Http://ontologydesignpatterns.org/wiki/Submissions:PartOf (not yet written)") |
|  Web reference | [http://www.neon-project.org/web-content/images/Publications/neon\_2008\_d2.5.1.pdf](http://www.neon-project.org/web-content/images/Publications/neon_2008_d2.5.1.pdf "http://www.neon-project.org/web-content/images/Publications/neon_2008_d2.5.1.pdf") |
|  Author(s) |  Elena Montiel-Ponsoda, Guadalupe Aguado de Cea, Mari Carmen Suárez-Figueroa, Asunción Gómez-Pérez |
|  Submitted by | [ElenaMontiel-Ponsoda](../User/ElenaMontiel-Ponsoda.md "User:ElenaMontiel-Ponsoda") |


  




#  Cases


_The __Lexico Syntactic ODPs corresponding to SubclassOf "or" Simple Part-Whole relation ODPs__ Lexico-Syntactic ODP includes the following cases (see also [abbreviations and symbols used in LSP Formalization](../Community/LSPSymbols.md "Community:LSPSymbols")):_


  






__NL Formulation__



* Arthropods include insects, crustaceans, spiders, scorpions, and centipedes.* Reproductive structures in female insects include ovaries, bursa copulatrix and uterus.

__LSP Formalization__




```
NP<class> include [(NP<class >,)* and] NP<class>

```

__Reusable JAPE code__: [SC\_PW\_1.jape](./SC_PW_1.jape "SC PW 1.jape")





[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[1](./Normalization@oldid=10071.md "Submissions:Lexico Syntactic ODPs corresponding to SubclassOf \"or\" Simple Part-Whole relation ODPs/1") page_





__NL Formulation__



* Seed producing plants are divided into angiosperms and gymnosperms.* Cells are divided into distinct sub-cellular compartments

__LSP Formalization__




```
NP<class> be divided/separate in/into [CN] [(NP<class >,)* and] NP<class>

```

__Reusable JAPE code__: [SC\_PW\_2.jape](./SC_PW_2.jape "SC PW 2.jape")





[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[2](../Adrian_Walker_2/Adrian_Walker_2.md "Submissions:Lexico Syntactic ODPs corresponding to SubclassOf \"or\" Simple Part-Whole relation ODPs/2") page_



#  Additional information


#  Reviews



__Reviews about Lexico Syntactic ODPs corresponding to SubclassOf "or" Simple Part-Whole relation ODPs__
There is no review about this proposal.
This revision (revision ID __8986__) takes in account the reviews: none


Other info at [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Lexico_Syntactic_ODPs_corresponding_to_SubclassOf_%22or%22_Simple_Part-Whole_relation_ODPs&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Lexico_Syntactic_ODPs_corresponding_to_SubclassOf_%22or%22_Simple_Part-Whole_relation_ODPs&action=evaluation")




  




#  Modeling issues



__Modeling issues about Lexico Syntactic ODPs corresponding to SubclassOf "or" Simple Part-Whole relation ODPs__
There is no Modeling issue related to this proposal.




  




#  References
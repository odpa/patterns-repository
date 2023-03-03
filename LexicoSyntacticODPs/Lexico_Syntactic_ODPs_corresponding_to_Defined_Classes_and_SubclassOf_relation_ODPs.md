#  Description




|  |  |
| --- | --- |
|  Name |  Lexico Syntactic ODPs corresponding to Defined Classes and SubclassOf relation ODPs |
|  Language |  English |
|  Also known as |  LSP-DC-SC-EN |
|  Intent |  Recurrent expressions in English that define a class by stating the relation between the class and the (super)class it belongs to, and making explicit the feature or property that makes the class different from the superclass. |
|  Solution description |  The set of Lexico-Syntactic ODPs included here have a direct correspondence to the Logical ODPs for modelling "Defined Clases" and the "SubclassOf relation", described in the Technical report D5.1.1, NeOn project Deliverable (see Web Reference below). |
|  Description of the correspondence relation between the LSPs and the ODPs |  one LSP to the combination of several ODPs |
|  Related ODP(s) |  |
|  Web reference |  |
|  Author(s) |  Elena Montiel-Ponsoda, Guadalupe Aguado de Cea, Mari Carmen Suárez-Figueroa, Asunción Gómez-Pérez |
|  Submitted by | [ElenaMontiel-Ponsoda](../User/ElenaMontiel-Ponsoda.md "User:ElenaMontiel-Ponsoda") |


  




#  Cases


_The __Lexico Syntactic ODPs corresponding to Defined Classes and SubclassOf relation ODPs__ Lexico-Syntactic ODP includes the following cases (see also [abbreviations and symbols used in LSP Formalization](../Community/LSPSymbols.md "Community:LSPSymbols")):_


  






__NL Formulation__



* A device is any machine or component that attaches to a computer.* Non-narcotic analgesics are drugs that have principally analgesic, antipyretic, and anti-inflammatory actions.

__LSP Formalization__




```
[A/any] NP<subclass> be [a/any] NP<superclass> REPRO VB [(NP<class>,)* and] NP<class>

```

__Reusable JAPE code__: [SC\_De\_1.jape](./SC_De_1.jape "SC De 1.jape")





[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[1](./Normalization@oldid=10071.md "Submissions:Lexico Syntactic ODPs corresponding to Defined Classes and SubclassOf relation ODPs/1") page_





__NL Formulation__



* A vegetarian pizza is a pizza without fish or meat.

__LSP Formalization__




```
[A/any] NP<subclass> be [a/any] NP<superclass> PREP [(NP<class>,)* and/or NP<class

```

__Reusable JAPE code__: [SC\_De\_2.jape](./SC_De_2.jape "SC De 2.jape")





[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[2](../Adrian_Walker_2/Adrian_Walker_2.md "Submissions:Lexico Syntactic ODPs corresponding to Defined Classes and SubclassOf relation ODPs/2") page_





__NL Formulation__



* A workflow that contains at least one business task is a business plan.

__LSP Formalization__




```
[A/any] NP<subclass> REPRO VB [(NP<class>,)* and/or NP<class> be [a] NP<superclass>

```

__Reusable JAPE code__: [SC\_De\_3.jape](./SC_De_3.jape "SC De 3.jape")





[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[3](./NegativePropertyAssertions@oldid=5903.md "Submissions:Lexico Syntactic ODPs corresponding to Defined Classes and SubclassOf relation ODPs/3") page_





__NL Formulation__



* Animal with backbones are called vertebrates.

__LSP Formalization__




```
[A/any] NP<subclass> PREP [(NP<class>,)* and] NP<class> be VB [a] NP<superclass>

```

__Reusable JAPE code__: [SC\_De\_4.jape](./SC_De_4.jape "SC De 4.jape")





[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[4](./ConceptTerms@oldid=5714.md "Submissions:Lexico Syntactic ODPs corresponding to Defined Classes and SubclassOf relation ODPs/4") page_



#  Additional information


#  Reviews



__Reviews about Lexico Syntactic ODPs corresponding to Defined Classes and SubclassOf relation ODPs__
There is no review about this proposal.
This revision (revision ID __9285__) takes in account the reviews: none


Other info at [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Lexico_Syntactic_ODPs_corresponding_to_Defined_Classes_and_SubclassOf_relation_ODPs&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Lexico_Syntactic_ODPs_corresponding_to_Defined_Classes_and_SubclassOf_relation_ODPs&action=evaluation")




  




#  Modeling issues



__Modeling issues about Lexico Syntactic ODPs corresponding to Defined Classes and SubclassOf relation ODPs__
There is no Modeling issue related to this proposal.




  




#  References


* NeOn Deliverable D5.1.1: NeOn modelling components [Documentation](http://droz.dia.fi.upm.es/neon/servlet/download?ontology=Documentation+Ontology&concept=Deliverable&instanceSet=neon&instance=D5.1.1%3A+NeOn+modelling+components&attribute=On-line+PDF+Version&value=NeOn_2007_D5.1.1.pdf "http://droz.dia.fi.upm.es/neon/servlet/download?ontology=Documentation+Ontology&concept=Deliverable&instanceSet=neon&instance=D5.1.1%3A+NeOn+modelling+components&attribute=On-line+PDF+Version&value=NeOn_2007_D5.1.1.pdf") | [reference page](../Community/References/NeOn_Deliverable_D5_1_1_5.md "Community:References/NeOn Deliverable D5 1 1 5")
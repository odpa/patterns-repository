#  Graphical representation


__Diagram__
_(this article has no graphical representation)_



#  General information




|  |  |
| --- | --- |
|  Name |  DisjointnessOfComplement (DOC) |
|  Also known as |  |
|  Author(s) |  |
|  SubmittedBy | [CatherineRoussey](../User/CatherineRoussey.md "User:CatherineRoussey"), [OscarCorcho](http://ontologydesignpatterns.org/wiki/index.php?title=User:OscarCorcho&action=edit&redlink=1 "User:OscarCorcho (not yet written)") |


  




#  Description




|  |  |
| --- | --- |
|  Motivation |  We have identified a set of patterns that are commonly used by domain experts in their DL formalisations and OWL implementations, and that normally result in unsatisfiable classes or modelling errors. As aforementioned all these antipatterns come from a misuse and misunderstanding of DL expressions by ontology developers. Thus they are all Logical AntiPatterns (LAP): they are independent from a specific domain of interest, but dependent on the expressivity of the logical formalism used for the representation. |
|  Aim |  The ontology developer may want to say that C1 and C2 cannot share instances, instead of defining C1 as the logical negation of C2. Hence it could be more appropriate to state that C1 and C2 are disjoint. |
|  Solution description |  C1 isEquivalentTo not C2should be replace byC1 disjointWith C2 |
|  Elements |  |
|  Implementation |  |
|  Reusable component |  |
|  Component type |  |


  




#  Example




|  |  |
| --- | --- |
|  Problem example |  Salt\_Lagoon isEquivalentTo not Fresh\_Waterssee concept Laguna\_Salada in Hydrontology |
|  Pattern solution example | [http://www.dia.fi.upm.es/~ocorcho/OWLDebugging/](http://www.dia.fi.upm.es/%7Eocorcho/OWLDebugging/ "http://www.dia.fi.upm.es/%7Eocorcho/OWLDebugging/") |
|  Consequences |  |


  




#  Pattern reference




|  |  |
| --- | --- |
|  Origin |  |
|  Known use |  |
|  Reference |  |
|  Related ODP |  |
|  Used in combination with |  |
|  Test |  |


#  Additional information


#  Scenarios



__Scenarios about DisjointnessOfComplement (DOC)__
No scenario is added to this Content OP.




#  Reviews



__Reviews about DisjointnessOfComplement (DOC)__


| Review article | [Posted on](../Property/CreationDate.md "Property:CreationDate") | [About revision (current is 9703)](../Property/ReviewAboutVersion.md "Property:ReviewAboutVersion") |
| --- | --- | --- |
| [AlessandroAdamou about DisjointnessOfComplement (DOC)](Reviews%253AAlessandroAdamou_about_DisjointnessOfComplement_(DOC).html "Reviews:AlessandroAdamou about DisjointnessOfComplement (DOC)") | 24550838 September 2009 | 55975,597 |
| [MathieuDAquin about DisjointnessOfComplement (DOC)](Reviews%253AMathieuDAquin_about_DisjointnessOfComplement_(DOC).html "Reviews:MathieuDAquin about DisjointnessOfComplement (DOC)") | 24550838 September 2009 | 57165,716 |
| [GerdGroener about DisjointnessOfComplement (DOC)](Reviews%253AGerdGroener_about_DisjointnessOfComplement_(DOC).html "Reviews:GerdGroener about DisjointnessOfComplement (DOC)") | 245508510 September 2009 | 57805,780 |


This revision (revision ID __9703__) takes in account the reviews: none


Other info at [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:DisjointnessOfComplement_%28DOC%29&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:DisjointnessOfComplement_%28DOC%29&action=evaluation")




  




#  Modeling issues



__Modeling issues about DisjointnessOfComplement (DOC)__
There is no Modeling issue related to this proposal.




  




#  References


  






|  |  Submission to event[WOP:2009](../WOP/2009.md "WOP:2009") |
| --- | --- |
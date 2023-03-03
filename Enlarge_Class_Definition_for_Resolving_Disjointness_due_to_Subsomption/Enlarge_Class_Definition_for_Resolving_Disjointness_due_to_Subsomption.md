#  Graphical representation


__Diagram__




[Image:Djedidi LOP2 WOP09.pdf](../Image/Djedidi_LOP2_WOP09.pdf.md "Image:Djedidi LOP2 WOP09.pdf")




#  General information




|  |  |
| --- | --- |
|  Name |  Enlarge Class Definition for Resolving Disjointness due to Subsumption. |
|  Also known as |  |
|  Author(s) |  Rim DJEDIDI |
|  SubmittedBy | [RimDjedidi](http://ontologydesignpatterns.org/wiki/index.php?title=User:RimDjedidi&action=edit&redlink=1 "User:RimDjedidi (not yet written)") |


  




#  Description




|  |  |
| --- | --- |
|  Motivation |  Problem :This pattern helps resolving a logical inconsistency triggered by a situation of disjoint classes subsuming a common sub-class. When we need to define – for some modeling issues related to domain of interest – a class as a sub-class of two disjoint classes, a disjointness inconsistency is caused. The problem can be illustrated by the following scenario: let’s consider a class Sub\_Class defined as a sub-class of a class Disjoint\_Class 2; and a class Disjoint\_Class 1 disjoint with the Disjoint\_Class 2 (see diagram in attached file). If we need to add a sub-class relation between the Sub\_Class and the Disjoint\_Class 1, this generates a disjointness inconsistency:- If the extension of the Sub\_Class contains individuals instantiating this sub-class, the logical inconsistency will be extended to the knowledge base; - If the Sub\_Class is not instantiated to individuals, it will be diagnosed as an unsatisfiable class.To solve this inconsistency, one can think about deleting the disjointness axiom. However, this can alter the semantics expressed in the ontology, and negatively affect consistency checking and automatic evaluation of existing individuals as explained in [1]. This pattern tackles the questions of how to resolve the inconsistency caused by such kind of subsumption while preserving existing knowledge.[1] Völker, J., Vrandecic, D., Sure, Y., Hotho, A.: Learning Disjointness. In F., Enrico, K., Michael, May. Wolfgang (Eds.). Proceedings of the 4th European Semantic Web Conference, ESWC 2007. LNCS: Vol. 4519 pp: 175-189. (2007) |
|  Aim |  Intent: The purpose of this pattern is to support the semantics of a subsumption defined under two disjoint classes and resolve the resulting inconsistency.Covered Requirements: The pattern solves a problem of disjointness inconsistency caused by a subsumption relation without deleting the disjointness axiom so that existing knowledge can be preserved. |
|  Solution description |  The pattern resolves a disjointness inconsistency –caused by a subsumption– by enlarging the definition of the sub-class object of the disjointness inconsistency, based on the definition of the involved disjoint classes. The definition of the sub-class is enlarged by the union (OR) of the definitions of the disjoint classes.The application of the solution can be described by the following process (see diagram in attached file): 1) The pattern enlarges the definition of the sub-class object of the disjointness inconsistency by defining –in its description– a union of the definitions of the disjoint classes involved in the inconsistency to be resolved. |
|  Elements |  the following elements are manipulated by the pattern:ID of the sub-class to enlarge (Sub\_Class).ID of the first disjoint class (Disjoint\_Class 1).ID of the second disjoint class (Disjoint\_Class 2). |
|  Implementation |  |
|  Reusable component |  |
|  Component type |  |


  




#  Example




|  |  |
| --- | --- |
|  Problem example |  Let’s consider the OWL ontology O defined by the following axioms:{Animal ⊑Fauna-Flora, Plant ⊑Fauna-Flora, Carnivorous-Plant ⊑Plant, Plant ⊑ Not(Animal)}If we apply a change to the ontology defining Carnivorous-Plant class as a sub-class of the class Animal, we cause a disjointness inconsistency. The proposed pattern resolves this kind of inconsistency. |
|  Pattern solution example |  |
|  Consequences |  The application of the pattern to resolve the example above is performed as follow:1) The pattern enlarges the definition of the sub-class object of the disjointness inconsistency Carnivorous-Plant by defining –in its description– a union of the definitions of the disjoint classes involved in the inconsistency: the classes Animal and Plant. |


  




#  Pattern reference




|  |  |
| --- | --- |
|  Origin |  |
|  Known use |  This pattern is proposed as another solution to the problem solved by the Logical OP "Define Hybrid Class Resolving Disjointness due to Subsumption" |
|  Reference |  |
|  Related ODP |  |
|  Used in combination with |  |
|  Test |  |


#  Additional information


#  Scenarios



__Scenarios about Enlarge Class Definition for Resolving Disjointness due to Subsomption__
No scenario is added to this Content OP.




#  Reviews



__Reviews about Enlarge Class Definition for Resolving Disjointness due to Subsomption__


| Review article | [Posted on](../Property/CreationDate.md "Property:CreationDate") | [About revision (current is 9704)](../Property/ReviewAboutVersion.md "Property:ReviewAboutVersion") |
| --- | --- | --- |
| [MariCarmenSuarezFigueroa about Enlarge Class Definition for Resolving Disjointness due to Subsomption](../Reviews/MariCarmenSuarezFigueroa_about_Enlarge_Class_Definition_for_Resolving_Disjointness_due_to_Subsomption.md "Reviews:MariCarmenSuarezFigueroa about Enlarge Class Definition for Resolving Disjointness due to Subsomption") | 24550838 September 2009 | 56245,624 |
| [MariCarmenSuarezFigueroa about Enlarge Class Definition for Resolving Disjointness due to Subsomption 2](../Reviews/MariCarmenSuarezFigueroa_about_Enlarge_Class_Definition_for_Resolving_Disjointness_due_to_Subsomption_2.md "Reviews:MariCarmenSuarezFigueroa about Enlarge Class Definition for Resolving Disjointness due to Subsomption 2") | 24550838 September 2009 | 57315,731 |
| [WimPeters about Enlarge Class Definition for Resolving Disjointness due to Subsomption](../Reviews/WimPeters_about_Enlarge_Class_Definition_for_Resolving_Disjointness_due_to_Subsomption.md "Reviews:WimPeters about Enlarge Class Definition for Resolving Disjointness due to Subsomption") | 24550849 September 2009 | 57315,731 |
| [FrancoisScharffe about Enlarge Class Definition for Resolving Disjointness due to Subsomption](../Reviews/FrancoisScharffe_about_Enlarge_Class_Definition_for_Resolving_Disjointness_due_to_Subsomption.md "Reviews:FrancoisScharffe about Enlarge Class Definition for Resolving Disjointness due to Subsomption") | 245508611 September 2009 | 58005,800 |


This revision (revision ID __9704__) takes in account the reviews: none


Other info at [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Enlarge_Class_Definition_for_Resolving_Disjointness_due_to_Subsomption&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Enlarge_Class_Definition_for_Resolving_Disjointness_due_to_Subsomption&action=evaluation")




  




#  Modeling issues



__Modeling issues about Enlarge Class Definition for Resolving Disjointness due to Subsomption__
There is no Modeling issue related to this proposal.




  




#  References


  






|  |  Submission to event[WOP:2009](../WOP/2009.md "WOP:2009") |
| --- | --- |
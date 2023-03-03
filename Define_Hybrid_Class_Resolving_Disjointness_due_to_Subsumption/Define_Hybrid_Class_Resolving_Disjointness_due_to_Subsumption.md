# 

 Graphical representation



__Diagram__ 





[Image:Djedidi LOP1 WOP09.pdf](../Image/Djedidi_LOP1_WOP09.pdf.md "Image:Djedidi LOP1 WOP09.pdf") 





# 

 General information




|  |  |
| --- | --- |
|  Name  |  Define Hybrid Class Resolving Disjointness due to Subsumption  |
|  Also known as  |  |
|  Author(s)  |  Rim Djedidi, Marie-Aude Aufaure  |
|  SubmittedBy  | [RimDjedidi](http://ontologydesignpatterns.org/wiki/index.php?title=User:RimDjedidi&action=edit&redlink=1 "User:RimDjedidi (not yet written)")  |



  





# 

 Description




|  |  |
| --- | --- |
|  Motivation  |  Problem :  This pattern helps resolving a logical inconsistency triggered by a situation of disjoint classes subsuming a common sub-class. When we need to define – for some modeling issues related to domain of interest – a class as a sub-class of two disjoint classes, a disjointness inconsistency is caused.The problem can be illustrated by the following scenario: let’s consider a class Sub\_Class defined as a sub-class of a class Disjoint\_Class 2; and a class Disjoint\_Class 1 disjoint with the Disjoint\_Class 2 (see diagram in attached file). If we need to add a sub-class relation between the Sub\_Class and the Disjoint\_Class 1, this generates a disjointness inconsistency:  - If the extension of the Sub\_Class contains individuals instantiating this sub-class, the logical inconsistency will be extended to the knowledge base;- If the Sub\_Class is not instantiated to individuals, it will be diagnosed as an unsatisfiable class.  To solve this inconsistency, one can think about deleting the disjointness axiom. However, this can alter the semantics expressed in the ontology, and negatively affect consistency checking and automatic evaluation of existing individuals as explained in [1].This pattern tackles the questions of how to resolve the inconsistency caused by such kind of subsumption while preserving existing knowledge.  [1] Völker, J., Vrandecic, D., Sure, Y., Hotho, A.: Learning Disjointness. In F., Enrico, K., Michael, May. Wolfgang (Eds.). Proceedings of the 4th European Semantic Web Conference, ESWC 2007. LNCS: Vol. 4519 pp: 175-189. (2007)  |
|  Aim  |  Intent: The purpose of this pattern is to support the semantics of a subsumption defined under two disjoint classes and resolve the resulting inconsistency.  Covered Requirements: The pattern solves a problem of disjointness inconsistency caused by a subsumption relation without deleting the disjointness axiom so that existing knowledge can be preserved.  |
|  Solution description  |  The pattern resolves a disjointness inconsistency –due to a subsumption–by defining a Hybrid Class based on the definition of disjoint classes implicated in the inconsistency; and redistributing correctly sub-class relations between the sub-class, the hybrid class, and the most specific common super-class of the disjoint classes implicated. The definition of the Hybrid Class is the union (OR) of the definitions of the disjoint classes.  The application of the solution can be described by the following process (see diagram in attached file):  1.The pattern defines a Hybrid Class as a union of the definitions of the disjoint classes implicated in the inconsistency to be resolved;2.The pattern defines a subsumption between the most specific common super-class of the disjoint classes implicated in the inconsistency, and the Hybrid Class created;3.The pattern defines a subsumption between the Hybrid Class and the sub-class involved in the inconsistency.  Consequences: The application of the pattern resolves the disjointness inconsistency (even if the involved sub-class is instantiated by individuals) and preserves existing knowledge. As a Logical OP, this pattern is independent from a specific domain of interest. However, it depends on the expressivity of the logical formalism used for the representation of the ontology. Therefore, the language of the targeted ontology should allow expressing class union.  |
|  Elements  |  The following elements are manipulated by the pattern:  ID of the sub-class (Sub\_Class).ID of the first disjoint class (Disjoint\_Class 1).ID of the second disjoint class (Disjoint\_Class 2).ID of the most specific common super-class of the disjoint classes involved (Common\_Super\_Class).  |
|  Implementation  |  |
|  Reusable component  |  |
|  Component type  |  |



  





# 

 Example




|  |  |
| --- | --- |
|  Problem example  |  Let’s consider the OWL ontology O defined by the following axioms:  {Animal ⊑Fauna-Flora, Plant ⊑Fauna-Flora, Carnivorous-Plant ⊑Plant, Plant ⊑ Not(Animal)}  If we apply a change to the ontology defining Carnivorous-Plant class as a sub-class of the class Animal, we cause a disjointness inconsistency. The proposed pattern resolves this kind of inconsistency.  |
|  Pattern solution example  |  |
|  Consequences  |  The application of the pattern to resolve the example above is performed as follow:  1.The pattern defines a class Animal\_Plant as a union of the definitions of the disjoint classes Animal and Plant;2.The pattern defines a subsumption between the most specific common super-class of the disjoint classes Fauna-Flora and the hybrid class created Animal\_Plant;3.The pattern defines a subsumption between the defined hybrid class Animal\_Plant and the sub-class Carnivorous-Plant involved in the inconsistency.  |



  





# 

 Pattern reference




|  |  |
| --- | --- |
|  Origin  |  |
|  Known use  |  |
|  Reference  |  |
|  Related ODP  |  |
|  Used in combination with  |  |
|  Test  |  |



# 

 Scenarios




__Scenarios about Define Hybrid Class Resolving Disjointness due to Subsumption__ 


 No scenario is added to this Content OP.
 




# 

 Reviews




__Reviews about Define Hybrid Class Resolving Disjointness due to Subsumption__ 



|  Review article  | [Posted on](../Property/CreationDate.md "Property:CreationDate")  | [About revision (current is 9702)](../Property/ReviewAboutVersion.md "Property:ReviewAboutVersion")  |
| --- | --- | --- |
| [BorisVillazón-Terrazas about Define Hybrid Class Resolving Disjointness due to Subsomption](../Reviews/BorisVillazón-Terrazas_about_Define_Hybrid_Class_Resolving_Disjointness_due_to_Subsomption.md "Reviews:BorisVillazón-Terrazas about Define Hybrid Class Resolving Disjointness due to Subsomption")  |  2455084  9 September 2009  |  5627  5,627  |
| [WimPeters about Define Hybrid Class Resolving Disjointness due to Subsomption](../Reviews/WimPeters_about_Define_Hybrid_Class_Resolving_Disjointness_due_to_Subsomption.md "Reviews:WimPeters about Define Hybrid Class Resolving Disjointness due to Subsomption")  |  2455084  9 September 2009  |  5753  5,753  |
| [RinkeHoekstra about Define Hybrid Class Resolving Disjointness due to Subsumption](../Community/RinkeHoekstra_about_Define_Hybrid_Class_Resolving_Disjointness_due_to_Subsumption.md "Community:RinkeHoekstra about Define Hybrid Class Resolving Disjointness due to Subsumption")  |  2455130  25 October 2009  |  5867  5,867  |
| [RinkeHoekstra about Define Hybrid Class Resolving Disjointness due to Subsumption 2](../Community/RinkeHoekstra_about_Define_Hybrid_Class_Resolving_Disjointness_due_to_Subsumption_2.md "Community:RinkeHoekstra about Define Hybrid Class Resolving Disjointness due to Subsumption 2")  |  2455130  25 October 2009  |  5867  5,867  |



 This revision (revision ID
 __9702__ 
 ) takes in account the reviews: none
 



 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Define_Hybrid_Class_Resolving_Disjointness_due_to_Subsumption&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Define_Hybrid_Class_Resolving_Disjointness_due_to_Subsumption&action=evaluation") 





  





# 

 Modeling issues




__Modeling issues about Define Hybrid Class Resolving Disjointness due to Subsumption__ 


 There is no Modeling issue related to this proposal.
 




  





# 

 References



  






|  |  Submission to event [WOP:2009](../WOP/2009.md "WOP:2009")  |
| --- | --- |
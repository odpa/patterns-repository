# 

 Graphical representation



__Diagram__ 
_(this article has no graphical representation)_ 




# 

 General information




|  |  |
| --- | --- |
|  Name  |  OnlynessIsLoneliness  |
|  Also known as  |  OIL  |
|  Author(s)  |  Catherine Roussey, Oscar Corcho  |
|  SubmittedBy  | [Catherine Roussey](http://ontologydesignpatterns.org/wiki/index.php?title=User:Catherine_Roussey&action=edit&redlink=1 "User:Catherine Roussey (not yet written)")  , [Oscar Corcho](http://ontologydesignpatterns.org/wiki/index.php?title=User:Oscar_Corcho&action=edit&redlink=1 "User:Oscar Corcho (not yet written)")  |



  





# 

 Description




|  |  |
| --- | --- |
|  Motivation  |  Our work is based on the debugging process of real ontologies that have been developed by domain experts, who are not necessarily too familiar with DL, and hence can misuse DL constructors and misunderstand the semantics of some OWL expressions, leading to unwanted unsatisfiable classes. Our patterns were first found during the debugging process of a medium-sized OWL ontology (165 classes) developed by a domain expert in the area of hydrology called HydrOntology. The first version of this ontology had a total of 114 unsatisfiable classes. The information provided by the debugging systems used on (root) unsatisfiable classes was not easily understandable by domain experts to find the reasons for their unsatisfiability. And in several occasions during the debugging process the generation of justifications for unsatisfiability took several hours, what made these tools hard to use. Using this debugging process and several other real ontologies debugging one, we found out that in several occasions domain experts were just changing axioms from the original ontology in a somehow random manner, even changing the intended meaning of the definitions instead of correcting errors in their formalisations.  We have identified a set of patterns that are commonly used by domain experts in their DL formalisations and OWL implementations, and that normally result in unsatisfiable classes or modelling errors. Thus they are antipatterns. A Koenig define antipatterns as patterns that appear obvious but are ineffective or far from optimal in practice, representing worst practice about how to structure and build software. We also have made an effort to identify common alternatives for providing solutions to them, so that they can be used by domain experts to debug their ontologies.  All these antipatterns come from a misuse and misunderstanding of DL expressions by ontology developers. Thus they are all Logical AntiPatterns (LAP): they are independent from a specific domain of interest, but dependent on the expressivity of the logical formalism used for the representation.  |
|  Aim  |  The ontology developer created a universal restriction to say that C1 instances can only be linked with property R to C2 instances. Next, a new universal restriction is added saying that C1 instances can only be linked with R to C3 instances, with C2 and C3 disjoint. In general, this is because the ontology developer forgot the previous axiom in the same class or in the parent class.  |
|  Solution description  |  C1 subClassOf R only C2; C1 subClassOf R only C3; C2 disjointWith C3  If it makes sense, we propose to the domain expert to transform the two universal restrictions into only one that refers to the disjunction of C2 and C3.  C1 subClassOf R only (C2 or C3); C2 disjointWith C3  other alternative solutions could be:  1) suppress the disjointness axiom.  2) create two sublass of C1 such as: C1.1 subClassOf C1; C1.1 subClassOf R only C2; C1.2 subClassOf C1; C1.2 subClassOf R only C3; C2 disjointWith C3;  3) create C4 such as C4 isEqualTo C2 or C3; C1 subClassOf R only C4; C2 disjointWith C3.  4) create two subproperty of R: R2 subPropertyOf R; R3 subProperty of R; C1 subClassOf R2 only C2; C1 subClassOf R3 only C3; C2 disjointWith C3.  |
|  Elements  |  |
|  Implementation  |  |
|  Reusable component  |  |
|  Component type  |  |



  





# 

 Example




|  |  |
| --- | --- |
|  Problem example  |  Transtitional\_Waters subClassOf is\_nearby only Sea\_Waters; Transitional\_Waters subClassOf is\_nearby only River\_Mouths; River\_Mouths disjointWith Sea\_Waters  see Aguas\_de\_Transicion concept in hydrontology.  Wet\_Zone subClassOf Wetlands and are\_inundated only Sea\_Water and are\_inundated only Surface\_Water and are\_inundated min 1 Thing;  see Zona\_Humeda concept in hydrontology.  |
|  Pattern solution example  | [http://www.dia.fi.upm.es/~ocorcho/OWLDebugging/](http://www.dia.fi.upm.es/%7Eocorcho/OWLDebugging/ "http://www.dia.fi.upm.es/%7Eocorcho/OWLDebugging/")  |
|  Consequences  |  Transtitional\_Waters subClassOf is\_nearby only (Sea\_Waters or River\_Mouths); River\_Mouths disjointWith Sea\_Waters  Wet\_Zone subClassOf Wetlands and are\_inundated only (Sea\_Water or Surface\_Water) and are\_inundated min 1 Thing;  |



  





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

 Additional information



# 

 Scenarios




__Scenarios about OnlynessIsLoneliness (OIL)__ 


 No scenario is added to this Content OP.
 




# 

 Reviews




__Reviews about OnlynessIsLoneliness (OIL)__ 



|  Review article  | [Posted on](../Property/CreationDate.md "Property:CreationDate")  | [About revision (current is 9706)](../Property/ReviewAboutVersion.md "Property:ReviewAboutVersion")  |
| --- | --- | --- |
| [LuigiIannone about OnlynessIsLoneliness (OIL)](Reviews%253ALuigiIannone_about_OnlynessIsLoneliness_(OIL).html "Reviews:LuigiIannone about OnlynessIsLoneliness (OIL)")  |  2455076  1 September 2009  |  5621  5,621  |
| [AlessandroAdamou about OnlynessIsLoneliness (OIL)](Reviews%253AAlessandroAdamou_about_OnlynessIsLoneliness_(OIL).html "Reviews:AlessandroAdamou about OnlynessIsLoneliness (OIL)")  |  2455085  10 September 2009  |  5777  5,777  |
| [StefanoDavid about OnlynessIsLoneliness (OIL)](Reviews%253AStefanoDavid_about_OnlynessIsLoneliness_(OIL).html "Reviews:StefanoDavid about OnlynessIsLoneliness (OIL)")  |  2455085  10 September 2009  |  5787  5,787  |
| [RinkeHoekstra about OnlynessIsLoneliness (OIL)](Community%253ARinkeHoekstra_about_OnlynessIsLoneliness_(OIL).html "Community:RinkeHoekstra about OnlynessIsLoneliness (OIL)")  |  2455129  24 October 2009  |  5787  5,787  |



 This revision (revision ID
 __9706__ 
 ) takes in account the reviews: none
 



 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:OnlynessIsLoneliness_%28OIL%29&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:OnlynessIsLoneliness_%28OIL%29&action=evaluation") 





  





# 

 Modeling issues




__Modeling issues about OnlynessIsLoneliness (OIL)__ 


 There is no Modeling issue related to this proposal.
 




  





# 

 References



  






|  |  Submission to event [WOP:2009](../WOP/2009.md "WOP:2009")  |
| --- | --- |
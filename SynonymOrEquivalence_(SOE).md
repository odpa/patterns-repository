# 

 Graphical representation



__Diagram__ 
_(this article has no graphical representation)_ 




# 

 General information




|  |  |
| --- | --- |
|  Name  |  SynonymOrEquivalence (SOE)  |
|  Also known as  |  |
|  Author(s)  |  |
|  SubmittedBy  | [Catherine Roussey](http://ontologydesignpatterns.org/wiki/index.php?title=User:Catherine_Roussey&action=edit&redlink=1 "User:Catherine Roussey (not yet written)")  , [Oscar Corcho](http://ontologydesignpatterns.org/wiki/index.php?title=User:Oscar_Corcho&action=edit&redlink=1 "User:Oscar Corcho (not yet written)")  |



  





# 

 Description




|  |  |
| --- | --- |
|  Motivation  |  We have identified a set of patterns that are commonly used by domain experts in their DL formalisations and OWL implementations, and that normally result in unsatisfiable classes or modelling errors. As aforementioned all these antipatterns come from a misuse and misunderstanding of DL expressions by ontology developers. Thus they are all Logical AntiPatterns (LAP): they are independent from a specific domain of interest, but dependent on the expressivity of the logical formalism used for the representation. We have categorized them into three groups:  |
|  Aim  |  The ontology developer wants to express that two classes C1 and C2 are identical. This is not very useful in a single ontology that does not import others. Indeed, what the ontology developer generally wants to represent is a terminological synonymy relation: the class C1 has two labels: C1 and C2. Usually one of the classes is not used anywhere else in the axioms defined in the ontology.  |
|  Solution description  |  C1 isEquivalentTo C2  The proposal for avoiding this antipattern is the following (if C2 is the less used term in the ontology) add all the comments and labels of C2 into C1 and remove C2  |
|  Elements  |  |
|  Implementation  |  |
|  Reusable component  |  |
|  Component type  |  |



  





# 

 Example




|  |  |
| --- | --- |
|  Problem example  |  Subterranean\_Watercourses isEquivalentTo Subterranean\_Rivers  see Corriente\_Subterranea concept in Hydrontology  |
|  Pattern solution example  | [http://www.dia.fi.upm.es/~ocorcho/OWLDebugging/](http://www.dia.fi.upm.es/%7Eocorcho/OWLDebugging/ "http://www.dia.fi.upm.es/%7Eocorcho/OWLDebugging/")  |
|  Consequences  |  |



  





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




__Scenarios about SynonymOrEquivalence (SOE)__ 


 No scenario is added to this Content OP.
 




# 

 Reviews




__Reviews about SynonymOrEquivalence (SOE)__ 



|  Review article  | [Posted on](../Property/CreationDate "Property:CreationDate")  | [About revision (current is 9708)](../Property/ReviewAboutVersion "Property:ReviewAboutVersion")  |
| --- | --- | --- |
| [MartaSabou about SynonymOrEquivalence (SOE)](../Reviews/MartaSabou_about_SynonymOrEquivalence_(SOE)).html "Reviews:MartaSabou about SynonymOrEquivalence (SOE)")  |  2455083  8 September 2009  |  5617  5,617  |
| [GerdGroener about SynonymOrEquivalence (SOE)](../Reviews/GerdGroener_about_SynonymOrEquivalence_(SOE)).html "Reviews:GerdGroener about SynonymOrEquivalence (SOE)")  |  2455083  8 September 2009  |  5709  5,709  |



 This revision (revision ID
 __9708__ 
 ) takes in account the reviews: none
 



 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:SynonymOrEquivalence_%28SOE%29&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:SynonymOrEquivalence_%28SOE%29&action=evaluation") 





  





# 

 Modeling issues




__Modeling issues about SynonymOrEquivalence (SOE)__ 


 There is no Modeling issue related to this proposal.
 




  





# 

 References



  






|  |  Submission to event [WOP:2009](../WOP/2009 "WOP:2009")  |
| --- | --- |
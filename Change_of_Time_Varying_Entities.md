# 

 Graphical representation



__Diagram__ 





[![Image:Before-after.png](images/9/97/Before-after.png)](../Image/Before-after.png "Image:Before-after.png")





# 

 General information




|  |  |
| --- | --- |
|  Name  |  Change of Time Varying Entities  |
|  Also known as  |  |
|  Author(s)  |  |
|  SubmittedBy  | [MeganKatsumi](../User/MeganKatsumi "User:MeganKatsumi")  |



  





# 

 Description




|  |  |
| --- | --- |
|  Motivation  |  This work is motivated by a project on urban informatics, iCity \cite{miller2014}, in which our role is to develop an ontology capable of representing the urban system -- both the information that is collected, as well as information that is simulated and analyzed by various research groups. Such an ontology would not only provide valuable integration and inference capabilities for the research groups internally, it would support sharing of the results on the Semantic Web, in particular for reproducibility of simulations and analyses. Owing to its popularity, tool support, and role as the de facto standard for the Semantic Web, OWL was selected as the logical language for the formalization of the ontology.  To capture the urban domain, the notion of change over time is a critical requirement: the population, family and household structures, transportation networks, and the locations of particular transportation vehicles (buses, household vehicles, and so on) are all subject to change.  Change over time plays a role in many domains, and is by no means a new research topic. In fact, several approaches for capturing change in OWL have been proposed in the literature. Despite these solutions, we have found that Semantic Web practitioners currently lack clear and precise method for how to apply these approaches to capture change at a domain level, whether reusing an atemporal ontology or developing an ontology from scratch.  |
|  Aim  |  The work presented here aims to provide a straightforward, pattern-based guide to implementing a representation of change for any given domain. In particular, we provide consideration for the reuse of atemporal ontologies, as our experience has led us to believe that this is an important design task.  |
|  Solution description  |  The solution is based on the 4D Fluents Ontology [2], as reinterpreted by Krieger [1].  [1] Krieger, H.U.: Where temporal description logics fail: Representing temporally changing relationships. In: Annual Conference on Arti�cial Intelligence. pp. 249-257. Springer (2008)  [2] Welty, C., Fikes, R., Makarios, S.: A reusable ontology for Fuents in owl. In: Formal Ontology in Information Systems (FOIS). vol. 150, pp. 226-236 (2006)  |
|  Elements  |  |
|  Implementation  |  A foundational ontology of change is to be imported. Then, based on the foundational classes of TimeVaryingEntity and Manifestation, a simple set of logical design patterns may be applied. A pragmatic guideline to support this process is provided in the accompanying paper submission.  Several additional logical design patterns are identified, along with descriptions of how they could be employed to provide extended semantics in a representation beyond OWL (e.g. SWRL), should additional reasoning capabilities be required.  |
|  Reusable component  | [http://ontology.eil.utoronto.ca/icity/Change](http://ontology.eil.utoronto.ca/icity/Change "http://ontology.eil.utoronto.ca/icity/Change")  |
|  Component type  |  |



  





# 

 Example




|  |  |
| --- | --- |
|  Problem example  |  |
|  Pattern solution example  |  |
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




__Scenarios about Change of Time Varying Entities__ 


 No scenario is added to this Content OP.
 




# 

 Reviews




__Reviews about Change of Time Varying Entities__ 


 There is no review about this proposal.
This revision (revision ID
 __13879__ 
 ) takes in account the reviews: none
 



 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Change_of_Time_Varying_Entities&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Change_of_Time_Varying_Entities&action=evaluation") 





  





# 

 Modeling issues




__Modeling issues about Change of Time Varying Entities__ 


 There is no Modeling issue related to this proposal.
 




  





# 

 References
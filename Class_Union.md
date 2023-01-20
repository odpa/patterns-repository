# 

 Graphical representation



__Diagram__ 





[![Image:class-union.png](public/images/5/53/Class-union.png)](../Image/Class-union.png "Image:class-union.png")





# 

 General information




|  |  |
| --- | --- |
|  Name  |  Class Union  |
|  Also known as  |  |
|  Author(s)  |  François Scharffe  |
|  SubmittedBy  | [FrancoisScharffe](../User/FrancoisScharffe "User:FrancoisScharffe")  |



  





# 

 Description




|  |  |
| --- | --- |
|  Domain (if applicable)  |  |
|  Alignment problem addressed  |  A class denoted in one ontology is the union of two classes in the second ontology  |
|  Alignment solution  |  This pattern establishes a correspondence between a pair of classes in the first ontology and a single class in the other. This pattern is agnostic as to whether the correspondence is unidirectional or bidirectional. Direction of the correspondence can be achieved through combination of the pattern with the Class equivalence or Class Subsumption pattern.  |
|  Alignment workflow  |  |
|  Reusable component  |  |



  





# 

 Example




|  |  |
| --- | --- |
|  Problem example  |  |
|  Solution example  |  Exemple in the alignment language RDF/XML syntax: ```<Cell> <entity1>  <Class>   <or rdf:ParseType="Collection">    <Class rdf:about="O1:PersonBornInCanada"/>    <Class rdf:about="O1:PersonWithCanadianParent"/>   </or>  </Class> </entity1> <entity2>  <Class rdf:about="O2:CanadianCitizenByBirth"/> </entity2> <relation>equivalence</relation></Cell>``` |
|  Consequences  |  A correspondence is established between the two classes  |



  





# 

 Reference




|  |  |
| --- | --- |
|  Origin  |  |
|  Known use  |  |
|  Reference  |  |
|  Related to  | [Submissions:Class equivalence](../Submissions/Class_equivalence "Submissions:Class equivalence")  , [Submissions:Class subsumption](../Submissions/Class_subsumption "Submissions:Class subsumption")  |
|  Test  |  |



  





# 

 Scenarios




__Scenarios about Class Union__ 


 No scenario is added to this Content OP.
 




# 

 Reviews




__Reviews about Class Union__ 


 There is no review about this proposal.
This revision (revision ID
 __8503__ 
 ) takes in account the reviews: none
 



 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Class_Union&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Class_Union&action=evaluation") 





  





# 

 Modeling issues




__Modeling issues about Class Union__ 


 There is no Modeling issue related to this proposal.
 




  





# 

 References
#  Graphical representation


__Diagram__




[![Image:class-intersection.png](./Class-intersection.png)](../Image/Class-intersection.png.md "Image:class-intersection.png")




#  General information




|  |  |
| --- | --- |
|  Name |  Class intersection |
|  Also known as |  |
|  Author(s) |  François Scharffe |
|  SubmittedBy | [FrancoisScharffe](../User/FrancoisScharffe.md "User:FrancoisScharffe") |


  




#  Description




|  |  |
| --- | --- |
|  Domain (if applicable) | [General](http://ontologydesignpatterns.org/wiki/index.php?title=General&action=edit&redlink=1 "General (not yet written)") |
|  Alignment problem addressed |  A class denoted in one ontology is the intersection of two classes in the secondontology. |
|  Alignment solution |  This pattern establishes a correpondence between a pair of classes in the first ontology and a single class in the other. This pattern is agnostic as to whether the correspondence is unidirectional or bidirectional. Direction of the correspondence can be achieved through combination of the pattern with the Equivalent Class or Class subsumption patterns. |
|  Alignment workflow |  |
|  Reusable component |  |


  




#  Example




|  |  |
| --- | --- |
|  Problem example |  |
|  Solution example |  Example solution in the ontology alignment language:```<Cell> <entity1>  <Class>   <and rdf:ParseType="Collection">    <Class rdf:about="o1:Human"/>     <Class rdf:about="o1:FemaleAnimal/>   </and>  </Class> </entity1> <entity2>  <Class rdf:about="o2:HumanFemale"/> </entity2> <relation>equivalence</relation></Cell>``` |
|  Consequences |  A correspondence is established between a class in a source ontology and the intersection of a set of classes in a target ontology. |


  




#  Reference




|  |  |
| --- | --- |
|  Origin |  |
|  Known use |  |
|  Reference |  |
|  Related to | [Submissions:Class equivalence](../Class_equivalence/Class_equivalence.md "Submissions:Class equivalence"), [Submissions:Class subsumption](../Class_subsumption/Class_subsumption.md "Submissions:Class subsumption") |
|  Test |  |


  




#  Scenarios



__Scenarios about Class intersection__
No scenario is added to this Content OP.




#  Reviews



__Reviews about Class intersection__
There is no review about this proposal.
This revision (revision ID __8959__) takes in account the reviews: none


Other info at [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Class_intersection&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Class_intersection&action=evaluation")




  




#  Modeling issues



__Modeling issues about Class intersection__
There is no Modeling issue related to this proposal.




  




#  References
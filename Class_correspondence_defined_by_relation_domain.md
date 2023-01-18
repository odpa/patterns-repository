# 

 Graphical representation



__Diagram__ 





[![Image:Class-by-relation-domain.png](../images/b/b4/Class-by-relation-domain.png)](../Image/Class-by-relation-domain.png "Image:Class-by-relation-domain.png")





# 

 General information




|  |  |
| --- | --- |
|  Name  |  Class correspondence defined by relation domain  |
|  Also known as  |  Subclass correspondence defined by relation domain  |
|  Author(s)  |  Francois Scharffe  |
|  SubmittedBy  | [FrancoisScharffe](../User/FrancoisScharffe "User:FrancoisScharffe")  |



  





# 

 Description




|  |  |
| --- | --- |
|  Domain (if applicable)  | [General](http://ontologydesignpatterns.org/wiki/index.php?title=General&action=edit&redlink=1 "General (not yet written)")  |
|  Alignment problem addressed  |  A class in one ontology is equivalent to the subclass of a class in a second ontology of exactly those instances which are in the domain of a specified relation.  |
|  Alignment solution  |  This pattern establishes a correspondence between a class and relation in one ontology and a class in another  |
|  Alignment workflow  |  |
|  Reusable component  |  |



  





# 

 Example




|  |  |
| --- | --- |
|  Problem example  |  |
|  Solution example  |  <Cell> ``` <entity1>   <Class rdf:about="o1:Parent"/> </entity1> <entity2>  <Class>   <and>    <Class rdf:about="o2:Animal">   </and>   <and>    <AttributeOccurenceCondition>     <onAttribute>      <Relation rdf:about="o2:children"/>     </onAttribute>    <AttributeOccurenceCondition>   </and>  </Class> </entity2> <relation>subsumption</relation></Cell>``` |
|  Consequences  |  |



  





# 

 Reference




|  |  |
| --- | --- |
|  Origin  |  |
|  Known use  |  |
|  Reference  |  |
|  Related to  | [Submissions:Class by Attribute Occurence Correspondence](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Class_by_Attribute_Occurence_Correspondence&action=edit&redlink=1 "Submissions:Class by Attribute Occurence Correspondence (not yet written)")  |
|  Test  |  |



  





# 

 Scenarios




__Scenarios about Class correspondence defined by relation domain__ 


 No scenario is added to this Content OP.
 




# 

 Reviews




__Reviews about Class correspondence defined by relation domain__ 


 There is no review about this proposal.
This revision (revision ID
 __8790__ 
 ) takes in account the reviews: none
 



 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Class_correspondence_defined_by_relation_domain&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Class_correspondence_defined_by_relation_domain&action=evaluation") 





  





# 

 Modeling issues




__Modeling issues about Class correspondence defined by relation domain__ 


 There is no Modeling issue related to this proposal.
 




  





# 

 References
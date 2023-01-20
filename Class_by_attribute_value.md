# 

 Graphical representation



__Diagram__ 





[![Image:class-by-attribute-value.png](public/images/f/fa/Class-by-attribute-value.png)](../Image/Class-by-attribute-value.png "Image:class-by-attribute-value.png")





# 

 General information




|  |  |
| --- | --- |
|  Name  |  Class by attribute value  |
|  Also known as  |  |
|  Author(s)  |  Francois Scharffe  |
|  SubmittedBy  | [FrancoisScharffe](../User/FrancoisScharffe "User:FrancoisScharffe")  |



  





# 

 Description




|  |  |
| --- | --- |
|  Domain (if applicable)  |  |
|  Alignment problem addressed  |  A class in one ontology is equivalent to the subclass of an ontology in a second  ontology of exactly those instances which have a specified property value.  |
|  Alignment solution  |  This pattern establishes a mapping between a class/property/property-value combination in one ontology and a class in another. This pattern is agnostic as to whether the mapping is unidirectional or bidirectional direction of the mapping can be achieved through combination of the pattern with the equivalent classes or class subsumption correspondence patterns.  |
|  Alignment workflow  |  The scope of a class in one ontology is narrower than the scope of a class  in the other ontology. Both scopes can be matched by restricting one class to those instances having a particular value for a certain property.  |
|  Reusable component  |  |



  





# 

 Example




|  |  |
| --- | --- |
|  Problem example  |  |
|  Solution example  |  Example in EDOAL: ```<Cell> <entity1>  <Class>   <and>    <Class rdf:about="vin:Vin">   </and>   <and>    <AttributeValueCondition>     <onAttribute>      <Property rdf:about="vin:terroir"/>     </onAttribute>     <comparator>xsd:Equal</comparator>     <value>geo:Bordelais</value>    </AttributeValueCondition>   </and>  </Class> </entity1> <entity2>  <Class rdf:about="wine:BordeauxWine"/> </entity2></Cell>``` |
|  Consequences  |  |



  





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




__Scenarios about Class by attribute value__ 


 No scenario is added to this Content OP.
 




# 

 Reviews




__Reviews about Class by attribute value__ 


 There is no review about this proposal.
This revision (revision ID
 __8958__ 
 ) takes in account the reviews: none
 



 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Class_by_attribute_value&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Class_by_attribute_value&action=evaluation") 





  





# 

 Modeling issues




__Modeling issues about Class by attribute value__ 


 There is no Modeling issue related to this proposal.
 




  





# 

 References
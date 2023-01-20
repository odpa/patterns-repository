# 

 Graphical representation



__Diagram__ 





[![Image:Symmetric_n-ary_relationship_v1.jpg‎](public/images/4/49/Symmetric_n-ary_relationship_v1.jpg)](../Image/Symmetric_n-ary_relationship_v1.jpg "Image:Symmetric_n-ary_relationship_v1.jpg‎")





# 

 General information




|  |  |
| --- | --- |
|  Name  |  Symmetric n-ary relationship  |
|  Also known as  |  |
|  Author(s)  |  MariaPoveda, MariCarmenSuarezFigueroa  |
|  SubmittedBy  | [MariaPoveda](../User/MariaPoveda "User:MariaPoveda")  , [MariCarmenSuarezFigueroa](../User/MariCarmenSuarezFigueroa "User:MariCarmenSuarezFigueroa")  |



  





# 

 Description




|  |  |
| --- | --- |
|  Motivation  |  The symmetric n-ary relationship pattern emerged from the need of modelling distances among two points.  This problem is a clear case of an n-ary relationship where the relation between two points needs a further argument to represent the distance between such points.  Once we have applied the n-ary pattern for this use case ( [http://www.w3.org/TR/swbp-n-aryRelations/#useCase1](http://www.w3.org/TR/swbp-n-aryRelations/#useCase1 "http://www.w3.org/TR/swbp-n-aryRelations/#useCase1")  ), we can realize that the origin and the destination of the n-ary relation belong to the same class. In addition, the value for the relationship is the same to represent the distance from A to B and vice-versa. Then, if we want to represent both distances we should instanciate the pattern twice, from A to B and vice-versa, resulting in a redundant representation.  |
|  Aim  |  This pattern allows representing symmetric n-ary relationships, i.e. binary relationships between two elements that need a further argument that has the same value for both directions of the relationship.  If SNAry is the symmetric n-ary relationship and z is its value for the elements x and y, then:SNAry(x,y)=z iff SNAry(y,x)=z  |
|  Solution description  |  A class to represent the n-ary relationship together with the value for the further needed argument (Relationship or Attribute) has been created.  A relationship between the abovementioned class and the classes involved in the symmetric n-ary relationship is created.  |
|  Elements  |  Class, Relationship, Attribute  Axioms: cardinality and equivalentClass  |
|  Implementation  |  |
|  Reusable component  |  |
|  Component type  |  |



  





# 

 Example




|  |  |
| --- | --- |
|  Problem example  |  For example, we might want to represent the distance expressed in kilometres between two places.  |
|  Pattern solution example  | [http://ontologydesignpatterns.org/wiki/images/b/bd/Symmetric\_n-ary\_relationship\_distance.jpg](public/images/b/bd/Symmetric_n-ary_relationship_distance.jpg "http://ontologydesignpatterns.org/wiki/public/images/b/bd/Symmetric_n-ary_relationship_distance.jpg")  |
|  Consequences  |  The main advantage of this pattern is that allows representing distance between places without including redundancy in the ontology.  |



  





# 

 Pattern reference




|  |  |
| --- | --- |
|  Origin  |  Modelling distance between stages of St James Way during the Geobuddies ontology network development ( [http://geobuddies.dia.fi.upm.es](http://geobuddies.dia.fi.upm.es "http://geobuddies.dia.fi.upm.es")  ).  |
|  Known use  |  Geobuddies ontology network  |
|  Reference  |  |
|  Related ODP  | [N-ary Relation: New Class (LP-NR -01)](http://ontologydesignpatterns.org/wiki/index.php?title=N-ary_Relation:_New_Class_%28LP-NR_-01%29&action=edit&redlink=1 "N-ary Relation: New Class (LP-NR -01) (not yet written)")  |
|  Used in combination with  |  |
|  Test  |  |



# 

 Additional information



# 

 Scenarios




__Scenarios about Symmetric n-ary relationship__ 


 No scenario is added to this Content OP.
 




# 

 Reviews




__Reviews about Symmetric n-ary relationship__ 



|  Review article  | [Posted on](../Property/CreationDate "Property:CreationDate")  | [About revision (current is 10106)](../Property/ReviewAboutVersion "Property:ReviewAboutVersion")  |
| --- | --- | --- |
| [OlafNoppens about Symmetric n-ary relationship](../Reviews/OlafNoppens_about_Symmetric_n-ary_relationship "Reviews:OlafNoppens about Symmetric n-ary relationship")  |  2455456  16 September 2010  |  10066  10,066  |
| [RimDJEDIDI about Symmetric n-ary relationship](../Reviews/RimDJEDIDI_about_Symmetric_n-ary_relationship "Reviews:RimDJEDIDI about Symmetric n-ary relationship")  |  2455456  16 September 2010  |  10106  10,106  |
| [AlessandroAdamou about Symmetric n-ary relationship](../Reviews/AlessandroAdamou_about_Symmetric_n-ary_relationship "Reviews:AlessandroAdamou about Symmetric n-ary relationship")  |  2455456  16 September 2010  |  10106  10,106  |



 This revision (revision ID
 __10106__ 
 ) takes in account the reviews: none
 



 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Symmetric_n-ary_relationship&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Symmetric_n-ary_relationship&action=evaluation") 





  





# 

 Modeling issues




__Modeling issues about Symmetric n-ary relationship__ 


 There is no Modeling issue related to this proposal.
 




  





# 

 References



  






|  |  Submission to event [WOP:2010](../WOP/2010 "WOP:2010")  |
| --- | --- |
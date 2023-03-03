# 

 Graphical representation



__Diagram__ 





[![Image:LP-IN-01v1_general.jpg](./20100928092414!LP-IN-01v1_general.jpg)](../Image/LP-IN-01v1_general.jpg.md "Image:LP-IN-01v1_general.jpg")





# 

 General information




|  |  |
| --- | --- |
|  Name  |  Summarization of an inverse n-ary relation  |
|  Also known as  |  |
|  Author(s)  |  MariaPoveda, MariCarmenSuarezFigueroa  |
|  SubmittedBy  | [MariaPoveda](../User/MariaPoveda.md "User:MariaPoveda")  , [MariCarmenSuarezFigueroa](../User/MariCarmenSuarezFigueroa.md "User:MariCarmenSuarezFigueroa")  |



  





# 

 Description




|  |  |
| --- | --- |
|  Motivation  |  An n-ary relationship should be used to address any of the following situations:  (a) a binary relationship that really needs a further argument. For example, to represent the distance between two places.  (b) two binary relationships that always go together and should be represented as one n-ary relation. For example, to represent the value of an observation (e.g. temperature in a patient) and its trend.  (c) a relationship that is really amongst several things. For example, to represent the spatial location of a person in a given point of time.  On the one hand, the motivation of this pattern is to express the inverse relationship of an n-ary relation where there are distinguished participants. This means that the relationship exists mainly between two entities and the rest of entities involved in the relationship can be considered as additional arguments. This situation can also mean that there is a single individual standing out as the subject or the "owner" of the relation.  On the other hand, the motivation is to provide a shorcut for queries that involve the distinguished participants in the n-ary relationship.  This pattern is inspired on the third consideration shown in [http://www.w3.org/TR/swbp-n-aryRelations/#choosingPattern1or2](http://www.w3.org/TR/swbp-n-aryRelations/#choosingPattern1or2 "http://www.w3.org/TR/swbp-n-aryRelations/#choosingPattern1or2")  . The difference in our case is that there are at least two distinguished participants in the relationship. Therefore, this pattern could be considered as an extension of the third consideration shown in [http://www.w3.org/TR/swbp-n-aryRelations./#choosingPattern1or2](http://www.w3.org/TR/swbp-n-aryRelations./#choosingPattern1or2 "http://www.w3.org/TR/swbp-n-aryRelations./#choosingPattern1or2")  applied to the use case of n-ary relationships described in [http://www.w3.org/TR/swbp-n-aryRelations/#useCase1](http://www.w3.org/TR/swbp-n-aryRelations/#useCase1 "http://www.w3.org/TR/swbp-n-aryRelations/#useCase1")  .  |
|  Aim  |  The aim of this pattern is to allow asking for n-ary relationships and their inverse relations between two distinguished participants without a complex query (Such a comples query would involve the class created to support the n-ary relation between the origin and destination classes of the n-ary relationship).  |
|  Solution description  |  The class "NAryRelationClass" is the class created to support the n-ary relationship (like in [http://www.w3.org/TR/swbp-n-aryRelations/#useCase1](http://www.w3.org/TR/swbp-n-aryRelations/#useCase1 "http://www.w3.org/TR/swbp-n-aryRelations/#useCase1")  ) and its further relations or attributes. The relationship "mainRelationship" and its inverse relation have been created to short-circuited the relation between the distinguished participants in the n-ary relationship.  |
|  Elements  |  Class, Relationship, Attribute and inverseOf  |
|  Implementation  |  |
|  Reusable component  |  |
|  Component type  |  |



  





# 

 Example




|  |  |
| --- | --- |
|  Problem example  |  We might want to represent that a service provider provides a service at a place in a given period of time with a particular price. The model should also represent that a service is offered by a provider.  We have also observed that the queries executed by our applications often ask for the relationship between providers and their services and rarely ask for the relationships about the services and where they are provided. [Image:N_aria_provider_service.JPG](../Image/N_aria_provider_service.JPG.md "Image:N_aria_provider_service.JPG") |
|  Pattern solution example  |  |
|  Consequences  |  The main advantage of this pattern is that allows asking for those services that are provided by a service provider and vice-versa without a complex query (this complex query would involve the class created to support the n-ary relation between service providers and services).  |



  





# 

 Pattern reference




|  |  |
| --- | --- |
|  Origin  |  Logical Pattern for Modelling N-ary Relation: Introducing a New Class for the Relation ( [http://www.w3.org/TR/swbp-n-aryRelations/#pattern1](http://www.w3.org/TR/swbp-n-aryRelations/#pattern1 "http://www.w3.org/TR/swbp-n-aryRelations/#pattern1")  ) and the third consideration in [http://www.w3.org/TR/swbp-n-aryRelations/#choosingPattern1or2](http://www.w3.org/TR/swbp-n-aryRelations/#choosingPattern1or2 "http://www.w3.org/TR/swbp-n-aryRelations/#choosingPattern1or2")  |
|  Known use  |  |
|  Reference  |  |
|  Related ODP  | [Logical Pattern for Modelling N-ary Relation: Introducing a New Class for the Relation](http://ontologydesignpatterns.org/wiki/index.php?title=Logical_Pattern_for_Modelling_N-ary_Relation:_Introducing_a_New_Class_for_the_Relation&action=edit&redlink=1 "Logical Pattern for Modelling N-ary Relation: Introducing a New Class for the Relation (not yet written)")  |
|  Used in combination with  | [Logical Pattern for Modelling N-ary Relation: Introducing a New Class for the Relation](http://ontologydesignpatterns.org/wiki/index.php?title=Logical_Pattern_for_Modelling_N-ary_Relation:_Introducing_a_New_Class_for_the_Relation&action=edit&redlink=1 "Logical Pattern for Modelling N-ary Relation: Introducing a New Class for the Relation (not yet written)")  |
|  Test  |  |



# 

 Additional information



# 

 Scenarios




__Scenarios about Summarization of an inverse n-ary relation__ 


 No scenario is added to this Content OP.
 




# 

 Reviews




__Reviews about Summarization of an inverse n-ary relation__ 



|  Review article  | [Posted on](../Property/CreationDate.md "Property:CreationDate")  | [About revision (current is 10179)](../Property/ReviewAboutVersion.md "Property:ReviewAboutVersion")  |
| --- | --- | --- |
| [CatherineRoussey about Inverse n-ary relationship](../Community/CatherineRoussey_about_Inverse_n-ary_relationship.md "Community:CatherineRoussey about Inverse n-ary relationship")  |  2455450  10 September 2010  |  10060  10,060  |
| [GerdGroener about Inverse n-ary relationship](../Reviews/GerdGroener_about_Inverse_n-ary_relationship.md "Reviews:GerdGroener about Inverse n-ary relationship")  |  2455450  10 September 2010  |  10060  10,060  |
| [OlafNoppens about Inverse n-ary relationship](../Reviews/OlafNoppens_about_Inverse_n-ary_relationship.md "Reviews:OlafNoppens about Inverse n-ary relationship")  |  2455456  16 September 2010  |  10101  10,101  |
| [AlessandroAdamou about Inverse n-ary relationship](../Reviews/AlessandroAdamou_about_Inverse_n-ary_relationship.md "Reviews:AlessandroAdamou about Inverse n-ary relationship")  |  2455456  16 September 2010  |  10101  10,101  |



 This revision (revision ID
 __10179__ 
 ) takes in account the reviews: none
 



 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Summarization_of_an_inverse_n-ary_relation&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Summarization_of_an_inverse_n-ary_relation&action=evaluation") 





  





# 

 Modeling issues




__Modeling issues about Summarization of an inverse n-ary relation__ 


 There is no Modeling issue related to this proposal.
 




  





# 

 References



  






|  |  Submission to event [WOP:2010](../WOP/2010.md "WOP:2010")  |
| --- | --- |
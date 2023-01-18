# 

 General information




|  |  |
| --- | --- |
|  Name  |  NegativePropertyAssertions  |
|  Also known as  |  |
|  Author(s)  |  |
|  SubmittedBy  | [OlafNoppens](../User/OlafNoppens "User:OlafNoppens")  |



  





# 

 Description




|  |  |
| --- | --- |
|  Motivation  |  Prior to OWL 2 negative property assertions (NPA) are difficult to model and, if it they are contained in an ontology, difficult to understand by humans. On the other side, using OWL 2 one can transform these _helping_  axioms modeling NPAs into OWL2 NPA axiom.  This pattern describe NPA for ontologies not containing explicit NPA axioms as syntactical sugars and allows for transforming axioms into OWL NPA axioms.  |
|  Aim  |  Expressing NPAs in ontologies prior to OWL 2 as well as given an transformation rule when using OWL 2.  |
|  Solution description  |  NegativeObjectPropertyAssertion(i1 prop i2) is equivalent to:  SubClassOf(ObjectOneOf(i1), ObjectComplementOf(ObjectSomeValuesFrom(prop, ObjectOneOf(i2)))))  |
|  Elements  |  Individiual i1  Individual i2  ObjectProperty prop  |
|  Implementation  |  |
|  Reusable component  |  |
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

 Scenarios




__Scenarios about NegativePropertyAssertions__ 


 No scenario is added to this Content OP.
 




# 

 Reviews




__Reviews about NegativePropertyAssertions__ 



|  Review article  | [Posted on](../Property/CreationDate "Property:CreationDate")  | [About revision (current is 5769)](../Property/ReviewAboutVersion "Property:ReviewAboutVersion")  |
| --- | --- | --- |
| [ValentinaPresutti about NegativePropertyAssertions](../Reviews/ValentinaPresutti_about_NegativePropertyAssertions "Reviews:ValentinaPresutti about NegativePropertyAssertions")  |  2455084  9 September 2009  |  5769  5,769  |
| [StefanoDavid about NegativePropertyAssertions](../Reviews/StefanoDavid_about_NegativePropertyAssertions "Reviews:StefanoDavid about NegativePropertyAssertions")  |  2455085  10 September 2009  |  5778  5,778  |
| [RinkeHoekstra about NegativePropertyAssertions](../Community/RinkeHoekstra_about_NegativePropertyAssertions "Community:RinkeHoekstra about NegativePropertyAssertions")  |  2455129  24 October 2009  |  5903  5,903  |



 This revision (revision ID
 __5769__ 
 ) takes in account the reviews: none
 



 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:NegativePropertyAssertions&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:NegativePropertyAssertions&action=evaluation") 





  






|  |  Submission to event [WOP2009:Main](http://ontologydesignpatterns.org/wiki/WOP2009:Main "WOP2009:Main")  |
| --- | --- |
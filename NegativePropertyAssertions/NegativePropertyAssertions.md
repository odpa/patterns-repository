# 

 Graphical representation



__Diagram__ 





[![Image:Npa-diagram.png](./Npa-diagram.png)](../Image/Npa-diagram.png.md "Image:Npa-diagram.png")





# 

 General information




|  |  |
| --- | --- |
|  Name  |  NegativePropertyAssertions  |
|  Also known as  |  |
|  Author(s)  |  |
|  SubmittedBy  | [OlafNoppens](../User/OlafNoppens.md "User:OlafNoppens")  |



  





# 

 Description




|  |  |
| --- | --- |
|  Motivation  |  The motivation of this pattern is to model _negative property assertions_  (NPAs) in ontology languages such as OWL 1 [1] that do not provide a special constructor for expressing it. It is worth mentioning that not all knowledge base systems can be migrated to OWL 2 [2] for several reasons. On the other hand, NPAs modeled according to this pattern can be migrated to OWL 2 using the newly introduced constructor.  A negative property assertion as defined in the upcoming OWL 2 states that a given individual _i_  is never connected to a given individual _j_  by a given property expression _P_  . In other words, asserting that _i_  is connected to _j_  by _P_  results in an inconsistent ontology. In this sense this assertion can be considered as a constraint that should not be violated. In contrast, considering an ontology where it cannot be inferred that _i_  is connected to _j_  by _P_  does not necessarily mean that there cannot be such a connection - in fact, it is merely not modeled.  [1] Patel-Schneider, P.F., Hayes, P., Horrocks, I.: OWL Web Ontology LanguageSemantics and Abstract Syntax, W3C Recommendation 10 February 2004.  [2] Motik, B., Patel-Schneider, P.F., Parsia, B.: OWL 2 Structural Speciﬁcation and Functional-Style Syntax. W3C Candidate Recommendation 11 June 2009, 2009.  |
|  Aim  |  Expressing NPAs in ontologies prior to OWL 2 as well as given an transformation rule when using OWL 2.  |
|  Solution description  |  NegativeObjectPropertyAssertion(prop i1 i2) is equivalent to (using OWL 2 Abstract Syntax):  SubClassOf(ObjectOneOf(i1), ObjectComplementOf(ObjectSomeValuesFrom(prop, ObjectOneOf(i2))))  Let _C_  and _D_  be concepts. Then _C_  and _D_  are disjoint if, and only if, _C_  is subsumed by the complement of _D_  , i.e., '(SubClassOf( C ObjectComplementOf(D) ).  The equivalence is correct because of the duality of disjointness, equivalence, and unsatisfiability: _C_  is subsumed by _D_  if, and only if, ObjectIntersectionOf( C ObjectComplementOf(D) ) is unsatisfiable, and the intersection of _C_  and _D_  is unsatisfiable if, and only if, _C' and_  D _are disjoint._  One also reminds that the extension of the concept ObjectSomeValuesFrom(prop C) is the set of individuals _i_  which are connected to an individual _j_  that is in the extension of the concept _C_  , by the property _prop_  .  Let _NegativePropertyAssertion(p a b)_  be a negative property assertion axiom, i.e., the individual _a_  is not related to _b_  by the property _p_  . Then the extension of _ObjectSomeValuesFrom( p ObjectOneOf(b) )_  which contain all individuals that are connected to _b_  by _p_  must not contain _a_  . This is true, if, and only if _ObjectOneOf(a)_  is disjoint to ObjectSomeValuesFrom( p ObjectOneOf(b) )  |
|  Elements  |  Individiual i1  Individual i2  ObjectProperty prop  |
|  Implementation  |  |
|  Reusable component  |  |
|  Component type  |  |



  





# 

 Example




|  |  |
| --- | --- |
|  Problem example  |  Consider a social network containing facts about people and their relationships.  Let _Adam_  and _Eve_  be two persons and like a property ( _A likes B_  ). Furthermore we know that _Adam_  does not like _Eve_  but we have no dislike relationship. Moreover, our language (such as OWL 1) does not have any NPA axiom constructor. The sample ontology is interpreted with respect to the open-world semantics, i. e. , one can not infer the dislike merely from the lack of a property assertion axiom _ObjectPropertyAssertion(like Adam Eve)_  . Then this fact can be expressed with the following axiom (we will also use the OWL 2 Abstract Syntax here): _SubClassOf (Adam ComplementOf(ObjectSomeValuesFrom( likes ObjectOneOf(Eve))))_  |
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




__Scenarios about NegativePropertyAssertions__ 


 No scenario is added to this Content OP.
 




# 

 Reviews




__Reviews about NegativePropertyAssertions__ 



|  Review article  | [Posted on](../Property/CreationDate.md "Property:CreationDate")  | [About revision (current is 9705)](../Property/ReviewAboutVersion.md "Property:ReviewAboutVersion")  |
| --- | --- | --- |
| [ValentinaPresutti about NegativePropertyAssertions](../Reviews/ValentinaPresutti_about_NegativePropertyAssertions.md "Reviews:ValentinaPresutti about NegativePropertyAssertions")  |  2455084  9 September 2009  |  5769  5,769  |
| [StefanoDavid about NegativePropertyAssertions](../Reviews/StefanoDavid_about_NegativePropertyAssertions.md "Reviews:StefanoDavid about NegativePropertyAssertions")  |  2455085  10 September 2009  |  5778  5,778  |
| [RinkeHoekstra about NegativePropertyAssertions](../Community/RinkeHoekstra_about_NegativePropertyAssertions.md "Community:RinkeHoekstra about NegativePropertyAssertions")  |  2455129  24 October 2009  |  5903  5,903  |



 This revision (revision ID
 __9705__ 
 ) takes in account the reviews: none
 



 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:NegativePropertyAssertions&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:NegativePropertyAssertions&action=evaluation") 





  





# 

 Modeling issues




__Modeling issues about NegativePropertyAssertions__ 


 There is no Modeling issue related to this proposal.
 




  





# 

 References



  






|  |  Submission to event [WOP:2009](../WOP/2009.md "WOP:2009")  |
| --- | --- |
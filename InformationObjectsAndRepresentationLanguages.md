# 

 Graphical representation



__Diagram__ 
_(this article has no graphical representation)_ 




# 

 General description




|  |  |
| --- | --- |
|  Name:  |  informationObjectsAndRepresentationLanguages  |
|  Submitted by:  | [AldoGangemi](../User/AldoGangemi "User:AldoGangemi")  |
|  Also Known As:  |  |
|  Intent:  |  -  |
|  Domains:  |  |
|  Competency Questions:  |  |
|  Solution description:  |  -  |
|  Reusable OWL Building Block:  | [http://www.ontologydesignpatterns.org/cp/owl/informationobjectsandrepresentationlanguages.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=http://www.ontologydesignpatterns.org/cp/owl/informationobjectsandrepresentationlanguages.owl&message=OWL building block&from_page_id=2276&update=)  (630)  |
|  Consequences:  |  |
|  Scenarios:  |  |
|  Known Uses:  |  |
|  Web References:  |  |
|  Other References:  |  |
|  Examples (OWL files):  |  |
|  Extracted From:  |  |
|  Reengineered From:  |  |
|  Has Components:  |  |
|  Specialization Of:  |  |
|  Related CPs:  |  |



  





# 

 Elements



_The
 __InformationObjectsAndRepresentationLanguages__ 
 Content OP locally defines the following ontology elements:_ 





[![ObjectProperty](public/images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__conceptualizes__ 
 (owl:ObjectProperty) A relation stating that an Agent is internally representing a SocialObject . E.g., 'John believes in the conspiracy theory'; 'Niels Bohr created the solar-system metaphor for the atomic theory'; 'Jacques assumes all swans are white'; 'the task force members share the attack plan'.
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[conceptualizes](../Submissions/InformationObjectsAndRepresentationLanguages/conceptualizes "Submissions:InformationObjectsAndRepresentationLanguages/conceptualizes") 
 page_ 



[![ObjectProperty](public/images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__formallyRepresents__ 
 (owl:ObjectProperty) The relation between formal expressions, and anything that they are supposed to represent.
 
 E.g., 'the predicate 'MariachiInTijuana' formallyRepresents the dul:Collection of all mariachis in Tijuana'; 'the equivalence relation '<=>' formallyRepresents the concept of two entities having the same properties'.
 



 Notice that formal expressions are formally interpreted by instances of dul:FormalEntity
 



[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[formallyRepresents](../Submissions/InformationObjectsAndRepresentationLanguages/formallyRepresents "Submissions:InformationObjectsAndRepresentationLanguages/formallyRepresents") 
 page_ 



[![ObjectProperty](public/images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasRepresentationLanguage__ 
 (owl:ObjectProperty)
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasRepresentationLanguage](../Submissions/InformationObjectsAndRepresentationLanguages/hasRepresentationLanguage "Submissions:InformationObjectsAndRepresentationLanguages/hasRepresentationLanguage") 
 page_ 



[![ObjectProperty](public/images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__isConceptualizedBy__ 
 (owl:ObjectProperty) A relation stating that an Agent is internally representing a Description . E.g., 'John believes in the conspiracy theory'; 'Niels Bohr created a solar-system metaphor for his atomic theory'; 'Jacques assumes all swans are white'; 'the task force shares the attack plan'.
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[isConceptualizedBy](../Submissions/InformationObjectsAndRepresentationLanguages/isConceptualizedBy "Submissions:InformationObjectsAndRepresentationLanguages/isConceptualizedBy") 
 page_ 



[![ObjectProperty](public/images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__isFormallyRepresentedIn__ 
 (owl:ObjectProperty) The relation between formal expressions, and anything that they are supposed to represent.
 
 E.g., 'the predicate 'MariachiInTijuana' formallyRepresents the dul:Collection of all mariachis in Tijuana'; 'the equivalence relation '<=>' formallyRepresents the concept of two entities having the same properties'.
 



 Notice that formal expressions are formally interpreted by instances of dul:FormalEntity
 



[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[isFormallyRepresentedIn](../Submissions/InformationObjectsAndRepresentationLanguages/isFormallyRepresentedIn "Submissions:InformationObjectsAndRepresentationLanguages/isFormallyRepresentedIn") 
 page_ 



[![ObjectProperty](public/images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__isRepresentationLanguageOf__ 
 (owl:ObjectProperty)
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[isRepresentationLanguageOf](../Submissions/InformationObjectsAndRepresentationLanguages/isRepresentationLanguageOf "Submissions:InformationObjectsAndRepresentationLanguages/isRepresentationLanguageOf") 
 page_ 



[![Class](public/images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__FormalExpression__ 
 (owl:Class) Any information object represented in a FormalLanguage, usually having a formal interpretation by a dul:FormalEntity, and used to formally represent any Entity
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[FormalExpression](../Submissions/InformationObjectsAndRepresentationLanguages/FormalExpression "Submissions:InformationObjectsAndRepresentationLanguages/FormalExpression") 
 page_ 



[![Class](public/images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__FormalLanguage__ 
 (owl:Class) A formal language, created by some human, with a fixed grammar, and usually with an explicit formal semantics (i.e. its elements have an interpretation wrt to formal entities such as sets, categories, etc.).
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[FormalLanguage](../Submissions/InformationObjectsAndRepresentationLanguages/FormalLanguage "Submissions:InformationObjectsAndRepresentationLanguages/FormalLanguage") 
 page_ 



[![Class](public/images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__IconicLanguage__ 
 (owl:Class) A language made up of graphical elements. It can be natural, artificial, and even formal.
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[IconicLanguage](../Submissions/InformationObjectsAndRepresentationLanguages/IconicLanguage "Submissions:InformationObjectsAndRepresentationLanguages/IconicLanguage") 
 page_ 



[![Class](public/images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__IconicObject__ 
 (owl:Class) An information object represented in an IconicLanguage
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[IconicObject](../Submissions/InformationObjectsAndRepresentationLanguages/IconicObject "Submissions:InformationObjectsAndRepresentationLanguages/IconicObject") 
 page_ 



[![Class](public/images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__Language__ 
 (owl:Class) A natural or artificial language, provided with an alphabet (or vocabulary) and combinatorial rules. In the case of natural languages, their components are 'temporary' and 'reconstructed' out of actual usage. For example, a grammar for a natural language has the status of a theory for that language, and alternative ones can exist (e.g. generative vs. construction grammars).
 
 Another distinction, between the general (systemic) rules for a language, and the local (contextual) rules for e.g. a certain context, speaker, place, etc., can be made separately.
 



 The most comprehensive classification of languages ha probably been made by Umberto Eco, based on the production modes of the 'signs' that are represented in a certain language. It uses several semiotic dimensions, and will be modeled in a forthcoming ontology.
 



[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[Language](../Submissions/InformationObjectsAndRepresentationLanguages/Language "Submissions:InformationObjectsAndRepresentationLanguages/Language") 
 page_ 



[![Class](public/images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__LinguisticObject__ 
 (owl:Class) An information object represented in a NaturalLanguage
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[LinguisticObject](../Submissions/InformationObjectsAndRepresentationLanguages/LinguisticObject "Submissions:InformationObjectsAndRepresentationLanguages/LinguisticObject") 
 page_ 



[![Class](public/images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__NaturalLanguage__ 
 (owl:Class) A natural language, evolved and used in a community across time.
 
 Natural languages components are 'temporary' and 'reconstructed' out of actual usage. For example, a grammar for a (part of a) natural language has the status of a theory for that language, but alternative ones can exist (e.g. generative vs. construction grammars).
 



[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[NaturalLanguage](../Submissions/InformationObjectsAndRepresentationLanguages/NaturalLanguage "Submissions:InformationObjectsAndRepresentationLanguages/NaturalLanguage") 
 page_ 


# 

 Additional information



# 

 Scenarios




__Scenarios about InformationObjectsAndRepresentationLanguages__ 


 No scenario is added to this Content OP.
 




# 

 Reviews




__Reviews about InformationObjectsAndRepresentationLanguages__ 


 There is no review about this proposal.
This revision (revision ID
 __9094__ 
 ) takes in account the reviews: none
 



 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:InformationObjectsAndRepresentationLanguages&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:InformationObjectsAndRepresentationLanguages&action=evaluation") 





  





# 

 Modeling issues




__Modeling issues about InformationObjectsAndRepresentationLanguages__ 


 There is no Modeling issue related to this proposal.
 




  





# 

 References
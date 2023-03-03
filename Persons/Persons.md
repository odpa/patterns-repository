__Diagram__ 
_(this article has no graphical representation)_ 




# 

 General description




|  |  |
| --- | --- |
|  Name:  |  Persons  |
|  Submitted by:  | [AldoGangemi](../User/AldoGangemi.md "User:AldoGangemi")  |
|  Also Known As:  |  |
|  Intent:  |  |
|  Domains:  |  |
|  Competency Questions:  |  |
|  Solution description:  |  |
|  Reusable OWL Building Block:  | [http://www.ontologydesignpatterns.org/cp/owl/persons.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=http://www.ontologydesignpatterns.org/cp/owl/persons.owl&message=OWL building block&from_page_id=2321&update=)  (800)  |
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
 __Persons__ 
 Content OP locally defines the following ontology elements:_ 





[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__actsFor__ 
 (owl:ObjectProperty) The relation holding between any Agent, and a SocialPerson. In principle, a SocialPerson requires at least one NaturalPerson in order to act, but this dependency can be 'delegated'; e.g. a university can be acted for by a department, which on its turm is acted for by natural persons.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[actsFor](./ActingFor/actsFor.md "Submissions:Persons/actsFor") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__actsThrough__ 
 (owl:ObjectProperty) The relation holding between any Agent, and a SocialPerson. In principle, a SocialPerson requires at least one NaturalPerson in order to act, but this dependency can be 'delegated'; e.g. a university can be acted for by a department, which on its turm is acted for by natural persons.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[actsThrough](./ActingFor/actsThrough.md "Submissions:Persons/actsThrough") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__introduces__ 
 (owl:ObjectProperty) A relation between a Description and a SocialPerson, e.g. a Constitutional Charter that introduces the SocialPerson 'PresidentOfRepublic'.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[introduces](./Persons/introduces.md "Submissions:Persons/introduces") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__isIntroducedBy__ 
 (owl:ObjectProperty) A relation between a Description and a SocialPerson, e.g. a Constitutional Charter that introduces the SocialPerson 'PresidentOfRepublic'.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[isIntroducedBy](./Persons/isIntroducedBy.md "Submissions:Persons/isIntroducedBy") 
 page_ 



[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__NaturalPerson__ 
 (owl:Class) A Person in the physical commonsense intuition: 'have you seen that person walking down the street?'
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[NaturalPerson](./Persons/NaturalPerson.md "Submissions:Persons/NaturalPerson") 
 page_ 



[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__Person__ 
 (owl:Class) Persons in commonsense intuition, which does not apparently distinguish between either natural or social persons.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[Person](./Persons/NaturalPerson.md "Submissions:Persons/Person") 
 page_ 



[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__SocialPerson__ 
 (owl:Class) A Person that needs the existence of a specific NaturalPerson in order to act (but the lifetime of the NaturalPerson has only to overlap that of the SocialPerson). The NaturalPerson through which it acts can be also indirectly related, e.g. an organization that acts through another organization, which actsThrough one or more NaturalPerson(s).
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[SocialPerson](./Persons/SocialPerson.md "Submissions:Persons/SocialPerson") 
 page_ 


  





# 

 Scenarios




__Scenarios about Persons__ 


 No scenario is added to this Content OP.
 




# 

 Reviews




__Reviews about Persons__ 


 There is no review about this proposal.
This revision (revision ID
 __8255__ 
 ) takes in account the reviews: none
 



 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Persons&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Persons&action=evaluation") 





# 

 Modeling issues




__Modeling issues about Persons__ 


 There is no Modeling issue related to this proposal.
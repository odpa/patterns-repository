# 

 Graphical representation



__Diagram__ 





[![Image:Place.png](public/images/f/f7/Place.png)](../Image/Place.png "Image:Place.png")





# 

 General description




|  |  |
| --- | --- |
|  Name:  |  Place  |
|  Submitted by:  | [AldoGangemi](../User/AldoGangemi "User:AldoGangemi")  |
|  Also Known As:  |  |
|  Intent:  |  To talk about places of things.  |
|  Domains:  | [General](../Community/General "Community:General")  |
|  Competency Questions:  | <li>       Where is a certain thing located? What is located at this place?      </li> |
|  Solution description:  |  This is a basic pattern, useful to represent generic locations for anything, which becomes a place when is assumed as a reference location.  |
|  Reusable OWL Building Block:  | [http://www.ontologydesignpatterns.org/cp/owl/place.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=http://www.ontologydesignpatterns.org/cp/owl/place.owl&message=OWL building block&from_page_id=1224&update=)  (990)  |
|  Consequences:  |  We can represent, transitively, where something is located. It remains unspecified what kind of location relation we are trying to represent: reference location, partial location, physical location, social or metaphoric location, etc.  Moreover, temporal location is not caught with this pattern (you need a placement situation for that).  |
|  Scenarios:  |  The Colosseum is located in Rome.  |
|  Known Uses:  |  |
|  Web References:  |  |
|  Other References:  |  |
|  Examples (OWL files):  |  |
|  Extracted From:  | <li><a class="external free" href="http://www.ontologydesignpatterns.org/ont/dul/DUL.owl" rel="nofollow" title="http://www.ontologydesignpatterns.org/ont/dul/DUL.owl">        http://www.ontologydesignpatterns.org/ont/dul/DUL.owl       </a></li> |
|  Reengineered From:  |  |
|  Has Components:  |  |
|  Specialization Of:  |  |
|  Related CPs:  |  |



  





# 

 Elements



_The
 __Place__ 
 Content OP locally defines the following ontology elements:_ 





[![ObjectProperty](public/images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasLocation__ 
 (owl:ObjectProperty) A generic, relative localization, holding between any entities. E.g. 'the cat is on the mat', 'Omar is in Samarcanda', 'the wound is close to the femural artery'.
 
 For 'absolute' locations, see SpaceRegion
 



[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasLocation](../Submissions/Place/hasLocation "Submissions:Place/hasLocation") 
 page_ 




[![ObjectProperty](public/images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__isLocationOf__ 
 (owl:ObjectProperty) A generic, relative localization, holding between any entities. E.g. 'Rome is the seat of the Pope', 'the liver is the location of the tumor'.
 



 As a very general notion of localization, it is assumed as transitive.
 



 For 'absolute' locations, see SpaceRegion
 



[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[isLocationOf](../Submissions/Place/isLocationOf "Submissions:Place/isLocationOf") 
 page_ 




[![Class](public/images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__Place__ 
 (owl:Class) A location, in a very generic sense: a political geographic entity (Roma, Lesotho), a location determined by the presence of other entities ('the area close to Roma'), pivot events or signs ("the area where the helicopter fell"), complements of other entities ('the area under the table'), as well as physical objects conceptualized as locations as their main identity criterion ('the territory of Italy').
 



 In this generic sense, a Place is an 'approximate', relative location. For an 'absolute', abstract location, cf. the pattern spaceregion.owl.
 



 Formally, a Place is defined by the fact of having something located in it; a Place is located in itself.
 



[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[Place](../Submissions/Place/Place "Submissions:Place/Place") 
 page_ 


# 

 Additional information



 (type):
 [http://www.w3.org/2002/07/owl#Ontology](http://www.w3.org/2002/07/owl#Ontology "http://www.w3.org/2002/07/owl#Ontology") 




 (imports):
 [http://www.ontologydesignpatterns.org/schemas/cpannotationschema.owl](http://www.ontologydesignpatterns.org/schemas/cpannotationschema.owl "http://www.ontologydesignpatterns.org/schemas/cpannotationschema.owl") 




# 

 Scenarios




__Scenarios about Place__ 


 No scenario is added to this Content OP.
 




# 

 Reviews




__Reviews about Place__ 


 There is no review about this proposal.
This revision (revision ID
 __8846__ 
 ) takes in account the reviews: none
 



 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Place&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Place&action=evaluation") 





  





# 

 Modeling issues




__Modeling issues about Place__ 


 There is no Modeling issue related to this proposal.
 




  





# 

 References
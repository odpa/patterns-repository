[![Image:classification.jpg](images/c/ca/Classification.jpg)](../Image/Classification.jpg "Image:classification.jpg")





# 

 General description




|  |  |
| --- | --- |
|  Name:  |  Classification  |
|  Submitted by:  | [User:ValentinaPresutti](http://ontologydesignpatterns.org/wiki/index.php?title=User:User:ValentinaPresutti&action=edit&redlink=1 "User:User:ValentinaPresutti (not yet written)")  |
|  Also Known As:  |  |
|  Intent:  |  To represent the relations between concepts (roles, task, parameters) and entities (person, events, values), which concepts can be assigned to. To formalize the application (e.g. tagging) of informal knowledge organization systems such as lexica, thesauri, subject directories, folksonomies, etc., where concepts are first-order elements.  |
|  Domains:  | [Community:General](http://ontologydesignpatterns.org/wiki/index.php?title=Community:Community:General&action=edit&redlink=1 "Community:Community:General (not yet written)")  |
|  Competency Questions:  | <li>       What concept is assigned to this entity?      </li><li>       Which category does this entity belong to?      </li> |
|  Solution description:  |  |
|  Reusable OWL Building Block:  | [http://www.ontologydesignpatterns.org/cp/owl/classification.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=http://www.ontologydesignpatterns.org/cp/owl/classification.owl&message=OWL building block&from_page_id=62&update=)  (1046)  |
|  Consequences:  |  It is possible to make assertions about e.g., categories, types, roles, which are typically considered at the meta-level of an ontology. Instances of Concept reify such elements, which are therefore put in the ordinary domain of an ontology. It is not possible to parametrize the classification over different dimensions e.g., time, space, etc.  |
|  Scenarios:  |  Mac OSX 10.5 is classified as an operating system in the Fujitsu-Siemens product catalog.  |
|  Known Uses:  |  |
|  Web References:  |  |
|  Other References:  |  |
|  Examples (OWL files):  |  |
|  Extracted From:  | <li><a class="external free" href="http://www.loa-cnr.it/ontologies/DUL.owl" rel="nofollow" title="http://www.loa-cnr.it/ontologies/DUL.owl">        http://www.loa-cnr.it/ontologies/DUL.owl       </a></li> |
|  Reengineered From:  |  |
|  Has Components:  |  |
|  Specialization Of:  |  |
|  Related CPs:  |  |



  





# 

 Elements



_The
 __Classification__ 
 Content OP locally defines the following ontology elements:_ 






[![Class](images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__Concept__ 
 (owl:Class) A concept is a Social Object. The
 [classifies](../Submissions/Classification/classifies "Submissions:Classification/classifies") 
 relation relates concepts to entities at some time
 



[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[Concept](../Submissions/Classification/Concept "Submissions:Classification/Concept") 
 page_ 




[![Class](images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__Entity__ 
 (owl:Class) Anything: real, possible, or imaginary, which some modeller wants to talk about for some purpose.
 



[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[Entity](../Submissions/Classification/Entity "Submissions:Classification/Entity") 
 page_ 




[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__classifies__ 
 (owl:ObjectProperty) A relation between a
 [Concept](../Submissions/Classification/Concept "Submissions:Classification/Concept") 
 and an
 [Entity](../Submissions/Classification/Entity "Submissions:Classification/Entity") 
 , e.g. the Role 'student' classifies a Person 'John'.
 



[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[classifies](../Submissions/Classification/classifies "Submissions:Classification/classifies") 
 page_ 




[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__is classified by__ 
 (owl:ObjectProperty) A relation between a
 [Concept](../Submissions/Classification/Concept "Submissions:Classification/Concept") 
 and an
 [Entity](../Submissions/Classification/Entity "Submissions:Classification/Entity") 
 , e.g. 'John is considered a typical rude man'; your last concert constitutes the achievement of a lifetime; '20-year-old means she's mature enough'.
 



[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[isClassifiedBy](../Submissions/Classification/isClassifiedBy "Submissions:Classification/isClassifiedBy") 
 page_ 


  





# 

 Scenarios




__Scenarios about Classification__ 


 No scenario is added to this Content OP.
 




# 

 Reviews




__Reviews about Classification__ 



|  Review article  | [Posted on](../Property/CreationDate "Property:CreationDate")  | [About revision (current is 2375)](../Property/ReviewAboutVersion "Property:ReviewAboutVersion")  |
| --- | --- | --- |
| [WimPeters about Classification](../Reviews/WimPeters_about_Classification "Reviews:WimPeters about Classification")  |  2454630  12 June 2008  |  2375  2,375  |



 This revision (revision ID
 __2375__ 
 ) takes in account the reviews: none
 



 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Classification&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Classification&action=evaluation")
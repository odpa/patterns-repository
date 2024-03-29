#  Graphical representation


__Diagram__




[![Image:classification.jpg](./Classification.jpg)](../Image/Classification.jpg.md "Image:classification.jpg")




#  General description




|  |  |
| --- | --- |
|  Name: |  Classification |
|  Submitted by: | [ValentinaPresutti](../User/ValentinaPresutti.md "User:ValentinaPresutti") |
|  Also Known As: |  |
|  Intent: |  To represent the relations between concepts (roles, task, parameters) and entities (person, events, values), which concepts can be assigned to. To formalize the application (e.g. tagging) of informal knowledge organization systems such as lexica, thesauri, subject directories, folksonomies, etc., where concepts are first-order elements. |
|  Domains: | [General](../Community/General.md "Community:General") |
|  Competency Questions: | <li> What concept is assigned to this entity?</li><li> Which category does this entity belong to?</li> |
|  Solution description: |  - |
|  Reusable OWL Building Block: | [http://www.ontologydesignpatterns.org/cp/owl/classification.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=http://www.ontologydesignpatterns.org/cp/owl/classification.owl&message=OWL building block&from_page_id=62&update=) (1046) |
|  Consequences: |  It is possible to make assertions about e.g., categories, types, roles, which are typically considered at the meta-level of an ontology. Instances of Concept reify such elements, which are therefore put in the ordinary domain of an ontology. It is not possible to parametrize the classification over different dimensions e.g., time, space, etc. |
|  Scenarios: |  Mac OSX 10.5 is classified as an operating system in the Fujitsu-Siemens product catalog. |
|  Known Uses: |  |
|  Web References: |  |
|  Other References: |  |
|  Examples (OWL files): |  |
|  Extracted From: | <li><a class="external free" href="http://www.loa-cnr.it/ontologies/DUL.owl" rel="nofollow" title="http://www.loa-cnr.it/ontologies/DUL.owl">http://www.loa-cnr.it/ontologies/DUL.owl</a></li> |
|  Reengineered From: |  |
|  Has Components: |  |
|  Specialization Of: |  |
|  Related CPs: |  |


  




#  Elements


_The __Classification__ Content OP locally defines the following ontology elements:_




[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __Concept__ (owl:Class) A concept is a Social Object. The  [classifies](./Classification/classifies.md "Submissions:Classification/classifies") relation relates concepts to entities at some time 



 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[Concept](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/hasMappedDomainConcept.md "Submissions:Classification/Concept") page_

[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __Entity__ (owl:Class) Anything: real, possible, or imaginary, which some modeller wants to talk about for some purpose. 



 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[Entity](../CollectionEntity/CollectionEntity.md "Submissions:Classification/Entity") page_

[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __classifies__ (owl:ObjectProperty) A relation between a  [Concept](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/hasMappedDomainConcept.md "Submissions:Classification/Concept") and an  [Entity](../CollectionEntity/CollectionEntity.md "Submissions:Classification/Entity"), e.g. the Role 'student' classifies a Person 'John'. 



 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[classifies](./Classification/classifies.md "Submissions:Classification/classifies") page_

[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __is classified by__ (owl:ObjectProperty) A relation between a  [Concept](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/hasMappedDomainConcept.md "Submissions:Classification/Concept") and an  [Entity](../CollectionEntity/CollectionEntity.md "Submissions:Classification/Entity"), e.g. 'John is considered a typical rude man'; your last concert constitutes the achievement of a lifetime; '20-year-old means she's mature enough'. 



 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isClassifiedBy](./Classification/isClassifiedBy.md "Submissions:Classification/isClassifiedBy") page_
#  Additional information


#  Scenarios



__Scenarios about Classification__
No scenario is added to this Content OP.




#  Reviews



__Reviews about Classification__


| Review article | [Posted on](../Property/CreationDate.md "Property:CreationDate") | [About revision (current is 9070)](../Property/ReviewAboutVersion.md "Property:ReviewAboutVersion") |
| --- | --- | --- |
| [WimPeters about Classification](../Reviews/WimPeters_about_Classification.md "Reviews:WimPeters about Classification") | 245463012 June 2008 | 23752,375 |


This revision (revision ID __9070__) takes in account the reviews: none


Other info at [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Classification&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Classification&action=evaluation")




  




#  Modeling issues



__Modeling issues about Classification__


| Modeling issue | [Competency question](../Property/CompetencyQuestion.md "Property:CompetencyQuestion") | [Domains](../Property/Domain.md "Property:Domain") |
| --- | --- | --- |
| [Situation classification](../Community/Situation_classification.md "Community:Situation classification") | What situations satisfy a certain description? What descriptions can be (partly) satisfied by that situation? What situations (partly) satisfying a certain description can emerge out of this dataset? |  |



  




#  References
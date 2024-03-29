#  Graphical representation


__Diagram__




[![Image:Topic.png](./Topic.png)](../Image/Topic.png.md "Image:Topic.png")




#  General description




|  |  |
| --- | --- |
|  Name: |  Topic |
|  Submitted by: | [SaraBernardini](../User/SaraBernardini.md "User:SaraBernardini"), [AldoGangemi](../User/AldoGangemi.md "User:AldoGangemi") |
|  Also Known As: |  |
|  Intent: |  To represent topics and their relations. |
|  Domains: | [General](../Community/General.md "Community:General") |
|  Competency Questions: | <li> What is the topic of something?</li><li> What topics are included in this one?</li><li> What are the topics near to that one?</li> |
|  Solution description: |  Topics are modelled as conceptual complexes with part of (containment), overlap, and vicinity relations, and can be related to any kind of entity. They are disjoint from "Concepts", which can be at the "core" of topics. |
|  Reusable OWL Building Block: | [http://ontologydesignpatterns.org/cp/owl/topic.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=http://ontologydesignpatterns.org/cp/owl/topic.owl&message=OWL building block&from_page_id=2121&update=) (770) |
|  Consequences: |  We are able to represent topics, subjects, or themes of something, and to organize topics into partonomic and topological structures.In order to represent more sophisticated relations between topics, concepts, terms, etc., refer to the full ontopic.owl ontology. |
|  Scenarios: |  "The topic of Moby Dick is the hatred of humanity", "What is the main subjects in neswpapers today? And more specifically?" |
|  Known Uses: |  |
|  Web References: |  |
|  Other References: |  |
|  Examples (OWL files): |  |
|  Extracted From: | <li><a class="external free" href="http://www.ontologydesignpatterns.org/ont/dul/ontopic.owl" rel="nofollow" title="http://www.ontologydesignpatterns.org/ont/dul/ontopic.owl">http://www.ontologydesignpatterns.org/ont/dul/ontopic.owl</a></li> |
|  Reengineered From: |  |
|  Has Components: |  |
|  Specialization Of: |  |
|  Related CPs: |  |


  




#  Elements


_The __Topic__ Content OP locally defines the following ontology elements:_



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __farTopicFrom__ (owl:ObjectProperty) The opposite to vicinity relation between two topics, e.g. 'star system' (as a Topic) is farTopicFrom 'geology' (as a Topic).
Distance is typically established with reference to a threshold on the number of concepts or entities that are common between the two topics. Alternatively, it can be established with reference to the a geometrical semantics applied to the spaces (super-topics) of which topics are part (cf. ontopic.owl ontology). 



 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[farTopicFrom](./Topic/farTopicFrom.md "Submissions:Topic/farTopicFrom") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasCoreConcept__ (owl:ObjectProperty) A Concept is a core concept for a Topic when it can classify many entities that have that Topic.
For example, Saxophone (as a Concept) isCoreConceptFor Saxophones (as a Topic). 



 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasCoreConcept](./Topic/hasCoreConcept.md "Submissions:Topic/hasCoreConcept") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasSubTopic__ (owl:ObjectProperty) The relation between two instances of a Topic, in terms of their cultural coverage. For example, Sport hasSubTopic Football. 
It can be used widely to talk about document annotations, subject directories, etc. 



 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasSubTopic](./Topic/hasSubTopic.md "Submissions:Topic/hasSubTopic") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasTopic__ (owl:ObjectProperty) The relation between something and its Topic (subject, argument, domain, theme, subject area, etc.). It can be used widely to talk about document annotations, subject directories, etc.
hasTopic is very general. For example, consider the following cases:


(1) A biography of Brigitte Bardot hasTopic 'star system'


(2) The concept of 'starlet' hasTopic 'cinema'


(3) A biography of Claude Chabrol hasTopic 'Nouvelle Vague'. 



 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasTopic](./Topic/hasTopic.md "Submissions:Topic/hasTopic") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isCoreConceptFor__ (owl:ObjectProperty) A Concept is a core concept for a Topic when it can classify many entities that have that Topic.
For example, Saxophone (as a Concept) isCoreConceptFor Saxophones (as a Topic). 



 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isCoreConceptFor](./Topic/isCoreConceptFor.md "Submissions:Topic/isCoreConceptFor") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isSubTopicOf__ (owl:ObjectProperty) The relation between two Topic(s), in terms of their cultural coverage. For example, Football isSubTopicOf Sport. 
It can be used widely to talk about document annotations, subject directories, etc. 



 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isSubTopicOf](./Topic/isSubTopicOf.md "Submissions:Topic/isSubTopicOf") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isTopicOf__ (owl:ObjectProperty) The relation between something and its Topic (subject, argument, domain, theme, subject area, etc.). It can be used widely to talk about document annotations, subject directories, etc.
hasTopic is very general. For example, consider the following cases:


(1) A biography of Brigitte Bardot hasTopic 'star system'


(2) The concept of 'starlet' hasTopic 'cinema'


(3) A biography of Claude Chabrol hasTopic 'Nouvelle Vague'. 



 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isTopicOf](./Topic/isTopicOf.md "Submissions:Topic/isTopicOf") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __nearTopicTo__ (owl:ObjectProperty) The vicinity relation between two topics, e.g. 'star system' (as a Topic) is nearTopicTo 'cinema' (as a Topic).
Vicinity is typically established with reference to a threshold on the number of concepts or entities that are common to the two Topic(s), or based on a geometrical semantics applied to the spaces common between two topics (cf. ontopic.owl ontology). 



 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[nearTopicTo](./Topic/nearTopicTo.md "Submissions:Topic/nearTopicTo") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __overlappingTopic__ (owl:ObjectProperty) The relation between two topics, e.g. 'star system' (as a Topic) is overlappingTopic with 'Bollywood movies' (as a Topic).
Overlap is typically established with reference to a threshold on the number of concepts or entities that are common between the two topics. Alternatively, it can be established with reference to the a geometrical semantics applied to the spaces (super-topics) of which topics are part (cf. ontopic.owl ontology). 



 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[overlappingTopic](./Topic/overlappingTopic.md "Submissions:Topic/overlappingTopic") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __Concept__ (owl:Class) A Concept is a social object, which is used to classify entities. Differently from a Topic
Both concepts and topics are used to classify entities, but concepts typically have an "is a" relation to the entities; e.g. 


(1) A biography of Brigitte Bardot hasTopic 'star system' (Topic)


(2) A biography of Brigitte Bardot is a Biography (Concept)


(3) A biography of Claude Chabrol hasTopic 'Nouvelle Vague' (Topic)


(4) The Nouvelle Vague is a CulturalMovement (Concept) 



 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[Concept](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/hasMappedDomainConcept.md "Submissions:Topic/Concept") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __Topic__ (owl:Class) A topic, or subject, argument, domain, theme, subject area, etc.
Topics have a controversial intuition across common sense, document management systems, knowledge organization systems, etc.


  



There is an interesting duality of topics: they are commonly interpreted as areas of shared knowledge within a Community (therefore as collections of social objects). On the other hand, existing directories and thesauri use 'topic' (or 'subject') more restrictively, as a relation between a document and a concept. 


  



For example, thesauri do not usually distinguish when their 'concepts' (cf. skos:Concept) are actually intended as concepts (in the sense of Concept in this pattern) and when they are intended as topics. The distinction is clear when you compare these two sample sentences: 'the football topic is part of the sport topic' vs. 'the concept of football is part of the concept of sport'. 


While the first is perfectly acceptable, the second is counterintuitive and even possibly wrong. This effect is due to the fact that concepts are 'intensional' notions and are not intended as areas of knowledge, document spaces, etc., which are 'extensional' notions.


  



Accordingly to these basic observations, in this pattern Concept and Topic result to be disjoint, and an appropriate representation should be in place in order to model thesauri. E.g. skos:Concept should be mapped to the union of Concept and Topic. 



 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[Topic](../SimpleTopic/SimpleTopic.md "Submissions:Topic/Topic") page_
#  Additional information


It is a simplified version of the ontology [http://ontologydesignpatterns.org/ont/dul/ontopic.owl](http://ontologydesignpatterns.org/ont/dul/ontopic.owl "http://ontologydesignpatterns.org/ont/dul/ontopic.owl")



#  Scenarios



__Scenarios about Topic__
No scenario is added to this Content OP.




#  Reviews



__Reviews about Topic__
There is no review about this proposal.
This revision (revision ID __9138__) takes in account the reviews: none


Other info at [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Topic&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Topic&action=evaluation")




  




#  Modeling issues



__Modeling issues about Topic__
There is no Modeling issue related to this proposal.




  




#  References
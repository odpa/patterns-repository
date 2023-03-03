#  General information




|  |  |
| --- | --- |
|  Name |  Pattern for re-engineering a term-based thesaurus, which follows the relationbased data model, into an ontology schema |
|  Problem |  Re-engineering a term-based thesaurus, which follows the relation-based model, to design an ontology schema. |


  




##  Non-Ontological Resource




|  |  |
| --- | --- |
|  Description |  A non-ontological resource holds a term-based thesaurus which follows the relation-based model.A thesaurus represents the knowledge of a domain with a collection of terms and a limited set of relations between them.The relation-based data model is a normalized structure, in which relationshiptypes are not defined as fields in a record, but they are simply data values in a relationship record, thus new relationship types can be introduced with ease. |
|  Graphical Representation | __Diagram__[Image:Relationbasedtermbased.png](../Image/Relationbasedtermbased.png.md "Image:Relationbasedtermbased.png") |


  




##  Ontology




|  |  |
| --- | --- |
|  Description |  The generated ontology will be based on the lightweight ontology architectural pattern (AP-LW-01). Each thesaurus term is mapped to a class. For the disambiguation of the semantics of the BT, NT and RT relations among thesaurus terms the pattern relies on an external resource. In the case the external resource does not provide any relation between two terms, the pattern takes advantage of the use of logical patterns for asserting the relation partOf, subClassOf or relatedClass. For the UF/USE relations we use the logical pattern proposed by Corcho et al. suggested as best practice in the context of this antipattern: the tendency to declare two classes equivalent when in fact their labels simply express synonym. |
|  Graphical Representation | __Diagram__[Image:RelationbasedtermbasedOntology.png](../Image/RelationbasedtermbasedOntology.png.md "Image:RelationbasedtermbasedOntology.png") |


  




##  Process




|  |  |
| --- | --- |
|  Description |  1. Identify the records which contain thesaurus terms without a broader term, within the term-term relationship entity.2. For each one of the above identified thesaurus terms ti:2.1. Obtain the thesaurus term within the term entity.2.2. Create the corresponding ontology class, Ci class, if it is not created yet.2.3. Identify the thesaurus term, tj, which are narrower terms of ti, within the term-term relationship entity.2.4. For each one of the above identified thesaurus terms tj :2.4.1. Obtain the thesaurus term within the term entity.2.4.2. Create the corresponding ontology class, Cj class, if it is not created yet.2.4.3. Using the external resource identify the semantics of the relation between Cj and Ci, and set up the relation identified.2.4.4. Repeat from step 2.2 for cj as a new ci2.5. Identify the thesaurus term, tr, which are related terms of ti, within the term-term relationship entity.2.6. For each one of the above identified thesaurus term tr:2.6.1. Obtain the thesaurus term within the term entity.2.6.2. Create the corresponding ontology class, Cr class, if it is not created yet.2.6.3. Using the external resource identify the semantics of the relation between Cr and Ci, and set up the relation identified.2.6.4. Repeat from step 2.4 for cr as a new ci2.7. Identify the thesaurus term, tq, which are equivalent terms of ti, within the term-term relationship entity.2.8. For each one of the above identified thesaurus term tq:2.8.1. Use the logical pattern proposed by Corcho et al.2.8.2. Repeat from step 2.6 for cq as a new ci |
|  Graphical Representation | __Diagram__[Image:Wftbthrello.png](../Image/Wftbthrello.png.md "Image:Wftbthrello.png") |


  




#  Scenario example




|  |  |
| --- | --- |
|  Description |  Suppose that someone wants to build an ontology schema based on earlier version of the AGROVOC Thesaurus, which is a term-based thesaurus and it follows the relation-based model. |


  




##  Example of a Non-Ontological Resource




|  |  |
| --- | --- |
|  Description |  The AGROVOC Thesaurus is an structured and controlled vocabulary designed to cover the terminology of all subject fields in agriculture, forestry, fisheries, food and related domains. |
|  Graphical Representation | __Diagram__[Image:RelationbasedtermbasedAgrovoc2.png](../Image/RelationbasedtermbasedAgrovoc2.png.md "Image:RelationbasedtermbasedAgrovoc2.png") |
|  Web Reference | [http://www.fao.org/agrovoc/](http://www.fao.org/agrovoc/ "http://www.fao.org/agrovoc/") |


  




##  Ontology example




|  |  |
| --- | --- |
|  Description |  The generated ontology will be based on the lightweight ontology architectural pattern (AP-LW-01). Each thesaurus term is mapped to a class. For the disambiguation of the semantics of the BT, NT and RT relations among thesaurus terms the pattern relies on an external resource. In the case the external resource does not provide any relation between two terms, the pattern takes advantage of the use of logical patterns for asserting the relation partOf, subClassOf or relatedClass. For the UF/USE relations we use the logical pattern proposed by Corcho et al. suggested as best practice in the context of this antipattern: the tendency to declare two classes equivalent when in fact their labels simply express synonym. |
|  Graphical Representation | __Diagram__[Image:relationbasedtermbasedSubClassOfExample.png](../Image/RelationbasedtermbasedSubClassOfExample.png.md "Image:relationbasedtermbasedSubClassOfExample.png") |
|  Web Reference | [http://droz.dia.fi.upm.es/ontologies](http://droz.dia.fi.upm.es/ontologies "http://droz.dia.fi.upm.es/ontologies") |


  




##  Process example




|  |  |
| --- | --- |
|  Description |  1. Create the Poaceae class.1.1. Create the Oryza class.1.2. Using the external resource identify the semantics of the relation betweenOryza and Poaceae, and set up the relation identified.1.2.1. Create the Rice class.1.2.2. Using the external resource identify the semantics of the relation between Rice and Oryza, and set up the relation identified.2. Create the Cereals class.2.1. Using the external resource identify the semantics of the relation betweenRice and Cereals, and set up the relation identified. |
|  Graphical Representation | __Diagram__[Image:Wftbthrelloexample.png](../Image/Wftbthrelloexample.png.md "Image:Wftbthrelloexample.png") |


  




#  About




|  |  |
| --- | --- |
|  SubmittedBy | [BorisVillazón-Terrazas](../User/BorisVillazón-Terrazas.md "User:BorisVillazón-Terrazas") |
|  Author |  BorisVillazón-Terrazas |
|  Also known as |  |
|  Known uses |  |
|  Related to |  |
|  Other References |  |


#  Additional information


#  Scenarios



__Scenarios about Pattern for re-engineering a term-based thesaurus, which follows the relationbased data model, into an ontology schema__
No scenario is added to this Content OP.




#  Reviews



__Reviews about Pattern for re-engineering a term-based thesaurus, which follows the relationbased data model, into an ontology schema__
There is no review about this proposal.
This revision (revision ID __11035__) takes in account the reviews: none


Other info at [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Pattern_for_re-engineering_a_term-based_thesaurus%2C_which_follows_the_relationbased_data_model%2C_into_an_ontology_schema&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Pattern_for_re-engineering_a_term-based_thesaurus%2C_which_follows_the_relationbased_data_model%2C_into_an_ontology_schema&action=evaluation")




  




#  Modeling issues



__Modeling issues about Pattern for re-engineering a term-based thesaurus, which follows the relationbased data model, into an ontology schema__
There is no Modeling issue related to this proposal.




  




#  References
#  General information




|  |  |
| --- | --- |
|  Name |  Pattern for re-engineering a classification scheme, which follows the flattened data model, into an ontology schema |
|  Problem |  Re-engineering a classification scheme, which follows the flattened model, to design an ontology schema. |


  




##  Non-Ontological Resource




|  |  |
| --- | --- |
|  Description |  A non-ontological resource holds a classification scheme which follows the flattened data model. A classification scheme is a rooted tree of concepts, in which each concept groups entities by some particular degree of similarity. The semantics of the hierarchical relation between parents and children concepts may vary depending of the context.The flattened data model is a denormalized structure for hierarchy representations.In this case, each hierarchy level is represented on a different column. There are as many columns as levels the classification scheme has. Therefore each row has the complete path from the root to a leaf node. |
|  Graphical Representation | __Diagram__[Image:FlattenedEntity.png](../Image/FlattenedEntity.png.md "Image:FlattenedEntity.png") |


  




##  Ontology




|  |  |
| --- | --- |
|  Description |  The generated ontology will be based on the taxonomy architectural pattern (AP-TX-01). Each category in the classification scheme is mapped to a class, and the semantics of the relationship between children and parent categories are disambiguated by using an external resource. In the case of that the external resource does not provide any relation between two items, the pattern takes advantage of the use of logical patterns for asserting the relation partOf or subClassOf. |
|  Graphical Representation | __Diagram__[Image:Ontology.png](../Image/Ontology.png.md "Image:Ontology.png") |


  




##  Process




|  |  |
| --- | --- |
|  Description |  1. Select all the classification scheme items from the first level, using the level column and taking care to avoid duplicity.2. For each one of the above selected classification scheme items cei:2.1. Create the corresponding ontology class, Ci class.2.2. Identify the classification scheme items, cej , on the next level, which are children of cei, by using the path and level columns.2.3. For each one of the above identified classification scheme items cej :2.3.1. Create the corresponding ontology class, Cj class.2.3.2. Using the external resource identify the semantics of the relation between Cj and Ci, and set up the relation identified.2.3.3. Repeat from step 2.2 for cej as a new cei.3. If there are more than one classification scheme items from the first level cei3.1. Create an ad-hoc class as the root class of the ontology.3.2. Using the external resource identify the semantics of the relation between Ci class and the root class, and set up the relation identified. |
|  Graphical Representation | __Diagram__[Image:Wfcsftso.png](../Image/Wfcsftso.png.md "Image:Wfcsftso.png") |


  




#  Scenario example




|  |  |
| --- | --- |
|  Description |  Suppose that someone wants to build an ontology based on a classification published as one table with a column for each classification level. |


  




##  Example of a Non-Ontological Resource




|  |  |
| --- | --- |
|  Description |  The Classification of Italian Education Titles published by the National Institute of Statistics (ISTAT) is represented following a flattened model. The first level of the classification (level code) is related to the education title level which comprises values as elementary, media, university, master, etc. The second level of the classification is the type of school or institutewhich offers the education title. The last level is the education title itself; it has a specific specialization code and also a code which is the concatenation of the previous code levels. |
|  Graphical Representation | __Diagram__[Image:flattenedEntityEducationTitle.png](../Image/FlattenedEntityEducationTitle.png.md "Image:flattenedEntityEducationTitle.png") |
|  Web Reference | [http://droz.dia.fi.upm.es/nors](http://droz.dia.fi.upm.es/nors "http://droz.dia.fi.upm.es/nors") |


  




##  Ontology example




|  |  |
| --- | --- |
|  Description |  The generated ontology will be based on the taxonomy architectural pattern (AP-TX-01). Each category in the classification scheme is mapped to a class, and the semantics of the relationship between children and parent categories are disambiguated by using an external resource. In the case of that the external resource does not provide any relation between two items, the pattern takes advantage of the use of logical patterns for asserting the relation partOf or subClassOf. |
|  Graphical Representation | __Diagram__[Image:OntologyFlattenedEducationTitles.png](../Image/OntologyFlattenedEducationTitles.png.md "Image:OntologyFlattenedEducationTitles.png") |
|  Web Reference | [http://droz.dia.fi.upm.es/ontologies](http://droz.dia.fi.upm.es/ontologies "http://droz.dia.fi.upm.es/ontologies") |


  




##  Process example




|  |  |
| --- | --- |
|  Description |  1. Create the HIGHER SECONDARY EDUCATION class.1.1. Create the Istituto professionale agrario class.1.2. Using the external resource identify the semantics of the relation betweenthe Istituto professionale agrario class and the HIGHER SECONDARY EDUCATION class, and set up the relation identified.1.2.1. Create the Esperto frutticoltore class.1.2.2. Using the external resource identify the semantics of the relation between the Esperto frutticoltore class and the Istituto professionale agrario class, and set up the relation identified.1.2.3. Create the Esperto olivicoltore class.1.2.4. Using the external resource identify the semantics of the relationbetween the Esperto olivicoltore class and the Istituto professionale agrario class, and set up the relation identified.2. Create the HIGHER SECONDARY EDUCATION - ALLOWS ACCESS TO UNIVERSITIES class.3. Create the Education Title class.4. Using the external resource identify the semantics of the relation between the HIGHER SECONDARY EDUCATION class and the Education Title class, and set up the relation identified.5. Using the external resource identify the semantics of the relation betweenthe HIGHER SECONDARY EDUCATION - ALLOWS ACCESS TO UNIVERSITIES class and the Education Title class, and set up the relation identified. |
|  Graphical Representation | __Diagram__[Image:Wfcsftsoexample.png](../Image/Wfcsftsoexample.png.md "Image:Wfcsftsoexample.png") |


  




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



__Scenarios about Pattern for re-engineering a classification scheme, which follows the flattened data model, into an ontology schema__
No scenario is added to this Content OP.




#  Reviews



__Reviews about Pattern for re-engineering a classification scheme, which follows the flattened data model, into an ontology schema__
There is no review about this proposal.
This revision (revision ID __9466__) takes in account the reviews: none


Other info at [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Pattern_for_re-engineering_a_classification_scheme%2C_which_follows_the_flattened_data_model%2C_into_an_ontology_schema&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Pattern_for_re-engineering_a_classification_scheme%2C_which_follows_the_flattened_data_model%2C_into_an_ontology_schema&action=evaluation")




  




#  Modeling issues



__Modeling issues about Pattern for re-engineering a classification scheme, which follows the flattened data model, into an ontology schema__
There is no Modeling issue related to this proposal.




  




#  References
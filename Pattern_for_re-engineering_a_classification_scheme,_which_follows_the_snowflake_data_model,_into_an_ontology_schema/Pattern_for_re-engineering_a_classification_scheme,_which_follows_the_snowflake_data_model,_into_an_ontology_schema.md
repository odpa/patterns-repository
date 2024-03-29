#  General information




|  |  |
| --- | --- |
|  Name |  Pattern for re-engineering a classification scheme, which follows the snowflake data model, into an ontology schema |
|  Problem |  Re-engineering a classification scheme, which follows the snowflake model, to design an ontology schema. |


  




##  Non-Ontological Resource




|  |  |
| --- | --- |
|  Description |  A non-ontological resource holds a classification scheme which follows the snowflake model. A classification scheme is a rooted tree of concepts, in which each concept groups entities by some particular degree of similarity. The semantics of the hierarchical relation between parents and children concepts may vary depending of the context. The snowflake data model is a normalized structure for hierarchy representations. In this case, the classification scheme items are grouped by levels or entities. There are as many groups as levels the classification scheme has. |
|  Graphical Representation | __Diagram__[Image:Snowflake.png](../Image/Snowflake.png.md "Image:Snowflake.png") |


  




##  Ontology




|  |  |
| --- | --- |
|  Description |  The generated ontology will be based on the taxonomy architectural pattern (AP-TX-01). Each category in the classification scheme is mapped to a class, and the semantics of the relationship between children and parent categories are disambiguated by using an external resource. In the case of that the external resource does not provide any relation between two items, the pattern takes advantage of the use of logical patterns for asserting the relation partOf or subClassOf. |
|  Graphical Representation | __Diagram__[Image:Ontology.png](../Image/Ontology.png.md "Image:Ontology.png") |


  




##  Process




|  |  |
| --- | --- |
|  Description |  1. Select all the classification scheme items from the first level.2. For each one of the above selected classification scheme items cei:2.1. Create the corresponding ontology class, Ci class.2.2. Identify the classification scheme items, cej , on the next level, which are children of cei, by using the parent key values.2.3. For each one of the above identified classification scheme items cej :2.3.1. Create the corresponding ontology class, Cj class.2.3.2. Using the external resource identify the semantics of the relation between Cj and Ci, and set up the relation identified.2.3.3. Repeat from step 2.2 for cej as a new cei.3. If there are more than one classification scheme items from the first level cei3.1. Create an ad-hoc class as the root class of the ontology.3.2. Using the external resource identify the semantics of the relation between Ci class and the root class, and set up the relation identified. |
|  Graphical Representation | __Diagram__[Image:Wfcssfso.png](../Image/Wfcssfso.png.md "Image:Wfcssfso.png") |


  




#  Scenario example




|  |  |
| --- | --- |
|  Description |  Suppose that someone wants to build an ontology based on an occupation hierarchical classification, which follows the snowflake data model. |


  




##  Example of a Non-Ontological Resource




|  |  |
| --- | --- |
|  Description |  Snowflake models are widely used on data warehouses to build hierarchical classifications on structures known as dimensions. Some examples of dimension are Time, Product Category, Geography, Occupations, etc.In this pattern the example is an occupation hierarchical classification hold on four different tables, one for each level (PROFESSIONI\_0, PROFESSIONI\_1, PROFESSIONI\_2, PROFESSIONI\_3). |
|  Graphical Representation | __Diagram__[Image:SnowflakeExample2.png](../Image/SnowflakeExample2.png.md "Image:SnowflakeExample2.png") |
|  Web Reference | [http://droz.dia.fi.upm.es/nors](http://droz.dia.fi.upm.es/nors "http://droz.dia.fi.upm.es/nors") |


  




##  Ontology example




|  |  |
| --- | --- |
|  Description |  The generated ontology will be based on the taxonomy architectural pattern (AP-TX-01). Each category in the classification scheme is mapped to a class, and the semantics of the relationship between children and parent categories are disambiguated by using an external resource. In the case of that the external resource does not provide any relation between two items, the pattern takes advantage of the use of logical patterns for asserting the relation partOf or subClassOf. |
|  Graphical Representation | __Diagram__[Image:OccupationsOntologySnowFlake.png](../Image/OccupationsOntologySnowFlake.png.md "Image:OccupationsOntologySnowFlake.png") |
|  Web Reference | [http://droz.dia.fi.upm.es/ontologies](http://droz.dia.fi.upm.es/ontologies "http://droz.dia.fi.upm.es/ontologies") |


  




##  Process example




|  |  |
| --- | --- |
|  Description |  1. Create the Professioni specialistiche e tecniche class.1.1. Create the Specialist e tecnici delle scienze informatiche class.1.2. Using the external resource identify the semantics of the relation between the Specialist e tecnici delle scienze informatiche class and the Professioni specialistiche e tecniche class, and set up the relation identified.1.3. Create the Specialist e tecnici delle gestione dimpresa class.1.4. Using the external resource identify the semantics of the relation betweenthe Specialist e tecnici delle gestione dimpresa class and the Professioni specialistiche e tecniche class, and set up the relation identified.2. Create the Professioni operative della gestione dimpresa class.3. Create the Occupation class.4. Using the external resource identify the semantics of the relation between the Professioni specialistiche e tecniche class and the Occupation class, and set up the relation identified.5. Using the external resource identify the semantics of the relation betweenthe Professioni operative della gestione dimpresa class and the Occupation class, and set up the relation identified. |
|  Graphical Representation | __Diagram__[Image:Wfcssfsoexample.png](../Image/Wfcssfsoexample.png.md "Image:Wfcssfsoexample.png") |


  




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



__Scenarios about Pattern for re-engineering a classification scheme, which follows the snowflake data model, into an ontology schema__
No scenario is added to this Content OP.




#  Reviews



__Reviews about Pattern for re-engineering a classification scheme, which follows the snowflake data model, into an ontology schema__
There is no review about this proposal.
This revision (revision ID __11037__) takes in account the reviews: none


Other info at [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Pattern_for_re-engineering_a_classification_scheme%2C_which_follows_the_snowflake_data_model%2C_into_an_ontology_schema&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Pattern_for_re-engineering_a_classification_scheme%2C_which_follows_the_snowflake_data_model%2C_into_an_ontology_schema&action=evaluation")




  




#  Modeling issues



__Modeling issues about Pattern for re-engineering a classification scheme, which follows the snowflake data model, into an ontology schema__
There is no Modeling issue related to this proposal.




  




#  References
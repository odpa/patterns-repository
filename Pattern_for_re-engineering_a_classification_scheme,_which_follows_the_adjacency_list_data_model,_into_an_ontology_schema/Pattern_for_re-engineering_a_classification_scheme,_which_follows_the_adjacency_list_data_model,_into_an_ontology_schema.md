#  General information




|  |  |
| --- | --- |
|  Name |  Pattern for re-engineering a classification scheme, which follows the adjacency list data model, into an ontology schema |
|  Problem |  Re-engineering a classification scheme, which follows the adjacency list model, to design an ontology schema. |


  




##  Non-Ontological Resource




|  |  |
| --- | --- |
|  Description |  A non-ontological resource holds a classification scheme which follows the adjacency list model.A classification scheme is a rooted tree of concepts, in which each concept groups entities by some particular degree of similarity. The semantics of the hierarchical relation between parents and children concepts may vary depending of the context. The adjacency list data model for hierarchical classifications proposes to create an entity which holds a list of items with a linking column associated to their parent items. |
|  Graphical Representation | __Diagram__[Image:AdjacencyList_1.png](../Image/AdjacencyList_1.png.md "Image:AdjacencyList_1.png") |


  




##  Ontology




|  |  |
| --- | --- |
|  Description |  The generated ontology will be based on the taxonomy architectural pattern (AP-TX-01). Each category in the classification scheme is mapped to a class, and the semantics of the relationship between children and parent categories are disambiguated by using an external resource. In the case of that the external resource does not provide any relation between two items, the pattern takes advantage of the use of logical patterns for asserting the relation partOf or subClassOf, as appropriate. |
|  Graphical Representation | __Diagram__[Image:Ontology.png](../Image/Ontology.png.md "Image:Ontology.png") |


  




##  Process




|  |  |
| --- | --- |
|  Description |  1. Identify the classification scheme items which do not have a parent key value, i.e. classification scheme items without parents.2. For each one of the above identified classification scheme items cei:2.1. Create the corresponding ontology class, Ci class.2.2. Identify the classification scheme items, cej , which are children of cei, by using the parent key values.2.3. For each one of the above identified classification scheme items cej :2.3.1. Create the corresponding ontology class, Cj class.2.3.2. Using the external resource identify the semantics of the relation between Cj and Ci, and set up the relation identified.2.3.3. Repeat from step 2.2 for cej as a new cei.3. If there are more than one classification scheme items without parent cei3.1. Create an ad-hoc class as the root class of the ontology.3.2. Using the external resource identify the semantics of the relation between Ci class and the root class, and set up the relation identified. |
|  Graphical Representation | __Diagram__[Image:Workflow_PR-NOR-CLTX-02.png](../Image/Workflow_PR-NOR-CLTX-02.png.md "Image:Workflow_PR-NOR-CLTX-02.png") |


  




#  Scenario example




|  |  |
| --- | --- |
|  Description |  Suppose that someone wants to build an ontology based on the water areas classification published by FAO. This classification scheme follows the adjacency list data model. |


  




##  Example of a Non-Ontological Resource




|  |  |
| --- | --- |
|  Description |  The FAO classification for water areas groups them according to some different criteria as environment, statistics, and jurisdiction, among others. |
|  Graphical Representation | __Diagram__[Image:AdjacencyListWaterAreas_1.png](../Image/AdjacencyListWaterAreas_1.png.md "Image:AdjacencyListWaterAreas_1.png") |
|  Web Reference | [http://www.fao.org/figis/servlet/RefServlet](http://www.fao.org/figis/servlet/RefServlet "http://www.fao.org/figis/servlet/RefServlet") |


  




##  Ontology example




|  |  |
| --- | --- |
|  Description |  The generated ontology will be based on the taxonomy architectural pattern (AP-TX-01). Each category in the classification scheme is mapped to a class, and the semantics of the relationship between children and parent categories are disambiguated by using an external resource. In the case of that the external resource does not provide any relation between two items, the pattern takes advantage of the use of logical patterns for asserting the relation partOf or subClassOf, as appropriate. |
|  Graphical Representation | __Diagram__[Image:WaterAreaOntology_1.png](../Image/WaterAreaOntology_1.png.md "Image:WaterAreaOntology_1.png") |
|  Web Reference | [http://www.fao.org/aims/neon.jsp](http://www.fao.org/aims/neon.jsp "http://www.fao.org/aims/neon.jsp") |


  




##  Process example




|  |  |
| --- | --- |
|  Description |  1. Create the Water area class.2. Create the Environmental area class.3. Using the external resource identify the semantics of the relation betweenEnvironmental area class and the Water area class, and set up the relation identified.3.1. Create the Inland/marine class.3.2. Using the external resource identify the semantics of the relation betweenInland/marine class and the Environmental area class, and set up the relation identified.3.3. Create the Ocean class.3.4. Using the external resource identify the semantics of the relation betweenOcean class and the Environmental area class, and set up the relation identified.3.5. Create the North/South/Equatorial class.3.6. Using the external resource identify the semantics of the relation betweenNorth/South/Equatorial class and the Environmental area class, and set up the relation identified.4. Create the Fishing Statistical area class.5. Using the external resource identify the semantics of the relation between Fishing Statistical area class and the Water area class, and set up the relation identified.5.1. Create the FAO statistical area class.5.2. Using the external resource identify the semantics of the relation between FAO statistical area class and the Fishing Statistical area class, and set up the relation identified.5.3. Create the Areal grid system class.5.4. Using the external resource identify the semantics of the relation betweenAreal grid system class and the Fishing Statistical area class, and set up the relation identified.6. Create the Jurisdiction area class.7. Using the external resource identify the semantics of the relation betweenJurisdiction area class and the Water area class, and set up the relation identified. |
|  Graphical Representation | __Diagram__[Image:Workflow_PR-NOR-CLTX-02_example.png](../Image/Workflow_PR-NOR-CLTX-02_example.png.md "Image:Workflow_PR-NOR-CLTX-02_example.png") |


  




#  About




|  |  |
| --- | --- |
|  SubmittedBy | [BorisVillazón-Terrazas](../User/BorisVillazón-Terrazas.md "User:BorisVillazón-Terrazas") |
|  Author |  BorisVillazón-Terrazas |
|  Also known as |  |
|  Known uses |  |
|  Related to | [Use the Architectural Pattern: TX-AP-01](http://ontologydesignpatterns.org/wiki/index.php?title=Use_the_Architectural_Pattern:_TX-AP-01&action=edit&redlink=1 "Use the Architectural Pattern: TX-AP-01 (not yet written)") |
|  Other References |  |


#  Additional information


#  Scenarios



__Scenarios about Pattern for re-engineering a classification scheme, which follows the adjacency list data model, into an ontology schema__
No scenario is added to this Content OP.




#  Reviews



__Reviews about Pattern for re-engineering a classification scheme, which follows the adjacency list data model, into an ontology schema__
There is no review about this proposal.
This revision (revision ID __8954__) takes in account the reviews: none


Other info at [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Pattern_for_re-engineering_a_classification_scheme%2C_which_follows_the_adjacency_list_data_model%2C_into_an_ontology_schema&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Pattern_for_re-engineering_a_classification_scheme%2C_which_follows_the_adjacency_list_data_model%2C_into_an_ontology_schema&action=evaluation")




  




#  Modeling issues



__Modeling issues about Pattern for re-engineering a classification scheme, which follows the adjacency list data model, into an ontology schema__
There is no Modeling issue related to this proposal.




  




#  References
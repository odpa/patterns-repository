#  General information




|  |  |
| --- | --- |
|  Name |  Pattern for re-engineering a term-based thesaurus, which follows the recordbased data model, into an ontology schema |
|  Problem |  Re-engineering a term-based thesaurus which follows the record-based model to design an ontology schema. |


  




##  Non-Ontological Resource




|  |  |
| --- | --- |
|  Description |  A non-ontological resource holds a term-based thesaurus which follows the record-based model.A thesaurus represents the knowledge of a domain with a collection of terms and a limited set of relations between them. The record-based data model is a denormalized structure, uses a record for every term with the information about the term, such as synonyms, broader, narrower and related terms. |
|  Graphical Representation | __Diagram__[Image:recordbasedtermbased.png](../Image/Recordbasedtermbased.png.md "Image:recordbasedtermbased.png") |


  




##  Ontology




|  |  |
| --- | --- |
|  Description |  The generated ontology will be based on the lightweight ontology architectural pattern (AP-LW-01). Each thesaurus term is mapped to a class. For the disambiguation of the semantics of the BT, NT and RT relations among thesaurus terms the pattern relies on an external resource. In the case of that the external resource does not provide any relation between two terms, the pattern takes advantage of the use of logical patterns for asserting the relation partOf, subClassOf or relatedClass. For the UF/USE relations we usethe logical pattern proposed by Corcho et al. suggested as best practice in thecontext of this antipattern: the tendency to declare two classes equivalent when in fact their labels simply express synonym. |
|  Graphical Representation | __Diagram__[Image:recordbasedtermbasedOntologycheck.png](../Image/RecordbasedtermbasedOntologycheck.png.md "Image:recordbasedtermbasedOntologycheck.png") |


  




##  Process




|  |  |
| --- | --- |
|  Description |  1. Identify the records which contain thesaurus terms without a broader term.2. For each one of the above identified thesaurus terms ti:2.1. Create the corresponding ontology class, Ci class, if it is not created yet.2.2. Identify the thesaurus terms, tj , which are narrower terms of ti. They arereferenced in the same record which contains ti.2.3. For each one of the above identified thesaurus term tj :2.3.1. Create the corresponding ontology class, Cj class, if it is not created yet.2.3.2. Using the external resource identify the semantics of the relation between Cj and Ci, and set up the relation identified.2.3.3. Repeat from step 2.2 for cj as a new ci2.4. Identify the thesaurus terms, tr, which are related terms of ti. They are referenced in the same record which contains ti.2.5. For each one of the above identified thesaurus terms tr:2.5.1. Create the corresponding ontology class, Cr class, if it is not created yet.2.5.2. Using the external resource identify the semantics of the relation between Cr and Ci, and set up the relation identified.2.5.3. Repeat from step 2.4 for cr as a new ci2.6. Identify the thesaurus terms, tq, which are equivalent terms of ti. They are referenced in the same record which contains ti.2.7. For each one of the above identified thesaurus terms tq:2.7.1. Use the logical pattern proposed by Corcho et al. 2.7.2. Repeat from step 2.6 for cq as a new ci. |
|  Graphical Representation | __Diagram__[Image:Workflow_PR-NOR-TSLO-01_1.png](../Image/Workflow_PR-NOR-TSLO-01_1.png.md "Image:Workflow_PR-NOR-TSLO-01_1.png") |


  




#  Scenario example




|  |  |
| --- | --- |
|  Description |  Suppose that someone wants to build a lightweight ontology based on the European Training Thesaurus (ETT), which is a term-based thesaurus and it follows the record-based model. |


  




##  Example of a Non-Ontological Resource




|  |  |
| --- | --- |
|  Description |  The European Training Thesaurus (ETT) constitutes the controlled vocabulary of reference in the field of vocational education and training (VET) in Europe. |
|  Graphical Representation | __Diagram__[Image:recordbasedtermbasedexample2.png](../Image/Recordbasedtermbasedexample2.png.md "Image:recordbasedtermbasedexample2.png") |
|  Web Reference | [http://libserver.cedefop.europa.eu/ett/en/](http://libserver.cedefop.europa.eu/ett/en/ "http://libserver.cedefop.europa.eu/ett/en/") |


  




##  Ontology example




|  |  |
| --- | --- |
|  Description |  The generated ontology will be based on the lightweight ontology architectural pattern (AP-LW-01). Each thesaurus term is mapped to a class. For the disambiguation of the semantics of the BT, NT and RT relations among thesaurus terms the pattern relies on an external resource. In the case of that the external resource does not provide any relation between two terms, the pattern takes advantage of the use of logical patterns for asserting the relation partOf, subClassOf or relatedClass. For the UF/USE relations we use the logical pattern proposed by Corcho et al. suggested as best practice in the context of this antipattern: the tendency to declare two classes equivalent when in fact their labels simply express synonym. |
|  Graphical Representation | __Diagram__[Image:recordbasedtermbasedOntologyETTcheck.png](../Image/RecordbasedtermbasedOntologyETTcheck.png.md "Image:recordbasedtermbasedOntologyETTcheck.png") |
|  Web Reference |  |


  




##  Process example




|  |  |
| --- | --- |
|  Description |  1. Create the learning class and the personal development class.2. Create the competence class.3. Using the external resource identify the semantics of the relation betweencompetence and learning, and set up the relation identified.4. Create the performance class.5. Using the external resource identify the semantics of the relation betweenperformance and personal development, and set up the relation identified.6. Assert that achievement is label of the performance class.7. Using the external resource identify the semantics of the relation betweencompetence and performance, and set up the relation identified.8. Create the skill class.9. Using the external resource identify the semantics of the relation between skill and competence, and set up the relation identified.9.1. Create the efficiency class.9.2. Using the external resource identify the semantics of the relation betweenefficiency and performance, and set up the relation identified.9.3. Create the failure class.9.4. Using the external resource identify the semantics of the relation betweenfailure and performance, and set up the relation identified.9.5. Create the success class.9.6. Using the external resource identify the semantics of the relation betweensuccess and performance, and set up the relation identified. |
|  Graphical Representation | __Diagram__[Image:wfthtbrbloexamplecheck.png](../Image/Wfthtbrbloexamplecheck.png.md "Image:wfthtbrbloexamplecheck.png") |


  




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



__Scenarios about Pattern for re-engineering a term-based thesaurus, which follows the recordbased data model, into an ontology schema__
No scenario is added to this Content OP.




#  Reviews



__Reviews about Pattern for re-engineering a term-based thesaurus, which follows the recordbased data model, into an ontology schema__
There is no review about this proposal.
This revision (revision ID __11033__) takes in account the reviews: none


Other info at [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Pattern_for_re-engineering_a_term-based_thesaurus%2C_which_follows_the_recordbased_data_model%2C_into_an_ontology_schema&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Pattern_for_re-engineering_a_term-based_thesaurus%2C_which_follows_the_recordbased_data_model%2C_into_an_ontology_schema&action=evaluation")




  




#  Modeling issues



__Modeling issues about Pattern for re-engineering a term-based thesaurus, which follows the recordbased data model, into an ontology schema__
There is no Modeling issue related to this proposal.




  




#  References
# 

 General information




|  |  |
| --- | --- |
|  Name  |  Pattern for re-engineering a classification scheme, which follows the path enumeration data model, into an ontology schema  |
|  Problem  |  Re-engineering a classification scheme which follows the path enumeration data model to design an ontology schema  |



  





## 

 Non-Ontological Resource




|  |  |
| --- | --- |
|  Description  |  A non-ontological resource holds a classification scheme which follows the path enumeration model.  A classification scheme is a rooted tree of concepts, in which each concept groups entities by some particular degree of similarity. The semantics of the hierarchical relation between parents and children concepts may vary depending of the context.The path enumeration data model, for classification schemes, takes advantage of that there is one and only one path from the root to every item in the classification. The path enumeration model stores that path as string by concatenating either the edges or the keys of the classification scheme items in the path.  |
|  Graphical Representation  | __Diagram__ [Image:PathEnumeration_1.png](../Image/PathEnumeration_1.png "Image:PathEnumeration_1.png") |



  





## 

 Ontology




|  |  |
| --- | --- |
|  Description  |  The generated ontology will be based on the taxonomy architectural pattern (AP-TX-01). Each category in the classification scheme is mapped to a class, and the semantics of the relationship between children and parent categories are disambiguated by using an external resource. In the case of that the external resource does not provide any relation between two items, the pattern takes advantage of the use of logical patterns for asserting the relation partOf or subClassOf, as appropriate.  |
|  Graphical Representation  | __Diagram__ [Image:Ontology.png](../Image/Ontology.png "Image:Ontology.png") |



  





## 

 Process




|  |  |
| --- | --- |
|  Description  |  1. Identify the classification scheme items whose their path enumeration values have the shortest length, i.e. classification scheme items without parents.  2. For each one of the above identified classification scheme items cei:  2.1. Create the corresponding ontology class, Ci class.  2.2. Identify the classification scheme items, cej , which are children of cei, by using the path enumeration values.  2.3. For each one of the above identified classification scheme items cej :  2.3.1. Create the corresponding ontology class, Cj class.  2.3.2. Using the external resource identify the semantics of the relation between Cj and Ci and set up the relation identified.  2.3.3. Repeat from step 2.2 for cej as a new cei.  3. If there are more than one classification scheme items without parent cei  3.1. Create an ad-hoc class as the root class of the ontology.  3.2. Using the external resource identify the semantics of the relation between Ci class and the root class, and set up the relation identified  |
|  Graphical Representation  | __Diagram__ [Image:Workflow_PR-NOR-CLTX-01_1.png](../Image/Workflow_PR-NOR-CLTX-01_1.png "Image:Workflow_PR-NOR-CLTX-01_1.png") |



  





# 

 Scenario example




|  |  |
| --- | --- |
|  Description  |  Suppose that someone wants to build an ontology based on the International Standard Classification of Occupations (for European Union purposes) ISCO-88 (COM).  |



  





## 

 Example of a Non-Ontological Resource




|  |  |
| --- | --- |
|  Description  |  The International Standard Classification of Occupations (for European Union purposes), 1988 version: ISCO-88 (COM) published by Eurostat is modeled with the path enumeration data model.  |
|  Graphical Representation  | __Diagram__ [Image:PathEnumerationOccupations2.png](../Image/PathEnumerationOccupations2.png "Image:PathEnumerationOccupations2.png") |
|  Web Reference  | [http://ec.europa.eu/eurostat/ramon/nomenclatures/index.cfm?%20TargetUrl=LST\_NOM&StrLanguageCode=EN&IntFamilyCode=260276&TxtSearch=](http://ec.europa.eu/eurostat/ramon/nomenclatures/index.cfm?%20TargetUrl=LST_NOM&StrLanguageCode=EN&IntFamilyCode=260276&TxtSearch= "http://ec.europa.eu/eurostat/ramon/nomenclatures/index.cfm?%20TargetUrl=LST_NOM&StrLanguageCode=EN&IntFamilyCode=260276&TxtSearch=")  |



  





## 

 Ontology example




|  |  |
| --- | --- |
|  Description  |  The generated ontology will be based on the taxonomy architectural pattern (AP-TX-01). Each category in the classification scheme is mapped to a class, and the semantics of the relationship between children and parent categories are disambiguated by using an external resource. In the case of that the external resource does not provide any relation between two items, the pattern takes advantage of the use of logical patterns for asserting the relation partOf or subClassOf, as appropriate.  |
|  Graphical Representation  | __Diagram__ [Image:OccupationsOntology.png](../Image/OccupationsOntology.png "Image:OccupationsOntology.png") |
|  Web Reference  | [http://droz.dia.fi.upm.es/hrmontology/](http://droz.dia.fi.upm.es/hrmontology/ "http://droz.dia.fi.upm.es/hrmontology/")  |



  





## 

 Process example




|  |  |
| --- | --- |
|  Description  |  1. Create the LEGISLATORS, SENIOR OFFICIALS AND MANAGERS class.  1.1. Create the Legislators and senior officials class.  1.2. Using the external resource identify the semantics of the relation betweenLegislators and senior officials and LEGISLATORS, SENIOR OFFICIALS AND MANAGERS and set up the relation identified.  1.3. Create the Corporate managers class.  1.4. Using the external resource identify the semantics of the relation betweenCorporate managers and LEGISLATORS, SENIOR OFFICIALS AND MANAGERS and set up the relation identified.  2. Create the PROFESSIONALS class.  3. Create the Occupation class.  4. Using the external resource identify the semantics of the relation between LEGISLATORS, SENIOR OFFICIALS AND MANAGERS and Occupation and set up the relation identified.  5. Using the external resource identify the semantics of the relation between PROFESSIONALS and Occupation and set up the relation identified.  |
|  Graphical Representation  | __Diagram__ [Image:Workflow_PR-NOR-CLTX-01_example_1.png](../Image/Workflow_PR-NOR-CLTX-01_example_1.png "Image:Workflow_PR-NOR-CLTX-01_example_1.png") |



  





# 

 About




|  |  |
| --- | --- |
|  SubmittedBy  | [BorisVillazón-Terrazas](../User/BorisVillazón-Terrazas "User:BorisVillazón-Terrazas")  |
|  Author  |  BorisVillazón-Terrazas  |
|  Also known as  |  |
|  Known uses  |  |
|  Related to  | [Use the Architectural Pattern: TX-AP-01](http://ontologydesignpatterns.org/wiki/index.php?title=Use_the_Architectural_Pattern:_TX-AP-01&action=edit&redlink=1 "Use the Architectural Pattern: TX-AP-01 (not yet written)")  |
|  Other References  |  |



# 

 Additional information



# 

 Scenarios




__Scenarios about Pattern for re-engineering a classification scheme, which follows the path enumeration data model, into an ontology schema__ 


 No scenario is added to this Content OP.
 




# 

 Reviews




__Reviews about Pattern for re-engineering a classification scheme, which follows the path enumeration data model, into an ontology schema__ 


 There is no review about this proposal.
This revision (revision ID
 __11039__ 
 ) takes in account the reviews: none
 



 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Pattern_for_re-engineering_a_classification_scheme%2C_which_follows_the_path_enumeration_data_model%2C_into_an_ontology_schema&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Pattern_for_re-engineering_a_classification_scheme%2C_which_follows_the_path_enumeration_data_model%2C_into_an_ontology_schema&action=evaluation") 





  





# 

 Modeling issues




__Modeling issues about Pattern for re-engineering a classification scheme, which follows the path enumeration data model, into an ontology schema__ 


 There is no Modeling issue related to this proposal.
 




  





# 

 References
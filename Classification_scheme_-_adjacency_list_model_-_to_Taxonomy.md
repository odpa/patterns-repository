# 

 General information




|  |  |
| --- | --- |
|  Name  |  Classification scheme - adjacency list model - to Taxonomy  |
|  Problem  |  Re-engineering a classification scheme which follows the adjacency list model to design a taxonomy.  APPLICABILITY  The semantics of the relation between parent and children items are subClassOf.  There is no multi-inheritance nor cyclic relations.  |



  





## 

 Non-Ontological Resource




|  |  |
| --- | --- |
|  Description  |  A non-ontological resource holds a classification scheme which follows the adjacency list model.  A classification scheme is a rooted tree of concepts, in which each concept groups entities by some particular degree of similarity.The semantics of the hierarchical relation between parents and children concepts may vary depending of the context.The adjacency list data model for hierarchical classifications proposes to create an entity which holds a list of items with a linking column associated to their parent items.  |
|  Graphical Representation  | __Diagram__ [Image:AdjacencyList.png](../Image/AdjacencyList.png "Image:AdjacencyList.png") |



  





## 

 Ontology




|  |  |
| --- | --- |
|  Description  |  The ontology generated will be based on the taxonomy architectural pattern (AP-TX-01). Each category in the classification scheme is mapped to a class, and the semantics of the relationship between children and parent categories are mapped to subClassOf relations.  |
|  Graphical Representation  | __Diagram__ [Image:Ontology.png](../Image/Ontology.png "Image:Ontology.png") |



  





## 

 Process




|  |  |
| --- | --- |
|  Description  |  1. Identify the classification scheme items which do not have a parent key value, i.e. classification scheme items without parents.  2. For each one of the above identified classification scheme items cei:  2.1. Create the corresponding ontology class, Ci class.  2.2. Identify the classification scheme items, cej , which are children of cei, by using the parent key values.  2.3. For each one of the above identified classification scheme items cej :  2.3.1. Create the corresponding ontology class, Cj class.  2.3.2. Set up the subClassOf relation between Cj and Ci.  2.3.3. Repeat from step 2.2 for cej as a new cei.  3. If there are more than one classification scheme items without parent cei  3.1. Create an ad-hoc class as the root class of the ontology.  3.2. Set up the subClassOf relation between Ci class and the root class.  |
|  Graphical Representation  | __Diagram__ [Image:Wfcsalsocheck.png](../Image/Wfcsalsocheck.png "Image:Wfcsalsocheck.png") |



  





# 

 Scenario example




|  |  |
| --- | --- |
|  Description  |  Suppose that someone wants to build an ontology based on the water areas classification published by FAO. This classification scheme follows the adjacency list data model.  |



  





## 

 Example of a Non-Ontological Resource




|  |  |
| --- | --- |
|  Description  |  The FAO classification for water areas groups them according to some different criteria as environment, statistics, and jurisdiction, among others.  |
|  Graphical Representation  | __Diagram__ [Image:AdjacencyListWaterAreas.png](../Image/AdjacencyListWaterAreas.png "Image:AdjacencyListWaterAreas.png") |
|  Web Reference  | [http://www.fao.org/figis/servlet/RefServlet](http://www.fao.org/figis/servlet/RefServlet "http://www.fao.org/figis/servlet/RefServlet")  |



  





## 

 Ontology example




|  |  |
| --- | --- |
|  Description  |  The ontology generated will be based on the taxonomy architectural pattern (AP-TX-01). Each category in the classification scheme is mapped to a class, and the semantics of the relationship between children and parent categories are mapped to subClassOf relations.  |
|  Graphical Representation  | __Diagram__ [Image:WaterAreaOntology.png](../Image/WaterAreaOntology.png "Image:WaterAreaOntology.png") |
|  Web Reference  | [http://www.fao.org/aims/neon.jsp](http://www.fao.org/aims/neon.jsp "http://www.fao.org/aims/neon.jsp")  |



  





## 

 Process example




|  |  |
| --- | --- |
|  Description  |  1. Create the Water area class.  2. Create the Environmental area class, and set up the subClassOf relation between the Environmental area class and the Water area class.  2.1. Create the Inland/marine class, and set up the subClassOf relation between the Inland/marine class and the Environmental area class.  2.2. Create the Ocean class, and set up the subClassOf relation between the Ocean class and the Environmental area class.  2.3. Create the North/South/Equatorial class, and set up the subClassOf relation between the North a South a Equatorial class and the Environmental area class.  3. Create the Fishing Statistical area class, and set up the subClassOf relationbetween the Fishing Statistical area class and the Water area class.  3.1. Create the FAO statistical area class, and set up the subClassOf relation between the FAO statistical area class and the Fishing Statistical area class.  3.2. Create the Areal grid system class, and set up the subClassOf relation between the Areal grid system class and the Fishing Statistical area class.  4. Create the Jurisdiction area class, and set up the subClassOf relation between the Jurisdiction area class and the Water area class.  |
|  Graphical Representation  | __Diagram__ [Image:wfcsalsoexamplecheck.png](../Image/Wfcsalsoexamplecheck.png "Image:wfcsalsoexamplecheck.png") |



  





# 

 About




|  |  |
| --- | --- |
|  SubmittedBy  | [BorisVillazón-Terrazas](../User/BorisVillazón-Terrazas "User:BorisVillazón-Terrazas")  |
|  Author  |  Boris Villazón Terrazas  |
|  Also known as  |  Classification scheme to Taxonomy (adjacency list model)  |
|  Known uses  |  |
|  Related to  | [Use the Architectural Pattern: TX-AP-01](http://ontologydesignpatterns.org/wiki/index.php?title=Use_the_Architectural_Pattern:_TX-AP-01&action=edit&redlink=1 "Use the Architectural Pattern: TX-AP-01 (not yet written)")  |
|  Other References  |  |



# 

 Additional information



# 

 Scenarios




__Scenarios about Classification scheme - adjacency list model - to Taxonomy__ 


 No scenario is added to this Content OP.
 




# 

 Reviews




__Reviews about Classification scheme - adjacency list model - to Taxonomy__ 



|  Review article  | [Posted on](../Property/CreationDate "Property:CreationDate")  | [About revision (current is 10787)](../Property/ReviewAboutVersion "Property:ReviewAboutVersion")  |
| --- | --- | --- |
| [RimDJEDIDI about Classification scheme - adjacency list model - to Taxonomy](../Reviews/RimDJEDIDI_about_Classification_scheme_-_adjacency_list_model_-_to_Taxonomy "Reviews:RimDJEDIDI about Classification scheme - adjacency list model - to Taxonomy")  |  2455082  7 September 2009  |  5625  5,625  |
| [VojtechSvatek about Classification scheme - adjacency list model - to Taxonomy](../Reviews/VojtechSvatek_about_Classification_scheme_-_adjacency_list_model_-_to_Taxonomy "Reviews:VojtechSvatek about Classification scheme - adjacency list model - to Taxonomy")  |  2455083  8 September 2009  |  5681  5,681  |
| [FrancoisScharffe about Classification scheme - adjacency list model - to Taxonomy](../Reviews/FrancoisScharffe_about_Classification_scheme_-_adjacency_list_model_-_to_Taxonomy "Reviews:FrancoisScharffe about Classification scheme - adjacency list model - to Taxonomy")  |  2455086  11 September 2009  |  5798  5,798  |



 This revision (revision ID
 __10787__ 
 ) takes in account the reviews: none
 



 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Classification_scheme_-_adjacency_list_model_-_to_Taxonomy&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Classification_scheme_-_adjacency_list_model_-_to_Taxonomy&action=evaluation") 





  





# 

 Modeling issues




__Modeling issues about Classification scheme - adjacency list model - to Taxonomy__ 


 There is no Modeling issue related to this proposal.
 




  





# 

 References



  






|  |  Submission to event [WOP:2009](../WOP/2009 "WOP:2009")  |
| --- | --- |
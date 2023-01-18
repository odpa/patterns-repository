# 

 General information




|  |  |
| --- | --- |
|  Name  |  Classification scheme - path enumeration model - to Taxonomy  |
|  Problem  |  Re-engineering a classification scheme which follows the path enumeration model to design a taxonomy.  APPLICABILITY  The semantics of the relation between parent and children items are subClassOf.  There is no multi-inheritance nor cyclic relations.  |



  





## 

 Non-Ontological Resource




|  |  |
| --- | --- |
|  Description  |  A non-ontological resource holds a classification scheme which follows the path enumeration model.  A classification scheme is a rooted tree of concepts, in which each concept groups entities by some particular degree of similarity. The semantics of the hierarchical relation between parents and children concepts may vary depending of the context.The path enumeration data model for classification schemes take advantage of that there is one and only one path from the root to every item in the classification. The path enumeration model stores that path as string by concatenating either the edges or the keys of the classification scheme items in the path.  |
|  Graphical Representation  | __Diagram__ [Image:PathEnumeration.png](../Image/PathEnumeration.png "Image:PathEnumeration.png") |



  





## 

 Ontology




|  |  |
| --- | --- |
|  Description  |  The generated ontology will be based on the taxonomy architectural pattern (AP-TX-01). Each category in the classification scheme is mapped to a class, and the semantics of the relationship between children and parent categories are mapped to subClassOf relations.  |
|  Graphical Representation  | __Diagram__ [Image:Ontology.png](../Image/Ontology.png "Image:Ontology.png") |



  





## 

 Process




|  |  |
| --- | --- |
|  Description  |  1. Identify the classification scheme items whose their path enumeration values are equal to their key values, i.e. classification scheme items without parents.  2. For each one of the above identified classification scheme items cei:  2.1. Create the corresponding ontology class, Ci class.  2.2. Identify the classification scheme items, cej , which are children of cei, by using the path enumeration values.  2.3. For each one of the above identified classification scheme items cej :  2.3.1. Create the corresponding ontology class, Cj class.  2.3.2. Set up the subClassOf relation between Cj and Ci.  2.3.3. Repeat from step 2.2 for cej as a new cei.  3. If there are more than one classification scheme items without parent cei  3.1. Create an ad-hoc class as the root class of the ontology.  3.2. Set up the subClassOf relation between Ci class and the root class.  |
|  Graphical Representation  | __Diagram__ [Image:Wfcspesocheck.png](../Image/Wfcspesocheck.png "Image:Wfcspesocheck.png") |



  





# 

 Scenario example




|  |  |
| --- | --- |
|  Description  |  Suppose that someone wants to build an ontology based on the International Standard Classification of Occupations (for European Union purposes) ISCO-88 (COM). This classification scheme follows the path enumeration data model.  |



  





## 

 Example of a Non-Ontological Resource




|  |  |
| --- | --- |
|  Description  |  The International Standard Classification of Occupations (for European Union purposes), 1988 version: ISCO-88 (COM) published by Eurostat is modeled with the path enumeration data model.  |
|  Graphical Representation  | __Diagram__ [Image:PathEnumerationOccupationscheck.png](../Image/PathEnumerationOccupationscheck.png "Image:PathEnumerationOccupationscheck.png") |
|  Web Reference  | [http://ec.europa.eu/eurostat/ramon/nomenclatures/index.cfm? TargetUrl=LST\_NOM&StrLanguageCode=EN&IntFamilyCode=260276&TxtSearch=](http://ec.europa.eu/eurostat/ramon/nomenclatures/index.cfm?%20TargetUrl=LST_NOM&StrLanguageCode=EN&IntFamilyCode=260276&TxtSearch= "http://ec.europa.eu/eurostat/ramon/nomenclatures/index.cfm?%20TargetUrl=LST_NOM&StrLanguageCode=EN&IntFamilyCode=260276&TxtSearch=")  |



  





## 

 Ontology example




|  |  |
| --- | --- |
|  Description  |  The generated ontology will be based on the taxonomy architectural pattern (AP-TX-01). Each occupation in the classification scheme is mapped to a class, and the semantics of the relationship between children and parent categories are mapped to subClassOf relations.  |
|  Graphical Representation  | __Diagram__ [Image:OccupationsOntology.png](../Image/OccupationsOntology.png "Image:OccupationsOntology.png") |
|  Web Reference  | [http://droz.dia.fi.upm.es/hrmontology/](http://droz.dia.fi.upm.es/hrmontology/ "http://droz.dia.fi.upm.es/hrmontology/")  |



  





## 

 Process example




|  |  |
| --- | --- |
|  Description  |  1. Create the LEGISLATORS, SENIOR OFFICIALS AND MANAGERS class.  1.1. Create the Legislators and senior officials class, and set up the subClassOf relation between the Legislators and senior officials class and theLEGISLATORS, SENIOR OFFICIALS AND MANAGERS class.  1.2. Create the Corporate managers class, and set up the subClassOf relation between the Corporate managers class and the LEGISLATORS, SENIOR OFFICIALS ANDMANAGERS class.  2. Create the PROFESSIONALS class.  3. Create the Occupation class.  4. Set up the subClassOf relation between the LEGISLATORS, SENIOR OFFICIALS AND MANAGERS class and the Occupation class.  5. Set up the subClassOf relation between the PROFESSIONALS class and the Occupation class.  |
|  Graphical Representation  | __Diagram__ [Image:Wfcspesoexamplecheck.png](../Image/Wfcspesoexamplecheck.png "Image:Wfcspesoexamplecheck.png") |



  





# 

 About




|  |  |
| --- | --- |
|  SubmittedBy  | [Boris Villazón Terrazas](http://ontologydesignpatterns.org/wiki/index.php?title=User:Boris_Villaz%C3%B3n_Terrazas&action=edit&redlink=1 "User:Boris Villazón Terrazas (not yet written)")  |
|  Author  |  Boris Villazón Terrazas  |
|  Also known as  |  Classification scheme - path enumeration model - to Taxonomy  |
|  Known uses  |  |
|  Related to  | [Use the Architectural Pattern: TX-AP-01](http://ontologydesignpatterns.org/wiki/index.php?title=Use_the_Architectural_Pattern:_TX-AP-01&action=edit&redlink=1 "Use the Architectural Pattern: TX-AP-01 (not yet written)")  |
|  Other References  |  |



# 

 Additional information



# 

 Scenarios




__Scenarios about Classification scheme - path enumeration model - to Taxonomy__ 


 No scenario is added to this Content OP.
 




# 

 Reviews




__Reviews about Classification scheme - path enumeration model - to Taxonomy__ 



|  Review article  | [Posted on](../Property/CreationDate "Property:CreationDate")  | [About revision (current is 8952)](../Property/ReviewAboutVersion "Property:ReviewAboutVersion")  |
| --- | --- | --- |
| [VioletaDamjanovic about Classification scheme - path enumeration model - to Taxonomy](../Reviews/VioletaDamjanovic_about_Classification_scheme_-_path_enumeration_model_-_to_Taxonomy "Reviews:VioletaDamjanovic about Classification scheme - path enumeration model - to Taxonomy")  |  2455083  8 September 2009  |  5629  5,629  |
| [KurtSandkuhl about Classification scheme - path enumeration model - to Taxonomy](../Reviews/KurtSandkuhl_about_Classification_scheme_-_path_enumeration_model_-_to_Taxonomy "Reviews:KurtSandkuhl about Classification scheme - path enumeration model - to Taxonomy")  |  2455083  8 September 2009  |  5712  5,712  |
| [GerdGroener about Classification scheme - path enumeration model - to Taxonomy](../Reviews/GerdGroener_about_Classification_scheme_-_path_enumeration_model_-_to_Taxonomy "Reviews:GerdGroener about Classification scheme - path enumeration model - to Taxonomy")  |  2455085  10 September 2009  |  5776  5,776  |



 This revision (revision ID
 __8952__ 
 ) takes in account the reviews: none
 



 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Classification_scheme_-_path_enumeration_model_-_to_Taxonomy&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Classification_scheme_-_path_enumeration_model_-_to_Taxonomy&action=evaluation") 





  





# 

 Modeling issues




__Modeling issues about Classification scheme - path enumeration model - to Taxonomy__ 


 There is no Modeling issue related to this proposal.
 




  





# 

 References



  






|  |  Submission to event [WOP2009](../WOP2009 "WOP2009")  |
| --- | --- |
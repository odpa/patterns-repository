# 

 Graphical representation



__Diagram__ 





[![Image:biologicalentities.jpg](./Biologicalentities.jpg)](../Image/Biologicalentities.jpg.md "Image:biologicalentities.jpg")





# 

 General description




|  |  |
| --- | --- |
|  Name:  |  biological entities  |
|  Submitted by:  | [ValentinaPresutti](../User/ValentinaPresutti.md "User:ValentinaPresutti")  |
|  Also Known As:  |  biological species  |
|  Intent:  |  To represent biological species and relations between them.  |
|  Domains:  | [Biology](../Community/Biology.md "Community:Biology")  , [Fishery](../Community/Fishery.md "Community:Fishery")  |
|  Competency Questions:  |  |
|  Solution description:  |  stub  |
|  Reusable OWL Building Block:  | [http://www.fao.org/aims/aos/fi/species\_v1.0\_model.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=http://www.fao.org/aims/aos/fi/species_v1.0_model.owl&message=OWL building block&from_page_id=335&update=)  (929)  |
|  Consequences:  |  Classification of biological entities for the fishery domain.  |
|  Scenarios:  |  TestScenario1, TestScenario2  |
|  Known Uses:  |  |
|  Web References:  |  |
|  Other References:  |  |
|  Examples (OWL files):  |  |
|  Extracted From:  |  |
|  Reengineered From:  |  |
|  Has Components:  |  |
|  Specialization Of:  |  |
|  Related CPs:  |  |



  





# 

 Elements



_The
 __Biological Entities__ 
 Content OP locally defines the following ontology elements:_ 





[Submissions:Biological Entities/biological entity](http://ontologydesignpatterns.org/wiki/Special:AddData/Ontology Element Form/Submissions:Biological_Entities/biological_entity "Submissions:Biological Entities/biological entity (not yet written)") 

[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[biological\_entity](http://ontologydesignpatterns.org/wiki/Special:AddData/Ontology Element Form/Submissions:Biological_Entities/biological_entity "Submissions:Biological Entities/biological entity (not yet written)") 
 page_ 




[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__family__ 
 (owl:Class) A type of
 [biological\_entity](http://ontologydesignpatterns.org/wiki/Special:AddData/Ontology Element Form/Submissions:Biological_Entities/biological_entity "Submissions:Biological Entities/biological entity (not yet written)") 
 . It is disjoint with
 [group](./Biological_Entities/group.md "Submissions:Biological Entities/group") 
 ,
 [order](./Biological_Entities/order.md "Submissions:Biological Entities/order") 
 , and
 [species](./Biological_Entities/species.md "Submissions:Biological Entities/species") 
 .
 



[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[family](./Biological_Entities/family.md "Submissions:Biological Entities/family") 
 page_ 




[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__group__ 
 (owl:Class) A type of
 [biological\_entity](http://ontologydesignpatterns.org/wiki/Special:AddData/Ontology Element Form/Submissions:Biological_Entities/biological_entity "Submissions:Biological Entities/biological entity (not yet written)") 
 . It is disjoint with
 [family](./Biological_Entities/family.md "Submissions:Biological Entities/family") 
 ,
 [order](./Biological_Entities/order.md "Submissions:Biological Entities/order") 
 , and
 [species](./Biological_Entities/species.md "Submissions:Biological Entities/species") 
 .
 



[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[group](./Biological_Entities/group.md "Submissions:Biological Entities/group") 
 page_ 




[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__species__ 
 (owl:Class) A type of
 [biological\_entity](http://ontologydesignpatterns.org/wiki/Special:AddData/Ontology Element Form/Submissions:Biological_Entities/biological_entity "Submissions:Biological Entities/biological entity (not yet written)") 
 . It is disjoint with
 [family](./Biological_Entities/family.md "Submissions:Biological Entities/family") 
 ,
 [order](./Biological_Entities/order.md "Submissions:Biological Entities/order") 
 , and
 [group](./Biological_Entities/group.md "Submissions:Biological Entities/group") 
 .
 



[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[species](./Biological_Entities/species.md "Submissions:Biological Entities/species") 
 page_ 




[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__order__ 
 (owl:Class) A type of
 [biological\_entity](http://ontologydesignpatterns.org/wiki/Special:AddData/Ontology Element Form/Submissions:Biological_Entities/biological_entity "Submissions:Biological Entities/biological entity (not yet written)") 
 . It is disjoint with
 [family](./Biological_Entities/family.md "Submissions:Biological Entities/family") 
 ,
 [group](./Biological_Entities/group.md "Submissions:Biological Entities/group") 
 , and
 [species](./Biological_Entities/species.md "Submissions:Biological Entities/species") 
 .
 



[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[order](./Biological_Entities/order.md "Submissions:Biological Entities/order") 
 page_ 




[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__includesOrder__ 
 (owl:ObjectProperty) This object property relates two biological entities. In fact both its domain and its range are the class
 [biological\_entity](http://ontologydesignpatterns.org/wiki/Special:AddData/Ontology Element Form/Submissions:Biological_Entities/biological_entity "Submissions:Biological Entities/biological entity (not yet written)") 




[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[includesOrder](./Biological_Entities/includesOrder.md "Submissions:Biological Entities/includesOrder") 
 page_ 




[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__includesFamily__ 
 (owl:ObjectProperty) This object property relates two biological entities. In fact both its domain and its range are the class
 [biological\_entity](http://ontologydesignpatterns.org/wiki/Special:AddData/Ontology Element Form/Submissions:Biological_Entities/biological_entity "Submissions:Biological Entities/biological entity (not yet written)") 




[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[includesFamily](./Biological_Entities/includesFamily.md "Submissions:Biological Entities/includesFamily") 
 page_ 




[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__includesSpecies__ 
 (owl:ObjectProperty) This object property relates two biological entities. In fact both its domain and its range are the class
 [biological\_entity](http://ontologydesignpatterns.org/wiki/Special:AddData/Ontology Element Form/Submissions:Biological_Entities/biological_entity "Submissions:Biological Entities/biological entity (not yet written)") 




[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[includesSpecies](./Biological_Entities/includesSpecies.md "Submissions:Biological Entities/includesSpecies") 
 page_ 



[Submissions:Biological Entities/hasCode](http://ontologydesignpatterns.org/wiki/Special:AddData/Ontology Element Form/Submissions:Biological_Entities/hasCode "Submissions:Biological Entities/hasCode (not yet written)") 

[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[hasCode](http://ontologydesignpatterns.org/wiki/Special:AddData/Ontology Element Form/Submissions:Biological_Entities/hasCode "Submissions:Biological Entities/hasCode (not yet written)") 
 page_ 



[Submissions:Biological Entities/hasID](http://ontologydesignpatterns.org/wiki/Special:AddData/Ontology Element Form/Submissions:Biological_Entities/hasID "Submissions:Biological Entities/hasID (not yet written)") 

[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[hasID](http://ontologydesignpatterns.org/wiki/Special:AddData/Ontology Element Form/Submissions:Biological_Entities/hasID "Submissions:Biological Entities/hasID (not yet written)") 
 page_ 



[Submissions:Biological Entities/hasMeta](http://ontologydesignpatterns.org/wiki/Special:AddData/Ontology Element Form/Submissions:Biological_Entities/hasMeta "Submissions:Biological Entities/hasMeta (not yet written)") 

[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[hasMeta](http://ontologydesignpatterns.org/wiki/Special:AddData/Ontology Element Form/Submissions:Biological_Entities/hasMeta "Submissions:Biological Entities/hasMeta (not yet written)") 
 page_ 



[Submissions:Biological Entities/hasName](http://ontologydesignpatterns.org/wiki/Special:AddData/Ontology Element Form/Submissions:Biological_Entities/hasName "Submissions:Biological Entities/hasName (not yet written)") 

[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[hasName](http://ontologydesignpatterns.org/wiki/Special:AddData/Ontology Element Form/Submissions:Biological_Entities/hasName "Submissions:Biological Entities/hasName (not yet written)") 
 page_ 



[Submissions:Biological Entities/hasNameFull](http://ontologydesignpatterns.org/wiki/Special:AddData/Ontology Element Form/Submissions:Biological_Entities/hasNameFull "Submissions:Biological Entities/hasNameFull (not yet written)") 

[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[hasNameFull](http://ontologydesignpatterns.org/wiki/Special:AddData/Ontology Element Form/Submissions:Biological_Entities/hasNameFull "Submissions:Biological Entities/hasNameFull (not yet written)") 
 page_ 



[Submissions:Biological Entities/hasNameScientific](http://ontologydesignpatterns.org/wiki/Special:AddData/Ontology Element Form/Submissions:Biological_Entities/hasNameScientific "Submissions:Biological Entities/hasNameScientific (not yet written)") 

[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[hasNameScientific](http://ontologydesignpatterns.org/wiki/Special:AddData/Ontology Element Form/Submissions:Biological_Entities/hasNameScientific "Submissions:Biological Entities/hasNameScientific (not yet written)") 
 page_ 


# 

 Additional information



 This proposal comes from one of the FAO ontologies developed in the context of the
 [NeOn project](http://www.neon-project.org "http://www.neon-project.org") 
 . The author of the ontology here proposed as CP is
 [CaterinaCaracciolo](../User/CaterinaCaracciolo.md "User:CaterinaCaracciolo") 
 .
 



# 

 Scenarios




__Scenarios about Biological Entities__ 


 No scenario is added to this Content OP.
 




# 

 Reviews




__Reviews about Biological Entities__ 



|  Review article  | [Posted on](../Property/CreationDate.md "Property:CreationDate")  | [About revision (current is 9212)](../Property/ReviewAboutVersion.md "Property:ReviewAboutVersion")  |
| --- | --- | --- |
| [Biological Entities Review ValentinaPresutti](../Reviews/Biological_Entities_Review_ValentinaPresutti.md "Reviews:Biological Entities Review ValentinaPresutti")  |  2454567  10 April 2008  |  2011  2,011  |



 This revision (revision ID
 __9212__ 
 ) takes in account the reviews: none
 



 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Biological_Entities&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Biological_Entities&action=evaluation") 





  





# 

 Modeling issues




__Modeling issues about Biological Entities__ 


 There is no Modeling issue related to this proposal.
 




  





# 

 References


* NeOn-FAO case study overview [Case study overview](http://aims.fao.org/website/NeON/sub2 "http://aims.fao.org/website/NeON/sub2")  | [reference page](../Community/References/NeOn-FAO-Case-study.md "Community:References/NeOn-FAO-Case-study")* Ontology-driven Stock Depletion Alert System [Documentation](http://www.neon-project.org/web-content/index.php?option=com_content&view=article&id=26&Itemid=46 "http://www.neon-project.org/web-content/index.php?option=com_content&view=article&id=26&Itemid=46")  | [reference page](../Community/References/NeOn-FAO-Ontology-driven-Stock-Depletion-Alert-System.md "Community:References/NeOn-FAO-Ontology-driven-Stock-Depletion-Alert-System")
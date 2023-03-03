# 

 Graphical representation



__Diagram__ 
_(this article has no graphical representation)_ 




# 

 General description




|  |  |
| --- | --- |
|  Name:  |  LinnaeanTaxonomy  |
|  Submitted by:  | [AldoGangemi](../User/AldoGangemi.md "User:AldoGangemi")  |
|  Also Known As:  |  |
|  Intent:  |  -  |
|  Domains:  |  |
|  Competency Questions:  |  |
|  Solution description:  |  --  |
|  Reusable OWL Building Block:  | [http://www.ontologydesignpatterns.org/cp/owl/linnaeantaxonomy.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=http://www.ontologydesignpatterns.org/cp/owl/linnaeantaxonomy.owl&message=OWL building block&from_page_id=2290&update=)  (751)  |
|  Consequences:  |  |
|  Scenarios:  |  |
|  Known Uses:  |  |
|  Web References:  |  |
|  Other References:  |  |
|  Examples (OWL files):  |  |
|  Extracted From:  |  |
|  Reengineered From:  | <li><a class="external free" href="http://en.wikipedia.org/wiki/Taxonomic_rank" rel="nofollow" title="http://en.wikipedia.org/wiki/Taxonomic_rank">        http://en.wikipedia.org/wiki/Taxonomic_rank       </a></li><li><a class="external free" href="http://en.wikipedia.org/wiki/Taxon" rel="nofollow" title="http://en.wikipedia.org/wiki/Taxon">        http://en.wikipedia.org/wiki/Taxon       </a></li><li><a class="external free" href="http://en.wikipedia.org/wiki/Linnaean_taxonomy" rel="nofollow" title="http://en.wikipedia.org/wiki/Linnaean_taxonomy">        http://en.wikipedia.org/wiki/Linnaean_taxonomy       </a></li> |
|  Has Components:  |  |
|  Specialization Of:  |  |
|  Related CPs:  |  |



  





# 

 Elements



_The
 __LinnaeanTaxonomy__ 
 Content OP locally defines the following ontology elements:_ 





[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__hasDirectHigherRank__ 
 (owl:ObjectProperty) This property relates two taxa, where the first is more specific then the second and there is no other taxon that is both more general than the first and more specific than the second.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[hasDirectHigherRank](./LinnaeanTaxonomy/hasDirectHigherRank.md "Submissions:LinnaeanTaxonomy/hasDirectHigherRank") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__hasDirectLowerRank__ 
 (owl:ObjectProperty) This property relates two taxa, where the first is less specific then the second and there is no other taxon that is both more specific than the first and more general than the second.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[hasDirectLowerRank](./LinnaeanTaxonomy/hasDirectLowerRank.md "Submissions:LinnaeanTaxonomy/hasDirectLowerRank") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__hasHigherRank__ 
 (owl:ObjectProperty) This property relates two taxa, where the first is more specific than the second.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[hasHigherRank](./LinnaeanTaxonomy/hasHigherRank.md "Submissions:LinnaeanTaxonomy/hasHigherRank") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__hasLowerRank__ 
 (owl:ObjectProperty) This property relates two taxa, where the first is less specific than the second.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[hasLowerRank](./LinnaeanTaxonomy/hasLowerRank.md "Submissions:LinnaeanTaxonomy/hasLowerRank") 
 page_ 



[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__Class__ 
 (owl:Class) Class is the third highest traditional taxon. E.g., in the case of humans the class is 'Mammalia'.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[Class](./LinnaeanTaxonomy/Class.md "Submissions:LinnaeanTaxonomy/Class") 
 page_ 



[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__Family__ 
 (owl:Class) Family is the fifth highest traditional taxon. E.g., in the case of humans the family is 'Hominidae'.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[Family](./Biological_Entities/includesFamily.md "Submissions:LinnaeanTaxonomy/Family") 
 page_ 



[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__Genus__ 
 (owl:Class) Genus is the sixth highest traditional taxon. E.g., in the case of humans the genus is 'Homo'.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[Genus](./LinnaeanTaxonomy/Genus.md "Submissions:LinnaeanTaxonomy/Genus") 
 page_ 



[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__Kingdom__ 
 (owl:Class) Kingdom is the highest traditional taxon. E.g., in the case of humans the kingdom is 'Animalia'.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[Kingdom](./LinnaeanTaxonomy/Kingdom.md "Submissions:LinnaeanTaxonomy/Kingdom") 
 page_ 



[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__Order__ 
 (owl:Class) Order is the fourth highest traditional taxon. E.g., in the case of humans the phylum is 'Primates'.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[Order](./Biological_Entities/includesOrder.md "Submissions:LinnaeanTaxonomy/Order") 
 page_ 



[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__Phylum__ 
 (owl:Class) Phylum is the second highest traditional taxon. E.g., in the case of humans the phylum is 'Chordata'.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[Phylum](./LinnaeanTaxonomy/Phylum.md "Submissions:LinnaeanTaxonomy/Phylum") 
 page_ 



[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__Species__ 
 (owl:Class) Species is the lowest traditional taxon. E.g., in the case of humans the species is 'Homo sapiens'.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[Species](../GearSpecies/GearSpecies.md "Submissions:LinnaeanTaxonomy/Species") 
 page_ 



[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__Taxon__ 
 (owl:Class) A taxon is a concept denoting a type of organism or of a group of organisms.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[Taxon](./LinnaeanTaxonomy/Taxon.md "Submissions:LinnaeanTaxonomy/Taxon") 
 page_ 


# 

 Additional information



 The linnaean taxonomy content ontology design pattern represents the layered classification invented by Linneus in the XVIII century. It is created by reengineering Wikipedia articles about taxa, taxonomic ranks, and linnaean taxonomy.
 



# 

 Scenarios




__Scenarios about LinnaeanTaxonomy__ 


 No scenario is added to this Content OP.
 




# 

 Reviews




__Reviews about LinnaeanTaxonomy__ 



|  Review article  | [Posted on](../Property/CreationDate.md "Property:CreationDate")  | [About revision (current is 9097)](../Property/ReviewAboutVersion.md "Property:ReviewAboutVersion")  |
| --- | --- | --- |
| [CatherineRoussey about LinnaeanTaxonomy](../Community/CatherineRoussey_about_LinnaeanTaxonomy.md "Community:CatherineRoussey about LinnaeanTaxonomy")  |  2456435  22 May 2013  |  9097  9,097  |



 This revision (revision ID
 __9097__ 
 ) takes in account the reviews: none
 



 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:LinnaeanTaxonomy&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:LinnaeanTaxonomy&action=evaluation") 





  





# 

 Modeling issues




__Modeling issues about LinnaeanTaxonomy__ 


 There is no Modeling issue related to this proposal.
 




  





# 

 References
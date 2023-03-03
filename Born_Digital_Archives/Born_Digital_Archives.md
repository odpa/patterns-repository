# 

 Graphical representation



__Diagram__ 





[![Image:BDA_ODP_Diagram.png](./BDA_ODP_Diagram.png)](../Image/BDA_ODP_Diagram.png.md "Image:BDA_ODP_Diagram.png")





# 

 General description




|  |  |
| --- | --- |
|  Name:  |  Born Digital Archives  |
|  Submitted by:  | [MarinaRiga](../User/MarinaRiga.md "User:MarinaRiga")  , [PanagiotisMitzias](../User/PanagiotisMitzias.md "User:PanagiotisMitzias")  , [EfstratiosKontopoulos](../User/EfstratiosKontopoulos.md "User:EfstratiosKontopoulos")  |
|  Also Known As:  |  |
|  Intent:  |  The pattern intends to model the domain of born digital archives. This pattern has been developed by [MKLab](http://mklab.iti.gr/ "http://mklab.iti.gr/")  at CERTH/ITI for the [PERICLES](http://www.pericles-project.eu/ "http://www.pericles-project.eu/")  FP7 project.  |
|  Domains:  | [Archives](./Born_Digital_Archives.md "Community:Archives")  |
|  Competency Questions:  | <li><p><i>         What are the main entities (units) that compose born digital archives?        </i>        These are:        <ul><li>          fonds         </li><li>          series         </li><li>          files         </li><li>          items         </li></ul></p></li>* _What is the hierarchy of units within a born digital archive?_  Fonds composed from series or files; series composed from files; files composed from items.* _Who is the creator of an archive?_  The creator is an entity of type foaf:Agent. |
|  Solution description:  |  The pattern's main entity is a unit, subclassed by fonds, series, files and items.  |
|  Reusable OWL Building Block:  | [http://mklab.iti.gr/pericles/BornDigitalArchives\_ODP.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=http://mklab.iti.gr/pericles/BornDigitalArchives_ODP.owl&message=OWL building block&from_page_id=4341&update=)  (545)  |
|  Consequences:  |  The design pattern is expected to facilitate the creation of domain ontologies related to Born Digital Archives that can be exploited in numerous fields. A well-established, comprehensible pattern will prove to be advantageous.  |
|  Scenarios:  | <li>       Series A has part file B.      </li><li>       Fonds C has part Series A.      </li><li>       File D has creator John Smith.      </li> |
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
 __Born Digital Archives__ 
 Content OP locally defines the following ontology elements:_ 





[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__hasCreator__ 
 (owl:ObjectProperty) Indicates the creator of a unit.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[hasCreator](./Born_Digital_Archives/hasCreator.md "Submissions:Born Digital Archives/hasCreator") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__hasPart__ 
 (owl:ObjectProperty) Indicates that a unit includes another unit.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[hasPart](./An_Ontology_Design_Pattern_for_Activity_Reasoning/hasPart.md "Submissions:Born Digital Archives/hasPart") 
 page_ 



[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__Creator__ 
 (owl:Class) The creator of a born digital archive unit
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[Creator](./Born_Digital_Archives/Creator.md "Submissions:Born Digital Archives/Creator") 
 page_ 



[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__File__ 
 (owl:Class) An organized unit of documents grouped together either for current use by the creator or in the process of archival arrangement, because they relate to the same subject, activity, or transaction. A file is usually the basic unit within a record series.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[File](./Born_Digital_Archives/File.md "Submissions:Born Digital Archives/File") 
 page_ 



[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__Fonds__ 
 (owl:Class)
 _Fonds_ 
 : The whole of the records, regardless of form or medium, organically created and/or accumulated and used by a particular person, family, or corporate body in the course of that creator's activities and functions.
   


_Sub-fonds_ 
 : A subdivision of a fonds containing a body of related records corresponding to administrative subdivisions in the originating agency or organization or, when that is not possible, to geographical, chronological, functional, or similar groupings of the material itself. When the creating body has a complex hierarchical structure, each sub-fonds has as many subordinate sub-fonds as are necessary to reflect the levels of the hierarchical structure of the primary subordinate administrative unit.
 



[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[Fonds](./Born_Digital_Archives/Fonds.md "Submissions:Born Digital Archives/Fonds") 
 page_ 



[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__Item__ 
 (owl:Class) The smallest intellectually indivisible archival unit, e.g., a letter, memorandum, report, photograph, sound recording.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[Item](./Bag/hasItem.md "Submissions:Born Digital Archives/Item") 
 page_ 



[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__Series__ 
 (owl:Class) Documents arranged in accordance with a filing system or maintained as a unit because they result from the same accumulation or filing process, or the same activity; have a particular form; or because of some other relationship arising out of their creation, receipt, or use. A series is also known as a records series.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[Series](../RecurrentEventSeries/RecurrentEventSeries.md "Submissions:Born Digital Archives/Series") 
 page_ 



[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__Unit__ 
 (owl:Class) An entity that participates in the assembly of a born digital archive.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[Unit](./Born_Digital_Archives/Unit.md "Submissions:Born Digital Archives/Unit") 
 page_ 


# 

 Additional information



# 

 Scenarios




__Scenarios about Born Digital Archives__ 


 No scenario is added to this Content OP.
 




# 

 Reviews




__Reviews about Born Digital Archives__ 


 There is no review about this proposal.
This revision (revision ID
 __13162__ 
 ) takes in account the reviews: none
 



 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Born_Digital_Archives&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Born_Digital_Archives&action=evaluation") 





  





# 

 Modeling issues




__Modeling issues about Born Digital Archives__ 


 There is no Modeling issue related to this proposal.
 




  





# 

 References
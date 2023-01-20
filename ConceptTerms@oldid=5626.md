[![Image:ConceptTermsPattern.jpg](public/images/0/09/ConceptTermsPattern.jpg)](../Image/ConceptTermsPattern.jpg "Image:ConceptTermsPattern.jpg")





# 

 General description




|  |  |
| --- | --- |
|  Name:  |  ConceptTerms  |
|  Submitted by:  | [Pierre-YvesVandenbussche](../User/Pierre-YvesVandenbussche "User:Pierre-YvesVandenbussche")  |
|  Also Known As:  |  |
|  Intent:  |  This CP allows designers to represent language complexity for concept description (preferred term, synonyms, translation relation,etc.).  |
|  Domains:  | [Linguistic](../Community/Linguistic "Community:Linguistic")  , [Vocabulary](../Community/Vocabulary "Community:Vocabulary")  |
|  Competency Questions:  | <li>       How to distinguish a preferred term or label from synonyms in order to name a concept?      </li><li>       How to enable cross language searching?      </li><li>       How to allow adding properties on term?      </li> |
|  Solution description:  |  A concept is named in a particular language by a preferred term and a set of simple non preferred terms. Those terms artifacts specialize the term entity which owns common properties for terms such as: language, source information (when creating vocabulary from corpora). This list of properties may be extended depending on vocabulary specific needs.  |
|  Reusable OWL Building Block:  | [http://sites.google.com/site/pierreyvesvandenbussche/resources/ConceptTerms.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=http://sites.google.com/site/pierreyvesvandenbussche/resources/ConceptTerms.owl&message=OWL building block&from_page_id=1661&update=)  (1151)  |
|  Consequences:  |  Compare to labels on a concept class, this solution has a higher data load.  |
|  Scenarios:  |  Used for terminology representation. For example, a preferred term "car" in english could be translated in "voiture" in french and linked to the same concept. Here translation relation is possible thanks to the term entity.  |
|  Known Uses:  |  |
|  Web References:  |  |
|  Other References:  |  |
|  Examples (OWL files):  |  |
|  Extracted From:  |  |
|  Reengineered From:  | <li>       BS8723-5 model:       <a class="external free" href="http://schemas.bs8723.org/" rel="nofollow" title="http://schemas.bs8723.org/">        http://schemas.bs8723.org/       </a></li> |
|  Has Components:  |  |
|  Specialization Of:  |  |
|  Related CPs:  |  |



  





# 

 Elements



_The
 __ConceptTerms__ 
 Content OP locally defines the following ontology elements:_ 




  





# 

 Scenarios




__Scenarios about ConceptTerms__ 

* This ontology contains an example ABox for the ConceptTerms CP available at [http://sites.google.com/site/pierreyvesvandenbussche/resources/ConceptTerms.owl](http://sites.google.com/site/pierreyvesvandenbussche/resources/ConceptTerms.owl "http://sites.google.com/site/pierreyvesvandenbussche/resources/ConceptTerms.owl")


 This ontology describes example coming from Eurovoc(
 [http://europa.eu/eurovoc/](http://europa.eu/eurovoc/ "http://europa.eu/eurovoc/") 
 ) where a concept has a preferred term "social sciences" in english and a simple non preferred term (i.e. synonyms) "humanities" in the same language whereas the same concept has a preferred term "sciences sociales" in french and a simple non preferred term "sciences humaines" in this language. We consider a second preferred term in english "award" which names a concept. In this particular information retrieval context, we define a coumpound non preferred term "social sciences awards" which is related to preferred terms "social sciences" and "award".
 [>>>](../Submissions/ConceptTerms/Scenario_1 "http://ontologydesignpatterns.org/wiki/Submissions:ConceptTerms/Scenario_1") 





# 

 Reviews




__Reviews about ConceptTerms__ 



|  Review article  | [Posted on](../Property/CreationDate "Property:CreationDate")  | [About revision (current is 5626)](../Property/ReviewAboutVersion "Property:ReviewAboutVersion")  |
| --- | --- | --- |
| [WimPeters about ConceptTerms](../Reviews/WimPeters_about_ConceptTerms "Reviews:WimPeters about ConceptTerms")  |  2455083  8 September 2009  |  5626  5,626  |
| [MariCarmenSuarezFigueroa about ConceptTerms](../Reviews/MariCarmenSuarezFigueroa_about_ConceptTerms "Reviews:MariCarmenSuarezFigueroa about ConceptTerms")  |  2455083  8 September 2009  |  5714  5,714  |
| [VojtechSvatek about ConceptTerms](../Reviews/VojtechSvatek_about_ConceptTerms "Reviews:VojtechSvatek about ConceptTerms")  |  2455083  8 September 2009  |  5714  5,714  |



 This revision (revision ID
 __5626__ 
 ) takes in account the reviews:
 [WimPeters about ConceptTerms](../Reviews/WimPeters_about_ConceptTerms "Reviews:WimPeters about ConceptTerms") 
 ,
 [VojtechSvatek about ConceptTerms](../Reviews/VojtechSvatek_about_ConceptTerms "Reviews:VojtechSvatek about ConceptTerms") 
 ,
 [MariCarmenSuarezFigueroa about ConceptTerms](../Reviews/MariCarmenSuarezFigueroa_about_ConceptTerms "Reviews:MariCarmenSuarezFigueroa about ConceptTerms") 




 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:ConceptTerms&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:ConceptTerms&action=evaluation") 





  






|  |  Submission to event [WOP2009](../WOP2009 "WOP2009")  |
| --- | --- |
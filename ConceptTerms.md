# 

 Graphical representation



__Diagram__ 





[![Image:ConceptTermsPattern.jpg](../images/0/09/ConceptTermsPattern.jpg)](../Image/ConceptTermsPattern.jpg "Image:ConceptTermsPattern.jpg")





# 

 General description




|  |  |
| --- | --- |
|  Name:  |  ConceptTerms  |
|  Submitted by:  | [Pierre-YvesVandenbussche](../User/Pierre-YvesVandenbussche "User:Pierre-YvesVandenbussche")  , [JeanCharlet](../User/JeanCharlet "User:JeanCharlet")  |
|  Also Known As:  |  |
|  Intent:  |  This CP allows designers to represent jointly conceptual and linguistic part of a vocabulary.  The pattern purpose is not to encompass all linguistic complexity as Linginfo or LMF does, but to describe linguistic information in more details than SKOS which names concept whith simple labels.  |
|  Domains:  | [Linguistic](../Community/Linguistic "Community:Linguistic")  , [Vocabulary](../Community/Vocabulary "Community:Vocabulary")  |
|  Competency Questions:  | <li>       How to distinguish a preferred term or label from synonyms in order to name a concept?      </li><li>       How to enable cross language searching?      </li><li>       How to allow adding properties on term?      </li> |
|  Solution description:  |  A concept is named in a particular language by a preferred term and a set of simple non preferred terms. Those terms artifacts specialize the term entity which owns common properties. This list of properties may be extended depending on vocabulary specific needs.  This pattern suits for various vocabularies (thesaurus, terminology, taxonomy…) and has been applied to GEMET, Eurovoc, CIM10 among other.Modeling takes into account:-the possibility to extend the current pattern in order to add some more precise linguistic information (for instance represent translation relation between two terms since term is a class)-minimal linguistic artifacts necessary for vocabulary resource access by providing a preferred Term to name a concept and some synonyms which are Simple non preferred terms.  |
|  Reusable OWL Building Block:  | [http://sites.google.com/site/pierreyvesvandenbussche/resources/ConceptTerms.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=http://sites.google.com/site/pierreyvesvandenbussche/resources/ConceptTerms.owl&message=OWL building block&from_page_id=1661&update=)  (1151)  |
|  Consequences:  |  Compare to labels on a concept class, this solution has a higher data load.  |
|  Scenarios:  |  Used for vocabulary representation. For example in Eurovoc( [http://europa.eu/eurovoc/](http://europa.eu/eurovoc/ "http://europa.eu/eurovoc/")  ), a concept has a preferred term "social sciences" in english and a simple non preferred term (i.e. synonyms) "humanities" in the same language whereas the same concept has a preferred term "sciences sociales" in french and a simple non preferred term "sciences humaines" in this language. If we wanted to add a translation relation between terms we could state that "social sciences" english term is a translation of "sciences sociales" french term. If we consider a second preferred term in english "award" which names a concept, in a particular information retrieval context, we could define a coumpound non preferred term "social sciences awards" which is related to preferred terms "social sciences" and "award".  |
|  Known Uses:  |  |
|  Web References:  |  |
|  Other References:  |  |
|  Examples (OWL files):  | <li><a class="external free" href="http://sites.google.com/site/pierreyvesvandenbussche/resources/ConceptTermsEurovocExample.owl" rel="nofollow" title="http://sites.google.com/site/pierreyvesvandenbussche/resources/ConceptTermsEurovocExample.owl">        http://sites.google.com/site/pierreyvesvandenbussche/resources/ConceptTermsEurovocExample.owl       </a></li> |
|  Extracted From:  |  |
|  Reengineered From:  | <li>       BS8723-5 model:       <a class="external free" href="http://schemas.bs8723.org/Examples.aspx" rel="nofollow" title="http://schemas.bs8723.org/Examples.aspx">        http://schemas.bs8723.org/Examples.aspx       </a>       In BS8723 model      </li><li>       triangular-shaped relations are defined between a thesaurus concept      </li><li>       a preferred term and some simple non preferred terms. We are convinced that maintaining this model can be optimized by reifying those relations in a single relation class. That is why we defines the Concept-Terms relation which reusing N-ary pattern in order to represent terms on a concept. Between all terms      </li><li>       we distinguish a preferred term and some synonyms (simple non preferred terms).      </li> |
|  Has Components:  |  |
|  Specialization Of:  |  |
|  Related CPs:  |  |



  





# 

 Elements



_The
 __ConceptTerms__ 
 Content OP locally defines the following ontology elements:_ 




  





  





# 

 Additional information



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



|  Review article  | [Posted on](../Property/CreationDate "Property:CreationDate")  | [About revision (current is 9079)](../Property/ReviewAboutVersion "Property:ReviewAboutVersion")  |
| --- | --- | --- |
| [WimPeters about ConceptTerms](../Reviews/WimPeters_about_ConceptTerms "Reviews:WimPeters about ConceptTerms")  |  2455083  8 September 2009  |  5626  5,626  |
| [MariCarmenSuarezFigueroa about ConceptTerms](../Reviews/MariCarmenSuarezFigueroa_about_ConceptTerms "Reviews:MariCarmenSuarezFigueroa about ConceptTerms")  |  2455083  8 September 2009  |  5714  5,714  |
| [VojtechSvatek about ConceptTerms](../Reviews/VojtechSvatek_about_ConceptTerms "Reviews:VojtechSvatek about ConceptTerms")  |  2455083  8 September 2009  |  5714  5,714  |



 This revision (revision ID
 __9079__ 
 ) takes in account the reviews:
 [WimPeters about ConceptTerms](../Reviews/WimPeters_about_ConceptTerms "Reviews:WimPeters about ConceptTerms") 
 ,
 [VojtechSvatek about ConceptTerms](../Reviews/VojtechSvatek_about_ConceptTerms "Reviews:VojtechSvatek about ConceptTerms") 
 ,
 [MariCarmenSuarezFigueroa about ConceptTerms](../Reviews/MariCarmenSuarezFigueroa_about_ConceptTerms "Reviews:MariCarmenSuarezFigueroa about ConceptTerms") 




 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:ConceptTerms&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:ConceptTerms&action=evaluation") 





  





# 

 Modeling issues




__Modeling issues about ConceptTerms__ 


 There is no Modeling issue related to this proposal.
 




  





# 

 References



  






|  |  Submission to event [WOP2009](../WOP2009 "WOP2009")  |
| --- | --- |
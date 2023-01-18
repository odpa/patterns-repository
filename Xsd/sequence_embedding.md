# 

 General information




|  |  |
| --- | --- |
|  Name  |  Structural XML/DTD embedding to ontological meronymy  |
|  Problem  |  This pattern addresses the re-engineering of certain embedded structures within XSD and DTD representations into a meronymic pattern.  |



  





## 

 Non-Ontological Resource




|  |  |
| --- | --- |
|  Description  |  \*For a description of XSD see: [http://en.wikipedia.org/wiki/XML\_Schema\_(W3C)](http://en.wikipedia.org/wiki/XML_Schema_(W3C) "http://en.wikipedia.org/wiki/XML_Schema_(W3C)")  The pattern covers the cases where an xsd:element is embedded into an xsd:sequence, which is in its turn embedded by an xsd:element. <li>       The graphical representation only illustrates the XSD case.      </li><li>       The DTD case is described in the example section.      </li> |
|  Graphical Representation  | __Diagram__ [Image:1.JPG](../../Image/1.JPG "Image:1.JPG") |



  





## 

 Ontology




|  |  |
| --- | --- |
|  Description  |  The ontology comprising the pattern representing the relevant XSD or DTD fragment.  |
|  Graphical Representation  | __Diagram__ [Image:Xsd-embedding2.JPG](../../Image/Xsd-embedding2.JPG "Image:Xsd-embedding2.JPG") |



  





## 

 Process




|  |  |
| --- | --- |
|  Description  |  The re-engineering process involves a number of steps: <li>       The creation of embedding class and embedded class(es)      </li><li>       The creation of an instance of the hasPart object property from the DOLCE Ultra Light ontology (       <a class="external free" href="http://www.ontologydesignpatterns.org/ont/dul/DUL.owl" rel="nofollow" title="http://www.ontologydesignpatterns.org/ont/dul/DUL.owl">        http://www.ontologydesignpatterns.org/ont/dul/DUL.owl       </a>       ) with embedding class as domain and embedded class(es) as range.      </li> |
|  Graphical Representation  | __Diagram__ [Image:Xsd-step3.png](../../Image/Xsd-step3.png "Image:Xsd-step3.png") |



  





# 

 Scenario example




|  |  |
| --- | --- |
|  Description  |  The application scenario is in the area of the modelling of lexical translational equivalence according to the format of the XLIFF and TMX standards for translation memory.  |



  





## 

 Example of a Non-Ontological Resource




|  |  |
| --- | --- |
|  Description  |  XLIFF  The purpose of the OASIS XLIFF standard ( [http://docs.oasis-open.org/xliff/v1.2/os/xliff-core.html](http://docs.oasis-open.org/xliff/v1.2/os/xliff-core.html "http://docs.oasis-open.org/xliff/v1.2/os/xliff-core.html")  ) is to define and promote, through extensible XML vocabularies, the adoption of a specification for the interchange of localizable software and document based objects and related metadata.XLIFF should be able to mark-up and capture localization information and interoperate with different processes and phases without loss of information. It should fulfill specific requirements of being tool-neutral. It should support the localization related aspects of internationalization and entire localization process. It also needs to support common software and content data formats. This should also provide an extensibility mechanism to allow the development of tools compatible with an implementer’s proprietary data formats and workflow requirements. <li>       1.	TransUnit: 	contains (a set of) translational equivalences      </li><li>       2.	Source: 	the source of the translation pair      </li><li>       3.	SegSource: 	the translatable text, divided into segments      </li><li>       4.	Mrk: 		Each segment is marked by means of the &lt;Mrk&gt; element with attribute “mType” set to the value "seg".      </li><li>       5.	Target: 	the target of the translation pair      </li><li>       6.	Alt-Trans: 	possible translations as Target instances      </li><li>       7.	Equiv-trans: 	Indicates if the target language translation is a direct equivalent of the source text.      </li> DTD embedding is exemplified (but not illustrated on this page) by Translation Memory eXchange standard (TMX) ( [http://www.lisa.org/Translation-Memory-e.34.0.html](http://www.lisa.org/Translation-Memory-e.34.0.html "http://www.lisa.org/Translation-Memory-e.34.0.html")  ). TMX is the vendor-neutral open XML standard for the exchange of Translation Memory data created by Computer Aided Translation and localization tools. The purpose of TMX is to allow easier exchange of translation memory data between tools and/or translation vendors with little or no loss of critical data during the process. In existence since 1998, TMX is a certifiable standard format. TMX is developed and maintained by OSCAR (Open Standards for Container/Content Allowing Re-use), a LISA (Localization Industry Standards Association) Special Interest Group. The following structure from TMX illustrates the same pattern conversion ```  <!ELEMENT tu     (tuv+) >``` This describes that a translation unit (tu) consists of one or more translation unit variants (tuv).A translationUnit contains the data for a given translation unit.A TranslationUnitVariant specifies text in a given language.A more detailed description of TMX can be found in NeOn deliverable D2.4.3: Multilingual and Localization Support for Ontologies (www.neon-project.org).  |
|  Graphical Representation  | __Diagram__ [Image:xsd-step4.png](../../Image/Xsd-step4.png "Image:xsd-step4.png") |
|  Web Reference  | [http://schemas.liquid-technologies.com/Oasis/XLIFF/1.2/default.html?url=http://schemas.liquid-technologies.com/Oasis/XLIFF/1.2/xliff-core-1\_2-strict\_xsd.html](http://schemas.liquid-technologies.com/Oasis/XLIFF/1.2/default.html?url=http://schemas.liquid-technologies.com/Oasis/XLIFF/1.2/xliff-core-1_2-strict_xsd.html "http://schemas.liquid-technologies.com/Oasis/XLIFF/1.2/default.html?url=http://schemas.liquid-technologies.com/Oasis/XLIFF/1.2/xliff-core-1_2-strict_xsd.html")  |



  





## 

 Ontology example




|  |  |
| --- | --- |
|  Description  |  The xsd:sequence embedding pattern as the resulting ontology pattern.  |
|  Graphical Representation  | __Diagram__ [Image:xsd-step5.JPG](../../Image/Xsd-step5.JPG "Image:xsd-step5.JPG") |
|  Web Reference  | [http://gate.ac.uk/gate-extras/neon/ontologies/xsd-embedding.owl](http://gate.ac.uk/gate-extras/neon/ontologies/xsd-embedding.owl "http://gate.ac.uk/gate-extras/neon/ontologies/xsd-embedding.owl")  |



  





## 

 Process example




|  |  |
| --- | --- |
|  Description  |  The ontological pattern re-engineered from the XLIFF fragment.  |
|  Graphical Representation  | __Diagram__ [Image:Xsd-embedding-6.png](../../Image/Xsd-embedding-6.png "Image:Xsd-embedding-6.png") |



  





# 

 About




|  |  |
| --- | --- |
|  SubmittedBy  | [Wim Peters](http://ontologydesignpatterns.org/wiki/index.php?title=User:Wim_Peters&action=edit&redlink=1 "User:Wim Peters (not yet written)")  |
|  Author  |  Wim Peters  |
|  Also known as  |  |
|  Known uses  |  |
|  Related to  |  |
|  Other References  |  |



  





# 

 Scenarios




__Scenarios about Xsd:sequence embedding__ 


 No scenario is added to this Content OP.
 




# 

 Reviews




__Reviews about Xsd:sequence embedding__ 



|  Review article  | [Posted on](../../Property/CreationDate "Property:CreationDate")  | [About revision (current is 9710)](../../Property/ReviewAboutVersion "Property:ReviewAboutVersion")  |
| --- | --- | --- |
| [MathieuDAquin about Xsd:sequence embedding](../../Reviews/MathieuDAquin_about_Xsd/sequence_embedding "Reviews:MathieuDAquin about Xsd:sequence embedding")  |  2455083  8 September 2009  |  5628  5,628  |
| [EnricoDaga about Xsd:sequence embedding](../../Reviews/EnricoDaga_about_Xsd/sequence_embedding "Reviews:EnricoDaga about Xsd:sequence embedding")  |  2455083  8 September 2009  |  5723  5,723  |
| [BorisVillazón-Terrazas about Xsd:sequence embedding](../../Reviews/BorisVillazón-Terrazas_about_Xsd/sequence_embedding "Reviews:BorisVillazón-Terrazas about Xsd:sequence embedding")  |  2455083  8 September 2009  |  5723  5,723  |



 This revision (revision ID
 __9710__ 
 ) takes in account the reviews: none
 



 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Xsd:sequence_embedding&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Xsd:sequence_embedding&action=evaluation") 





# 

 Modeling issues




__Modeling issues about Xsd:sequence embedding__ 


 There is no Modeling issue related to this proposal.
 




  






|  |  Submission to event [WOP:2009](../../WOP/2009 "WOP:2009")  |
| --- | --- |
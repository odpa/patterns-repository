# 

 Graphical representation



__Diagram__ 
_(this article has no graphical representation)_ 




# 

 General description




|  |  |
| --- | --- |
|  Name:  |  scorepart  |
|  Submitted by:  | [AndreaPoltronieri](../User/AndreaPoltronieri "User:AndreaPoltronieri")  |
|  Also Known As:  |  |
|  Intent:  |  This content ODP formalises the structure and the hierarchies of a music score/symbolic representation system.  |
|  Domains:  |  |
|  Competency Questions:  | <li>       What is the instrument playing a specific score part?      </li><li>       How many voices does the score part have?      </li><li>       Which are the metrics defining the sections of the score part?      </li> |
|  Solution description:  |  |
|  Reusable OWL Building Block:  | [http://ontologydesignpatterns.org/cp/owl/scorepart.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=http://ontologydesignpatterns.org/cp/owl/scorepart.owl&message=OWL building block&from_page_id=4803&update=)  (98)  |
|  Consequences:  |  |
|  Scenarios:  |  |
|  Known Uses:  |  |
|  Web References:  |  |
|  Other References:  |  |
|  Examples (OWL files):  |  |
|  Extracted From:  |  |
|  Reengineered From:  | <li><a class="external free" href="https://purl.org/andreapoltronieri/HaMSEontology" rel="nofollow" title="https://purl.org/andreapoltronieri/HaMSEontology">        https://purl.org/andreapoltronieri/HaMSEontology       </a></li> |
|  Has Components:  |  |
|  Specialization Of:  |  |
|  Related CPs:  |  |



  





# 

 Elements



_The
 __Scorepart__ 
 Content OP locally defines the following ontology elements:_ 





[![Class](images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__Part__ 
 (owl:Class) A part of a a score notation or a symbolic notation assigned to a specific instrument.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[Part](../Submissions/Scorepart/Part "Submissions:Scorepart/Part") 
 page_ 



[![Class](images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__Section__ 
 (owl:Class) A group of notes that share the same metric and clef.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[Section](../Submissions/Scorepart/Section "Submissions:Scorepart/Section") 
 page_ 



[![Class](images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__Instrument__ 
 (owl:Class) Any of various devices or contrivances that can be used to produce musical tones or sound. Any taxonomy can be used to subsume this concept. The default one is one extracted by Ivan Herman from the Musicbrainz instrument taxonomy, conforming to SKOS. This concept holds a seeAlso link towards this taxonomy.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[Instrument](../Submissions/Scorepart/Instrument "Submissions:Scorepart/Instrument") 
 page_ 



[![Class](images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__Voice__ 
 (owl:Class) One of several parts that can be performed within the same staff (e.g. alto and soprano).
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[Voice](../Submissions/Scorepart/Voice "Submissions:Scorepart/Voice") 
 page_ 



[![Class](images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__HomogeneousFragment__ 
 (owl:Class) A group of notes that share the same metric and clef.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[HomogeneousFragment](../Submissions/Scorepart/HomogeneousFragment "Submissions:Scorepart/HomogeneousFragment") 
 page_ 



[![DatatypeProperty](images/thumb/a/a5/DatatypeProperty.gif/20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif "DatatypeProperty")
__hasMidiProgram__ 
 (owl:DatatypeProperty) The instrument playing a specific part expressed by a MIDI program.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasMidiProgram](../Submissions/Scorepart/hasMidiProgram "Submissions:Scorepart/hasMidiProgram") 
 page_ 



[![DatatypeProperty](images/thumb/a/a5/DatatypeProperty.gif/20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif "DatatypeProperty")
__hasStaff__ 
 (owl:DatatypeProperty) The staff assigned to a specific instrument part in a music score.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasStaff](../Submissions/Scorepart/hasStaff "Submissions:Scorepart/hasStaff") 
 page_ 



[![DatatypeProperty](images/thumb/a/a5/DatatypeProperty.gif/20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif "DatatypeProperty")
__hasClef__ 
 (owl:DatatypeProperty) The clef that describes the hight of a note in a music score.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasClef](../Submissions/Scorepart/hasClef "Submissions:Scorepart/hasClef") 
 page_ 



[![DatatypeProperty](images/thumb/a/a5/DatatypeProperty.gif/20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif "DatatypeProperty")
__hasTempo__ 
 (owl:DatatypeProperty) The tempo of an homogeneous fragment, expressed in bpm (integer).
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasTempo](../Submissions/Scorepart/hasTempo "Submissions:Scorepart/hasTempo") 
 page_ 



[![DatatypeProperty](images/thumb/a/a5/DatatypeProperty.gif/20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif "DatatypeProperty")
__hasMetric__ 
 (owl:DatatypeProperty) The metric of a specific section of a music score.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasMetric](../Submissions/Scorepart/hasMetric "Submissions:Scorepart/hasMetric") 
 page_ 



[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__isPlayedBy__ 
 (owl:ObjectProperty) Connects the part of the score/symbolic notation to the instrument that is assigned to play such part.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[isPlayedBy](../Submissions/Scorepart/isPlayedBy "Submissions:Scorepart/isPlayedBy") 
 page_ 



[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasVoice__ 
 (owl:ObjectProperty) Connects the part of the score/symbolic notation to its constituing sections.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasVoice](../Submissions/Scorepart/hasVoice "Submissions:Scorepart/hasVoice") 
 page_ 



[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasSection__ 
 (owl:ObjectProperty) Connects the part of the score/symbolic notation to its constituing sections.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasSection](../Submissions/Scorepart/hasSection "Submissions:Scorepart/hasSection") 
 page_ 



[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasFragment__ 
 (owl:ObjectProperty) Connects the part of the score/symbolic notation to its constituing sections.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasFragment](../Submissions/Scorepart/hasFragment "Submissions:Scorepart/hasFragment") 
 page_ 



[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__isFragmentOf__ 
 (owl:ObjectProperty) Inverse of hasFragment
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[isFragmentOf](../Submissions/Scorepart/isFragmentOf "Submissions:Scorepart/isFragmentOf") 
 page_ 



[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__isSectionOf__ 
 (owl:ObjectProperty) Inverse of hasSection. Connects the section of the score/symbolic notation to the belongng part.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[isSectionOf](../Submissions/Scorepart/isSectionOf "Submissions:Scorepart/isSectionOf") 
 page_ 



[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__isVoiceOf__ 
 (owl:ObjectProperty) Inverse of hasVoice. Connects the voice of the score/symbolic notation to the belonging part.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[isVoiceOf](../Submissions/Scorepart/isVoiceOf "Submissions:Scorepart/isVoiceOf") 
 page_ 



[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__playsPart__ 
 (owl:ObjectProperty) Inverse of isPlayedBy. Connects an instrument to the the part that the instrument plays.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[playsPart](../Submissions/Scorepart/playsPart "Submissions:Scorepart/playsPart") 
 page_ 


# 

 Additional information



# 

 Scenarios




__Scenarios about Scorepart__ 


 No scenario is added to this Content OP.
 




# 

 Reviews




__Reviews about Scorepart__ 


 There is no review about this proposal.
This revision (revision ID
 __14271__ 
 ) takes in account the reviews: none
 



 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Scorepart&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Scorepart&action=evaluation") 





# 

 Modeling issues




__Modeling issues about Scorepart__ 


 There is no Modeling issue related to this proposal.
 




# 

 References



  

 The Score Part pattern models the structure and the hierarchies of a music score.
In this module are used as template the following Ontology Design Patterns:
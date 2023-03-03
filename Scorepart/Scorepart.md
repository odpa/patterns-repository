#  Graphical representation


__Diagram__
_(this article has no graphical representation)_



#  General description




|  |  |
| --- | --- |
|  Name: |  scorepart |
|  Submitted by: | [AndreaPoltronieri](../User/AndreaPoltronieri.md "User:AndreaPoltronieri") |
|  Also Known As: |  |
|  Intent: |  This content ODP formalises the structure and the hierarchies of a music score/symbolic representation system. |
|  Domains: |  |
|  Competency Questions: | <li> What is the instrument playing a specific score part?</li><li> How many voices does the score part have?</li><li> Which are the metrics defining the sections of the score part?</li> |
|  Solution description: |  |
|  Reusable OWL Building Block: | [http://ontologydesignpatterns.org/cp/owl/scorepart.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=http://ontologydesignpatterns.org/cp/owl/scorepart.owl&message=OWL building block&from_page_id=4803&update=) (98) |
|  Consequences: |  |
|  Scenarios: |  |
|  Known Uses: |  |
|  Web References: |  |
|  Other References: |  |
|  Examples (OWL files): |  |
|  Extracted From: |  |
|  Reengineered From: | <li><a class="external free" href="https://purl.org/andreapoltronieri/HaMSEontology" rel="nofollow" title="https://purl.org/andreapoltronieri/HaMSEontology">https://purl.org/andreapoltronieri/HaMSEontology</a></li> |
|  Has Components: |  |
|  Specialization Of: |  |
|  Related CPs: |  |


  




#  Elements


_The __Scorepart__ Content OP locally defines the following ontology elements:_



[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __Part__ (owl:Class) A part of a a score notation or a symbolic notation assigned to a specific instrument. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[Part](./An_Ontology_Design_Pattern_for_Activity_Reasoning/hasPart.md "Submissions:Scorepart/Part") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __Section__ (owl:Class) A group of notes that share the same metric and clef. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[Section](./Scorepart/hasSection.md "Submissions:Scorepart/Section") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __Instrument__ (owl:Class) Any of various devices or contrivances that can be used to produce musical tones or sound. Any taxonomy can be used to subsume this concept. The default one is one extracted by Ivan Herman from the Musicbrainz instrument taxonomy, conforming to SKOS. This concept holds a seeAlso link towards this taxonomy. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[Instrument](./Scorepart/Instrument.md "Submissions:Scorepart/Instrument") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __Voice__ (owl:Class) One of several parts that can be performed within the same staff (e.g. alto and soprano). 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[Voice](./Scorepart/hasVoice.md "Submissions:Scorepart/Voice") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __HomogeneousFragment__ (owl:Class) A group of notes that share the same metric and clef. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[HomogeneousFragment](./Scorepart/HomogeneousFragment.md "Submissions:Scorepart/HomogeneousFragment") page_
[![DatatypeProperty](./20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif.md "DatatypeProperty") __hasMidiProgram__ (owl:DatatypeProperty) The instrument playing a specific part expressed by a MIDI program. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasMidiProgram](./Scorepart/hasMidiProgram.md "Submissions:Scorepart/hasMidiProgram") page_
[![DatatypeProperty](./20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif.md "DatatypeProperty") __hasStaff__ (owl:DatatypeProperty) The staff assigned to a specific instrument part in a music score. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasStaff](./Scorepart/hasStaff.md "Submissions:Scorepart/hasStaff") page_
[![DatatypeProperty](./20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif.md "DatatypeProperty") __hasClef__ (owl:DatatypeProperty) The clef that describes the hight of a note in a music score. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasClef](./Scorepart/hasClef.md "Submissions:Scorepart/hasClef") page_
[![DatatypeProperty](./20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif.md "DatatypeProperty") __hasTempo__ (owl:DatatypeProperty) The tempo of an homogeneous fragment, expressed in bpm (integer). 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasTempo](./Scorepart/hasTempo.md "Submissions:Scorepart/hasTempo") page_
[![DatatypeProperty](./20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif.md "DatatypeProperty") __hasMetric__ (owl:DatatypeProperty) The metric of a specific section of a music score. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasMetric](./OOPMetrics/hasMetric.md "Submissions:Scorepart/hasMetric") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isPlayedBy__ (owl:ObjectProperty) Connects the part of the score/symbolic notation to the instrument that is assigned to play such part. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isPlayedBy](./Scorepart/isPlayedBy.md "Submissions:Scorepart/isPlayedBy") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasVoice__ (owl:ObjectProperty) Connects the part of the score/symbolic notation to its constituing sections. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasVoice](./Scorepart/hasVoice.md "Submissions:Scorepart/hasVoice") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasSection__ (owl:ObjectProperty) Connects the part of the score/symbolic notation to its constituing sections. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasSection](./Scorepart/hasSection.md "Submissions:Scorepart/hasSection") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasFragment__ (owl:ObjectProperty) Connects the part of the score/symbolic notation to its constituing sections. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasFragment](./Scorepart/hasFragment.md "Submissions:Scorepart/hasFragment") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isFragmentOf__ (owl:ObjectProperty) Inverse of hasFragment 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isFragmentOf](./Scorepart/isFragmentOf.md "Submissions:Scorepart/isFragmentOf") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isSectionOf__ (owl:ObjectProperty) Inverse of hasSection. Connects the section of the score/symbolic notation to the belongng part. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isSectionOf](./Scorepart/isSectionOf.md "Submissions:Scorepart/isSectionOf") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isVoiceOf__ (owl:ObjectProperty) Inverse of hasVoice. Connects the voice of the score/symbolic notation to the belonging part. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isVoiceOf](./Scorepart/isVoiceOf.md "Submissions:Scorepart/isVoiceOf") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __playsPart__ (owl:ObjectProperty) Inverse of isPlayedBy. Connects an instrument to the the part that the instrument plays. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[playsPart](./Scorepart/playsPart.md "Submissions:Scorepart/playsPart") page_
#  Additional information


#  Scenarios



__Scenarios about Scorepart__
No scenario is added to this Content OP.




#  Reviews



__Reviews about Scorepart__
There is no review about this proposal.
This revision (revision ID __14271__) takes in account the reviews: none


Other info at [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Scorepart&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Scorepart&action=evaluation")




#  Modeling issues



__Modeling issues about Scorepart__
There is no Modeling issue related to this proposal.




#  References


  

The Score Part pattern models the structure and the hierarchies of a music score.
In this module are used as template the following Ontology Design Patterns:
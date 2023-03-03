#  Graphical representation


__Diagram__




[![Image:Scorepart_pattern.png](./Scorepart_pattern.png)](../Image/Scorepart_pattern.png.md "Image:Scorepart_pattern.png")




#  General description




|  |  |
| --- | --- |
|  Name: |  notepattern |
|  Submitted by: | [AndreaPoltronieri](../User/AndreaPoltronieri.md "User:AndreaPoltronieri") |
|  Also Known As: |  |
|  Intent: |  The Music Note ODP models a symbolic note and its symbolic attributes. |
|  Domains: |  |
|  Competency Questions: | <li> what is the name of a note?</li><li> what part of the score does a note belong to?</li><li> what are the dynamic indications referring to a note in the score?</li><li> what is the fundamental frequency of a note?</li><li> what are the different frequencies that make up the spectrum of a note?</li><li> what is the duration in seconds of a note</li><li> in a given performance?</li><li> how is the envelope of a note shaped?</li> |
|  Solution description: |  |
|  Reusable OWL Building Block: | [http://ontologydesignpatterns.org/cp/owl/notepattern.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=http://ontologydesignpatterns.org/cp/owl/notepattern.owl&message=OWL building block&from_page_id=4806&update=) (110) |
|  Consequences: |  |
|  Scenarios: |  |
|  Known Uses: |  |
|  Web References: |  |
|  Other References: |  |
|  Examples (OWL files): |  |
|  Extracted From: |  |
|  Reengineered From: | <li><a class="external free" href="https://purl.org/andreapoltronieri/HaMSEontology" rel="nofollow" title="https://purl.org/andreapoltronieri/HaMSEontology">https://purl.org/andreapoltronieri/HaMSEontology</a></li> |
|  Has Components: | <li><a href="../Information_realization/Information_realization.md" title="Submissions:Information realization">Submissions:Information realization</a></li> |
|  Specialization Of: |  |
|  Related CPs: | <li><a class="new" href="http://ontologydesignpatterns.org/wiki/index.php?title=Submissions://purl.org/andreapoltronieri/musicalobject&amp;action=edit&amp;redlink=1" title="Submissions://purl.org/andreapoltronieri/musicalobject (not yet written)">Submissions://purl.org/andreapoltronieri/musicalobject</a></li><li><a class="new" href="http://ontologydesignpatterns.org/wiki/index.php?title=Submissions://purl.org/andreapoltronieri/scorepart&amp;action=edit&amp;redlink=1" title="Submissions://purl.org/andreapoltronieri/scorepart (not yet written)">Submissions://purl.org/andreapoltronieri/scorepart</a></li> |


  




#  Elements


_The __Notepattern__ Content OP locally defines the following ontology elements:_



[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __SymbolicNote__ (owl:Class) A music note from the western temperament system. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[SymbolicNote](./Notepattern/SymbolicNote.md "Submissions:Notepattern/SymbolicNote") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __Accidental__ (owl:Class) The accidental of a note (e.g. sharp). 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[Accidental](./Notepattern/Accidental.md "Submissions:Notepattern/Accidental") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __Position__ (owl:Class) The position of a symbolic note 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[Position](./Notepattern/hasMeasurePosition.md "Submissions:Notepattern/Position") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __NotePitch__ (owl:Class) The pitch of a symbolic note. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[NotePitch](./Notepattern/hasNotePitch.md "Submissions:Notepattern/NotePitch") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __NoteDuration__ (owl:Class) The quantised duration of a symbolic music note. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[NoteDuration](./Notepattern/hasNoteDuration.md "Submissions:Notepattern/NoteDuration") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __NoteDynamic__ (owl:Class) The dynamic of a symbolic note. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[NoteDynamic](./Notepattern/hasNoteDynamic.md "Submissions:Notepattern/NoteDynamic") page_
[![DatatypeProperty](./20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif.md "DatatypeProperty") __hasMeasure__ (owl:DatatypeProperty) The measure (expressed in bars) to which a note belongs in a music score. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasMeasure](./Notepattern/hasMeasure.md "Submissions:Notepattern/hasMeasure") page_
[![DatatypeProperty](./20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif.md "DatatypeProperty") __hasMeasurePosition__ (owl:DatatypeProperty) The position the symbolic note have within the bar 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasMeasurePosition](./Notepattern/hasMeasurePosition.md "Submissions:Notepattern/hasMeasurePosition") page_
[![DatatypeProperty](./20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif.md "DatatypeProperty") __hasMidiPitch__ (owl:DatatypeProperty) The pitch of a note expressed by means of its MIDI number. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasMidiPitch](./Notepattern/hasMidiPitch.md "Submissions:Notepattern/hasMidiPitch") page_
[![DatatypeProperty](./20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif.md "DatatypeProperty") __isDefinedByOctave__ (owl:DatatypeProperty) The octave on which the note is defined. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isDefinedByOctave](./Notepattern/isDefinedByOctave.md "Submissions:Notepattern/isDefinedByOctave") page_
[![DatatypeProperty](./20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif.md "DatatypeProperty") __hasLiteralDynamic__ (owl:DatatypeProperty) The dynamic expressed in a music score by means of adjectives (e.g. piano). 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasLiteralDynamic](./Notepattern/hasLiteralDynamic.md "Submissions:Notepattern/hasLiteralDynamic") page_
[![DatatypeProperty](./20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif.md "DatatypeProperty") __hasMidiVelocity__ (owl:DatatypeProperty) The dynamics of the note expressed symbolically by means of the MIDI command "velocity". 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasMidiVelocity](./Notepattern/hasMidiVelocity.md "Submissions:Notepattern/hasMidiVelocity") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasNoteDynamic__ (owl:ObjectProperty) Connects a symbolic note to its symbolic dynamic. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasNoteDynamic](./Notepattern/hasNoteDynamic.md "Submissions:Notepattern/hasNoteDynamic") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isDynamicOf__ (owl:ObjectProperty) Inverse of hasNoteDynamic. Connects a duration class to the symbolic note that have this specific dynamic. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isDynamicOf](./Notepattern/isDynamicOf.md "Submissions:Notepattern/isDynamicOf") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasNoteDuration__ (owl:ObjectProperty) Connects a symbolic note to its symbolic quantised duration. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasNoteDuration](./Notepattern/hasNoteDuration.md "Submissions:Notepattern/hasNoteDuration") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isDurationOfNote__ (owl:ObjectProperty) Inverse of hasNoteDuration. Connects a duration class to the symbolic note that have this specific duration. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isDurationOfNote](./Notepattern/isDurationOfNote.md "Submissions:Notepattern/isDurationOfNote") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasNotePitch__ (owl:ObjectProperty) Connects a symbolic note to its symbolic pitch. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasNotePitch](./Notepattern/hasNotePitch.md "Submissions:Notepattern/hasNotePitch") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isPitchOf__ (owl:ObjectProperty) Inverse of hasPitch. Connects a duration class to the symbolic note that have this specific pitch. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isPitchOf](./Notepattern/isPitchOf.md "Submissions:Notepattern/isPitchOf") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasAccidental__ (owl:ObjectProperty) The accidental of a note (e.g. sharp). 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasAccidental](./Notepattern/hasAccidental.md "Submissions:Notepattern/hasAccidental") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isAccidentalOf__ (owl:ObjectProperty) Inverse of hasAccidental 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isAccidentalOf](./Notepattern/isAccidentalOf.md "Submissions:Notepattern/isAccidentalOf") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasPosition__ (owl:ObjectProperty) Connects the symbolic note with its duration 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasPosition](./Notepattern/hasPosition.md "Submissions:Notepattern/hasPosition") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isPositionOf__ (owl:ObjectProperty) Inverse of hasPosition 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isPositionOf](./Notepattern/isPositionOf.md "Submissions:Notepattern/isPositionOf") page_
  




#  Additional information


#  Scenarios



__Scenarios about Notepattern__
No scenario is added to this Content OP.




#  Reviews



__Reviews about Notepattern__
There is no review about this proposal.
This revision (revision ID __14262__) takes in account the reviews: none


Other info at [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Notepattern&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Notepattern&action=evaluation")




#  Modeling issues



__Modeling issues about Notepattern__
There is no Modeling issue related to this proposal.




#  References


  

The Note Pattern models a music note both in relation to a music score and in relation to the musical object produced by playing such note.
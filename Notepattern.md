# 

 Graphical representation



__Diagram__ 





[![Image:Scorepart_pattern.png](public/images/0/02/Scorepart_pattern.png)](../Image/Scorepart_pattern.png "Image:Scorepart_pattern.png")





# 

 General description




|  |  |
| --- | --- |
|  Name:  |  notepattern  |
|  Submitted by:  | [AndreaPoltronieri](../User/AndreaPoltronieri "User:AndreaPoltronieri")  |
|  Also Known As:  |  |
|  Intent:  |  The Music Note ODP models a symbolic note and its symbolic attributes.  |
|  Domains:  |  |
|  Competency Questions:  | <li>       what is the name of a note?      </li><li>       what part of the score does a note belong to?      </li><li>       what are the dynamic indications referring to a note in the score?      </li><li>       what is the fundamental frequency of a note?      </li><li>       what are the different frequencies that make up the spectrum of a note?      </li><li>       what is the duration in seconds of a note      </li><li>       in a given performance?      </li><li>       how is the envelope of a note shaped?      </li> |
|  Solution description:  |  |
|  Reusable OWL Building Block:  | [http://ontologydesignpatterns.org/cp/owl/notepattern.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=http://ontologydesignpatterns.org/cp/owl/notepattern.owl&message=OWL building block&from_page_id=4806&update=)  (110)  |
|  Consequences:  |  |
|  Scenarios:  |  |
|  Known Uses:  |  |
|  Web References:  |  |
|  Other References:  |  |
|  Examples (OWL files):  |  |
|  Extracted From:  |  |
|  Reengineered From:  | <li><a class="external free" href="https://purl.org/andreapoltronieri/HaMSEontology" rel="nofollow" title="https://purl.org/andreapoltronieri/HaMSEontology">        https://purl.org/andreapoltronieri/HaMSEontology       </a></li> |
|  Has Components:  | <li><a href="Submissions%253AInformation_realization.html" title="Submissions:Information realization">        Submissions:Information realization       </a></li> |
|  Specialization Of:  |  |
|  Related CPs:  | <li><a class="new" href="http://ontologydesignpatterns.org/wiki/index.php?title=Submissions://purl.org/andreapoltronieri/musicalobject&amp;action=edit&amp;redlink=1" title="Submissions://purl.org/andreapoltronieri/musicalobject (not yet written)">        Submissions://purl.org/andreapoltronieri/musicalobject       </a></li><li><a class="new" href="http://ontologydesignpatterns.org/wiki/index.php?title=Submissions://purl.org/andreapoltronieri/scorepart&amp;action=edit&amp;redlink=1" title="Submissions://purl.org/andreapoltronieri/scorepart (not yet written)">        Submissions://purl.org/andreapoltronieri/scorepart       </a></li> |



  





# 

 Elements



_The
 __Notepattern__ 
 Content OP locally defines the following ontology elements:_ 





[![Class](public/images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__SymbolicNote__ 
 (owl:Class) A music note from the western temperament system.
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[SymbolicNote](../Submissions/Notepattern/SymbolicNote "Submissions:Notepattern/SymbolicNote") 
 page_ 



[![Class](public/images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__Accidental__ 
 (owl:Class) The accidental of a note (e.g. sharp).
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[Accidental](../Submissions/Notepattern/Accidental "Submissions:Notepattern/Accidental") 
 page_ 



[![Class](public/images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__Position__ 
 (owl:Class) The position of a symbolic note
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[Position](../Submissions/Notepattern/Position "Submissions:Notepattern/Position") 
 page_ 



[![Class](public/images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__NotePitch__ 
 (owl:Class) The pitch of a symbolic note.
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[NotePitch](../Submissions/Notepattern/NotePitch "Submissions:Notepattern/NotePitch") 
 page_ 



[![Class](public/images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__NoteDuration__ 
 (owl:Class) The quantised duration of a symbolic music note.
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[NoteDuration](../Submissions/Notepattern/NoteDuration "Submissions:Notepattern/NoteDuration") 
 page_ 



[![Class](public/images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__NoteDynamic__ 
 (owl:Class) The dynamic of a symbolic note.
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[NoteDynamic](../Submissions/Notepattern/NoteDynamic "Submissions:Notepattern/NoteDynamic") 
 page_ 



[![DatatypeProperty](public/images/thumb/a/a5/DatatypeProperty.gif/20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif "DatatypeProperty")
__hasMeasure__ 
 (owl:DatatypeProperty) The measure (expressed in bars) to which a note belongs in a music score.
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasMeasure](../Submissions/Notepattern/hasMeasure "Submissions:Notepattern/hasMeasure") 
 page_ 



[![DatatypeProperty](public/images/thumb/a/a5/DatatypeProperty.gif/20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif "DatatypeProperty")
__hasMeasurePosition__ 
 (owl:DatatypeProperty) The position the symbolic note have within the bar
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasMeasurePosition](../Submissions/Notepattern/hasMeasurePosition "Submissions:Notepattern/hasMeasurePosition") 
 page_ 



[![DatatypeProperty](public/images/thumb/a/a5/DatatypeProperty.gif/20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif "DatatypeProperty")
__hasMidiPitch__ 
 (owl:DatatypeProperty) The pitch of a note expressed by means of its MIDI number.
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasMidiPitch](../Submissions/Notepattern/hasMidiPitch "Submissions:Notepattern/hasMidiPitch") 
 page_ 



[![DatatypeProperty](public/images/thumb/a/a5/DatatypeProperty.gif/20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif "DatatypeProperty")
__isDefinedByOctave__ 
 (owl:DatatypeProperty) The octave on which the note is defined.
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[isDefinedByOctave](../Submissions/Notepattern/isDefinedByOctave "Submissions:Notepattern/isDefinedByOctave") 
 page_ 



[![DatatypeProperty](public/images/thumb/a/a5/DatatypeProperty.gif/20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif "DatatypeProperty")
__hasLiteralDynamic__ 
 (owl:DatatypeProperty) The dynamic expressed in a music score by means of adjectives (e.g. piano).
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasLiteralDynamic](../Submissions/Notepattern/hasLiteralDynamic "Submissions:Notepattern/hasLiteralDynamic") 
 page_ 



[![DatatypeProperty](public/images/thumb/a/a5/DatatypeProperty.gif/20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif "DatatypeProperty")
__hasMidiVelocity__ 
 (owl:DatatypeProperty) The dynamics of the note expressed symbolically by means of the MIDI command "velocity".
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasMidiVelocity](../Submissions/Notepattern/hasMidiVelocity "Submissions:Notepattern/hasMidiVelocity") 
 page_ 



[![ObjectProperty](public/images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasNoteDynamic__ 
 (owl:ObjectProperty) Connects a symbolic note to its symbolic dynamic.
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasNoteDynamic](../Submissions/Notepattern/hasNoteDynamic "Submissions:Notepattern/hasNoteDynamic") 
 page_ 



[![ObjectProperty](public/images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__isDynamicOf__ 
 (owl:ObjectProperty) Inverse of hasNoteDynamic. Connects a duration class to the symbolic note that have this specific dynamic.
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[isDynamicOf](../Submissions/Notepattern/isDynamicOf "Submissions:Notepattern/isDynamicOf") 
 page_ 



[![ObjectProperty](public/images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasNoteDuration__ 
 (owl:ObjectProperty) Connects a symbolic note to its symbolic quantised duration.
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasNoteDuration](../Submissions/Notepattern/hasNoteDuration "Submissions:Notepattern/hasNoteDuration") 
 page_ 



[![ObjectProperty](public/images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__isDurationOfNote__ 
 (owl:ObjectProperty) Inverse of hasNoteDuration. Connects a duration class to the symbolic note that have this specific duration.
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[isDurationOfNote](../Submissions/Notepattern/isDurationOfNote "Submissions:Notepattern/isDurationOfNote") 
 page_ 



[![ObjectProperty](public/images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasNotePitch__ 
 (owl:ObjectProperty) Connects a symbolic note to its symbolic pitch.
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasNotePitch](../Submissions/Notepattern/hasNotePitch "Submissions:Notepattern/hasNotePitch") 
 page_ 



[![ObjectProperty](public/images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__isPitchOf__ 
 (owl:ObjectProperty) Inverse of hasPitch. Connects a duration class to the symbolic note that have this specific pitch.
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[isPitchOf](../Submissions/Notepattern/isPitchOf "Submissions:Notepattern/isPitchOf") 
 page_ 



[![ObjectProperty](public/images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasAccidental__ 
 (owl:ObjectProperty) The accidental of a note (e.g. sharp).
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasAccidental](../Submissions/Notepattern/hasAccidental "Submissions:Notepattern/hasAccidental") 
 page_ 



[![ObjectProperty](public/images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__isAccidentalOf__ 
 (owl:ObjectProperty) Inverse of hasAccidental
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[isAccidentalOf](../Submissions/Notepattern/isAccidentalOf "Submissions:Notepattern/isAccidentalOf") 
 page_ 



[![ObjectProperty](public/images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasPosition__ 
 (owl:ObjectProperty) Connects the symbolic note with its duration
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasPosition](../Submissions/Notepattern/hasPosition "Submissions:Notepattern/hasPosition") 
 page_ 



[![ObjectProperty](public/images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__isPositionOf__ 
 (owl:ObjectProperty) Inverse of hasPosition
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[isPositionOf](../Submissions/Notepattern/isPositionOf "Submissions:Notepattern/isPositionOf") 
 page_ 


  





# 

 Additional information



# 

 Scenarios




__Scenarios about Notepattern__ 


 No scenario is added to this Content OP.
 




# 

 Reviews




__Reviews about Notepattern__ 


 There is no review about this proposal.
This revision (revision ID
 __14262__ 
 ) takes in account the reviews: none
 



 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Notepattern&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Notepattern&action=evaluation") 





# 

 Modeling issues




__Modeling issues about Notepattern__ 


 There is no Modeling issue related to this proposal.
 




# 

 References



  

 The Note Pattern models a music note both in relation to a music score and in relation to the musical object produced by playing such note.
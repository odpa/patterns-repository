# 

 Graphical representation



__Diagram__ 





[![Image:Musicalobject_pattern.png](./Musicalobject_pattern.png)](../Image/Musicalobject_pattern.png.md "Image:Musicalobject_pattern.png")





# 

 General description




|  |  |
| --- | --- |
|  Name:  |  musicalobject  |
|  Submitted by:  | [AndreaPoltronieri](../User/AndreaPoltronieri.md "User:AndreaPoltronieri")  |
|  Also Known As:  |  |
|  Intent:  |  This content ODP models the acoustic features of a music note played in a performance.  |
|  Domains:  | [Music](../Community/Music.md "Community:Music")  |
|  Competency Questions:  | <li>       what is the fundamental frequency of a musical object?      </li><li>       what are the different frequencies that make up the spectrum of a musical object?      </li><li>       what is the duration in seconds of a musical object      </li><li>       in a given performance?      </li><li>       how is the envelope of a musical object shaped?      </li> |
|  Solution description:  |  The pattern models the physical characteristics that can be extracted from the sound wave produced by an instrument playing a musical note. The MusicalObject class is connected to four classes that describe these physical characteristics, namely duration, sound intensity, frequency and envelope. The MusicObjectDuration class expresses the duration in seconds of the musical object, by means of the object property hasDurationInSeconds. In the same way, the musical intensity is modelled via the SoundIntensity class. Frequency is modelled by means of the class Frequency and its sub-classes FundamentalFrequency and PartialFrequency. For each expressed frequency, the magnitude of the frequency is also indicated using the hasFrequencyMagnitude object property. Finally, the Envelope class is connected to four object properties that describe the envelope of the waveform according to the ADSR model, namely hasAttack, hasSustain, hasDecay and hasRelease.  |
|  Reusable OWL Building Block:  | [https://purl.org/andreapoltronieri/musicalobject](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=https://purl.org/andreapoltronieri/musicalobject&message=OWL building block&from_page_id=4791&update=)  (0)  |
|  Consequences:  |  |
|  Scenarios:  |  |
|  Known Uses:  |  |
|  Web References:  |  |
|  Other References:  |  |
|  Examples (OWL files):  |  |
|  Extracted From:  |  |
|  Reengineered From:  |  |
|  Has Components:  |  |
|  Specialization Of:  |  |
|  Related CPs:  | <li><a class="new" href="http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Http://ontologydesignpatterns.org/wiki/Submissions:Notepattern&amp;action=edit&amp;redlink=1" title="Submissions:Http://ontologydesignpatterns.org/wiki/Submissions:Notepattern (not yet written)">        Submissions:http://ontologydesignpatterns.org/wiki/Submissions:Notepattern       </a></li><li><a class="new" href="http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Submissions:http://ontologydesignpatterns.org/wiki/Submissions:Scorepart&amp;action=edit&amp;redlink=1" title="Submissions:Submissions:http://ontologydesignpatterns.org/wiki/Submissions:Scorepart (not yet written)">        Submissions:Submissions:http://ontologydesignpatterns.org/wiki/Submissions:Scorepart       </a></li> |



  





# 

 Elements



_The
 __Musicalobject__ 
 Content OP locally defines the following ontology elements:_ 





[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__Envelope__ 
 (owl:Class) The envelope of a musical object's soundwave. In physics and engineering, the envelope of an oscillating signal is a smooth curve outlining its extremes.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[Envelope](./Musicalobject/Envelope.md "Submissions:Musicalobject/Envelope") 
 page_ 



[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__Frequency__ 
 (owl:Class) The frequency of a musical object.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[Frequency](./Musicalobject/Frequency.md "Submissions:Musicalobject/Frequency") 
 page_ 



[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__FundamentalFrequency__ 
 (owl:Class) The foundamental frequency of a musical object. The fundamental frequency is defined as the frequency of the lowest constituing partial of a signal.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[FundamentalFrequency](./Musicalobject/FundamentalFrequency.md "Submissions:Musicalobject/FundamentalFrequency") 
 page_ 



[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__PartialFrequency__ 
 (owl:Class) A frequency other than the foundamental Frequencyuency.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[PartialFrequency](./Musicalobject/PartialFrequency.md "Submissions:Musicalobject/PartialFrequency") 
 page_ 



[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__MusicalObject__ 
 (owl:Class) A musical object is the result of the realisation of a set of instructions that the musician or a computer system uses to realise a piece of music (e.g. music notation).
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[MusicalObject](./Musicalobject/MusicalObject.md "Submissions:Musicalobject/MusicalObject") 
 page_ 



[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__MusicalObjectDuration__ 
 (owl:Class) The duration of a musical object.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[MusicalObjectDuration](./Musicalobject/MusicalObjectDuration.md "Submissions:Musicalobject/MusicalObjectDuration") 
 page_ 



[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__SoundIntensity__ 
 (owl:Class) The intensity of the sound produced by a musical object.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[SoundIntensity](./Musicalobject/hasSoundIntensity.md "Submissions:Musicalobject/SoundIntensity") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__hasDuration__ 
 (owl:ObjectProperty) Connects a musical object to its duration.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[hasDuration](./An_Ontology_Design_Pattern_for_Activity_Reasoning/hasDuration.md "Submissions:Musicalobject/hasDuration") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__hasEnvelope__ 
 (owl:ObjectProperty) Connects a musical object to the envelope of the soundwave it produces.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[hasEnvelope](./Musicalobject/hasEnvelope.md "Submissions:Musicalobject/hasEnvelope") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__hasFrequency__ 
 (owl:ObjectProperty) Connects a musical object to the frequencies it produces.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[hasFrequency](./Musicalobject/hasFrequency.md "Submissions:Musicalobject/hasFrequency") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__hasSoundIntensity__ 
 (owl:ObjectProperty) Connects a musical object to the sound intensity produced.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[hasSoundIntensity](./Musicalobject/hasSoundIntensity.md "Submissions:Musicalobject/hasSoundIntensity") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__isDurationOf__ 
 (owl:ObjectProperty) Inverse of hasDuration. Connects the duration of a musical event to the musical event itself.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[isDurationOf](./Musicalobject/isDurationOf.md "Submissions:Musicalobject/isDurationOf") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__isEnvelopeOf__ 
 (owl:ObjectProperty) Inverse of hasEvelope. Connects the envelope of a musical event to the musical event itself.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[isEnvelopeOf](./Musicalobject/isEnvelopeOf.md "Submissions:Musicalobject/isEnvelopeOf") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__isFrequencyOf__ 
 (owl:ObjectProperty) Inverse of hasFrequency. Connects the frequency of a musical event to the musical event itself.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[isFrequencyOf](./Musicalobject/isFrequencyOf.md "Submissions:Musicalobject/isFrequencyOf") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__isSoundIntensityOf__ 
 (owl:ObjectProperty) Inverse of hasSoundIntensity. Connects the sound intensity of a musical event to the musical event itself.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[isSoundIntensityOf](./Musicalobject/isSoundIntensityOf.md "Submissions:Musicalobject/isSoundIntensityOf") 
 page_ 



[![DatatypeProperty](./20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif.md "DatatypeProperty")
__hasAttack__ 
 (owl:DatatypeProperty) Describes the attack time (expressed in seconds) of the soundwave's envelope, according to the ADSR model.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[hasAttack](./Musicalobject/hasAttack.md "Submissions:Musicalobject/hasAttack") 
 page_ 



[![DatatypeProperty](./20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif.md "DatatypeProperty")
__hasDecay__ 
 (owl:DatatypeProperty) Describes the decay time (epressed in seconds) of the soundwave's envelope, according to the ADSR model.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[hasDecay](./Musicalobject/hasDecay.md "Submissions:Musicalobject/hasDecay") 
 page_ 



[![DatatypeProperty](./20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif.md "DatatypeProperty")
__hasDurationInSeconds__ 
 (owl:DatatypeProperty) Expresses the duration in seconds of a musical object.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[hasDurationInSeconds](./Musicalobject/hasDurationInSeconds.md "Submissions:Musicalobject/hasDurationInSeconds") 
 page_ 



[![DatatypeProperty](./20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif.md "DatatypeProperty")
__hasFrequencyMagnitude__ 
 (owl:DatatypeProperty) The amplitude of a frequency component of a complex sound.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[hasFrequencyMagnitude](./Musicalobject/hasFrequencyMagnitude.md "Submissions:Musicalobject/hasFrequencyMagnitude") 
 page_ 



[![DatatypeProperty](./20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif.md "DatatypeProperty")
__hasIntensityValue__ 
 (owl:DatatypeProperty) The value of the sound intensity of a musical object.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[hasIntensityValue](./Musicalobject/hasIntensityValue.md "Submissions:Musicalobject/hasIntensityValue") 
 page_ 



[![DatatypeProperty](./20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif.md "DatatypeProperty")
__hasRelease__ 
 (owl:DatatypeProperty) Describes the release time (epressed in seconds) of the soundwave's envelope, according to the ADSR model.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[hasRelease](./Musicalobject/hasRelease.md "Submissions:Musicalobject/hasRelease") 
 page_ 



[![DatatypeProperty](./20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif.md "DatatypeProperty")
__hasSustain__ 
 (owl:DatatypeProperty) Describes the sustain time (epressed in seconds) of the soundwave's envelope, according to the ADSR model.
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[hasSustain](./Musicalobject/hasSustain.md "Submissions:Musicalobject/hasSustain") 
 page_ 


# 

 Additional information



# 

 Scenarios




__Scenarios about Musicalobject__ 


 No scenario is added to this Content OP.
 




# 

 Reviews




__Reviews about Musicalobject__ 


 There is no review about this proposal.
This revision (revision ID
 __14258__ 
 ) takes in account the reviews: none
 



 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Musicalobject&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Musicalobject&action=evaluation") 





  





# 

 Modeling issues




__Modeling issues about Musicalobject__ 


 There is no Modeling issue related to this proposal.
 




  





# 

 References
#  Graphical representation


__Diagram__




[![Image:HistoricalMap.jpg](./HistoricalMap.jpg)](../Image/HistoricalMap.jpg.md "Image:HistoricalMap.jpg")




#  General description




|  |  |
| --- | --- |
|  Name: |  HistoricalMap |
|  Submitted by: | [EleniGkadolou](../User/EleniGkadolou.md "User:EleniGkadolou") |
|  Also Known As: |  |
|  Intent: |  The ontology's intent is to describe a historical map and its attributes. |
|  Domains: | [Cartography](../Community/Cartography.md "Community:Cartography") |
|  Competency Questions: |  |
|  Solution description: |  Historical map's semantic documentation |
|  Reusable OWL Building Block: | [http://gaia.gge.unb.ca/eg/HistoricalMap.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=http://gaia.gge.unb.ca/eg/HistoricalMap.owl&message=OWL building block&from_page_id=3477&update=) (759) |
|  Consequences: |  |
|  Scenarios: |  |
|  Known Uses: |  |
|  Web References: |  |
|  Other References: |  |
|  Examples (OWL files): |  |
|  Extracted From: |  |
|  Reengineered From: |  |
|  Has Components: |  |
|  Specialization Of: |  |
|  Related CPs: |  |


  




#  Elements


_The __HistoricalMap__ Content OP locally defines the following ontology elements:_



[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __PrimeMeridian__ (owl:Class) The first lline of longitude from which the longitute is calculated. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[PrimeMeridian](./HistoricalMap/hasPrimeMeridian.md "Submissions:HistoricalMap/PrimeMeridian") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __MapMathematicalElement__ (owl:Class) The mathematical parameters for creating a map. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[MapMathematicalElement](./HistoricalMap/MapMathematicalElement.md "Submissions:HistoricalMap/MapMathematicalElement") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __Scale__ (owl:Class) The mathematical ratio that gives the size of something in the earth surface and the size of it in the map. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[Scale](./HistoricalMap/hasScale.md "Submissions:HistoricalMap/Scale") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __ReferenceSystem__ (owl:Class) The system of axes that uses coordinates to establish position 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[ReferenceSystem](./HistoricalMap/hasReferenceSystem.md "Submissions:HistoricalMap/ReferenceSystem") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __Projection__ (owl:Class) The mathematical process for representing earth in the plane. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[Projection](./HistoricalMap/hasProjection.md "Submissions:HistoricalMap/Projection") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __Orientation__ (owl:Class) The position of the map in relation to the North (True, Magnetic, Grid North). 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[Orientation](./HistoricalMap/hasOrientation.md "Submissions:HistoricalMap/Orientation") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __MathematicalNote__ (owl:Class) Any note written on the map concerning mathematical information. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[MathematicalNote](./HistoricalMap/hasMathematicalNote.md "Submissions:HistoricalMap/MathematicalNote") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __Collection__ (owl:Class) Several things (historical maps) grouped together or considered as a whole (Wordnet). 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[Collection](../Collection/Collection.md "Submissions:HistoricalMap/Collection") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __HistoricalMap__ (owl:Class) A diagrammatic representation of the earth's surface (or part of it) belonging to the past (Wordnet). 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[HistoricalMap](./HistoricalMap.md "Submissions:HistoricalMap/HistoricalMap") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __includes__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[includes](./Experience_&_Observation/includes.md "Submissions:HistoricalMap/includes") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasCurrentOwner__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasCurrentOwner](./HistoricalMap/hasCurrentOwner.md "Submissions:HistoricalMap/hasCurrentOwner") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __Collector__ (owl:Class) A person or organisation that owns 1 or more historical maps. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[Collector](./HistoricalMap/Collector.md "Submissions:HistoricalMap/Collector") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __Actor__ (owl:Class) A person who acts and gets things done (Wordnet). 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[Actor](./HistoricalMap/Actor.md "Submissions:HistoricalMap/Actor") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __MapElement__ (owl:Class) A characteristic of map. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[MapElement](./HistoricalMap/MapElement.md "Submissions:HistoricalMap/MapElement") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __Title__ (owl:Class) The heading of the map.There may be more than one titles (sub-titles). 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[Title](./HistoricalMap/hasTitle.md "Submissions:HistoricalMap/Title") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __Technique__ (owl:Class) The process by which the map was created or published. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[Technique](./HistoricalMap/Technique.md "Submissions:HistoricalMap/Technique") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __Subject__ (owl:Class) The theme of the map e.g. the establishment of new national borders 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[Subject](./HistoricalMap/hasSubject.md "Submissions:HistoricalMap/Subject") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __SpatialCoverage__ (owl:Class) The spatial extend of the geographic area that is depicted in the map. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[SpatialCoverage](./HistoricalMap/SpatialCoverage.md "Submissions:HistoricalMap/SpatialCoverage") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __Language__ (owl:Class) The language(s) used for the literals in the map. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[Language](./HistoricalMap/hasLanguage.md "Submissions:HistoricalMap/Language") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __Dimension__ (owl:Class) The dimensions of the map, length and width. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[Dimension](./HistoricalMap/Dimension.md "Submissions:HistoricalMap/Dimension") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __Note__ (owl:Class) Any note (except mathematical) that is written on the map. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[Note](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/hasScopeNote.md "Submissions:HistoricalMap/Note") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __Material__ (owl:Class) The material of which the map is published. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[Material](./HistoricalMap/Material.md "Submissions:HistoricalMap/Material") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __MapDescriptiveElement__ (owl:Class) All the metadata that are used for describing a map and for its cataloguing. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[MapDescriptiveElement](./HistoricalMap/MapDescriptiveElement.md "Submissions:HistoricalMap/MapDescriptiveElement") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __SpatialObject__ (owl:Class) The class spatial-object represents everything that can have a spatial representation. It is superclass of feature and geometry (Geosparql). 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[SpatialObject](./HistoricalMap/SpatialObject.md "Submissions:HistoricalMap/SpatialObject") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __Creator__ (owl:Class) The person who created the map. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[Creator](./Born_Digital_Archives/Creator.md "Submissions:HistoricalMap/Creator") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __created__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[created](./HistoricalMap/created.md "Submissions:HistoricalMap/created") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __Cartographer__ (owl:Class) A person who makes maps. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[Cartographer](./HistoricalMap/Cartographer.md "Submissions:HistoricalMap/Cartographer") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __Publisher__ (owl:Class) The person responsible for the publication of the map. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[Publisher](./HistoricalMap/Publisher.md "Submissions:HistoricalMap/Publisher") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __designed__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[designed](./HistoricalMap/designed.md "Submissions:HistoricalMap/designed") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __published__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[published](./HistoricalMap/published.md "Submissions:HistoricalMap/published") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isPublishedBy__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isPublishedBy](./HistoricalMap/isPublishedBy.md "Submissions:HistoricalMap/isPublishedBy") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasOrientation__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasOrientation](./HistoricalMap/hasOrientation.md "Submissions:HistoricalMap/hasOrientation") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasLanguage__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasLanguage](./HistoricalMap/hasLanguage.md "Submissions:HistoricalMap/hasLanguage") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasProjection__ (owl:FunctionalProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasProjection](./HistoricalMap/hasProjection.md "Submissions:HistoricalMap/hasProjection") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isCreatedBy__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isCreatedBy](./HistoricalMap/isCreatedBy.md "Submissions:HistoricalMap/isCreatedBy") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasTitle__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasTitle](./HistoricalMap/hasTitle.md "Submissions:HistoricalMap/hasTitle") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasReferenceSystem__ (owl:FunctionalProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasReferenceSystem](./HistoricalMap/hasReferenceSystem.md "Submissions:HistoricalMap/hasReferenceSystem") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasSubject__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasSubject](./HistoricalMap/hasSubject.md "Submissions:HistoricalMap/hasSubject") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isMadeBy__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isMadeBy](./HistoricalMap/isMadeBy.md "Submissions:HistoricalMap/isMadeBy") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isPartOf__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isPartOf](./An_Ontology_Design_Pattern_for_Activity_Reasoning/isPartOf.md "Submissions:HistoricalMap/isPartOf") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasScale__ (owl:FunctionalProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasScale](./HistoricalMap/hasScale.md "Submissions:HistoricalMap/hasScale") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasNote__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasNote](./HistoricalMap/hasNote.md "Submissions:HistoricalMap/hasNote") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasDimension__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasDimension](./HistoricalMap/hasDimension.md "Submissions:HistoricalMap/hasDimension") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasMathematicalNote__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasMathematicalNote](./HistoricalMap/hasMathematicalNote.md "Submissions:HistoricalMap/hasMathematicalNote") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasPrimeMeridian__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasPrimeMeridian](./HistoricalMap/hasPrimeMeridian.md "Submissions:HistoricalMap/hasPrimeMeridian") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isDesignedBy__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isDesignedBy](./HistoricalMap/isDesignedBy.md "Submissions:HistoricalMap/isDesignedBy") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isMadeOf__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isMadeOf](./HistoricalMap/isMadeOf.md "Submissions:HistoricalMap/isMadeOf") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isCurrentOwnerOf__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isCurrentOwnerOf](./HistoricalMap/isCurrentOwnerOf.md "Submissions:HistoricalMap/isCurrentOwnerOf") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasDateOfPublication__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasDateOfPublication](./HistoricalMap/hasDateOfPublication.md "Submissions:HistoricalMap/hasDateOfPublication") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __MyProperties__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[MyProperties](./HistoricalMap/MyProperties.md "Submissions:HistoricalMap/MyProperties") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isPublishedAt__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isPublishedAt](./HistoricalMap/isPublishedAt.md "Submissions:HistoricalMap/isPublishedAt") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isMathematicalNoteOf__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isMathematicalNoteOf](./HistoricalMap/isMathematicalNoteOf.md "Submissions:HistoricalMap/isMathematicalNoteOf") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isEditedBy__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isEditedBy](./HistoricalMap/isEditedBy.md "Submissions:HistoricalMap/isEditedBy") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __edited__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[edited](./HistoricalMap/edited.md "Submissions:HistoricalMap/edited") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isLanguageOf__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isLanguageOf](./HistoricalMap/isLanguageOf.md "Submissions:HistoricalMap/isLanguageOf") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isOrientationOf__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isOrientationOf](./HistoricalMap/isOrientationOf.md "Submissions:HistoricalMap/isOrientationOf") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasDateOfEdition__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasDateOfEdition](./HistoricalMap/hasDateOfEdition.md "Submissions:HistoricalMap/hasDateOfEdition") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isDepictedIn__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isDepictedIn](./HistoricalMap/isDepictedIn.md "Submissions:HistoricalMap/isDepictedIn") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __depicts__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[depicts](./HistoricalMap/depicts.md "Submissions:HistoricalMap/depicts") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasPlaceOfPublication__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasPlaceOfPublication](./HistoricalMap/hasPlaceOfPublication.md "Submissions:HistoricalMap/hasPlaceOfPublication") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasDateOfCreation__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasDateOfCreation](./HistoricalMap/hasDateOfCreation.md "Submissions:HistoricalMap/hasDateOfCreation") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasColor__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasColor](./HistoricalMap/hasColor.md "Submissions:HistoricalMap/hasColor") page_
[![DatatypeProperty](./20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif.md "DatatypeProperty") __type__ (owl:DatatypeProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[type](../Class_by_attribute_type/Class_by_attribute_type.md "Submissions:HistoricalMap/type") page_
[![DatatypeProperty](./20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif.md "DatatypeProperty") __copy__ (owl:DatatypeProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[copy](./HistoricalMap/copy.md "Submissions:HistoricalMap/copy") page_
[![DatatypeProperty](./20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif.md "DatatypeProperty") __numberOfSheets__ (owl:DatatypeProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[numberOfSheets](./HistoricalMap/numberOfSheets.md "Submissions:HistoricalMap/numberOfSheets") page_
[![DatatypeProperty](./20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif.md "DatatypeProperty") __date__ (owl:DatatypeProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[date](./HistoricalMap/date.md "Submissions:HistoricalMap/date") page_
#  Additional information


#  Scenarios



__Scenarios about HistoricalMap__
No scenario is added to this Content OP.




#  Reviews



__Reviews about HistoricalMap__
There is no review about this proposal.
This revision (revision ID __11533__) takes in account the reviews: none


Other info at [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:HistoricalMap&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:HistoricalMap&action=evaluation")




  




#  Modeling issues



__Modeling issues about HistoricalMap__
There is no Modeling issue related to this proposal.




  




#  References
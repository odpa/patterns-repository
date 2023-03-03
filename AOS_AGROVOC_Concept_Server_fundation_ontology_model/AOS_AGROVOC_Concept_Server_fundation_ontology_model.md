#  Graphical representation


__Diagram__
_(this article has no graphical representation)_



#  General description




|  |  |
| --- | --- |
|  Name: |  AOS AGROVOC Concept Server foundation ontology model |
|  Submitted by: | [MargheritaSini](../User/MargheritaSini.md "User:MargheritaSini") |
|  Also Known As: |  AGROVOC Concept Server OWL Model, ASC, AOS |
|  Intent: |  Act as a basic model for Agricultural Related Ontologies, in particular for the AGROVOC Concept Server. The model clearly identify concepts (domain concepts) from terms (which are represented as instances). Both concepts and terms have specific relationships connecting them. |
|  Domains: | [Agriculture](../Community/Agriculture.md "Community:Agriculture") |
|  Competency Questions: | <li> What is the structure i should use if i want to distinguish between domain concepts and their terminology?</li> |
|  Solution description: |  - |
|  Reusable OWL Building Block: | [http://www.fao.org/aims/aos/aos.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=http://www.fao.org/aims/aos/aos.owl&message=OWL building block&from_page_id=1251&update=) (1012) |
|  Consequences: |  This model can be compared to the LIR model. A mapping between the two model exists. Therefore, using the AOS will make your ontology compatible with the LIR and therefore the NeOn Toolkit. |
|  Scenarios: |  |
|  Known Uses: |  |
|  Web References: |  |
|  Other References: |  |
|  Examples (OWL files): |  |
|  Extracted From: |  |
|  Reengineered From: | <li> AGROVOC Thesaurus</li> |
|  Has Components: |  |
|  Specialization Of: |  |
|  Related CPs: | <li><a href="../HasPest/HasPest.md" title="Submissions:HasPest">Submissions:HasPest</a></li> |


  




#  Elements


_The __AOS AGROVOC Concept Server fundation ontology model__ Content OP locally defines the following ontology elements:_



[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __c\_geographic\_concept\_above\_country\_level__ (owl:Class) This concept is used to group all geographical regions encompassing one or more countries (e.g. Central Africa includes many countries). See also: [http://en.wikipedia.org/wiki/Central\_Africa](http://en.wikipedia.org/wiki/Central_Africa "http://en.wikipedia.org/wiki/Central_Africa")
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[c\_geographic\_concept\_above\_country\_level](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/c_geographic_concept_above_country_level.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/c geographic concept above country level") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __c\_geographic\_concept__ (owl:Class) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[c\_geographic\_concept](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/c_geographic_concept.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/c geographic concept") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __c\_geographic\_concept\_below\_country\_level__ (owl:Class) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[c\_geographic\_concept\_below\_country\_level](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/c_geographic_concept_below_country_level.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/c geographic concept below country level") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __c\_taxonomic\_term\_animals__ (owl:Class) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[c\_taxonomic\_term\_animals](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/c_taxonomic_term_animals.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/c taxonomic term animals") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __c\_taxonomic\_term__ (owl:Class) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[c\_taxonomic\_term](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/c_taxonomic_term.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/c taxonomic term") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __c\_geographic\_concept\_country\_level__ (owl:Class) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[c\_geographic\_concept\_country\_level](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/c_geographic_concept_country_level.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/c geographic concept country level") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __c\_domain\_concept__ (owl:Class) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[c\_domain\_concept](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/c_domain_concept.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/c domain concept") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __c\_category__ (owl:Class) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[c\_category](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/c_category.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/c category") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __c\_scientific\_term__ (owl:Class) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[c\_scientific\_term](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/c_scientific_term.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/c scientific term") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __c\_noun__ (owl:Class) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[c\_noun](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/c_noun.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/c noun") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __c\_taxonomic\_term\_viruses__ (owl:Class) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[c\_taxonomic\_term\_viruses](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/c_taxonomic_term_viruses.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/c taxonomic term viruses") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __c\_definition__ (owl:Class) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[c\_definition](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/c_definition.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/c definition") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __c\_entity\_annotation__ (owl:Class) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[c\_entity\_annotation](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/c_entity_annotation.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/c entity annotation") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __c\_taxonomic\_term\_bacteria__ (owl:Class) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[c\_taxonomic\_term\_bacteria](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/c_taxonomic_term_bacteria.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/c taxonomic term bacteria") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __c\_lexicalization__ (owl:Class) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[c\_lexicalization](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/c_lexicalization.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/c lexicalization") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __c\_image__ (owl:Class) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[c\_image](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/c_image.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/c image") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __c\_taxonomic\_term\_fungi__ (owl:Class) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[c\_taxonomic\_term\_fungi](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/c_taxonomic_term_fungi.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/c taxonomic term fungi") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __c\_chemical\_term__ (owl:Class) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[c\_chemical\_term](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/c_chemical_term.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/c chemical term") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __c\_taxonomic\_term\_plant__ (owl:Class) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[c\_taxonomic\_term\_plant](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/c_taxonomic_term_plant.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/c taxonomic term plant") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __c\_chemical\_concept__ (owl:Class) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[c\_chemical\_concept](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/c_chemical_concept.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/c chemical concept") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __c\_classification\_scheme__ (owl:Class) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[c\_classification\_scheme](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/c_classification_scheme.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/c classification scheme") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isUsedToMake__ (owl:ObjectProperty) Y <is used to make> X. A substance or a product Y from which a product X can be mainly (in terms of importance) obtained. E.g. "cow milk" <is used to make> "cheddar cheese"; "hops" <is used to make> "beer" (see <composed\_of>); 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isUsedToMake](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/isUsedToMake.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/isUsedToMake") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __essiveRelationship__ (owl:SymmetricProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[essiveRelationship](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/essiveRelationship.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/essiveRelationship") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isMadeFrom__ (owl:TransitiveProperty) X <isMadeFrom> Y. A product X obtained mainly (in terms of importance) from a substance or a product Y. E.g. "cheddar cheese" <isMadeFrom> "cow milk"; "beer" <isMadeFrom> "hops" (see <composedOf>); 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isMadeFrom](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/isMadeFrom.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/isMadeFrom") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __domainSpecificRelationship__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[domainSpecificRelationship](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/domainSpecificRelationship.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/domainSpecificRelationship") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __objectProperty__ (owl:ObjectProperty) Root Property for all object properties. Introduced in order to make querying and organization of properties easier. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[objectProperty](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/objectProperty.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/objectProperty") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasRelatedType__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasRelatedType](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/hasRelatedType.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/hasRelatedType") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isRelatedTypeOf__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isRelatedTypeOf](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/isRelatedTypeOf.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/isRelatedTypeOf") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasRelatedConcept__ (owl:SymmetricProperty) The most generic relationship to relate two domain concepts. This is used if two concepts are related and none of the more speciifc relationships can be applied. It is also used for backward compatibility to thesauri, i.e. all the more specific relationships can be resolved to this relationship and will translate to the <related term> or RT thesaurus relationship. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasRelatedConcept](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/hasRelatedConcept.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/hasRelatedConcept") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasTransliteration__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasTransliteration](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/hasTransliteration.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/hasTransliteration") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasRelatedTerm__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasRelatedTerm](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/hasRelatedTerm.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/hasRelatedTerm") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isAGrowthEnvironmentFor__ (owl:ObjectProperty) Y <is a growth environment for> X. An environment Y favorable to a taxon X. This is used as the inverse relationship of <grows in>. Use this in a plant and related domain (e.g. fungi). E.g. "isarn region" <is a growth environment for> "jasmine rice"; "moist soil" <is a growth environment for> "rice"; 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isAGrowthEnvironmentFor](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/isAGrowthEnvironmentFor.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/isAGrowthEnvironmentFor") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __growsIn__ (owl:ObjectProperty) X <grows in> Y. A taxon X grows in an environment Y. Use this in a plant and related domain (e.g. fungi). E.g. "jasmine rice" <grows in> "isarn region"; "rice" <grows in> "moist soil"; 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[growsIn](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/growsIn.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/growsIn") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __instrumentalRelationship__ (owl:SymmetricProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[instrumentalRelationship](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/instrumentalRelationship.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/instrumentalRelationship") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isAchievedByMeansOf__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isAchievedByMeansOf](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/isAchievedByMeansOf.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/isAchievedByMeansOf") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasGoalOrProcess__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasGoalOrProcess](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/hasGoalOrProcess.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/hasGoalOrProcess") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isMeansFor__ (owl:ObjectProperty) X <isMeans for> Y. An object or process X mainly used to perform a process Y. See also <used as>. E.g. "curry paste grinding" <performed\_with\_instrument> "curry paste grinding machine"; "weapon" <is means for> "killing"; "fishing pole" <is means for> "fishing"; "alcohol" <is means for> "cleaning"; Ploughs <is means for> Ploughing ;but NOT "knives" <is means for> "felling" (because knives are not primarily used for cutting down trees); 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isMeansFor](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/isMeansFor.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/isMeansFor") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isPerformedByMeansOf__ (owl:ObjectProperty) Y <is performed by means of> X. An object or process X mainly used to perform a process Y. See also <used\_as>. E.g. "curry paste grinding" <is performed by means of> "curry paste grinding machine"; "killing" <is performed by means of> "weapon"; "fishing" <is performed by means of> "fishing pole"; "cleaning" <is performed by means of> "alcohol"; but NOT "knives" <means\_for> "felling" (because knives are not primarily used for cutting down trees); 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isPerformedByMeansOf](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/isPerformedByMeansOf.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/isPerformedByMeansOf") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isReferencedInAnnotationOf__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isReferencedInAnnotationOf](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/isReferencedInAnnotationOf.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/isReferencedInAnnotationOf") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __annotationRefersTo__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[annotationRefersTo](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/annotationRefersTo.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/annotationRefersTo") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isMemberOf__ (owl:ObjectProperty) X <is member of> Y. A social or political unit (group or individual) X; 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isMemberOf](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/isMemberOf.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/isMemberOf") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __partitiveRelationship__ (owl:SymmetricProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[partitiveRelationship](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/partitiveRelationship.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/partitiveRelationship") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasMember__ (owl:ObjectProperty) Y <has member> X. A social or political groupe Y in which a social or political unit (group or individual) X 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasMember](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/hasMember.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/hasMember") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasImage__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasImage](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/hasImage.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/hasImage") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isImageOf__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isImageOf](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/isImageOf.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/isImageOf") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isControlledBy__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isControlledBy](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/isControlledBy.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/isControlledBy") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __causativeRelationship__ (owl:SymmetricProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[causativeRelationship](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/causativeRelationship.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/causativeRelationship") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __controls__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[controls](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/controls.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/controls") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isProcessFor__ (owl:ObjectProperty) X <is process for> Y. One or more actions, activities, methods X that produce a change or development Y. E.g.: "sterilization" <is process for> "fruit cleaning"; 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isProcessFor](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/isProcessFor.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/isProcessFor") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __usesProcess__ (owl:ObjectProperty) Y <uses process> X. One or more actions, activities, methods X that produce a change or development Y. E.g.: "fruit cleaning" <uses process> "sterilization"; 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[usesProcess](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/usesProcess.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/usesProcess") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasAbbreviation__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasAbbreviation](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/hasAbbreviation.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/hasAbbreviation") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isAbbreviationOf__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isAbbreviationOf](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/isAbbreviationOf.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/isAbbreviationOf") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __precedes__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[precedes](./An_Ontology_Design_Pattern_for_Activity_Reasoning/precedes.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/precedes") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __temporalRelationship__ (owl:SymmetricProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[temporalRelationship](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/temporalRelationship.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/temporalRelationship") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __follows__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[follows](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/follows.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/follows") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __developsInto__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[developsInto](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/developsInto.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/developsInto") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __developsFrom__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[developsFrom](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/developsFrom.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/developsFrom") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __performs__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[performs](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/performs.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/performs") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isPerformedBy__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isPerformedBy](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/isPerformedBy.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/isPerformedBy") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __use__ (owl:ObjectProperty) relationship to keep track of the thesaurus UF+ (used for +) relationships 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[use](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/use.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/use") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __usedForPlus__ (owl:ObjectProperty) relationship to import the thesaurus UF+ (used for +) relationships 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[usedForPlus](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/usedForPlus.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/usedForPlus") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __thesaurusRelationship__ (owl:ObjectProperty) for backward compatibility to thesauri 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[thesaurusRelationship](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/thesaurusRelationship.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/thesaurusRelationship") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __prevents__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[prevents](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/prevents.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/prevents") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isPreventedBy__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isPreventedBy](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/isPreventedBy.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/isPreventedBy") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasBroaderSynonym__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasBroaderSynonym](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/hasBroaderSynonym.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/hasBroaderSynonym") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasNarrowerSynonym__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasNarrowerSynonym](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/hasNarrowerSynonym.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/hasNarrowerSynonym") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasSynonym__ (owl:SymmetricProperty) X <has synonym> Y. A word X that means the same or nearly the same as another word Y. E.g. "bucket" <has synonym> "pail"; "pail" <has synonym> "bucket"; 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasSynonym](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/hasSynonym.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/hasSynonym") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasSymptom__ (owl:ObjectProperty) X <has symptom> Y. A disease X presents disease characteristic Y in an organism. E.g. "BSE" <has symptom> "anorexia"; 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasSymptom](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/hasSymptom.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/hasSymptom") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __indicates__ (owl:ObjectProperty) Y <indicates> X. A disease characteristic Y in an organism indicates disease X. E.g. "anorexia" <indicates> "BSE"; 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[indicates](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/indicates.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/indicates") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isUseOf__ (owl:ObjectProperty) Y <is use of> X. {Use} Y <is\_use\_of> {Taxon} X. Use this in a plant domain. - {use} Y <is\_use\_of> {chemical substance} X. Use this for chemical substance. E.g.: "fruit" <is use of> "apple"; "cleaner" <is use of> "alcohol"; "pesticide" <is use of> "ddt"; 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isUseOf](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/isUseOf.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/isUseOf") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isUsedAs__ (owl:ObjectProperty) X <is used as> Y. {Taxon} X <is used as> {use} Y. Use this in a plant domain. - {chemical substance} X <is used as> {use} Y. Use this for chemical substance. E.g.: "apple" <is used as> "fruit"; "alcohol" <is used as> "cleaner"; "ddt" <is used as> "pesticide"; 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isUsedAs](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/isUsedAs.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/isUsedAs") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __afflicts__ (owl:ObjectProperty) X <afflicts> Y. The disease X could adversely affect the health of an organism Y. E.g. "BSE" <afflicts> "cows"; 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[afflicts](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/afflicts.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/afflicts") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isAfflictedBy__ (owl:ObjectProperty) Y <is afflicted by> X. The health of an organism Y could adversely be affected by the disease X. E.g. "cows" <is afflicted by> "BSE"; 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isAfflictedBy](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/isAfflictedBy.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/isAfflictedBy") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __affects__ (owl:ObjectProperty) X <affects> Y. Agent X acts on object Y in such a way that Y changes state or location. E.g. "sterilization" <affects> "bacteria"; "pest control" <affects> "pest"; "pollution of agriculture" <affects> "agriculture"; 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[affects](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/affects.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/affects") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __belongsToScheme__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[belongsToScheme](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/belongsToScheme.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/belongsToScheme") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasCategory__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasCategory](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/hasCategory.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/hasCategory") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasPest__ (owl:ObjectProperty) Y <has pest> X. An organism Y in which the organism X causes harm. E.g. "Litchi chinensis" <has pest> "Bactrocera dorsalis"; 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasPest](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/hasPest.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/hasPest") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isPestOf__ (owl:ObjectProperty) X <is pest of> Y. An organism X causes harm to organism Y. E.g. "Bactrocera dorsalis" <is pest of> "Litchi chinensis"; 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isPestOf](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/isPestOf.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/isPestOf") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isOutputFrom__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isOutputFrom](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/isOutputFrom.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/isOutputFrom") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isInputFor__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isInputFor](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/isInputFor.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/isInputFor") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __cropWildRelativeRelationship__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[cropWildRelativeRelationship](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/cropWildRelativeRelationship.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/cropWildRelativeRelationship") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasAuthor__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasAuthor](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/hasAuthor.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/hasAuthor") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isAuthorOf__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isAuthorOf](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/isAuthorOf.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/isAuthorOf") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isScientificNameOf__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isScientificNameOf](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/isScientificNameOf.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/isScientificNameOf") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasScientificName__ (owl:ObjectProperty) use this relationship to link a scientific name (taxonomic term, chemical term, etc.) to its common name. The scientific name and the common name usually describe the same concept 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasScientificName](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/hasScientificName.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/hasScientificName") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isCausedBy__ (owl:ObjectProperty) Y <is caused by> X. A result Y occurred because of an agent X (animate or inanimate). E.g.: "BSE" <is caused by> "prions"; "water erosion" <is caused by> "water"; 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isCausedBy](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/isCausedBy.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/isCausedBy") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __causes__ (owl:ObjectProperty) X <causes> Y. Agent X (animate or inanimate) brings about a result Y. Examples: "prions" <causes> "BSE"; "water" <causes> "water erosion"; 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[causes](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/causes.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/causes") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isBeneficialFor__ (owl:ObjectProperty) X <is beneficial for> Y. Agent X behaves in a way that produces some result Y that is advantageous to some beneficiary. A means X through which a consequence Y can be achieved. E.g. "biological control arthropods" <is beneficial for> "biological control"; "pest control" <is beneficial for> "plant health"; 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isBeneficialFor](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/isBeneficialFor.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/isBeneficialFor") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __benefitsFrom__ (owl:ObjectProperty) Y <benefits from> X. A result Y that is advantageous to some beneficiary, produced by the behaviour of an agent X. A consequence Y achieved through a means X. E.g. "biological control" <benefits from> "biological control arthropods"; "plant health" <benefits from> "pest control"; 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[benefitsFrom](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/benefitsFrom.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/benefitsFrom") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasTheme__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasTheme](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/hasTheme.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/hasTheme") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isThemeOf__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isThemeOf](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/isThemeOf.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/isThemeOf") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isSourceOf__ (owl:ObjectProperty) Y <is source of> X. A source Y from which a substance or product X can be exclusively obtained, without any additional substance or product. E.g. "cow" <is source of> "cow milk"; "plant" <is source of> "plant oil"; "olive tree" <is source of> "olive wood"; "chicken" <is source of> "chicken meat"; but NOT "hops" <is source of> "beer" (see <used\_to\_make>); 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isSourceOf](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/isSourceOf.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/isSourceOf") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isDerivedFrom__ (owl:ObjectProperty) X <is derived from> Y. A substance or product X obtained exclusively from source Y without any additional substance or product. E.g. "cow milk" <is derived from> "cow"; "plant oil" <is derived from> "plant"; "olive wood" <is derived from> "olive tree"; "chicken meat" <is derived from> "chicken"; but NOT "beer" <is derived from> "hops" (see <made\_from>); 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isDerivedFrom](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/isDerivedFrom.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/isDerivedFrom") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasAcronym__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasAcronym](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/hasAcronym.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/hasAcronym") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isAcronymOf__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isAcronymOf](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/isAcronymOf.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/isAcronymOf") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isPropertyOf__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isPropertyOf](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/isPropertyOf.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/isPropertyOf") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasProperty__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasProperty](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/hasProperty.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/hasProperty") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasMappedDomainConcept__ (owl:ObjectProperty) to map domain concepts to any category in a classification scheme 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasMappedDomainConcept](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/hasMappedDomainConcept.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/hasMappedDomainConcept") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __belongsToCategory__ (owl:ObjectProperty) to map any domain concept to any category of any classification scheme 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[belongsToCategory](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/belongsToCategory.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/belongsToCategory") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isProducedBy__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isProducedBy](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/isProducedBy.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/isProducedBy") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __produces__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[produces](./An_Ontology_Design_Pattern_for_Activity_Reasoning/produces.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/produces") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isAffectedBy__ (owl:ObjectProperty) Y <is affected by> X. An object Y changes state or location because of an action of an agent X. E.g. "bacteria" <is affected by> "sterilization"; "pest" <is affected by> "pest control"; "agriculture" <is affected by> "pollution of agriculture"; 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isAffectedBy](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/isAffectedBy.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/isAffectedBy") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __portion__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[portion](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/portion.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/portion") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __portionOf__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[portionOf](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/portionOf.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/portionOf") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasDefinition__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasDefinition](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/hasDefinition.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/hasDefinition") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isDefinitionOf__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isDefinitionOf](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/isDefinitionOf.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/isDefinitionOf") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasObjectOfActivity__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasObjectOfActivity](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/hasObjectOfActivity.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/hasObjectOfActivity") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isObjectOfActivity__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isObjectOfActivity](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/isObjectOfActivity.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/isObjectOfActivity") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isActedUponBy__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isActedUponBy](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/isActedUponBy.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/isActedUponBy") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __actsUpon__ (owl:ObjectProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[actsUpon](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/actsUpon.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/actsUpon") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isSubprocessOf__ (owl:ObjectProperty) Y <is subprocess of> X. Y is one of one or more processes naturally or conventionally associated with the realization of process X. E.g. "pasteurization" <is subprocess of> "milk production"; 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isSubprocessOf](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/isSubprocessOf.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/isSubprocessOf") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __includesSubprocess__ (owl:TransitiveProperty) X <includes subprocess> Y. Process X naturally or conventionally realized at the minimum through process Y. Equivalent to <includes subprocess>. E.g. "milk production" <includes subprocess> "pasteurization"; 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[includesSubprocess](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/includesSubprocess.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/includesSubprocess") page_
[![DatatypeProperty](./20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif.md "DatatypeProperty") __hasTermVariant__ (owl:DatatypeProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasTermVariant](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/hasTermVariant.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/hasTermVariant") page_
[![DatatypeProperty](./20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif.md "DatatypeProperty") __datatypeProperty__ (owl:DatatypeProperty) Root Property for all datatype properties. Introduced in order to make querying and organization of properties easier. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[datatypeProperty](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/datatypeProperty.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/datatypeProperty") page_
[![DatatypeProperty](./20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif.md "DatatypeProperty") __hasChemicalFormula__ (owl:DatatypeProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasChemicalFormula](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/hasChemicalFormula.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/hasChemicalFormula") page_
[![DatatypeProperty](./20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif.md "DatatypeProperty") __hasScopeNote__ (owl:DatatypeProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasScopeNote](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/hasScopeNote.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/hasScopeNote") page_
[![DatatypeProperty](./20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif.md "DatatypeProperty") __hasStemmedForm__ (owl:DatatypeProperty) This relationship is used to enter the stemmed form of term. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasStemmedForm](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/hasStemmedForm.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/hasStemmedForm") page_
[![DatatypeProperty](./20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif.md "DatatypeProperty") __hasPlural__ (owl:DatatypeProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasPlural](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/hasPlural.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/hasPlural") page_
[![DatatypeProperty](./20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif.md "DatatypeProperty") __hasImageDescription__ (owl:DatatypeProperty) To provide a description of what can be seen on the image 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasImageDescription](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/hasImageDescription.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/hasImageDescription") page_
[![DatatypeProperty](./20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif.md "DatatypeProperty") __hasSpellingVariant__ (owl:DatatypeProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasSpellingVariant](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/hasSpellingVariant.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/hasSpellingVariant") page_
[![DatatypeProperty](./20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif.md "DatatypeProperty") __hasImageName__ (owl:DatatypeProperty) Each image should be assigned a name. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasImageName](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/hasImageName.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/hasImageName") page_
[![DatatypeProperty](./20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif.md "DatatypeProperty") __hasChangeHistory__ (owl:DatatypeProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasChangeHistory](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/hasChangeHistory.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/hasChangeHistory") page_
[![DatatypeProperty](./20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif.md "DatatypeProperty") __hasCode__ (owl:DatatypeProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasCode](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/hasCode.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/hasCode") page_
[![DatatypeProperty](./20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif.md "DatatypeProperty") __hasSingular__ (owl:DatatypeProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasSingular](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/hasSingular.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/hasSingular") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasComponent__ (owl:TransitiveProperty) Y <has component> X. An object X that is a part of a whole Y and has also an existence independently from Y. E.g. "engine" <has component> "engine part"; "tree" <has component> "leaf"; "cell" <has component> "chromosome"; but NOT "blood" <has component> "blood cell" (see <is composed of>); 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasComponent](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/hasComponent.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/hasComponent") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isComponentOf__ (owl:TransitiveProperty) X <is component of> Y. An object X that is a part of a whole Y and has also an existence independently from Y. E.g. "engine part" <is component of> "engine"; "leaf" <is component of> "tree"; "chromosome" <is component of> "cell"; but NOT "blood cell" <is component of> "blood" (see <composes>); 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isComponentOf](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/isComponentOf.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/isComponentOf") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasPart__ (owl:TransitiveProperty) X <has part> Y. A composite entity X that can be identified as composed by one or more parts, between which Y. Use this relationship when none of the other partitivity relations (<component>, <composed\_of>, <portion>, <member>, <includes\_subprocess>) apply. E.g. in a plant ontology: {Taxonomic} <has part> {PartPlant}; 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasPart](./An_Ontology_Design_Pattern_for_Activity_Reasoning/hasPart.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/hasPart") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __spatiallyIncludes__ (owl:TransitiveProperty) X <spatially includes> Y. Part X is an inalienable part of Y. E.g. "Africa" <spatially includes> "Congo"; "Asia" <spatially includes> "Southeast Asia"; "arm" <spatially includes> "hand"; 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[spatiallyIncludes](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/spatiallyIncludes.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/spatiallyIncludes") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isSpatiallyIncludedIn__ (owl:TransitiveProperty) Y <is spatially included in> X. Part X is an inalienable part of Y. E.g. "Congo" <is spatially included in> "Africa"; "Southeast Asia" <is spatially included in> "Asia"; "hand" <is spatially included in> "arm"; 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isSpatiallyIncludedIn](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/isSpatiallyIncludedIn.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/isSpatiallyIncludedIn") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __compose__ (owl:TransitiveProperty) Y <compose> X. A relation in which X composed of Y holds is one where Y consists of the material or substance of which X is made. This relation also subsumes <ingredient\_of> and <substance\_of> relations. E.g. "blood gas", "blood lipid", "blood protein", "blood cell" <composes> "blood"; "water", "yeast" <compose> "beer"; 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[compose](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/compose.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/compose") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isComposedOf__ (owl:TransitiveProperty) X <is composed of> Y. A relation in which X composed of Y holds is one where Y consists of the material or substance of which X is made. This relation also subsumes <ingredient\_of> and <substance\_of> relations. E.g. "blood" <is composed of> "blood cell", ""blood gas", "blood lipid", "blood protein"; "beer" <is composed of> "water", "yeast", (and by inheritance "hops" c.f. <made\_from>); 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isComposedOf](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/isComposedOf.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/isComposedOf") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isPartOf__ (owl:TransitiveProperty) Y <is part of> X. A part Y that compose an entity X. Use this relationship when none of the other partitivity relations (<component>, <composed\_of>, <portion>, <member>, <includes\_subprocess>) apply. E.g. in a plant ontology: {PlantPart} <is part of> {Taxonomic}; 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isPartOf](./An_Ontology_Design_Pattern_for_Activity_Reasoning/isPartOf.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/isPartOf") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasPortion__ (owl:TransitiveProperty) X <has portion> Y. A mass X from which a piece Y can be taken. E.g. "plant" <has portion> "cutting"; "chicken" <has portion> "chicken skin"; "a loaf of bread" <has portion> "a slice"; 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasPortion](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/hasPortion.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/hasPortion") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isPortionOf__ (owl:TransitiveProperty) Y <is portion of> X. Relation between a mass X and a piece Y taken from the mass. E.g. "cutting" <is portion of> "plant"; "chicken skin" <is portion of> "chicken"; "a slice" <is portion of> "a loaf of bread"; 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isPortionOf](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/isPortionOf.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/isPortionOf") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isSubCategoryOf__ (owl:TransitiveProperty) Relationship that is used in order to model the hierarchy of a classification scheme. A category can be in different positions in the hierarchy depending on the classification scheme you are looking at. Therefore, this relationship should not be instantiated directly to create the hierarchy, but rather a sub property specifically created for a particular classification scheme. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isSubCategoryOf](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/isSubCategoryOf.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/isSubCategoryOf") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasSubCategory__ (owl:TransitiveProperty) Inverse relationship of the <is sub category of> relationship. This relationship is used to build a hierarchy of categories within a classification scheme. A <has sub category> B means that B is a sub-category of A, i.e. B is a more specific category than A, lower in the hierarchy. Since one category can be in different places in the hierarchy in different classification schemes, do not instantiate this relationship directly, but use the sub-properties specifically for the classification scheme for which the sub-category relationship holds. For example use the <has ASC sub category> relationship to state that A <has ASC sub category> B in the Agris Subject Categories (ASC) classification scheme. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasSubCategory](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/hasSubCategory.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/hasSubCategory") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isFaoPaSubCategoryOf__ (owl:TransitiveProperty) This relationship describes the hierarchy of categories in the FAO Priority Areas (FAO PA) classification scheme. Its inverse relationship is 'has FAO PA sub category'. Use this relationship to declare that one category is the sub category of another category in the FAO PA classification scheme. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isFaoPaSubCategoryOf](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/isFaoPaSubCategoryOf.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/isFaoPaSubCategoryOf") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasFaoPaSubCategory__ (owl:TransitiveProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasFaoPaSubCategory](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/hasFaoPaSubCategory.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/hasFaoPaSubCategory") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasAscSubCategory__ (owl:TransitiveProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasAscSubCategory](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/hasAscSubCategory.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/hasAscSubCategory") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isAscSubCategoryOf__ (owl:TransitiveProperty) This relationship describes the hierarchy of categories in the Agris Subject Categories (ASC) classification scheme. Its inverse relationship is 'has ASC sub category'. Use this relationship to declare that one category is the sub category of another category in the ASC classification scheme. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isAscSubCategoryOf](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/isAscSubCategoryOf.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/isAscSubCategoryOf") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasTranslation__ (owl:SymmetricProperty) X <has translation> Y . Word X that has the same meaning of Y in another language. E.g. "vache" (FR) <has translation> "cow" (EN); "cow" (EN) <has translation> "vache" (FR); 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasTranslation](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/hasTranslation.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/hasTranslation") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __takenFromSource__ (owl:FunctionalProperty) The source (website, dictionary, thesaurus, classification scheme, terminology system, etc.) where the definition has been taken from. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[takenFromSource](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/takenFromSource.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/takenFromSource") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasFishery3AlphaCode__ (owl:FunctionalProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasFishery3AlphaCode](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/hasFishery3AlphaCode.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/hasFishery3AlphaCode") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasImageSource__ (owl:FunctionalProperty) The source of an image is the institution, web site, etc. where the image has been taken from. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasImageSource](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/hasImageSource.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/hasImageSource") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasTaxonomicCode__ (owl:FunctionalProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasTaxonomicCode](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/hasTaxonomicCode.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/hasTaxonomicCode") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasCodeFaoPa__ (owl:FunctionalProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasCodeFaoPa](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/hasCodeFaoPa.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/hasCodeFaoPa") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasDateCreated__ (owl:FunctionalProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasDateCreated](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/hasDateCreated.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/hasDateCreated") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isMainLabel__ (owl:FunctionalProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isMainLabel](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/isMainLabel.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/isMainLabel") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasSourceLink__ (owl:FunctionalProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasSourceLink](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/hasSourceLink.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/hasSourceLink") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasImageLink__ (owl:FunctionalProperty) The link to the physical image, for example the URL, where the image is available. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasImageLink](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/hasImageLink.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/hasImageLink") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isLexicalizationOf__ (owl:FunctionalProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isLexicalizationOf](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/isLexicalizationOf.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/isLexicalizationOf") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasLexicalization__ (owl:InverseFunctionalProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasLexicalization](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/hasLexicalization.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/hasLexicalization") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasCodeAgrovoc__ (owl:FunctionalProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasCodeAgrovoc](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/hasCodeAgrovoc.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/hasCodeAgrovoc") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasStatus__ (owl:FunctionalProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasStatus](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/hasStatus.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/hasStatus") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasCodeFaoterm__ (owl:FunctionalProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasCodeFaoterm](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/hasCodeFaoterm.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/hasCodeFaoterm") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasDateLastUpdated__ (owl:FunctionalProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasDateLastUpdated](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/hasDateLastUpdated.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/hasDateLastUpdated") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasCodeAsfa__ (owl:FunctionalProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasCodeAsfa](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/hasCodeAsfa.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/hasCodeAsfa") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasCodeAsc__ (owl:FunctionalProperty) 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasCodeAsc](./AOS_AGROVOC_Concept_Server_fundation_ontology_model/hasCodeAsc.md "Submissions:AOS AGROVOC Concept Server fundation ontology model/hasCodeAsc") page_
#  Additional information


Last revised by KCEW: set the correct namespaces for xmlns, xml:base, and owl:Ontology.
Last revised by KCEW: removed all remaining instances.


(type): [http://www.w3.org/2002/07/owl#Ontology](http://www.w3.org/2002/07/owl#Ontology "http://www.w3.org/2002/07/owl#Ontology")


(versionInfo): 20080508


(comment): Last revised by KCEW: set the correct namespaces for xmlns, xml:base, and owl:Ontology.


(comment): Last revised by KCEW: removed all remaining instances.



#  Scenarios



__Scenarios about AOS AGROVOC Concept Server fundation ontology model__
No scenario is added to this Content OP.




#  Reviews



__Reviews about AOS AGROVOC Concept Server fundation ontology model__


| Review article | [Posted on](../Property/CreationDate.md "Property:CreationDate") | [About revision (current is 10752)](../Property/ReviewAboutVersion.md "Property:ReviewAboutVersion") |
| --- | --- | --- |
| [Kerekestunde about AOS AGROVOC Concept Server fundation ontology model](../Community/Kerekestunde_about_AOS_AGROVOC_Concept_Server_fundation_ontology_model.md "Community:Kerekestunde about AOS AGROVOC Concept Server fundation ontology model") | 245534225 May 2010 | 92099,209 |


This revision (revision ID __10752__) takes in account the reviews: none


Other info at [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:AOS_AGROVOC_Concept_Server_fundation_ontology_model&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:AOS_AGROVOC_Concept_Server_fundation_ontology_model&action=evaluation")




  




#  Modeling issues



__Modeling issues about AOS AGROVOC Concept Server fundation ontology model__
There is no Modeling issue related to this proposal.




  




#  References


* Agrovoc Thesaurus [Project Home Page](http://www.fao.org/agrovoc "http://www.fao.org/agrovoc") | [reference page](../Community/References/Agrovoc_Thesaurus.md "Community:References/Agrovoc Thesaurus")
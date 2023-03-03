#  General information




|  |  |
| --- | --- |
|  Name | [Faceted Classification Scheme](./Faceted_Classification_Scheme.md "Community:Faceted Classification Scheme") (FCS) |
|  Problem |  Ontological representation of a specific domain concept conceptualized using a Faceted Classification Scheme (FCS). |


  




##  Non-Ontological Resource




|  |  |
| --- | --- |
|  Description |  A FCS is defined as: "a set of mutually exclusive and jointly exhaustive categories, each made by isolating one perspective on the items (a facet), that combine to completely describe all the objects in question, and which users can use, by searching and browsing, to find what they need" [(Denton, 2003)](../Community/References/How_to_Make_a_Faceted_Classification_and_Put_It_On_the_Web_3.md "Community:References/How to Make a Faceted Classification and Put It On the Web 3").The following notation is introduced to refer to the elements of a generic FCS in the figure below:<li><i>Target Domain Concept</i> (<i>TDC</i>) denotes the domain of discourse. The domain-specific concept targeted by the FCS.</li><li><i>Facet_i</i> denotes one of the facets of the FCS.</li><li><i>F_iTerm_j</i> denotes one of the terms of <i>Facet_i</i>.</li><li><i>Item_x</i> denotes one the items from the domain of discourse (<i>TDC</i>) to be classified.</li> |
|  Graphical Representation | __Diagram__[Image:FacetedClassificationScheme_GenericStructure.png](../Image/FacetedClassificationScheme_GenericStructure.png.md "Image:FacetedClassificationScheme_GenericStructure.png") |


  




##  Ontology




|  |  |
| --- | --- |
|  Description |  Generic structure of the [Normalization](../Normalization/Normalization.md "Submissions:Normalization") ODP used to represent a Faceted Classification Scheme (FCS).[The symbol (≡) denotes an OWL defined class.](../Image/NormalizationGenericStructure1.png.md "The symbol (≡) denotes an OWL defined class.") The symbol (≡) denotes an OWL defined class.The figure below represents a further generalization of the [Normalization](../Normalization/Normalization.md "Submissions:Normalization") ODP and introduces the following notation:<li><i>:TDC</i> denotes a primitive class representing the domain concept being normalized.</li><li><i>:Module_i</i> denotes a primitive class that represents one of the modules.</li><li><i>:M_iClass_j</i> denotes a primitive class that represents a subset of the module class <i>:Module_i</i>.</li><li><i>:hasModule_i</i> denotes an object property that links every module <i>:Module_i</i> to the different subclasses of the target domain concept <i>:M_iClass_jTDC</i> and <i>:SpecificTDC_x</i>.</li><li><i>:M_iClass_jTDC</i> denotes a defined class that represents a subset of the target domain concept class <i>:TDC</i>. Every class <i>:M_iClass_jTDC</i> is defined based on its relationship to the single corresponding class <i>:M_iClass_j</i> that it is derived from.</li><li><i>:SpecificTDC_x</i> denotes a primitive class that represents a subset of the target domain concept class <i>:TDC</i> and an entity from the domain to be classified. Every class <i>:SpecificTDC_x</i> is described based on its relationship to various classes <i>:M_iClass_j</i> from potentially different modules. As a consequence of this relationship, the classes <i>:SpecificTDC_x</i> could introduce the polyhierarchy scenarios in the ontology model that the <a href="../Normalization/Normalization.md" title="Submissions:Normalization">Normalization</a> ODP aims to manage and untangle.</li>The implementation of a generic defined class _:M\_iClass\_jTDC_ is given as follows:```_:M\_iClass\_jTDC_ rdf:type owl:Class ;               rdfs:subClassOf _:TDC_ ;               owl:equivalentClass [ rdf:type owl:Restriction ;                                     owl:onProperty _:hasModule\_i_ ;                                     owl:someValuesFrom _:M\_iClass\_j_                                   ] .```The implementation of a generic class _:SpecificTDC\_x_ is given as follows:```_:SpecificTDC\_x_ rdf:type owl:Class ;               rdfs:subClassOf _:TDC_ ,                               [ rdf:type owl:Restriction ;                                 owl:onProperty _:hasModule\_i_ ;                                 owl:someValuesFrom _:M\_iClass\_j_                               ] ,                               [ ... rest of existential restrictions on property _:hasModule\_i_                                     for every class _:M\_iClass\_j_ that participates                                     in the description of _:SpecificTDC\_x_                               ] .```This implementation of the classes _:M\_iClass\_jTDC_ and _:SpecificTDC\_x_ respectively, enable a reasoner to infer and maintain the subsumption relations between a given class _:SpecificTDC\_x_ and the various classes _:M\_iClass\_jTDC_ that it is related to. |
|  Graphical Representation | __Diagram__[Image:NormalizationGenericStructure2.png](../Image/NormalizationGenericStructure2.png.md "Image:NormalizationGenericStructure2.png") |


  




##  Process




|  |  |
| --- | --- |
|  Description |  Mapping between the elements in the generic structure of a Faceted Classification Scheme and the [Normalization](../Normalization/Normalization.md "Submissions:Normalization") ODP.The table below summarizes the alignment of the elements in the generic structure of both conceptual models. This alignment enables the conversion from a FCS to an OWL DL ontology by applying the [Normalization](../Normalization/Normalization.md "Submissions:Normalization") ODP:<li> The first column (leftmost), contains the elements of a generic FCS as introduced in section <b>Non-Ontological Resource</b> above.</li><li> The second column contains the elements of the <a href="../Normalization/Normalization.md" title="Submissions:Normalization">Normalization</a> ODP generic structure</li>as introduced in section __Ontology__ above.<li> The third column represents the selected OWL notation for the elements of a generic FCS in the context of the <a href="../Normalization/Normalization.md" title="Submissions:Normalization">Normalization</a> ODP generic structure.</li><li> The forth column (rightmost), indicates the OWL implementation chosen for every element. The selection complies with the requirements of the normalization mechanism.</li>Based on the principle of representating each facet of a FCS as a module of the [Normalization](../Normalization/Normalization.md "Submissions:Normalization") ODP, the underlying ideas behind the mappings in the figure(table) above can be outlined as follows:<li> The target domain concept <i>TDC</i> represents the domain of discourse of both a FCS and the <a href="../Normalization/Normalization.md" title="Submissions:Normalization">Normalization</a> ODP. The primitive class <i>:TDC</i> fulfills that role in the normalized ontology.</li><li> A facet <i>Facet_i</i> from a generic FCS corresponds to a module <i>:Module_i</i> in the <a href="../Normalization/Normalization.md" title="Submissions:Normalization">Normalization</a> ODP, therefore it becomes a primitive class <i>:Facet_i</i> in the normalized ontology model.</li><li> A facet <i>Facet_i</i> from a FCS also becomes an object property <i>:hasFacet_i</i> in the normalized ontology, given that for every module <i>:Module_i</i> in the <a href="../Normalization/Normalization.md" title="Submissions:Normalization">Normalization</a> ODP, there is an object property <i>:has_Module_i</i>.</li><li> From the relationship between facet and module, it follows that a facet term <i>F_iTerm_j</i> from a FCS maps to a module subclass <i>:M_iClass_j</i> from the <a href="../Normalization/Normalization.md" title="Submissions:Normalization">Normalization</a> ODP. Both elements represents the same notion in their respective conceptual models. A subvidision, a refinement of the facet or module that they complement respectively. Therefore, a facet term <i>F_iTerm_j</i> from a FCS becomes a primitive class <i>:F_iTerm_j</i> in the normalized ontology.</li><li> A facet term <i>F_iTerm_j</i> from a FCS also produces a defined class <i>:F_iTerm_jTDC</i> in the normalized ontology, given that for every primitive class <i>:M_iClass_j</i> in the <a href="../Normalization/Normalization.md" title="Submissions:Normalization">Normalization</a> ODP, there is a corresponding defined class <i>:M_iClass_jTDC</i>.</li><li> Every item <i>Item_x</i> to be classified in the FCS aligns to a class <i>:Specific_x</i> that is automatically classified by a reasoner in the <a href="../Normalization/Normalization.md" title="Submissions:Normalization">Normalization</a> ODP. Therefore, every element <i>Item_x</i> is represented as a primitive class <i>:SpecificTDC_x</i> in the normalized ontology.</li> |
|  Graphical Representation | __Diagram__[Image:FacetedClassificationSchemeGenericStructure.png](../Image/FacetedClassificationSchemeGenericStructure.png.md "Image:FacetedClassificationSchemeGenericStructure.png") |


  




#  Scenario example




|  |  |
| --- | --- |
|  Description |  To create an ontology model to represent an existing Faceted Classification Scheme for a specific domain concept. |


  




##  Example of a Non-Ontological Resource




|  |  |
| --- | --- |
|  Description |  The figure below recaps the final FCS developed for the "Dishwashing Detergent" domain example in [(Denton, 2003)](../Community/References/How_to_Make_a_Faceted_Classification_and_Put_It_On_the_Web_3.md "Community:References/How to Make a Faceted Classification and Put It On the Web 3")(§ 2.4). The elements of the schema fit into the generic structure of a FCS presented in section __Non-Ontological Resource__ earlier, where:<li> The <i>TDC</i> element is populated with the domain "Dishwashing Detergent".</li><li><i>Facet_i</i> elements are populated with the facets: "Agent", "Form", "Brand Name", "Scent", "Effect On Agent", and "Special Property".</li><li><i>F_iTerm_j</i> elements are populated with the terms or foci listed below (grouped by facet):<ul><li> Agent: dishwasher, person.</li><li> Form: gel, gelpac, liquid, powder, tablet.</li><li> Brand Name: Cascade, Electrasol, Ivory, No Name, Palmolive, President's Choice, Sunlight.</li><li> Scent: green apple, green tea, lavender, lemon, mandarin, ocean breeze, orange blossom, orchard fresh, passion flower, ruby red grapefruit, ylang ylang.</li><li> Effect on Agent: aroma therapy (subdivisions: invigorating, relaxing).</li><li> Special Property: antibacterial.</li></ul></li><li><i>Item_x</i> elements are populated in this case with two example items to classify:<ul><li> "President's Choice Antibacterial Hand Soap and Dishwashing Liquid".</li><li> "Palmolive Aroma Therapy, Lavender and Ylang Ylang".</li></ul></li>To illustrate the representation of a specific dishwashing detergent, let us reuse the two classification examples presented in [(Denton, 2003)](../Community/References/How_to_Make_a_Faceted_Classification_and_Put_It_On_the_Web_3.md "Community:References/How to Make a Faceted Classification and Put It On the Web 3")(§ 2.4). Applying the "Dishwashing Detergent" FCS developed in the cited reference, the item "President's Choice Antibacterial Hand Soap and Dishwashing Liquid" is classified as follows:<li> Agent: person</li><li> Form: liquid</li><li> Brand Name: President's Choice</li><li> Scent: (none)</li><li> Effect on Agent: (none)</li><li> Special Property: antibacterial</li>The item "Palmolive Aroma Therapy, Lavender and Ylang Ylang," is classified as:<li> Agent: person</li><li> Form: liquid</li><li> Brand Name: Palmolive</li><li> Scent: lavender, ylang ylang</li><li> Effect on Agent: aroma therapy</li><li> Special Property: (none)</li> |
|  Graphical Representation | __Diagram__[Image:Denton_-_2003_-_FCS_Dishwashing_Detergent.jpg](../Image/Denton_-_2003_-_FCS_Dishwashing_Detergent.jpg.md "Image:Denton_-_2003_-_FCS_Dishwashing_Detergent.jpg") |
|  Web Reference | [http://www.miskatonic.org/library/facet-web-howto.html](http://www.miskatonic.org/library/facet-web-howto.html "http://www.miskatonic.org/library/facet-web-howto.html") |


  




##  Ontology example




|  |  |
| --- | --- |
|  Description |  OWL representation of the "Dishwashing Detergent" domain concept Faceted Classification Scheme applying the Normalization ODP.[List of object properties.](../Image/FacetedClassificationSchemeOntoExObjProp.png.md "List of object properties.") List of object properties.The symbol (≡) denotes an OWL defined class. |
|  Graphical Representation | __Diagram__[Image:FacetedClassificationStructureOntologyExample.png](../Image/FacetedClassificationStructureOntologyExample.png.md "Image:FacetedClassificationStructureOntologyExample.png") |
|  Web Reference | [http://dl.dropbox.com/u/1666716/Attachments/detergent\_fcs\_normalisation\_prot3x\_owl.owl](http://dl.dropbox.com/u/1666716/Attachments/detergent_fcs_normalisation_prot3x_owl.owl "http://dl.dropbox.com/u/1666716/Attachments/detergent_fcs_normalisation_prot3x_owl.owl") |


  




##  Process example




|  |  |
| --- | --- |
|  Description |  According to the guidelines derived from the table in section __Process__ above and the implementation of a class _:SpecificTDC\_x_ given in section __Ontology__ above, the description of the example detergent "President's Choice Antibacterial Hand Soap & Dishwashing Liquid" in the normalized ontology can be stated as follows:```:PresidentsPersonLiquidAntibacterial    rdf:type owl:Class ;    rdfs:subClassOf :DishDetergent ,                    [ rdf:type owl:Restriction ;                      owl:onProperty :hasAgent ;                      owl:someValuesFrom :Person                    ] ,                    [ rdf:type owl:Restriction ;                      owl:onProperty :hasForm ;                      owl:someValuesFrom :Liquid                    ] ,                    [ rdf:type owl:Restriction ;                      owl:onProperty :hasBrandName ;                      owl:someValuesFrom :PresidentsChoice                    ] ,                    [ rdf:type owl:Restriction ;                      owl:onProperty :hasSpecialProperty ;                      owl:someValuesFrom :Antibacterial                    ] .```The description of the example detergent "Palmolive Aroma Therapy, Lavender and Ylang Ylang," would be:```:PalmoliveAromaTherapyLavenderYlangYlang    rdf:type owl:Class ;    rdfs:subClassOf :DishDetergent ,                    [ rdf:type owl:Restriction ;                      owl:onProperty :hasAgent ;                      owl:someValuesFrom :Person                    ] ,                    [ rdf:type owl:Restriction ;                      owl:onProperty :hasForm ;                      owl:someValuesFrom :Liquid                    ] ,                    [ rdf:type owl:Restriction ;                      owl:onProperty :hasBrandName ;                      owl:someValuesFrom :Palmolive                    ] ,                    [ rdf:type owl:Restriction ;                      owl:onProperty :hasScent ;                      owl:someValuesFrom :Lavender                    ] ,                    [ rdf:type owl:Restriction ;                      owl:onProperty :hasScent ;                      owl:someValuesFrom :YlangYlang                    ] ,                    [ rdf:type owl:Restriction ;                      owl:onProperty :hasEffectOnAgent ;                      owl:someValuesFrom :AromaTherapy                    ] .``` |
|  Graphical Representation | __Diagram__[Image:MappingFCSNormalizationODP.png](../Image/MappingFCSNormalizationODP.png.md "Image:MappingFCSNormalizationODP.png") |


  




#  About




|  |  |
| --- | --- |
|  SubmittedBy | [BenedictoRodriguezCastro](../User/BenedictoRodriguezCastro.md "User:BenedictoRodriguezCastro") |
|  Author |  BenedictoRodriguezCastro, HughGlaser, LesCarr |
|  Also known as |  |
|  Known uses |  |
|  Related to | [Submissions:Normalization](../Normalization/Normalization.md "Submissions:Normalization"), [Submissions:Partition](../Partition/Partition.md "Submissions:Partition"), [Submissions:ClassAsPropertyValue](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:ClassAsPropertyValue&action=edit&redlink=1 "Submissions:ClassAsPropertyValue (not yet written)") |
|  Other References |  |


#  Additional information


#  Scenarios



__Scenarios about Faceted Classification Scheme__
No scenario is added to this Content OP.




#  Reviews



__Reviews about Faceted Classification Scheme__


| Review article | [Posted on](../Property/CreationDate.md "Property:CreationDate") | [About revision (current is 10104)](../Property/ReviewAboutVersion.md "Property:ReviewAboutVersion") |
| --- | --- | --- |
| [RimDJEDIDI about Faceted Classification Scheme](../Reviews/RimDJEDIDI_about_Faceted_Classification_Scheme.md "Reviews:RimDJEDIDI about Faceted Classification Scheme") | 245545515 September 2010 | 1006710,067 |
| [BorisVillazón-Terrazas about Faceted Classification Scheme](../Reviews/BorisVillazón-Terrazas_about_Faceted_Classification_Scheme.md "Reviews:BorisVillazón-Terrazas about Faceted Classification Scheme") | 245545717 September 2010 | 1010410,104 |
| [VojtechSvatek about Faceted Classification Scheme](../Reviews/VojtechSvatek_about_Faceted_Classification_Scheme.md "Reviews:VojtechSvatek about Faceted Classification Scheme") | 245545717 September 2010 | 1010410,104 |
| [AndreaNuzzolese about Faceted Classification Scheme](../Reviews/AndreaNuzzolese_about_Faceted_Classification_Scheme.md "Reviews:AndreaNuzzolese about Faceted Classification Scheme") | 245546020 September 2010 | 1010410,104 |


This revision (revision ID __10104__) takes in account the reviews: none


Other info at [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Faceted_Classification_Scheme&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Faceted_Classification_Scheme&action=evaluation")




  




#  Modeling issues



__Modeling issues about Faceted Classification Scheme__


| Modeling issue | [Competency question](../Property/CompetencyQuestion.md "Property:CompetencyQuestion") | [Domains](../Property/Domain.md "Property:Domain") |
| --- | --- | --- |
| [Multiple Alternative Classification Criteria](../Community/Multiple_Alternative_Classification_Criteria.md "Community:Multiple Alternative Classification Criteria") | Allow me to retrieve all "elements" (classes/individuals) of a "domain concept" viewed by a combination of "values" (or "terms") from various "classification criteria" (or "facets"). |  |
| [View Inheritance](../View_Inheritance/View_Inheritance.md "Community:View Inheritance") | For examplein the case of the representation of the "wine" domain concept:<li> Allow me to select a bottle of wine by color<br/>region<br/>flavour and(or) ocassion. </li>In the case of the representation of the "pizza" domain concept:<li> Allow me to select a pizza based on the type of base<br/>the toppings and(or) the name.</li> |  |



  




#  References


* Egana-Aranguren, Mikel. Role and Application of Ontology Design Patterns in Bio-ontologies. PhD thesis, School of Computer Science, University of Manchester, 2009. [Documentation](http://mikeleganaaranguren.files.wordpress.com/2010/01/thesis.pdf "http://mikeleganaaranguren.files.wordpress.com/2010/01/thesis.pdf") | [reference page](../Community/References/Role_and_Application_of_Ontology_Design_Patterns_in_Bio-ontologies_2.md "Community:References/Role and Application of Ontology Design Patterns in Bio-ontologies 2")* Denton, William. How to Make a Faceted Classification and Put It On the Web. Nov 2003. [Documentation](http://www.miskatonic.org/library/facet-web-howto.html "http://www.miskatonic.org/library/facet-web-howto.html") | [reference page](../Community/References/How_to_Make_a_Faceted_Classification_and_Put_It_On_the_Web_3.md "Community:References/How to Make a Faceted Classification and Put It On the Web 3")* Rodriguez-Castro, B., Glaser, H. and Carr, L. (2010) How to Reuse a Faceted Classification and Put it on the Semantic Web. In: The 9th International Semantic Web Conference (ISWC), November 2010, Shanghai, China. [Documentation](http://eprints.ecs.soton.ac.uk/21488/ "http://eprints.ecs.soton.ac.uk/21488/") | [reference page](../Community/References/How_to_Reuse_a_Faceted_Classification_and_Put_it_on_the_Semantic_Web_2.md "Community:References/How to Reuse a Faceted Classification and Put it on the Semantic Web 2")* Alan L. Rector. Modularisation of domain ontologies implemented in description logics and related formalisms including owl. In K-CAP '03: Proceedings of the 2nd international conference on Knowledge capture, pages 121{128, New York, NY, USA, 2003. ACM. [ISBN 1-58113-583-1](http://ontologydesignpatterns.org/wiki/Special:BookSources/1581135831). Documentation | [reference page](../Community/References/Modularisation_of_domain_ontologies_implemented_in_description_logics_and_related_formalisms_including_owl_4.md "Community:References/Modularisation of domain ontologies implemented in description logics and related formalisms including owl 4")* Normalization Ontology Design Pattern [Documentation](http://www.gong.manchester.ac.uk/odp/html/Normalisation.html "http://www.gong.manchester.ac.uk/odp/html/Normalisation.html") | [reference page](../Community/References/Normalization_ODP_3.md "Community:References/Normalization ODP 3")* Spiteri, Louise. A simplified model for facet analysis: Ranganathan 101. Canadian Journal of Information and Library Science, 23(1/2):1-30, 1998. [Documentation](http://iainstitute.org/en/learn/research/a_simplified_model_for_facet_analysis.php "http://iainstitute.org/en/learn/research/a_simplified_model_for_facet_analysis.php") | [reference page](../Community/References/A_simplified_model_for_facet_analysis/_Ranganathan_101.md "Community:References/A simplified model for facet analysis: Ranganathan 101")

  






|  |  Submission to event[WOP:2010](../WOP/2010.md "WOP:2010") |
| --- | --- |
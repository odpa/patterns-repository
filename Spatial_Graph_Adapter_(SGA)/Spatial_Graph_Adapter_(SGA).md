#  Graphical representation


__Diagram__
_(this article has no graphical representation)_



#  General description




|  |  |
| --- | --- |
|  Name: |  Spatial Graph Adapter (SGA) Pattern |
|  Submitted by: | [Holly Ferguson](http://ontologydesignpatterns.org/wiki/index.php?title=User:Holly_Ferguson&action=edit&redlink=1 "User:Holly Ferguson (not yet written)") |
|  Also Known As: |  SGA |
|  Intent: |  Link to OWL File: [https://raw.githubusercontent.com/HollyFerguson/Spatial-Graph-Adapter-Pattern/master/SGA\_Protege\_OWL.owl](https://raw.githubusercontent.com/HollyFerguson/Spatial-Graph-Adapter-Pattern/master/SGA_Protege_OWL.owl "https://raw.githubusercontent.com/HollyFerguson/Spatial-Graph-Adapter-Pattern/master/SGA_Protege_OWL.owl")PDF of SGA Pattern Image: [Image:USOcore3.pdf](../Image/USOcore3.pdf.md "Image:USOcore3.pdf")To answer the modern, interdisciplinary questions asked within the Building domain, industry tools and data standards need to become far more interoperable in order to be able to provide a full and accurate set of analysis to engineers and designers. To provide this full picture from which to make decisions, we needed a way to resolve the spatial data that tools provide in order to synthesize it together. In addition to missing, incorrect, and inconsistent information, there is also the challenge of not being able to use existing spatial patterns to capture the full granularity or specificity of the geospatial descriptions required to capture full and dynamic geometric contexts.The Spatial Graph Adapter (SGA) pattern provides us a way to extend the simple identification of geometries and simultaneously assign further descriptions and self-context as well as contextual and relational references to other spatial objects in or surrounding the original entity. For example, not only can we use existing notions say that one surface is adjacent to another, but we have a way to say exactly what type of adjacency and to what extent it is adjacent (more examples in accompanying paper). The SGA has also been implemented for several building industry schemas and our further research is in bringing this and other patterns into full use in a Linked Data Platform (ongoing). |
|  Domains: | [http://ontologydesignpatterns.org/wiki/Community:Building\_and\_Construction](http://ontologydesignpatterns.org/wiki/Special:AddData/Domain Form/Community:Http://ontologydesignpatterns.org/wiki/Community:Building_and_Construction "Community:Http://ontologydesignpatterns.org/wiki/Community:Building and Construction (not yet written)") |
|  Competency Questions: | <li> 1. What spaces is this damaged structural beam a part of (without needing to iterate through every existing spatial component or coordinate set)?</li>2. Exactly how much of this structural element is exposed and to what spaces?3. What are all of the spatial elements in this graph that contain void spaces (air spaces in assemblies that could be susceptible to damage)?4. What thermal or occupancy zones is this assembly associated with (these may or may not have to do with adjacency or locality)?5. What sets of columns are responsible for supporting floors X and Y? |
|  Solution description: |  After several iterations of studying building industry data standards (in particular, GBXML, IFC, and CityGML), we began to map not only terms between them, but also conceptual level indicators. First we capture the main spatial arrangement of geometric elements which are extracted automatically from a spatial instance file. Secondly, the SGA pattern allows us to contextualize additional relationships to capture schema-specific ideas to ultimately be able to ask all the data questions simultaneously. We do acknowledge that in several cases there could be benefits to aligning it with other mereotopological or SIO pattern concepts, but these have not been necessary thus far.Even if we use a common definition for adjacency, such as where two objects would be touching could be considered adjacent, this fails when we want to know, say what columns or walls are adjacent to a space. It is true that they may be touching some building geometries, but what about the cases where you would have adjacent columns, but they are touching only the open air that define that side of a space (not touching but still on that visual or schema induced boundary)? The SGA pattern allows us to extract this type of information and add it as Attributes or ContextualizedRelations to other objects, solving this issue by being able to, for example, group building elements even as what may seem arbitrary in isolated examples. Schemas produce a wide array of these situations, and even more when we start to translate between them. |
|  Reusable OWL Building Block: | [https://raw.githubusercontent.com/HollyFerguson/Spatial-Graph-Adapter-Pattern/master/SGA\_Protege\_OWL.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=https://raw.githubusercontent.com/HollyFerguson/Spatial-Graph-Adapter-Pattern/master/SGA_Protege_OWL.owl&message=OWL building block&from_page_id=4095&update=) (0) |
|  Consequences: | [SGA Pattern](../Image/USOcore3.jpg.md "SGA Pattern") SGA PatternWith the capabilities the SGA pattern provides, it has been found to be useful and as been implemented for IFC, GBXML, and CityGML is currently in progress. Once this mapping was produced and captured via this pattern, further work was possible and completed in the form of View helper files and all of this is being worked into an operational Linked Data Platform to further enhance open data exchange. Our work was inspired by ideas from Spatial Information Theory, biomedical research for the Semanticscience Integrated Ontology (SIO), Mereotopology, and geospatial data efforts via the Open Geospatial Consortium (OGC), although these are not the only works regarding spatial descriptions. |
|  Scenarios: |  IFC, GBXML, and CityGML (current work) |
|  Known Uses: | [Building translation adapter or lifter pattern](http://Building%20translation%20adapter%20or%20lifter%20pattern "http://Building%20translation%20adapter%20or%20lifter%20pattern") |
|  Web References: |  |
|  Other References: |  |
|  Examples (OWL files): | <li></li> |
|  Extracted From: | <li></li> |
|  Reengineered From: |  |
|  Has Components: |  |
|  Specialization Of: |  |
|  Related CPs: |  |


  




#  Elements


_The __Spatial Graph Adapter (SGA)__ Content OP locally defines the following ontology elements:_


  




#  Additional information


Our work was inspired by ideas from Spatial Information Theory, biomedical research for the Semanticscience Integrated Ontology (SIO), Mereotopology, and geospatial data efforts via the Open Geospatial Consortium (OGC), although these are not the only works regarding spatial descriptions.


With the capabilities the SGA pattern provides, it has been found to be useful and as been implemented for IFC, GBXML, and CityGML is currently in progress. Once this mapping was produced and captured via this pattern, further work was possible and completed in the form of View helper files and all of this is being worked into an operational Linked Data Platform to further enhance open data exchange.


For the development of the pattern and for versions of data standards worked with thus far, we have crossed-checked our research with a team of Ontologists, Computer Scientists, Architects, Engineers, and other domain experts. We have also built a visualization method to verify what is being populated within the pattern relative to what data was in the original spatial schema instance file. The pattern has been used with a set of six test models ranging in complexity from one room to sixty-plus rooms on multiple levels. Additional models are planned to be tested in future iterations of the work.



#  Scenarios



__Scenarios about Spatial Graph Adapter (SGA)__
No scenario is added to this Content OP.




#  Reviews



__Reviews about Spatial Graph Adapter (SGA)__
There is no review about this proposal.
This revision (revision ID __12678__) takes in account the reviews: [Requested](http://ontologydesignpatterns.org/wiki/index.php?title=Reviews:Requested&action=edit&redlink=1 "Reviews:Requested (not yet written)")


Other info at [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Spatial_Graph_Adapter_%28SGA%29&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Spatial_Graph_Adapter_%28SGA%29&action=evaluation")




  




#  Modeling issues



__Modeling issues about Spatial Graph Adapter (SGA)__
There is no Modeling issue related to this proposal.




  




#  References


  






|  |  Submission to event[WOP:2016](../WOP/2016.1.md "WOP:2016") |
| --- | --- |
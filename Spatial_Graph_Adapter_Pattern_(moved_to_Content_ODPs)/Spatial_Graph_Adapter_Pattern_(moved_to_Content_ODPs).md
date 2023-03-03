# 

 Graphical representation



__Diagram__ 
_(this article has no graphical representation)_ 




# 

 General information




|  |  |
| --- | --- |
|  Name  |  Spatial Graph Adapter Pattern  |
|  Also known as  |  SGA Pattern  |
|  Author(s)  |  Holly Ferguson, Charles Vardeman II, Michelle Cheatham, Adila Krisnadhi  |
|  SubmittedBy  | [Holly Ferguson](http://ontologydesignpatterns.org/wiki/index.php?title=User:Holly_Ferguson&action=edit&redlink=1 "User:Holly Ferguson (not yet written)")  |



  





# 

 Description




|  |  |
| --- | --- |
|  Domain (if applicable)  | [Building Information Modeling and Spatial Representations](http://ontologydesignpatterns.org/wiki/index.php?title=Building_Information_Modeling_and_Spatial_Representations&action=edit&redlink=1 "Building Information Modeling and Spatial Representations (not yet written)")  |
|  Alignment problem addressed  | [Image:USOcore3.pdf](../Image/USOcore3.pdf.md "Image:USOcore3.pdf")  SGA Pattern: Image: [http://ontologydesignpatterns.org/wiki/Image:USOcore3.jpg](../Image/USOcore3.jpg.md "http://ontologydesignpatterns.org/wiki/Image:USOcore3.jpg")  Current OWL File Located at: [https://github.com/HollyFerguson/Spatial-Graph-Adapter-Pattern](https://github.com/HollyFerguson/Spatial-Graph-Adapter-Pattern "https://github.com/HollyFerguson/Spatial-Graph-Adapter-Pattern")  To answer the modern, interdisciplinary questions asked within the Building domain, industry tools and data standards need to become far more interoperable in order to be able to provide a full and accurate set of analysis to engineers and designers. To provide this full picture from which to make decisions, we needed a way to resolve the spatial data that tools provide in order to synthesize it together. In addition to missing, incorrect, and inconsistent information, there is also the challenge of not being able to use existing spatial patterns to capture the full granularity or specificity of the geospatial descriptions required to capture full and dynamic geometric contexts.  |
|  Alignment solution  |  The Spatial Graph Adapter (SGA) pattern provides us a way to extend the simple identification of geometries and simultaneously assign further descriptions and self-context as well as contextual and relational references to other spatial objects in or surrounding the original entity. For example, not only can we use existing notions say that one surface is adjacent to another, but we have a way to say exactly what type of adjacency and to what extent it is adjacent (more examples in accompanying paper). The SGA has also been implemented for several building industry schemas model sets our further research in bringing this and other patterns into full use in a Linked Data Platform (ongoing).  |
|  Alignment workflow  |  After several iterations of studying building industry data standards (in particular, GBXML, IFC, and CityGML), we began to map not only terms between them, but also conceptual level indicators. First we capture the main spatial arrangement of geometric elements which are extracted automatically from a spatial instance file. Secondly, the SGA pattern allows us to contextualize additional relationships to capture schema-specific ideas to ultimately be able to ask all the data questions simultaneously. We do acknowledge that in several cases there could be benefits to aligning it with other mereotopological or SIO pattern concepts, but these have not been necessary thus far.  |
|  Reusable component  |  |



  





# 

 Example




|  |  |
| --- | --- |
|  Problem example  |  |
|  Solution example  |  Example Problem Question:  What Building Components are adjacent to this Space (Both creating enclosure or not creating enclosure)?  Even if we use a common definition for adjacency, such as where two objects would be touching could be considered adjacent, this fails when we want to know, say what columns or walls are adjacent to a space. It is true that they may be touching some building geometries, but what about the cases where you would have adjacent columns, but they are touching only the open air that define that side of a space (not touching but still on that visual or schema induced boundary)?  |
|  Consequences  |  The SGA pattern allows us to extract this type of information and add it as Attributes or ContextualizedRelations to other objects, solving this issue by being able to, for example, group building elements even as what may seem arbitrary in isolated examples. Schemas produce a wide array of these situations, and even more when we start to translate between them.  |



  





# 

 Reference




|  |  |
| --- | --- |
|  Origin  |  Our work was inspired by ideas from Spatial Information Theory, biomedical research for the Semanticscience Integrated Ontology (SIO), Mereotopology, and geospatial data efforts via the Open Geospatial Consortium (OGC), although these are not the only works regarding spatial descriptions.  |
|  Known use  |  With the capabilities the SGA pattern provides, it has been found to be useful and as been implemented for IFC, GBXML, and CityGML is currently in progress. Once this mapping was produced and captured via this pattern, further work was possible and completed in the form of View helper files and all of this is being worked into an operational Linked Data Platform to further enhance open data exchange.  |
|  Reference  |  |
|  Related to  | [Submissions:Not applicable at this time](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Not_applicable_at_this_time&action=edit&redlink=1 "Submissions:Not applicable at this time (not yet written)")  , [Submissions:to be added.](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:To_be_added.&action=edit&redlink=1 "Submissions:To be added. (not yet written)")  |
|  Test  |  For the development of the pattern and for versions of data standards worked with thus far, we have crossed-checked our research with a team of Ontologists, Computer Scientists, Architects, Engineers, and other domain experts. We have also built a visualization method to verify what is being populated within the pattern relative to what data was in the original spatial schema instance file. The pattern has been used with a set of six test models ranging in complexity from one room to sixty-plus rooms on multiple levels. Additional models are planned to be tested in future iterations of the work.  |



  

 Current OWL File Located at:
 [https://github.com/HollyFerguson/Spatial-Graph-Adapter-Pattern](https://github.com/HollyFerguson/Spatial-Graph-Adapter-Pattern "https://github.com/HollyFerguson/Spatial-Graph-Adapter-Pattern") 




# 

 Scenarios




__Scenarios about Spatial Graph Adapter Pattern (moved to Content ODPs)__ 


 No scenario is added to this Content OP.
 




# 

 Reviews




__Reviews about Spatial Graph Adapter Pattern (moved to Content ODPs)__ 


 There is no review about this proposal.
This revision (revision ID
 __12661__ 
 ) takes in account the reviews:
 [Developed with Ontologists, Computer Scientists, Engineers, and Architects - Will also take into account and make necessary edits from any reviews given about the accompanying paper submitted to WOP:2016.](http://ontologydesignpatterns.org/wiki/index.php?title=Reviews:Developed_with_Ontologists%2C_Computer_Scientists%2C_Engineers%2C_and_Architects_-_Will_also_take_into_account_and_make_necessary_edits_from_any_reviews_given_about_the_accompanying_paper_submitted_to_WOP:2016.&action=edit&redlink=1 "Reviews:Developed with Ontologists, Computer Scientists, Engineers, and Architects - Will also take into account and make necessary edits from any reviews given about the accompanying paper submitted to WOP:2016. (not yet written)") 




 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Spatial_Graph_Adapter_Pattern_%28moved_to_Content_ODPs%29&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Spatial_Graph_Adapter_Pattern_%28moved_to_Content_ODPs%29&action=evaluation") 





  





# 

 Modeling issues




__Modeling issues about Spatial Graph Adapter Pattern (moved to Content ODPs)__ 


 There is no Modeling issue related to this proposal.
 




  





# 

 References



  






|  |  Submission to event [WOP:2016](../WOP/2016.1.md "WOP:2016")  |
| --- | --- |
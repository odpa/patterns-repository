#  Graphical representation


__Diagram__




[![Image:Experience and observation.png](./Experience_and_observation.png)](../Image/Experience_and_observation.png.md "Image:Experience and observation.png")




#  General description




|  |  |
| --- | --- |
|  Name: |  Experience & Observation |
|  Submitted by: | [AlessandroAdamou](../User/AlessandroAdamou.md "User:AlessandroAdamou") |
|  Also Known As: |  |
|  Intent: |  to represent the epistemological "missing link" between a cognitive activity, e.g. the interaction with a cultural object, and any evidence of the effects this activity has on the individuals that are engaged with it; what can collectively be considered as an experience. |
|  Domains: | [Humanities](../Community/Humanities.md "Community:Humanities"), [Social Science](../Community/Social_Science.md "Community:Social Science") |
|  Competency Questions: | <li> In what ways can one person be engaged in a single activity?</li>- What personal observations were produced by reflecting upon an activity being carried out?- Which activities performed by someone have prompted an observation from that person and which haven't? |
|  Solution description: |  # SPARQL queries follow, in the same order as the CQs```  PREFIX : <[http://modellingdh.github.io/ont/odp/term/](http://modellingdh.github.io/ont/odp/term/ "http://modellingdh.github.io/ont/odp/term/")>  PREFIX activ: <[http://ontology.eil.utoronto.ca/icity/ActivitySpecification/](http://ontology.eil.utoronto.ca/icity/ActivitySpecification/ "http://ontology.eil.utoronto.ca/icity/ActivitySpecification/")>``````  SELECT DISTINCT ?engagement ?activity WHERE {    ?engagement :onActivity ?activity  }``````  SELECT DISTINCT ?observation WHERE {    ?activity a activ:Activity       ; :includes ?observation     . ?observation a :Observation  }``````  SELECT DISTINCT ?activity WHERE {    { ?activity a :Prompt }     UNION    { ?activity a activ:Activity ; :produced [ ] }  }``` |
|  Reusable OWL Building Block: | [https://raw.githubusercontent.com/modellingDH/odp\_experience/master/owl/cp\_experience.owl.rdfxml](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=https://raw.githubusercontent.com/modellingDH/odp_experience/master/owl/cp_experience.owl.rdfxml&message=OWL building block&from_page_id=4646&update=) (0) |
|  Consequences: |  Adopting this pattern decomposes the lax notion of experience (e.g. through engaging in reading a book or incidentally hearing some music) into distinguishable elements that can be used in e.g. text annotation with greater precision than with a single named entity representing the experience. |
|  Scenarios: |  A letter or diary entry reports on the writer's experience when reading a book or listening to music |
|  Known Uses: | [https://raw.githubusercontent.com/eureadit/crowdsourcing-ontology/master/owl/crowdsourcing-evidences.owl.ttl](https://raw.githubusercontent.com/eureadit/crowdsourcing-ontology/master/owl/crowdsourcing-evidences.owl.ttl "https://raw.githubusercontent.com/eureadit/crowdsourcing-ontology/master/owl/crowdsourcing-evidences.owl.ttl") |
|  Web References: |  |
|  Other References: |  |
|  Examples (OWL files): | <li><a class="external free" href="https://raw.githubusercontent.com/modellingDH/odp_experience/master/examples/concert.ttl" rel="nofollow" title="https://raw.githubusercontent.com/modellingDH/odp_experience/master/examples/concert.ttl">https://raw.githubusercontent.com/modellingDH/odp_experience/master/examples/concert.ttl</a></li> |
|  Extracted From: | <li><a class="external free" href="https://raw.githubusercontent.com/eureadit/reading-experience-ontology/master/data-model-v2.owl" rel="nofollow" title="https://raw.githubusercontent.com/eureadit/reading-experience-ontology/master/data-model-v2.owl">https://raw.githubusercontent.com/eureadit/reading-experience-ontology/master/data-model-v2.owl</a></li> |
|  Reengineered From: |  |
|  Has Components: | <li><a href="../Persons/Persons.md" title="Submissions:Persons">Submissions:Persons</a></li><li><a href="../ActivitySpecification/ActivitySpecification.md" title="Submissions:ActivitySpecification">Submissions:ActivitySpecification</a></li> |
|  Specialization Of: |  |
|  Related CPs: | <li><a href="../Persons/Persons.md" title="Submissions:Persons">Submissions:Persons</a></li><li><a href="./Experience_&_Observation.md" title="Submissions:Observation">Submissions:Observation</a></li><li><a href="../ActivitySpecification/ActivitySpecification.md" title="Submissions:ActivitySpecification">Submissions:ActivitySpecification</a></li><li><a href="../Transition/Transition.md" title="Submissions:Transition">Submissions:Transition</a></li> |


  




#  Elements


_The __Experience & Observation__ Content OP locally defines the following ontology elements:_



[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __Engagement__ (owl:Class) The product of a reflection upon an observation, which embodies subjective traits of an experience (Example: "After reading this passage of 'To Kill a Mockingbird', I came to a clearer understanding of the many facets of social intolerance"). 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[Engagement](./Experience_&_Observation/Engagement.md "Submissions:Experience & Observation/Engagement") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __Observation__ (owl:Class) The product of an act of scrutiny which may or may not have been performed with a critical disposition (Example: "My thoughts from reading this passage of 'To Kill a Mockingbird'"). 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[Observation](./AquaticResourceObservation.md "Submissions:Experience & Observation/Observation") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __inActivity__ (owl:ObjectProperty) what activity/ies are affecting or affected by a certain engagement 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[inActivity](./Experience_&_Observation/inActivity.md "Submissions:Experience & Observation/inActivity") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isReflectionOn__ (owl:ObjectProperty) Used to connect the subjective elements of an experience with the corresponding observation, which is extrapolated from the content being interacted with and in itself may not be including a critique. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isReflectionOn](./Experience_&_Observation/isReflectionOn.md "Submissions:Experience & Observation/isReflectionOn") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isReflectedUponIn__ (owl:ObjectProperty) Inverse of isReflectionOn 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isReflectedUponin](./Experience_&_Observation/isReflectedUponin.md "Submissions:Experience & Observation/isReflectedUponin") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isEngagedIn__ (owl:ObjectProperty) Because an activity may engage other participants than the one performing it, engagements are in general considered individual rather than collective, therefore each participants has their own engagement and only some of them will be conscious and/or documented. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isEngagedIn](./Experience_&_Observation/isEngagedIn.md "Submissions:Experience & Observation/isEngagedIn") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasEngagement__ (owl:ObjectProperty) inverse of inActivity 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasEngagement](./Experience_&_Observation/hasEngagement.md "Submissions:Experience & Observation/hasEngagement") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __producedObservation__ (owl:ObjectProperty) This property can be used to denote that something is (even indirectly, not necessary through direct reflection) responsible for the existence of an observation. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[producedObservation](./Experience_&_Observation/producedObservation.md "Submissions:Experience & Observation/producedObservation") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __includes__ (owl:ObjectProperty) A relation of mereological nature that connects a given observation with the activity that originates them: it strengthens the argument that observations are always active processes from a cognitive standpoint, regardless of how conscious they may be. 
A standard mereological property from another content pattern may be used in lieu of this one and therefore aligned with it. [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[includes](./Experience_&_Observation/includes.md "Submissions:Experience & Observation/includes") page_
#  Additional information


#  Scenarios



__Scenarios about Experience & Observation__
No scenario is added to this Content OP.




#  Reviews



__Reviews about Experience & Observation__
There is no review about this proposal.
This revision (revision ID __14298__) takes in account the reviews: none


Other info at [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Experience_%26_Observation&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Experience_%26_Observation&action=evaluation")




  




#  Modeling issues



__Modeling issues about Experience & Observation__
There is no Modeling issue related to this proposal.




  




#  References
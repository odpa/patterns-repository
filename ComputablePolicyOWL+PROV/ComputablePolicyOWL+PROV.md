#  Graphical representation


__Diagram__




[![Image:owl+prov.png](./owl+prov.png)]("OWL+PROV Design Pattern diagram")




#  General description




|  |  |
| --- | --- |
|  Name: |  Computable Policy |
|  Submitted by: | [Henrique Santos](../User/HenriqueSantos.md "User:HenriqueSantos") |
|  Also Known As: | OWL+PROV |
|  Intent: |  To represent machine-interpetrable and computable policies, supporting automated policy decisions using OWL reasoners. |
|  Domains: | Domain-agnostic |
|  Competency Questions: | <li> What is the effect of a policy?</li><li> Which are the applicable policies during a given timeframe/instant?</li><li> Which are the application policies in a specific geo-location?</li><li> Which policy rule has priority during evaluation?</li> |
|  Solution description: |  A recurrent event series is modelled as an intersection of a collection and a situation. Indeed, a recurrent event is seen as a collection, since it contains entities that share one or more common properties and are unified conceptually (unifying factors). These entities are member of the collection, and are all consecutive events. At the same time, a recurrent event is a situation, intended as a relational context in which the contextualised things are based on a frame: a recurrent event is similar to a plan that defines how the things involved in that plan (i.e. the specific events) shall be carried out, e.g. where the events shall be located, in which time of the year, etc. |
|  Reusable OWL Building Block: | [http://www.ontologydesignpatterns.org/cp/owl/recurrenteventseries.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=http://www.ontologydesignpatterns.org/cp/owl/recurrenteventseries.owl&message=OWL building block&from_page_id=4561&update=) (369) |
|  Consequences: |  A series of recurrent events, its unifying factors and the recurrent time period can be modelled. |
|  Scenarios: |  Umbria Jazz is a collection of events, which all take place in July and in the Italian region of Umbria, and has the musical genre jazz as a topic. Its events recur at regular time periods, i.e. annually. |
|  Known Uses: |  |
|  Web References: |  |
|  Other References: |  |
|  Examples (OWL files): |  |
|  Extracted From: |  |
|  Reengineered From: |  |
|  Has Components: |  |
|  Specialization Of: |  |
|  Related CPs: | <li><a href="../Situation/Situation.md" title="Submissions:Situation">Submissions:Situation</a></li><li><a href="../Sequence/Sequence.md" title="Submissions:Sequence">Submissions:Sequence</a></li><li><a href="../Classification/Classification.md" title="Submissions:Classification">Submissions:Classification</a></li><li><a href="../CollectionEntity/CollectionEntity.md" title="Submissions:CollectionEntity">Submissions:CollectionEntity</a></li> |


  




#  Elements


_The __RecurrentEventSeries__ Content OP locally defines the following ontology elements:_



#  Additional information


#  Scenarios



__Scenarios about RecurrentEventSeries__
No scenario is added to this Content OP.




#  Reviews



__Reviews about RecurrentEventSeries__
There is no review about this proposal.
This revision (revision ID __13662__) takes in account the reviews: none


Other info at [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:RecurrentEventSeries&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:RecurrentEventSeries&action=evaluation")




  




#  Modeling issues



__Modeling issues about RecurrentEventSeries__
There is no Modeling issue related to this proposal.




  




#  References
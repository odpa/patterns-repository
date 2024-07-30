#  Graphical representation


__Diagram__

![OWL+PROV Design Pattern diagram](./owl+prov.png "OWL+PROV Design Pattern diagram")

#  General description

|  |  |
| --- | --- |
|  Name: |  Computable Policy |
|  Submitted by: | [Henrique Santos](../User/HenriqueSantos.md "User:HenriqueSantos") |
|  Also Known As: | OWL+PROV |
|  Intent: |  To represent machine-interpetrable and computable policies, supporting automated policy decisions using OWL reasoners. |
|  Domains: | Domain-agnostic |
|  Competency Questions: | <li> What is the effect of a policy?</li><li> Which are the applicable policies during a given timeframe/instant?</li><li> Which are the application policies in a specific geo-location?</li><li> Which policy rule has priority during evaluation?</li> |
|  Solution description: |  OWL+PROV is novel ontology design pattern for representing policies and guidelines using the OWL and PROV semantic web W3C standards. The pattern advocates for the creation of a class hierarchy, which incrementally appends the policy's rules to support the explanation of policy evaluation results. |
|  Reusable OWL Building Block: | [Example 1](owl+prov.ttl) |
|  Consequences: |  Ontologies created following this pattern extend domain knowledge graphs to include the encoding of the policy's rules in class equivalencies, expressed as OWL restrictions over domain entities. |
|  Scenarios: |  Umbria Jazz is a collection of events, which all take place in July and in the Italian region of Umbria, and has the musical genre jazz as a topic. Its events recur at regular time periods, i.e. annually. |
|  Known Uses: Radio Spectrum Sharing, Diabetes Guidelines |  |
|  Web References: |  |
|  Other References: |  |
|  Examples (OWL files): |  |
|  Extracted From: |  |
|  Reengineered From: |  |
|  Has Components: |  |
|  Specialization Of: |  |
|  Related CPs: |  |


  




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
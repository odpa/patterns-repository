#  Graphical representation


__Diagram__




[Image:Roehl-Jansen Disposition.pdf](../Image/Roehl-Jansen_Disposition.pdf.md "Image:Roehl-Jansen Disposition.pdf")




#  General description




|  |  |
| --- | --- |
|  Name: |  Disposition |
|  Submitted by: | [LudgerJansen](../User/LudgerJansen.md "User:LudgerJansen") |
|  Also Known As: |  Non-propositional Disposition |
|  Intent: |  This pattern allow the representation of non-probabilistic dispositions with unique triggering and realization process types. |
|  Domains: | [Upper Ontology](../Community/Upper_Ontology.md "Community:Upper Ontology"), [Biology](../Community/Biology.md "Community:Biology"), [General](../Community/General.md "Community:General") |
|  Competency Questions: | <li> What is the triggering process for a given disposition? (e.g.</li><li> a dose of penicilin can unfold its antibiotic disposition when being swallowed)</li>What is the realization of a given disposition? (e.g.<li> developing a fever</li><li> rash)</li> |
|  Solution description: |  Relations are being defined between dispositions, their realizations processes and their triggering processes. The pattern is easily compatible with many top-level ontologies. In this description, we use classes from BFO and BioTop.References: - Roehl/Jansen: "Representing Dispositions", Journal of Biomedical Semantics 2011, 2(Suppl 4):S4 (9 August 2011).- BioTop, [http://www.imbi.uni-freiburg.de/ontology/biotop/](http://www.imbi.uni-freiburg.de/ontology/biotop/ "http://www.imbi.uni-freiburg.de/ontology/biotop/"). |
|  Reusable OWL Building Block: |  Roehl-jansen\_disposition-pattern.owl (0) |
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


_The __Disposition__ Content OP locally defines the following ontology elements:_



#  Additional information


Bearer (owl:Class): BFO: independent continuant, BioTop: material object


Trigger (owl:Class): BFO: process; Biotop: process


Disposition (owl:Class): BFO (dependent continuant: realizable:) disposition; Biotop: disposition


Realization (owl:Class): BFO: process; Biotop: process


hasDisposition (owl:ObjectProperty): This relation is a subrelation of bearerOf which expresses the relation of an instance of an independent continuant to an instance of a dependent continuant, that is a quality or a disposition. hasDisposition expresses that certain types of things have a certain disposition essentially. All instances will have instances of the disposition type inhering in them, e.g. all aspirin pills have the disposition to relieve pain.


inheresIn (owl:ObjectProperty): Expresses the relation between a disposition and its bearer. Even if particular dispositions are of the same type, their bearers do not have to be of the same type. Tablets of quite different types, like aspirins and paracetamols, can be bearers of instances the same disposition type to relieve pain e.g. aspirin as well as paracetamol. If all instances of a disposition have bearers of the same type, we can represent this by means of the inheres\_in relation:
D inheres\_in B := For all x, if x instance\_of D, then there is some y such that: y instance\_of B and x inheres\_in y.


hasTriggerR (owl:ObjectProperty): relation between the realization process and the triggering process (dropping of the glass and its breaking)
R has\_triggerR T := For all x, if x instance\_of Rm then there is some y, such that y instance\_of T and x has\_triggerR y.


has\_triggerD (owl:ObjectProperty)\*: relation that holds between the disposition and the triggering process (fragility of the glass and its breaking)
D has\_triggerD T := For all x, if x instance\_of D, then there is some y, such that if x has\_triggerD y, then y instance\_of T.


hasRealization (owl:ObjectProperty): This relation connects a disposition instance with any process instance which is its realization. A type of process R is the realization type of a disposition type D if and only if any instance of D is realized, then the realization is of type R; i.e. 
D has\_realization R := For all x, if x instance\_of D, then necessarily for all y: if x has\_realization y, then y instance\_of R. 


  




#  Scenarios



__Scenarios about Disposition__
No scenario is added to this Content OP.




#  Reviews



__Reviews about Disposition__
There is no review about this proposal.
This revision (revision ID __12033__) takes in account the reviews: none


Other info at [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Disposition&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Disposition&action=evaluation")




  




#  Modeling issues



__Modeling issues about Disposition__
There is no Modeling issue related to this proposal.




  




#  References
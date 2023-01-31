# 

 Graphical representation





[![](images/thumb/d/df/ODPEEP.jpg/800px-ODPEEP.jpg)](../Image/ODPEEP.jpg "ODPEEP.jpg")




# 

 General description




|  |  |
| --- | --- |
|  Name:  |  EEP  |
|  Submitted by:  | [IKERESNAOLA-GONZALEZ](../User/IKERESNAOLA-GONZALEZ "User:IKERESNAOLA-GONZALEZ")  |
|  Also Known As:  |  |
|  Intent:  |  To represent executions made by executors that implement procedures. Executions are events like observations or actuations. Executors are systems like sensors or actuators that produce executions. Executors implement procedures to carry out their goals. Executions and executors are taken over features of interest and their intrinsic properties/qualities.  |
|  Domains:  | [Building and Construction](../Community/Building_and_Construction "Community:Building and Construction")  , [General](../Community/General "Community:General")  |
|  Competency Questions:  | <li>       CQ1: What are the observations/actuations performed by a given procedure?      </li><li>       CQ2: What are the observations/actuations performed by a given sensor/actuator?      </li><li>       CQ3: What are the procedures implemented by a given sensor/actuator?      </li><li>       CQ4: What are the features of interest on a given observation/actuation?      </li><li>       CQ5: What are the properties/qualities sensed/actuated by a given      </li><li>       observations/actuations?      </li><li>       CQ6: What are the features of interest of a given sensor/actuator?      </li><li>       CQ7: What are the properties/qualities sensed/actuated by a given executor?      </li> |
|  Solution description:  |  The Execution-Executor-Procedure (EEP) ODP imports the AffectedBy ODP ( [https://w3id.org/affectedBy](https://w3id.org/affectedBy "https://w3id.org/affectedBy")  ), that involves classes for Features of Interest and their intrinsic Properties/Qualities.  The EEP ODP is an adaptation of the Procedure Execution Ontology (PEP) ( [https://w3id.org/pep/pep-1.1](https://w3id.org/pep/pep-1.1 "https://w3id.org/pep/pep-1.1")  ) from the SEAS ontology which, in turn, is a generalization of the Observation-Sensor-Procedure and Actuation-Actuator-Procedure patterns used in the SOSA ( [http://www.w3.org/ns/sosa/](http://www.w3.org/ns/sosa/ "http://www.w3.org/ns/sosa/")  ) and SSN ( [http://www.w3.org/ns/ssn/](http://www.w3.org/ns/ssn/ "http://www.w3.org/ns/ssn/")  ) ontologies.From the AffectedBy ODP, the EEP ODP imports the notion that a property/quality is intrinsic to the feature of interest that it belongs to (i.e., according to the definition of the class Quality in the DUL ontology [http://www.ontologydesignpatterns.org/ont/dul/DUL.owl](http://www.ontologydesignpatterns.org/ont/dul/DUL.owl "http://www.ontologydesignpatterns.org/ont/dul/DUL.owl")  ).Apart from the two classes imported from the AffectedBy ODP (aff:FeatureOfIntetest and aff:Quality), the EEP ODP consists of three more classes: Execution, Executor, and Procedure. The class Execution and their three functional object properties eep:madeBy, eep:usedProcedure, and eep:onQuality, form the backbone of the ODP. The property eep:madeBy links an execution to its executor, the property eep:usedProcedure links an execution to its procedure, and the property eep:onQuality links an execution to the quality/property concerned by the execution. Therefore, an execution jointly with their three object values of the three aforementioned properties can be considered as a n-ary relationship. Note that every quality belongs to unique feature of interest. Therefore, a feature of interest is involved in the n-ary relationship.The remaining object properties: eep:implements, that links executors to procedures, eep:hasFeatureOfInteres, that links executions to features of interest, eep:forQuality, that links executors to qualities, and eep:forFeatureOfInterest, that links executors to features of interest, are defined in terms of the functional object properties using property chain axioms.  |
|  Reusable OWL Building Block:  | [https://w3id.org/eep](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=https://w3id.org/eep&message=OWL building block&from_page_id=4467&update=)  (0)  |
|  Consequences:  |  Axioms included in the EEP ODP provide inferences that allow to answer the competency questions properly. Therefore, solving some weaknesses of the sosa/ssn ontologies.  Note that only triples about the four functional object properties: eep:madeBy, eep:usedProcedure, eep:onQuality, and aff:belongsTo, needs to be asserted, the remaining triples are inferred by the property axioms.  |
|  Scenarios:  |  |
|  Known Uses:  | [https://w3id.org/eepsa](https://w3id.org/eepsa "https://w3id.org/eepsa")  |
|  Web References:  |  |
|  Other References:  |  |
|  Examples (OWL files):  | <li><a class="external free" href="http://193.144.237.227:8890/DAV/home/dba/ODP/EEP_Example.owl" rel="nofollow" title="http://193.144.237.227:8890/DAV/home/dba/ODP/EEP_Example.owl">        http://193.144.237.227:8890/DAV/home/dba/ODP/EEP_Example.owl       </a></li> |
|  Extracted From:  |  |
|  Reengineered From:  | <li><a class="external free" href="https://w3id.org/pep/pep-1.1" rel="nofollow" title="https://w3id.org/pep/pep-1.1">        https://w3id.org/pep/pep-1.1       </a></li><li><a class="external free" href="http://www.w3.org/ns/sosa/" rel="nofollow" title="http://www.w3.org/ns/sosa/">        http://www.w3.org/ns/sosa/       </a></li><li><a class="external free" href="http://www.w3.org/ns/ssn/" rel="nofollow" title="http://www.w3.org/ns/ssn/">        http://www.w3.org/ns/ssn/       </a></li><li><a class="external free" href="http://www.ontologydesignpatterns.org/ont/dul/DUL.owl" rel="nofollow" title="http://www.ontologydesignpatterns.org/ont/dul/DUL.owl">        http://www.ontologydesignpatterns.org/ont/dul/DUL.owl       </a></li> |
|  Has Components:  | <li><a href="Submissions%253AAffectedBy.html" title="Submissions:AffectedBy">        Submissions:AffectedBy       </a></li> |
|  Specialization Of:  |  |
|  Related CPs:  |  |



  





# 

 Elements



_The
 __EEP__ 
 Content OP locally defines the following ontology elements:_ 




# 

 Additional information



# 

 Scenarios




__Scenarios about EEP__ 


 No scenario is added to this Content OP.
 




# 

 Reviews




__Reviews about EEP__ 


 There is no review about this proposal.
This revision (revision ID
 __13498__ 
 ) takes in account the reviews: none
 



 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:EEP&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:EEP&action=evaluation") 





  





# 

 Modeling issues




__Modeling issues about EEP__ 


 There is no Modeling issue related to this proposal.
 




  





# 

 References
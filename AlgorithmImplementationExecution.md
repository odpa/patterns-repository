# 

 Graphical representation



__Diagram__ 





[![Image:AlgorithmImplementationExecution_ver2.png](../images/2/2b/AlgorithmImplementationExecution_ver2.png)](../Image/AlgorithmImplementationExecution_ver2.png "Image:AlgorithmImplementationExecution_ver2.png")





# 

 General description




|  |  |
| --- | --- |
|  Name:  |  AlgorithmImplementationExecution  |
|  Submitted by:  | [AgnieszkaLawrynowicz](../User/AgnieszkaLawrynowicz "User:AgnieszkaLawrynowicz")  , [DiegoEsteves](http://ontologydesignpatterns.org/wiki/index.php?title=User:DiegoEsteves&action=edit&redlink=1 "User:DiegoEsteves (not yet written)")  , [PancePanov](http://ontologydesignpatterns.org/wiki/index.php?title=User:PancePanov&action=edit&redlink=1 "User:PancePanov (not yet written)")  , [SasoDzeroski](http://ontologydesignpatterns.org/wiki/index.php?title=User:SasoDzeroski&action=edit&redlink=1 "User:SasoDzeroski (not yet written)")  , [TommasoSoru](http://ontologydesignpatterns.org/wiki/index.php?title=User:TommasoSoru&action=edit&redlink=1 "User:TommasoSoru (not yet written)")  , [JoaquinVanschoren](http://ontologydesignpatterns.org/wiki/index.php?title=User:JoaquinVanschoren&action=edit&redlink=1 "User:JoaquinVanschoren (not yet written)")  |
|  Also Known As:  |  |
|  Intent:  |  To model algorithm specifications, their implementations and executions, together with parameters of implementations, settings of the parameters for the execution, and inputs the execution consumes (e.g., data) and outputs the execution produces (e.g., models, reports).  |
|  Domains:  | [General](../Community/General "Community:General")  , [Software](../Community/Software "Community:Software")  , [Software Engineering](../Community/Software_Engineering "Community:Software Engineering")  , [Workflow](../Community/Workflow "Community:Workflow")  |
|  Competency Questions:  | <li>       Which algorithm is implemented by this implementation?      </li><li>       What are the implementations of this algorithm?      </li><li>       Which implementation is executed?      </li><li>       What are the parameters of this implementation?      </li><li>       What are the parameter settings of particular parameters in this execution?      </li><li>       What is the input to this implementation execution?      </li><li>       What is the output produced by the this implementation execution?      </li><li>       What algorithm does this execution realize?      </li><li>       What task does this execution achieves?      </li><li>       What is the duration of this execution?      </li><li>       What is the input this task is defined on?      </li> |
|  Solution description:  |  Beloit it is provided the formalization of the pattern in the Web Ontology Language (OWL) in Manchester syntax:  Algorithm SubClassOf InformationEntity  Implementation SubClassOf InformationEntity  Implementation SubClassOf implements some Algorithm  Implementation SubClassOf hasParameter some Parameter  Execution SubClassOf Process  Execution SubClassOf hasInput some ParameterSetting  Execution SubClassOf realizes some Algorithm  Execution SubClassOf achieves some Task  Execution SubClassOf hasDuration some TimeInterval  Parameter SubClassOf InformationEntity  ParameterSetting SubClassOf InformationEntity  ParameterSetting SubClassOf specifiedBy some Parameter  ParameterSetting SubClassOf hasValue some rdfs:Literal  Input SubClassOf InformationEntity  Output SubClassOf InformationEntity  Task SubClassOf InformationEntity  Task SubClassOf definedOn some Input  Top SubClassOf hasInput only Input  Top SubClassOf hasOutput only Output  |
|  Reusable OWL Building Block:  | [https://github.com/ML-Schema/core/blob/master/AlgorithmImplementationExecution.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=https://github.com/ML-Schema/core/blob/master/AlgorithmImplementationExecution.owl&message=OWL building block&from_page_id=4056&update=)  (0)  |
|  Consequences:  |  |
|  Scenarios:  |  Consider a scenario in machine learning (ML) domain. The scenario deals with a machine learning task completion and it is based on an example derived from the OpenML portal ( [http://www.openml.org/](http://www.openml.org/ "http://www.openml.org/")  ).  There is an ML Task `:task29`  which is a supervised classification task defined on the dataset `:credit-a`  . This task is achieved by the Execution `:run100241`  which executes the Implementation `:wekaLogistic`  of the Algorithm `:logisticRegression`  .  The Implementation `:wekaLogistic`  has five hyperparameters (Parameter): `:wekaLogisticC`  , `:wekaLogisticDoNotCheckCapabilities`  , `:wekaLogisticM`  , `:wekaLogisticOutputDebugInfo`  , `:wekaLogisticR`  . The values of two of these hyperparameters are set. The hyper parameter `:wekaLogisticM`  has value set to -1 (expressed via the ParameterSetting `:wekaLogisticMSetting29`  ), and the hyper parameter `:wekaLogisticR`  that has its value set to `"1.0E-8"^^xsd:float`  (expressed via the ParameterSetting `:wekaLogisticRSetting29`  ).  The Execution `:run100241`  has on Input the `:credit-a`  dataset and the parameter settings and its Output is the ML model `:wekaLogisticModel100241`  .  |
|  Known Uses:  | [ML Schema](http://ML%20Schema "http://ML%20Schema")  , [DMOP](http://DMOP "http://DMOP")  , [Function Ontology](http://Function%20Ontology "http://Function%20Ontology")  , [MEX](http://MEX "http://MEX")  , [OBI](http://OBI "http://OBI")  , [OntoDM](http://OntoDM "http://OntoDM")  |
|  Web References:  |  |
|  Other References:  |  |
|  Examples (OWL files):  |  |
|  Extracted From:  |  |
|  Reengineered From:  | <li>       ML Schema      </li><li><a class="external free" href="https://www.w3.org/community/ml-schema/" rel="nofollow" title="https://www.w3.org/community/ml-schema/">        https://www.w3.org/community/ml-schema/       </a></li> |
|  Has Components:  | <li><a href="Submissions%253ATimeInterval.html" title="Submissions:TimeInterval">        Submissions:TimeInterval       </a></li> |
|  Specialization Of:  |  |
|  Related CPs:  | <li><a href="Submissions%253ABasicPlan.html" title="Submissions:BasicPlan">        Submissions:BasicPlan       </a></li><li><a href="Submissions%253ABasicPlanExecution.html" title="Submissions:BasicPlanExecution">        Submissions:BasicPlanExecution       </a></li><li><a href="Submissions%253AParameter.html" title="Submissions:Parameter">        Submissions:Parameter       </a></li> |



  





# 

 Elements



_The
 __AlgorithmImplementationExecution__ 
 Content OP locally defines the following ontology elements:_ 




# 

 Additional information



# 

 Scenarios




__Scenarios about AlgorithmImplementationExecution__ 


 No scenario is added to this Content OP.
 




# 

 Reviews




__Reviews about AlgorithmImplementationExecution__ 


 There is no review about this proposal.
This revision (revision ID
 __12852__ 
 ) takes in account the reviews: none
 



 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:AlgorithmImplementationExecution&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:AlgorithmImplementationExecution&action=evaluation") 





  





# 

 Modeling issues




__Modeling issues about AlgorithmImplementationExecution__ 


 There is no Modeling issue related to this proposal.
 




  





# 

 References
# 

 Graphical representation



__Diagram__ 





[![Image:Reactor-pattern.png](images/4/4b/Reactor-pattern.png)](../Image/Reactor-pattern.png "Image:Reactor-pattern.png")





# 

 General description




|  |  |
| --- | --- |
|  Name:  |  Reactor pattern  |
|  Submitted by:  | [MonikaSolanki](../User/MonikaSolanki "User:MonikaSolanki")  |
|  Also Known As:  |  |
|  Intent:  |  The remit of the reactor pattern is to enable the modelling of reactive processes that consume inputs and produce outputs under specific environmental conditions and on being triggered by certain events.  |
|  Domains:  |  |
|  Competency Questions:  | <li>       1. What are the inputs consumed by a certain process?      </li><li>       2. What environmental conditions need to hold for the process to get activated?      </li><li>       3. What are the outputs produced by the process?      </li><li>       4. Which event triggers a specific process?      </li><li>       5. What is the measurement criteria for a specific parameter?      </li> |
|  Solution description:  |  The reactor pattern provides a building block for the ontological modelling of reactive processes. The pattern can be used across domains in scenarios where a reactor is used to run processes that consume inputs to produce outputs under controlled environmental conditions and when triggered by certain events. As an example, the pattern has been applied to the algal biomass domain to model the reactive process of algae cultivation.  |
|  Reusable OWL Building Block:  | [http://windermere.aston.ac.uk/~monika/ontologies/Reactor.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=http://windermere.aston.ac.uk/~monika/ontologies/Reactor.owl&message=OWL building block&from_page_id=3357&update=)  (863)  |
|  Consequences:  |  The main advantage of this pattern is that its provides ontological  modelling capabilities for the inputs, outputs and environmentalconditions that govern reactive processes across several domains,independent of modelling details of the actual reactor involved. Thiseffectively caters for exposing a black box view of the process, whichis very desirable when querying the model for consumption andproduction logistics of the process.  |
|  Scenarios:  |  As an exemplifier for the reactor pattern, we present a use case fromthe domain of algal biomass. We employ the reactor pattern in anontology OntoMDL. The ontology models a process for algal biomasscultivation. OntoMDL implements the Minimum DescriptiveLanguage(MDL) standard prescribed by the AlgalBiomass Organisation(ABO) for algal operation. The set of descriptivemetrics recommended by MDL as inputs to the process are carbon, water, total infrastructure area, total energy, nutrients, consumables andlabour. Possible outputs from the process are algal constituentproducts, indirect algal products, uncaptured gas emission, liquidwaste output, solid waste output. Some environmental conditions thatmust hold for the algae to be harvested are, (1)The water must be in a temperature range that will support the specific algal species being grown.(2)The pH range for most cultured algal species should be between 7 and 9, with the optimum range being 8.2-8.7.The event that triggers of the algae cultivation is the addition of the source culture to the growing containers or reactors.  |
|  Known Uses:  |  |
|  Web References:  |  |
|  Other References:  |  |
|  Examples (OWL files):  |  |
|  Extracted From:  |  |
|  Reengineered From:  |  |
|  Has Components:  |  |
|  Specialization Of:  |  |
|  Related CPs:  |  |



  





# 

 Elements



_The
 __Reactor pattern__ 
 Content OP locally defines the following ontology elements:_ 





[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__definesCondition__ 
 (owl:ObjectProperty)
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[definesCondition](../Submissions/Reactor_pattern/definesCondition "Submissions:Reactor pattern/definesCondition") 
 page_ 



[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasEnvironemntalCondition__ 
 (owl:ObjectProperty)
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasEnvironemntalCondition](../Submissions/Reactor_pattern/hasEnvironemntalCondition "Submissions:Reactor pattern/hasEnvironemntalCondition") 
 page_ 



[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasInputParameter__ 
 (owl:ObjectProperty)
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasInputParameter](../Submissions/Reactor_pattern/hasInputParameter "Submissions:Reactor pattern/hasInputParameter") 
 page_ 



[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasMeasurement__ 
 (owl:ObjectProperty)
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasMeasurement](../Submissions/Reactor_pattern/hasMeasurement "Submissions:Reactor pattern/hasMeasurement") 
 page_ 



[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasOutputParameter__ 
 (owl:ObjectProperty)
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasOutputParameter](../Submissions/Reactor_pattern/hasOutputParameter "Submissions:Reactor pattern/hasOutputParameter") 
 page_ 



[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasProcessParameter__ 
 (owl:ObjectProperty)
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasProcessParameter](../Submissions/Reactor_pattern/hasProcessParameter "Submissions:Reactor pattern/hasProcessParameter") 
 page_ 



[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__triggeredBy__ 
 (owl:ObjectProperty)
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[triggeredBy](../Submissions/Reactor_pattern/triggeredBy "Submissions:Reactor pattern/triggeredBy") 
 page_ 



[![DatatypeProperty](images/thumb/a/a5/DatatypeProperty.gif/20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif "DatatypeProperty")
__hasDescription__ 
 (owl:DatatypeProperty)
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasDescription](../Submissions/Reactor_pattern/hasDescription "Submissions:Reactor pattern/hasDescription") 
 page_ 



[![Class](images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__EnvironmentalCondition__ 
 (owl:Class) An entity that represents the environmental condition
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[EnvironmentalCondition](../Submissions/Reactor_pattern/EnvironmentalCondition "Submissions:Reactor pattern/EnvironmentalCondition") 
 page_ 



[![Class](images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__Event__ 
 (owl:Class) An entity representing the event that triggers the process
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[Event](../Submissions/Reactor_pattern/Event "Submissions:Reactor pattern/Event") 
 page_ 



[![Class](images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__InputParameter__ 
 (owl:Class) An entity representing the input to a process
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[InputParameter](../Submissions/Reactor_pattern/InputParameter "Submissions:Reactor pattern/InputParameter") 
 page_ 



[![Class](images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__OutputParameter__ 
 (owl:Class) An entity representing the output to a process
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[OutputParameter](Submissions%253AReactor_pattern/OutputParameter.html "Submissions:Reactor pattern/OutputParameter") 
 page_ 



[![Class](images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__Process__ 
 (owl:Class) An entity representing a placeholder for a process.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[Process](../Submissions/Reactor_pattern/Process "Submissions:Reactor pattern/Process") 
 page_ 



[![Class](images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__ProcessParameter__ 
 (owl:Class) An overarching entity representing the parameters defined for the process
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[ProcessParameter](../Submissions/Reactor_pattern/ProcessParameter "Submissions:Reactor pattern/ProcessParameter") 
 page_ 



[![Class](images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__ReactiveProcess__ 
 (owl:Class) An entity representing a reactive process
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[ReactiveProcess](../Submissions/Reactor_pattern/ReactiveProcess "Submissions:Reactor pattern/ReactiveProcess") 
 page_ 


# 

 Additional information



 The Reactor Pattern enables the modelling of processes that consume inputs and produce outputs under specific environmental conditions and on being triggered by certain events. Reactor pattern is a content ontology design pattern and is especially targeted towards modelling reactive processes with a black box view of the process.
 



# 

 Scenarios




__Scenarios about Reactor pattern__ 


 No scenario is added to this Content OP.
 




# 

 Reviews




__Reviews about Reactor pattern__ 



|  Review article  | [Posted on](../Property/CreationDate "Property:CreationDate")  | [About revision (current is 11175)](../Property/ReviewAboutVersion "Property:ReviewAboutVersion")  |
| --- | --- | --- |
| [AlessandroAdamou about Reactor pattern](../Reviews/AlessandroAdamou_about_Reactor_pattern "Reviews:AlessandroAdamou about Reactor pattern")  |  2456164  24 August 2012  |  11155  11,155  |
| [AndreaNuzzolese about Reactor pattern](../Reviews/AndreaNuzzolese_about_Reactor_pattern "Reviews:AndreaNuzzolese about Reactor pattern")  |  2456169  29 August 2012  |  11175  11,175  |
| [VojtechSvatek about Reactor pattern](../Reviews/VojtechSvatek_about_Reactor_pattern "Reviews:VojtechSvatek about Reactor pattern")  |  2456171  31 August 2012  |  11175  11,175  |
| [IonelVirgilPop about Reactor pattern](../Community/IonelVirgilPop_about_Reactor_pattern "Community:IonelVirgilPop about Reactor pattern")  |  2456164  24 August 2012  |  11175  11,175  |



 This revision (revision ID
 __11175__ 
 ) takes in account the reviews: none
 



 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Reactor_pattern&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Reactor_pattern&action=evaluation") 





  





# 

 Modeling issues




__Modeling issues about Reactor pattern__ 


 There is no Modeling issue related to this proposal.
 




  





# 

 References



  






|  |  Submission to event [WOP:2012](../WOP/2012 "WOP:2012")  |
| --- | --- |
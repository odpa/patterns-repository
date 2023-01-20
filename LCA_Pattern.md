# 

 Graphical representation



__Diagram__ 





[![Image:LCAFlow.png](public/images/4/4b/LCAFlow.png)](../Image/LCAFlow.png "Image:LCAFlow.png")





# 

 General description




|  |  |
| --- | --- |
|  Name:  |  LCA Pattern  |
|  Submitted by:  | [YingjieHu](../User/YingjieHu "User:YingjieHu")  |
|  Also Known As:  |  |
|  Intent:  |  Life Cycle Assessment (LCA) studies the environmental impact of products taking into account their entire life-span and production chain. This ontology design pattern specifies key aspects of LCA/LCI data models, namely the notions of flows, activities, agents, and products, as well as their properties.  |
|  Domains:  |  |
|  Competency Questions:  | <li>       Is a certain flow a reference product?      </li><li>       What is the location of an activity?      </li> |
|  Solution description:  |  The pattern is intended to foster interoperability between existing data models, specifications, and software, and thereby act as a joint building block for the rapidly increasing interest in semantics within the broader LCA community.  |
|  Reusable OWL Building Block:  | [http://descartes-core.org/ontologies/lca/1.0/LCAPattern.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=http://descartes-core.org/ontologies/lca/1.0/LCAPattern.owl&message=OWL building block&from_page_id=3924&update=)  (623)  |
|  Consequences:  |  This ontology design pattern does neither cover the process of carrying out life cycle assessments, e.g., how data is gathered or how so-called system boundaries are defined, nor does it provide the variety of spatial, temporal, and thematic attributes used to scope inventory items, e.g., to express the fact that coal extraction may have varying impacts depending on the geographic region and used technology.  |
|  Scenarios:  |  The proposed ontology design pattern 1 is meant to form a common core for the semantic description of key elements of life cycle inventories. A solar panel example: assessing the impacts of operating a solar array goes beyond the pure manufacturing and assembly of the photovoltaic modules. It also includes transportation emissions, installation emissions, operation emissions, and the final disposal emissions. Such assessment first requires the gathering of all relevant data from different sources into a so-called Life Cycle Inventory (LCI), followed by the actual assessment of the environmental impacts based on the gathered data, used models, and the literature. Understanding the complex impact of products is crucial for arriving at, and maintaining, a sustainable world where human needs are met without causing harm to the environment or impacting the ability of future generations to meet their needs.  |
|  Known Uses:  |  |
|  Web References:  |  |
|  Other References:  |  |
|  Examples (OWL files):  |  |
|  Extracted From:  |  |
|  Reengineered From:  |  |
|  Has Components:  |  |
|  Specialization Of:  |  |
|  Related CPs:  | <li><a class="new" href="http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:This_pattern_can_be_linked_to_the_Property_pattern_to_add_property_information.&amp;action=edit&amp;redlink=1" title="Submissions:This pattern can be linked to the Property pattern to add property information. (not yet written)">        Submissions:This pattern can be linked to the Property pattern to add property information.       </a></li> |



  





# 

 Elements



_The
 __LCA Pattern__ 
 Content OP locally defines the following ontology elements:_ 





[![ObjectProperty](public/images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasCompartment__ 
 (owl:ObjectProperty)
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasCompartment](../Submissions/LCA_Pattern/hasCompartment "Submissions:LCA Pattern/hasCompartment") 
 page_ 



[![ObjectProperty](public/images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasLocation__ 
 (owl:ObjectProperty)
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasLocation](../Submissions/LCA_Pattern/hasLocation "Submissions:LCA Pattern/hasLocation") 
 page_ 



[![ObjectProperty](public/images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasProperty__ 
 (owl:ObjectProperty)
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasProperty](../Submissions/LCA_Pattern/hasProperty "Submissions:LCA Pattern/hasProperty") 
 page_ 



[![ObjectProperty](public/images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasTemporalExtent__ 
 (owl:ObjectProperty)
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasTemporalExtent](../Submissions/LCA_Pattern/hasTemporalExtent "Submissions:LCA Pattern/hasTemporalExtent") 
 page_ 



[![ObjectProperty](public/images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__isInputOf__ 
 (owl:ObjectProperty)
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[isInputOf](../Submissions/LCA_Pattern/isInputOf "Submissions:LCA Pattern/isInputOf") 
 page_ 



[![ObjectProperty](public/images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__isOutputOf__ 
 (owl:ObjectProperty)
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[isOutputOf](../Submissions/LCA_Pattern/isOutputOf "Submissions:LCA Pattern/isOutputOf") 
 page_ 



[![ObjectProperty](public/images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__performs__ 
 (owl:ObjectProperty)
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[performs](../Submissions/LCA_Pattern/performs "Submissions:LCA Pattern/performs") 
 page_ 



[![ObjectProperty](public/images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__playsRoleOf__ 
 (owl:ObjectProperty)
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[playsRoleOf](../Submissions/LCA_Pattern/playsRoleOf "Submissions:LCA Pattern/playsRoleOf") 
 page_ 



[![Class](public/images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__Activity__ 
 (owl:Class) Each activity is performed by at least one agent such as an coal power plant that performs the generation of electricity.
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[Activity](../Submissions/LCA_Pattern/Activity "Submissions:LCA Pattern/Activity") 
 page_ 



[![Class](public/images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__Agent__ 
 (owl:Class)
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[Agent](../Submissions/LCA_Pattern/Agent "Submissions:LCA Pattern/Agent") 
 page_ 



[![Class](public/images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__Compartment__ 
 (owl:Class)
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[Compartment](../Submissions/LCA_Pattern/Compartment "Submissions:LCA Pattern/Compartment") 
 page_ 



[![Class](public/images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__ElementaryFlow__ 
 (owl:Class) It describes material or energy that is entering the system from the environment without any previous transformation by humans or is leaving the system by being released into the environment without further human transformation
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[ElementaryFlow](../Submissions/LCA_Pattern/ElementaryFlow "Submissions:LCA Pattern/ElementaryFlow") 
 page_ 



[![Class](public/images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__Flow__ 
 (owl:Class) Flows are streams of material or energy that can act as the inputs and outputs of activities.
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[Flow](../Submissions/LCA_Pattern/Flow "Submissions:LCA Pattern/Flow") 
 page_ 



[![Class](public/images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__IntermediateFlow__ 
 (owl:Class) Intermediate flows occur between processes of the studied system.
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[IntermediateFlow](../Submissions/LCA_Pattern/IntermediateFlow "Submissions:LCA Pattern/IntermediateFlow") 
 page_ 



[![Class](public/images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__Location__ 
 (owl:Class)
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[Location](../Submissions/LCA_Pattern/Location "Submissions:LCA Pattern/Location") 
 page_ 



[![Class](public/images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__Product__ 
 (owl:Class)
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[Product](../Submissions/LCA_Pattern/Product "Submissions:LCA Pattern/Product") 
 page_ 



[![Class](public/images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__Property__ 
 (owl:Class)
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[Property](../Submissions/LCA_Pattern/Property "Submissions:LCA Pattern/Property") 
 page_ 



[![Class](public/images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__ReferencedProduct__ 
 (owl:Class)
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[ReferencedProduct](../Submissions/LCA_Pattern/ReferencedProduct "Submissions:LCA Pattern/ReferencedProduct") 
 page_ 



[![Class](public/images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__Time__ 
 (owl:Class)
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[Time](../Submissions/LCA_Pattern/Time "Submissions:LCA Pattern/Time") 
 page_ 



__air__ 
 (owl:NamedIndividual)
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[air](../Submissions/LCA_Pattern/air "Submissions:LCA Pattern/air") 
 page_ 



__soil__ 
 (owl:NamedIndividual)
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[soil](../Submissions/LCA_Pattern/soil "Submissions:LCA Pattern/soil") 
 page_ 



__water__ 
 (owl:NamedIndividual)
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[water](../Submissions/LCA_Pattern/water "Submissions:LCA Pattern/water") 
 page_ 


# 

 Additional information



 In a nutshell, estimating the environmental impact of a certain product requires an understanding of all impacts accumulated during the creation, lifetime, and decommissioning of said product. With respect to the solar panel example introduced in our related paper, the creation of the solar arrays requires multiple activities such as the transportation of resources, the generation of electric power by a coal power plant necessary to manufacture certain parts of the panels, or the disposal of polluted sludge accumulated during the production. In other words, the Eco-efficiency of solar panels depends on the activities involved in all stages of their life-cycle.
 



# 

 Scenarios




__Scenarios about LCA Pattern__ 


 No scenario is added to this Content OP.
 




# 

 Reviews




__Reviews about LCA Pattern__ 


 There is no review about this proposal.
This revision (revision ID
 __12311__ 
 ) takes in account the reviews: none
 



 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:LCA_Pattern&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:LCA_Pattern&action=evaluation") 





  





# 

 Modeling issues




__Modeling issues about LCA Pattern__ 


 There is no Modeling issue related to this proposal.
 




  





# 

 References
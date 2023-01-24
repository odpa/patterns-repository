# 

 Graphical representation



__Diagram__ 





[![Image:Resourceabundanceobservation.jpg](../images/7/7a/Resourceabundanceobservation.jpg)](../Image/Resourceabundanceobservation.jpg "Image:Resourceabundanceobservation.jpg")





# 

 General description




|  |  |
| --- | --- |
|  Name:  |  ResourceAbundanceObservation  |
|  Submitted by:  | [AldoGangemi](../User/AldoGangemi "User:AldoGangemi")  , [EvaBlomqvist](../User/EvaBlomqvist "User:EvaBlomqvist")  |
|  Also Known As:  |  |
|  Intent:  |  The intent of the pattern is to be able to represent observations of aquatic resources, where the observations have been made a certain year and has certain other parameters.  |
|  Domains:  | [Fishery](../Community/Fishery "Community:Fishery")  |
|  Competency Questions:  | <li>       What resource is observed? For what year and at what abundance level?      </li> |
|  Solution description:  |  ...  |
|  Reusable OWL Building Block:  | [http://www.ontologydesignpatterns.org/cp/owl/fsdas/resourceabundanceobservation.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=http://www.ontologydesignpatterns.org/cp/owl/fsdas/resourceabundanceobservation.owl&message=OWL building block&from_page_id=1187&update=)  (617)  |
|  Consequences:  |  The patterns states that for each instance of the resource observation all parameters exist, this does not however mean that they are necessarily present in the knowledge base. Any dependencies between parameters have not been taken intor account, there are no formal restrictions on the combination possible. The parameters are intended to have a fixed set of values (to be defined as nominals) but this is not explicit in the pattern.  |
|  Scenarios:  |  Give me the resource observations for the year 2004 Give me the resource observations where the abundance level is 'Low abundance'  |
|  Known Uses:  |  |
|  Web References:  |  |
|  Other References:  |  |
|  Examples (OWL files):  |  |
|  Extracted From:  |  |
|  Reengineered From:  |  |
|  Has Components:  |  |
|  Specialization Of:  | <li><a href="Submissions%253AObservation.html" title="Submissions:Observation">        Submissions:Observation       </a></li> |
|  Related CPs:  |  |



  





# 

 Elements



_The
 __ResourceAbundanceObservation__ 
 Content OP locally defines the following ontology elements:_ 





[![Class](../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__AbundanceLevel__ 
 (owl:Class)
 
[![](../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[AbundanceLevel](../Submissions/ResourceAbundanceObservation/AbundanceLevel "Submissions:ResourceAbundanceObservation/AbundanceLevel") 
 page_ 



[![Class](../../images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__ResourceAbundanceObservation__ 
 (owl:Class) An observation of a resource characterised by different parameters.
 
[![](../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[ResourceAbundanceObservation](../Submissions/ResourceAbundanceObservation/ResourceAbundanceObservation "Submissions:ResourceAbundanceObservation/ResourceAbundanceObservation") 
 page_ 



[![DatatypeProperty](../images/thumb/a/a5/DatatypeProperty.gif/20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif "DatatypeProperty")
__hasReferenceYear__ 
 (owl:DatatypeProperty)
 
[![](../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasReferenceYear](../Submissions/ResourceAbundanceObservation/hasReferenceYear "Submissions:ResourceAbundanceObservation/hasReferenceYear") 
 page_ 



[![ObjectProperty](../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasAbundanceLevel__ 
 (owl:ObjectProperty)
 
[![](../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasAbundanceLevel](../Submissions/ResourceAbundanceObservation/hasAbundanceLevel "Submissions:ResourceAbundanceObservation/hasAbundanceLevel") 
 page_ 



[![ObjectProperty](../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasResource__ 
 (owl:ObjectProperty)
 
[![](../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasResource](../Submissions/ResourceAbundanceObservation/hasResource "Submissions:ResourceAbundanceObservation/hasResource") 
 page_ 



[![ObjectProperty](../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__isResourceOf__ 
 (owl:ObjectProperty)
 
[![](../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[isResourceOf](../Submissions/ResourceAbundanceObservation/isResourceOf "Submissions:ResourceAbundanceObservation/isResourceOf") 
 page_ 



[![ObjectProperty](../../../../images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__isAbundanceLevelOf__ 
 (owl:ObjectProperty)
 
[![](../../../../../../../images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[isAbundanceLevelOf](../Submissions/ResourceAbundanceObservation/isAbundanceLevelOf "Submissions:ResourceAbundanceObservation/isAbundanceLevelOf") 
 page_ 


# 

 Additional information



 (type):
 [http://www.w3.org/2002/07/owl#Ontology](http://www.w3.org/2002/07/owl#Ontology "http://www.w3.org/2002/07/owl#Ontology") 




 (hasUnitTest): SELECT ?x WHERE {?x a :AquaticResourceObservation.  ?x :hasReferenceYear
 



# 

 Scenarios




__Scenarios about ResourceAbundanceObservation__ 


 No scenario is added to this Content OP.
 




# 

 Reviews




__Reviews about ResourceAbundanceObservation__ 


 There is no review about this proposal.
This revision (revision ID
 __9117__ 
 ) takes in account the reviews: none
 



 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:ResourceAbundanceObservation&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:ResourceAbundanceObservation&action=evaluation") 





  





# 

 Modeling issues




__Modeling issues about ResourceAbundanceObservation__ 


 There is no Modeling issue related to this proposal.
 




  





# 

 References
# 

 Graphical representation



__Diagram__ 





[![Image:Vesselspecies2.jpg](./Vesselspecies2.jpg)](../Image/Vesselspecies2.jpg.md "Image:Vesselspecies2.jpg")





# 

 General description




|  |  |
| --- | --- |
|  Name:  |  VesselSpecies  |
|  Submitted by:  | [AlessandroAdamou](../User/AlessandroAdamou.md "User:AlessandroAdamou")  |
|  Also Known As:  |  |
|  Intent:  |  to provide a direct relation between aquatic species and vessels that are able to catch them, regardless of the fishing gear used.  |
|  Domains:  | [Fishery](../Community/Fishery.md "Community:Fishery")  |
|  Competency Questions:  | <li>       what vessel types can catch what species? (provided that species are caught by geartypes are used by vessel types)      </li> |
|  Solution description:  |  ---  |
|  Reusable OWL Building Block:  | [http://www.ontologydesignpatterns.org/cp/owl/fsdas/vesselspecies.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=http://www.ontologydesignpatterns.org/cp/owl/fsdas/vesselspecies.owl&message=OWL building block&from_page_id=925&update=)  (665)  |
|  Consequences:  |  This pattern should be used in scenarios where a VesselType can be deemed suitable for catching some AquaticSpecies for reasons other than mounting some fishing gear of a suitable GearType. It is strictly related to the gearspecies pattern, in that it uses the catchesSpecies and isCaught property pair to define this behaviour. For the sake of reuse, no domain is declared for catchesSpecies, appropriate restrictions having beed applied instead.  |
|  Scenarios:  |  give me the species caught using 'gillneters'  |
|  Known Uses:  |  |
|  Web References:  |  |
|  Other References:  |  |
|  Examples (OWL files):  |  |
|  Extracted From:  |  |
|  Reengineered From:  |  |
|  Has Components:  | <li><a href="../GearSpecies/GearSpecies.md" title="Submissions:GearSpecies">        Submissions:GearSpecies       </a></li><li><a href="../GearVessel/GearVessel.md" title="Submissions:GearVessel">        Submissions:GearVessel       </a></li> |
|  Specialization Of:  |  |
|  Related CPs:  | <li><a href="../GearSpecies/GearSpecies.md" title="Submissions:GearSpecies">        Submissions:GearSpecies       </a></li> |



  





# 

 Elements



_The
 __VesselSpecies__ 
 Content OP locally defines the following ontology elements:_ 





[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__isCaughtBy__ 
 (owl:ObjectProperty) Actually a composed property: this needs either a property chain, a SPARQL query, or a SWRL rule to gather a value. E.g. in SPARQL:
 
  





 CONSTRUCT {?x :catchesSpecies ?y . ?y isCaughtBy ?x}
 



 WHERE {
 



 ?x gearvessel:usesGearType ?z .
 



 ?z gearspecies:catchesSpecies ?y
 



 }
 



[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[isCaughtBy](./GearSpecies/isCaughtBy.md "Submissions:VesselSpecies/isCaughtBy") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__catchesSpecies__ 
 (owl:ObjectProperty) Actually a composed property: this needs either a property chain, a SPARQL query, or a SWRL rule to gather a value. E.g. in SPARQL:
 
  





 CONSTRUCT {?x :catchesSpecies ?y . ?y isCaughtBy ?x}
 



 WHERE {
 



 ?x gearvessel:usesGearType ?z .
 



 ?z gearspecies:catchesSpecies ?y
 



 }
 



[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[catchesSpecies](./GearSpecies/catchesSpecies.md "Submissions:VesselSpecies/catchesSpecies") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__isCaughtByVesselType__ 
 (owl:ObjectProperty)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[isCaughtByVesselType](./VesselSpecies/isCaughtByVesselType.md "Submissions:VesselSpecies/isCaughtByVesselType") 
 page_ 


# 

 Additional information



 This pattern composes gearvessel.owl and gearspecies.owl.
This must be inferred compositionally, and requires either more sophisticated logical pattern, like 'property chain', available in OWL2 (but not in OWL1), or a complex reasoning pattern, like 'DL classifier+SPARQL', or 'DL classifier+SWRL rule firing'.
 



 (type):
 [http://www.w3.org/2002/07/owl#Ontology](http://www.w3.org/2002/07/owl#Ontology "http://www.w3.org/2002/07/owl#Ontology") 




 (versionInfo): Created by Alessandro Adamou
 



 (comment): This pattern composes gearvessel.owl and gearspecies.owl.
This must be inferred compositionally, and requires either more sophisticated logical pattern, like 'property chain', available in OWL2 (but not in OWL1), or a complex reasoning pattern, like 'DL classifier+SPARQL', or 'DL classifier+SWRL rule firing'.
 



 (relatedCPs):
 [http://www.ontologydesignpatterns.org/cp/owl/fsdas/gearspecies.owl](http://www.ontologydesignpatterns.org/cp/owl/fsdas/gearspecies.owl "http://www.ontologydesignpatterns.org/cp/owl/fsdas/gearspecies.owl") 




 (hasComponent): <
 [http://www.ontologydesignpatterns.org/cp/owl/fsdas/gearspecies.owl](http://www.ontologydesignpatterns.org/cp/owl/fsdas/gearspecies.owl "http://www.ontologydesignpatterns.org/cp/owl/fsdas/gearspecies.owl") 
 >
 



 (imports):
 [http://www.ontologydesignpatterns.org/schemas/cpannotationschema.owl](http://www.ontologydesignpatterns.org/schemas/cpannotationschema.owl "http://www.ontologydesignpatterns.org/schemas/cpannotationschema.owl") 




 (imports):
 [http://www.ontologydesignpatterns.org/cp/owl/fsdas/gearspecies.owl](http://www.ontologydesignpatterns.org/cp/owl/fsdas/gearspecies.owl "http://www.ontologydesignpatterns.org/cp/owl/fsdas/gearspecies.owl") 




 (hasComponent): <
 [http://www.ontologydesignpatterns.org/cp/owl/fsdas/gearvessel.owl](http://www.ontologydesignpatterns.org/cp/owl/fsdas/gearvessel.owl "http://www.ontologydesignpatterns.org/cp/owl/fsdas/gearvessel.owl") 
 >
 



 (imports):
 [http://www.ontologydesignpatterns.org/cp/owl/fsdas/gearvessel.owl](http://www.ontologydesignpatterns.org/cp/owl/fsdas/gearvessel.owl "http://www.ontologydesignpatterns.org/cp/owl/fsdas/gearvessel.owl") 




 (versionInfo): 1.1
 



# 

 Scenarios




__Scenarios about VesselSpecies__ 


 No scenario is added to this Content OP.
 




# 

 Reviews




__Reviews about VesselSpecies__ 



|  Review article  | [Posted on](../Property/CreationDate.md "Property:CreationDate")  | [About revision (current is 9141)](../Property/ReviewAboutVersion.md "Property:ReviewAboutVersion")  |
| --- | --- | --- |
| [AldoGangemi about VesselSpecies](../Reviews/AldoGangemi_about_VesselSpecies.md "Reviews:AldoGangemi about VesselSpecies")  |  2454908  17 March 2009  |  3686  3,686  |



 This revision (revision ID
 __9141__ 
 ) takes in account the reviews:
 [AldoGangemi about VesselSpecies](../Reviews/AldoGangemi_about_VesselSpecies.md "Reviews:AldoGangemi about VesselSpecies") 




 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:VesselSpecies&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:VesselSpecies&action=evaluation") 





  





# 

 Modeling issues




__Modeling issues about VesselSpecies__ 


 There is no Modeling issue related to this proposal.
 




  





# 

 References
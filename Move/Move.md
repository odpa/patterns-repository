# 

 Graphical representation



__Diagram__ 
_(this article has no graphical representation)_ 




# 

 General description




|  |  |
| --- | --- |
|  Name:  |  Move  |
|  Submitted by:  | [AldoGangemi](../User/AldoGangemi.md "User:AldoGangemi")  |
|  Also Known As:  |  |
|  Intent:  |  --  |
|  Domains:  |  |
|  Competency Questions:  |  |
|  Solution description:  |  --  |
|  Reusable OWL Building Block:  | [http://www.ontologydesignpatterns.org/cp/owl/move.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=http://www.ontologydesignpatterns.org/cp/owl/move.owl&message=OWL building block&from_page_id=2303&update=)  (673)  |
|  Consequences:  |  |
|  Scenarios:  |  |
|  Known Uses:  |  |
|  Web References:  |  |
|  Other References:  |  |
|  Examples (OWL files):  |  |
|  Extracted From:  | <li><a class="external free" href="http://cidoc.ics.forth.gr/cidoc_v4.2.owl" rel="nofollow" title="http://cidoc.ics.forth.gr/cidoc_v4.2.owl">        http://cidoc.ics.forth.gr/cidoc_v4.2.owl       </a></li> |
|  Reengineered From:  | <li><a class="external free" href="http://cidoc.ics.forth.gr/cidoc_v4.2.owl" rel="nofollow" title="http://cidoc.ics.forth.gr/cidoc_v4.2.owl">        http://cidoc.ics.forth.gr/cidoc_v4.2.owl       </a></li> |
|  Has Components:  |  |
|  Specialization Of:  |  |
|  Related CPs:  |  |



  





# 

 Elements



_The
 __Move__ 
 Content OP locally defines the following ontology elements:_ 





[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__consistsOf__ 
 (owl:ObjectProperty) This property describes the decomposition of an instance of Move into discrete, subsidiary move.
 
  





 The sub-moves into which the move is decomposed form a logical whole, although the entire picture may not be completely known, and the sub-moves are constitutive of the general move.
 



[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[consistsOf](./Move/consistsOf.md "Submissions:Move/consistsOf") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__formsPartOf__ 
 (owl:ObjectProperty)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[formsPartOf](./Move/formsPartOf.md "Submissions:Move/formsPartOf") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__moved__ 
 (owl:ObjectProperty) This property identifies the Physical Object that is moved during a move event.
 
  





 The property implies the object's passive participation. For example, Monet's painting "Impression sunrise" was moved for the first Impressionist exhibition in 1874.
 



 In reality, a move must concern at least one object.
 



[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[moved](./Move/moved.md "Submissions:Move/moved") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__movedBy__ 
 (owl:ObjectProperty)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[movedBy](./Move/movedBy.md "Submissions:Move/movedBy") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__movedFrom__ 
 (owl:ObjectProperty) This property identifies the starting Place of an Move.
 
  





 A move will be linked to an origin, such as the move of an artefact from storage to display. A move may be linked to many origins. In this case the move describes the picking up of a set of objects. The area of the move includes the origin, route and destination.
 



[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[movedFrom](./Move/movedFrom.md "Submissions:Move/movedFrom") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__movedTo__ 
 (owl:ObjectProperty) This property identifies the destination of a Move.
 
  





 A move will be linked to a destination, such as the move of an artefact from storage to display. A move may be linked to many terminal instances of E53 Places. In this case the move describes a distribution of a set of objects. The area of the move includes the origin, route and destination.
 



[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[movedTo](./Move/movedTo.md "Submissions:Move/movedTo") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__tookPlaceAt__ 
 (owl:ObjectProperty) This property describes the spatial location of an instance of a Move.
 
  





 The related Place should be seen as an approximation of the geographical area within which the phenomena that characterise the move in question occurred. took place at (witnessed) does not convey any meaning other than spatial positioning (generally on the surface of the earth).
 



[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[tookPlaceAt](./Move/tookPlaceAt.md "Submissions:Move/tookPlaceAt") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__wasDestinationOf__ 
 (owl:ObjectProperty)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[wasDestinationOf](./Move/wasDestinationOf.md "Submissions:Move/wasDestinationOf") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__wasOriginOf__ 
 (owl:ObjectProperty)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[wasOriginOf](./Move/wasOriginOf.md "Submissions:Move/wasOriginOf") 
 page_ 



[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty")
__witnessed__ 
 (owl:ObjectProperty)
 
[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[witnessed](./Move/witnessed.md "Submissions:Move/witnessed") 
 page_ 



[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__Move__ 
 (owl:Class) This class comprises changes of the physical location of the instances of Physical Object.
 
  





 Note, that the class Move inherits the property 'took place at' (witnessed): Place. This property should be used to describe the trajectory or a larger area within which a move takes place, whereas the properties moved to (was destination of), moved from (was origin of) describe the start and end points only. Moves may also be documented to consistsOf other moves (via consistsOf (formsPartOf)), in order to describe intermediate stages on a trajectory. In that case, start and end points of the partial moves should match appropriately between each other and with the overall event. {@en}
 



[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[Move](./Move.md "Submissions:Move/Move") 
 page_ 



[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__PhysicalObject__ 
 (owl:Class) This class comprises items of a material nature that are units for documentation and have physical boundaries that separate them completely in an objective way from other objects.
 
  





 The class also includes all aggregates of objects made for functional purposes of whatever kind, independent of physical coherence, such as a set of chessmen. Typically, instances of E19 Physical Object can be moved (if not too heavy).
 



  





 In some contexts, such objects, except for aggregates, are also called "bona fide objects" (Smith and Varzi, 2000, pp.401-420), i.e. naturally defined objects.
 



  





 The decision as to what is documented as a complete item, rather than by its parts or components, may be a purely administrative decision or may be a result of the order in which the item was acquired.
 



[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[PhysicalObject](./Move/PhysicalObject.md "Submissions:Move/PhysicalObject") 
 page_ 



[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class")
__Place__ 
 (owl:Class) This class comprises extents in space, in particular on the surface of the earth, in the pure sense of physics: independent from temporal phenomena and matter. The instances of E53 Place are usually determined by reference to the position of "immobile" objects such as buildings, cities, mountains, rivers, or dedicated geodetic marks. A Place can be determined by combining a frame of reference and a location with respect to this frame. It may be identified by one or more instances of E44 Place Appellation. It is sometimes argued that instances of E53 Place are best identified by global coordinates or absolute reference systems. However, relative references are often more relevant in the context of cultural documentation and tend to be more precise. In particular, we are often interested in position in relation to large, mobile objects, such as ships. For example, the Place at which Nelson died is known with reference to a large mobile object, H.M.S Victory. A resolution of this Place in terms of absolute coordinates would require knowledge of the movements of the vessel and the precise time of death, either of which may be revised, and the result would lack historical and cultural relevance.
 
 Any object can serve as a frame of reference for E53 Place determination. The model foresees the notion of a "section" of an E19 Physical Object as a valid E53 Place determination. {@en}
 



[![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif")
_[Place](../Place/Place.md "Submissions:Move/Place") 
 page_ 


# 

 Additional information



 The move content ontology design pattern. This CP represents the action of moving a physical object from a place to another. The move CP is extracted from the CIDOC ontology.
 



# 

 Scenarios




__Scenarios about Move__ 


 No scenario is added to this Content OP.
 




# 

 Reviews




__Reviews about Move__ 


 There is no review about this proposal.
This revision (revision ID
 __9103__ 
 ) takes in account the reviews: none
 



 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Move&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Move&action=evaluation") 





  





# 

 Modeling issues




__Modeling issues about Move__ 


 There is no Modeling issue related to this proposal.
 




  





# 

 References
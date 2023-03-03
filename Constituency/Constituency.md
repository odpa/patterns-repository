#  Graphical representation


__Diagram__




[![Image:constituency.jpg](./Constituency.jpg)](../Image/Constituency.jpg.md "Image:constituency.jpg")




#  General description




|  |  |
| --- | --- |
|  Name: |  constituency |
|  Submitted by: | [ValentinaPresutti](../User/ValentinaPresutti.md "User:ValentinaPresutti") |
|  Also Known As: |  |
|  Intent: |  To represent the constituents of a layered structure. |
|  Domains: | [Parts and Collections](../Community/Parts_and_Collections.md "Community:Parts and Collections") |
|  Competency Questions: | <li> Which are the constituents of this entity?</li><li> What does this entity is constituent of?</li> |
|  Solution description: |  - |
|  Reusable OWL Building Block: | [http://www.ontologydesignpatterns.org/cp/owl/constituency.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=http://www.ontologydesignpatterns.org/cp/owl/constituency.owl&message=OWL building block&from_page_id=276&update=) (732) |
|  Consequences: |  A desirable advantage of this CP is that we are able to talk e.g. of physical constituents ofnon-physical objects (e.g. systems), while this is typically impossible in terms of parts. This Content OP has to be distinguished from  [part of](../PartOf/PartOf.md "Submissions:PartOf"),  [collection entity](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:CollectionEntiy&action=edit&redlink=1 "Submissions:CollectionEntiy (not yet written)"), and  [componency](../Componency/Componency.md "Submissions:Componency") Content OPs. |
|  Scenarios: |  Different types of wood constitute this table. |
|  Known Uses: |  |
|  Web References: |  |
|  Other References: |  |
|  Examples (OWL files): |  |
|  Extracted From: | <li><a class="external free" href="http://www.loa-cnr.it/ontologies/DUL.owl" rel="nofollow" title="http://www.loa-cnr.it/ontologies/DUL.owl">http://www.loa-cnr.it/ontologies/DUL.owl</a></li> |
|  Reengineered From: |  |
|  Has Components: |  |
|  Specialization Of: |  |
|  Related CPs: |  |


  




#  Elements


_The __Constituency__ Content OP locally defines the following ontology elements:_




[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __Entity__ (owl:Class) Anything: real, possible, or imaginary, which some modeller wants to talk about for some purpose. 



 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[Entity](../CollectionEntity/CollectionEntity.md "Submissions:Constituency/Entity") page_

[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasConstituent__ (owl:ObjectProperty) Constituency depends on some layering of the world described by the ontology. 
For example, scientiﬁc granularity (e.g. body-organ-tissue-cell) or ontological 'strata' (e.g. social-mental-biological-physical) are typical layerings. Intuitively, a constituent is a part belonging to a lower 
layer. Since layering is actually a partition of the world described by the ontology, constituents are not properly classiﬁed as parts, although this kindship can be intuitive for common sense. Example of constituents include the wood pieces constituting a table, the persons constituting a social system, the 
molecules constituting a person, the atoms constituting a river, etc. In all these examples, we notice a typical discontinuity between the constituted and the constituent object: e.g. a table is conceptualized at a functional layer, while wood pieces are conceptualized at a material layer, a social system is 
conceptualized at a different layer from the persons that constitute it, a person is conceptualized at a different layer from the molecules that constitute them, and a river is conceptualized at a different layer from the atoms that constitute it. The object property  [isConstituentOf](./Constituency/isConstituentOf.md "Submissions:Constituency/isConstituentOf") is its inverse. 



 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasConstituent](./Constituency/hasConstituent.md "Submissions:Constituency/hasConstituent") page_

[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __isConstituentOf__ (owl:ObjectProperty) The inverse of the  [hasConstituent](./Constituency/hasConstituent.md "Submissions:Constituency/hasConstituent") object property. 



 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[isConstituentOf](./Constituency/isConstituentOf.md "Submissions:Constituency/isConstituentOf") page_
#  Additional information


#  Scenarios



__Scenarios about Constituency__
No scenario is added to this Content OP.




#  Reviews



__Reviews about Constituency__
There is no review about this proposal.
This revision (revision ID __9080__) takes in account the reviews: none


Other info at [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Constituency&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Constituency&action=evaluation")




  




#  Modeling issues



__Modeling issues about Constituency__
There is no Modeling issue related to this proposal.




  




#  References
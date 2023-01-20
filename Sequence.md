# 

 Graphical representation



__Diagram__ 





[![Image:Sequence.png](public/images/b/b2/Sequence.png)](../Image/Sequence.png "Image:Sequence.png")





# 

 General description




|  |  |
| --- | --- |
|  Name:  |  Sequence  |
|  Submitted by:  | [AldoGangemi](../User/AldoGangemi "User:AldoGangemi")  |
|  Also Known As:  |  |
|  Intent:  |  To represent sequence schemas. It defines the notion of transitive and intransitive precedence and their inverses.  It can then be used between tasks, processes, time intervals, spatially locate objects, situations, etc.  |
|  Domains:  | [General](../Community/General "Community:General")  , [Organization](../Community/Organization "Community:Organization")  , [Workflow](../Community/Workflow "Community:Workflow")  , [Time](../Community/Time "Community:Time")  |
|  Competency Questions:  | <li>       What is before what?      </li><li>       What's next?      </li><li>       What's immediately following this?      </li> |
|  Solution description:  |  This pattern is a basic one; it represents the 'path' cognitive schema, which underlies many different conceptualizations: spatial paths, time lines, event sequences, organizational hierarchies, graph paths, etc.  Sequence pattern reuses the logical pattern [Transitive reduction](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:TransitiveReduction&action=edit&redlink=1 "Submissions:TransitiveReduction (not yet written)")  , in order to represent both transitive and non-transitive precedence relations.  |
|  Reusable OWL Building Block:  | [http://ontologydesignpatterns.org/cp/owl/sequence.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=http://ontologydesignpatterns.org/cp/owl/sequence.owl&message=OWL building block&from_page_id=756&update=)  (910)  |
|  Consequences:  |  We can represent and reason over transitive or intransitive sequences of any kind. However, since coreference cannot be expressed in OWL, it is not possible to represent and reason over loops and other sequences involving coreference.  |
|  Scenarios:  |  |
|  Known Uses:  |  |
|  Web References:  |  |
|  Other References:  |  |
|  Examples (OWL files):  |  |
|  Extracted From:  | <li><a class="external free" href="http://www.ontologydesignpatterns.org/ont/dul/DUL.owl" rel="nofollow" title="http://www.ontologydesignpatterns.org/ont/dul/DUL.owl">        http://www.ontologydesignpatterns.org/ont/dul/DUL.owl       </a></li> |
|  Reengineered From:  |  |
|  Has Components:  |  |
|  Specialization Of:  |  |
|  Related CPs:  |  |



  





# 

 Elements



_The
 __Sequence__ 
 Content OP locally defines the following ontology elements:_ 





[![ObjectProperty](public/images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__directlyFollows__ 
 (owl:ObjectProperty) The intransitive follows relation. For example, Wednesday directly precedes Thursday. Directness of precedence depends on the designer conceptualization.
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[directlyFollows](../Submissions/Sequence/directlyFollows "Submissions:Sequence/directlyFollows") 
 page_ 



[![ObjectProperty](public/images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__directlyPrecedes__ 
 (owl:ObjectProperty) The intransitive precedes relation. For example, Monday directly precedes Tuesday. Directness of precedence depends on the designer conceptualization.
 
[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[directlyPrecedes](../Submissions/Sequence/directlyPrecedes "Submissions:Sequence/directlyPrecedes") 
 page_ 



[![ObjectProperty](public/images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__follows__ 
 (owl:ObjectProperty) A relation between entities, expressing a 'sequence' schema.
 
 E.g. 'year 2000 follows 1999', 'preparing coffee' follows 'deciding what coffee to use', 'II World War follows I World War', etc.
 



 It can be used between tasks, processes or time intervals, and subproperties would fit best in order to distinguish the different uses.
 



[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[follows](../Submissions/Sequence/follows "Submissions:Sequence/follows") 
 page_ 



[![ObjectProperty](public/images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__precedes__ 
 (owl:ObjectProperty) A relation between entities, expressing a 'sequence' schema.
 
 E.g. 'year 1999 precedes 2000', 'deciding what coffee to use' precedes 'preparing coffee', 'World War II follows World War I', 'in the Milan to Rome autoroute, Bologna precedes Florence', etc.
 



 It can then be used between tasks, processes, time intervals, spatially locate objects, situations, etc.
 



 Subproperties can be defined in order to distinguish the different uses.
 



[![](public/images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[precedes](../Submissions/Sequence/precedes "Submissions:Sequence/precedes") 
 page_ 


# 

 Additional information



# 

 Scenarios




__Scenarios about Sequence__ 


 No scenario is added to this Content OP.
 




# 

 Reviews




__Reviews about Sequence__ 


 There is no review about this proposal.
This revision (revision ID
 __9120__ 
 ) takes in account the reviews: none
 



 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Sequence&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Sequence&action=evaluation") 





  





# 

 Modeling issues




__Modeling issues about Sequence__ 


 There is no Modeling issue related to this proposal.
 




  





# 

 References
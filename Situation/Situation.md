___Situation__ 
 has
 [Category:OntologyElement](../../Category/OntologyElement "Category:OntologyElement") 
 and is an
 [element of](../../Property/ElementOf "Property:ElementOf") 
[Situation](../../Submissions/Situation "Submissions:Situation")_




  





[![Class](../public/images/thumb/2/27/Class.gif/45px-Class.gif)](../../Image/Class.gif "Class")


__Name__ 
 : Situation
 



__Type:__ 
 owl:Class
 



__Description__ 
 : A view on a set of entities. It can be seen as a 'relational context', reifying a relation.
 



 For example, a PlanExecution is a context including some actions executed by agents according to certain parameters and expected tasks to be achieved from a Plan; a DiagnosedSituation is a context of observed entities that is interpreted on the basis of a Diagnosis, etc.
 



 Situation is also able to represent reified n-ary relations, where isSettingFor is the top-level relation for all binary projections of the n-ary relation. If used in a transformation pattern for n-ary relations, the designer should take care of:
 



 - creating only one situation for each instance of an n-ary relation, otherwise the 'identification constraint' (Calvanese et al., IJCAI 2001) could be violated
 



 - adding an 'exact cardinality' restriction corresponding to the arity of the n-ary relation, otherwise the designer would actually represent a polymorphic relation.
___hasSubCategory__ 
 has
 [Category:OntologyElement](../../Category/OntologyElement "Category:OntologyElement") 
 and is an
 [element of](../../Property/ElementOf "Property:ElementOf") 
[AOS AGROVOC Concept Server fundation ontology model](../../Submissions/AOS_AGROVOC_Concept_Server_fundation_ontology_model "Submissions:AOS AGROVOC Concept Server fundation ontology model")_




  





[![ObjectProperty](../public/images/thumb/c/c3/ObjectProperty.gif/45px-ObjectProperty.gif)](../../Image/ObjectProperty.gif "ObjectProperty")


__Name__ 
 : hasSubCategory
 



__Type:__ 
 owl:TransitiveProperty
 



__Description__ 
 : Inverse relationship of the <is sub category of> relationship. This relationship is used to build a hierarchy of categories within a classification scheme. A <has sub category> B means that B is a sub-category of A, i.e. B is a more specific category than A, lower in the hierarchy. Since one category can be in different places in the hierarchy in different classification schemes, do not instantiate this relationship directly, but use the sub-properties specifically for the classification scheme for which the sub-category relationship holds. For example use the <has ASC sub category> relationship to state that A <has ASC sub category> B in the Agris Subject Categories (ASC) classification scheme.
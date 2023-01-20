___Parameter__ 
 has
 [Category:OntologyElement](../../Category/OntologyElement "Category:OntologyElement") 
 and is an
 [element of](../../Property/ElementOf "Property:ElementOf") 
[Parameter](../../Submissions/Parameter "Submissions:Parameter")_




  





[![Class](../public/images/thumb/2/27/Class.gif/45px-Class.gif)](../../Image/Class.gif "Class")


__Name__ 
 : Parameter
 



__Type:__ 
 owl:Class
 



__Description__ 
 : A Concept that classifies something having a certain value, e.g. 'High' can be said of people taller than 185 cm.
 



 However, in order to formally represent this constraint, we need to add an anonymous type to a parameter instance, using a property that convey the semantics of the parameter, e.g.:
 



 High rdf:type Person and (some hasHeight (Height and (oneOf isTallerThan 185) and (oneOf hasUnitOfMeasure centimeter)))
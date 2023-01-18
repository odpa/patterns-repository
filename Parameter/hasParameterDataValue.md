___hasParameterDataValue__ 
 has
 [Category:OntologyElement](../../Category/OntologyElement "Category:OntologyElement") 
 and is an
 [element of](../../Property/ElementOf "Property:ElementOf") 
[Parameter](../../Submissions/Parameter "Submissions:Parameter")_




  





[![DatatypeProperty](../../images/thumb/a/a5/DatatypeProperty.gif/45px-DatatypeProperty.gif)](../../Image/DatatypeProperty.gif "DatatypeProperty")


__Name__ 
 : hasParameterDataValue
 



__Type:__ 
 owl:DatatypeProperty
 



__Description__ 
 : Parametrizes values from a datatype. For example, a Parameter AgeForDriving hasParameterDataValue 18 on datatype xsd:int, in the Italian traffic code. In this example, AgeForDriving isDefinedIn the Norm ItalianTrafficCodeAgeDriving.
 



 More complex parametrization requires workarounds. E.g. AgeRangeForDrugUsage could parametrize data value: 14 to 50 on the datatype: xsd:int. Since complex datatypes are not allowed in OWL1.0, a solution to this can only work by creating two 'sub-parameters': MinimumAgeRangeForDrugUsage (that hasParameterDataValue 14) and MaximumAgeRangeForDrugUsage (that hasParameterDataValue 50), which are components of the main Parameter AgeRangeForDrugUsage.
 



 Ordering on subparameters can be created by using or specializing the object property 'precedes'.
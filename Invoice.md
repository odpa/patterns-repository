# 

 Graphical representation



__Diagram__ 





[![Image:Invoice.jpg](images/e/eb/Invoice.jpg)](../Image/Invoice.jpg "Image:Invoice.jpg")





# 

 General description




|  |  |
| --- | --- |
|  Name:  |  Invoice  |
|  Submitted by:  | [AldoGangemi](../User/AldoGangemi "User:AldoGangemi")  , [JoseManuelGomez](../User/JoseManuelGomez "User:JoseManuelGomez")  |
|  Also Known As:  |  |
|  Intent:  |  To represent the core attributes of an invoice  |
|  Domains:  | [Business](../Community/Business "Community:Business")  |
|  Competency Questions:  | <li>       What are the transactions involved in this invoice?      </li><li>       What is the order this invoice is referring to?      </li><li>       What is the line item for this invoice?      </li><li>       What is the amount of the transactions involved in this invoice?      </li><li>       What currency is applied to this invoice?      </li> |
|  Solution description:  |  -  |
|  Reusable OWL Building Block:  | [http://www.ontologydesignpatterns.org/cp/owl/invoice.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=http://www.ontologydesignpatterns.org/cp/owl/invoice.owl&message=OWL building block&from_page_id=362&update=)  (982)  |
|  Consequences:  |  Heterogeneous models for invoices can be aligned to this pattern, which then acts as a semantic facade to different invoice management applications. The Context class can be used to gather temporal,spatial and organizational data. Otherwise, other specific patterns can be composed in order to deal with that.  |
|  Scenarios:  |  An invoice refers to transactions related to an ordered item for a certain amount of currency, and is grounded in a (legally valid) document.  |
|  Known Uses:  |  |
|  Web References:  |  |
|  Other References:  |  |
|  Examples (OWL files):  |  |
|  Extracted From:  | <li><a class="external free" href="http://www-neon-project.org/InvoiceReferenceOntology" rel="nofollow" title="http://www-neon-project.org/InvoiceReferenceOntology">        http://www-neon-project.org/InvoiceReferenceOntology       </a></li> |
|  Reengineered From:  | <li><a class="external free" href="http://www-neon-project.org/InvoiceReferenceOntology" rel="nofollow" title="http://www-neon-project.org/InvoiceReferenceOntology">        http://www-neon-project.org/InvoiceReferenceOntology       </a></li> |
|  Has Components:  |  |
|  Specialization Of:  |  |
|  Related CPs:  |  |



  





# 

 Elements



_The
 __Invoice__ 
 Content OP locally defines the following ontology elements:_ 






[![Class](images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__Buying__ 
 (owl:Class) The intention to buy in a financial transaction or order
 



[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[Buying](../Submissions/Invoice/Buying "Submissions:Invoice/Buying") 
 page_ 




[![Class](images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__Context__ 
 (owl:Class) The context of an invoice (space, time, organization)
 



[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[Context](../Submissions/Invoice/Context "Submissions:Invoice/Context") 
 page_ 




[![Class](images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__Currency measure__ 
 (owl:Class) A currency unit, e.g. euro cent, dollar
 



[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[CurrencyMeasure](../Submissions/Invoice/CurrencyMeasure "Submissions:Invoice/CurrencyMeasure") 
 page_ 




[![Class](images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__Grounding__ 
 (owl:Class) A physical invoice document
 



[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[Grounding](../Submissions/Invoice/Grounding "Submissions:Invoice/Grounding") 
 page_ 




[![Class](images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__Invoice__ 
 (owl:Class) An invoice (information object)
 



[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[Invoice](../Submissions/Invoice/Invoice "Submissions:Invoice/Invoice") 
 page_ 




[![Class](images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__Line item__ 
 (owl:Class) A single item in a commercial transaction
 



[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[LineItem](Submissions%253AInvoice/LineItem.html "Submissions:Invoice/LineItem") 
 page_ 




[![Class](images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__Order__ 
 (owl:Class) A stated intention, either spoken or written, to engage in a commercial transaction for specific products or services. From a buyer's point of view it expresses the intention to buy and is called a purchase order (
 [buying](../Submissions/Invoice/Buying "Submissions:Invoice/Buying") 
 in this pattern). From a seller's point of view it expresses the intention to sell and is referred to as a sales order (
 [selling](../Submissions/Invoice/Selling "Submissions:Invoice/Selling") 
 in this pattern)
 



[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[Order](../Submissions/Invoice/Order "Submissions:Invoice/Order") 
 page_ 




[![Class](images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__Selling__ 
 (owl:Class) The intention to sell in a financial transaction or order
 



[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[Selling](../Submissions/Invoice/Selling "Submissions:Invoice/Selling") 
 page_ 




[![Class](images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__Transaction amount__ 
 (owl:Class) The amount of currency involved in the transaction referred in the invoice
 



[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[TransactionAmount](http://ontologydesignpatterns.org/wiki/Submissions:Invoice/TransactionAmount "Submissions:Invoice/TransactionAmount") 
 page_ 




[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__buyer transaction__ 
 (owl:ObjectProperty) A relation between an invoice and a buying (buyer-oriented transaction)
 



[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[buyerTransaction](http://ontologydesignpatterns.org/wiki/Submissions:Invoice/buyerTransaction "Submissions:Invoice/buyerTransaction") 
 page_ 



[Submissions:Invoice/context](http://ontologydesignpatterns.org/wiki/Special:AddData/Ontology Element Form/Submissions:Invoice/context "Submissions:Invoice/context (not yet written)") 

[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[context](http://ontologydesignpatterns.org/wiki/Special:AddData/Ontology Element Form/Submissions:Invoice/context "Submissions:Invoice/context (not yet written)") 
 page_ 




[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__grounding__ 
 (owl:ObjectProperty) A relation between an invoice and the document that realizes it
 



[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[grounding](Submissions%253AInvoice/grounding.html "Submissions:Invoice/grounding") 
 page_ 




[![DatatypeProperty](images/thumb/a/a5/DatatypeProperty.gif/20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif "DatatypeProperty")
__invoice currency code__ 
 (owl:DatatypeProperty) A relation between an invoice and the code of its currency
 



[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[invoiceCurrencyCode](../Submissions/Invoice/invoiceCurrencyCode "Submissions:Invoice/invoiceCurrencyCode") 
 page_ 



[Submissions:Invoice/invoiceCurrencyType](http://ontologydesignpatterns.org/wiki/Special:AddData/Ontology Element Form/Submissions:Invoice/invoiceCurrencyType "Submissions:Invoice/invoiceCurrencyType (not yet written)") 

[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[invoiceCurrencyType](http://ontologydesignpatterns.org/wiki/Special:AddData/Ontology Element Form/Submissions:Invoice/invoiceCurrencyType "Submissions:Invoice/invoiceCurrencyType (not yet written)") 
 page_ 




[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__issue date__ 
 (owl:ObjectProperty) A relation between an invoice and a date description, e.g. from W3 Time ontology
 



[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[issuedate](../Submissions/Invoice/issuedate "Submissions:Invoice/issuedate") 
 page_ 




[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__line item__ 
 (owl:ObjectProperty) A relation between an invoice and a line item
 



[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[lineItem](../Submissions/Invoice/lineItem "Submissions:Invoice/lineItem") 
 page_ 



[Submissions:Invoice/priceCurrencyType](http://ontologydesignpatterns.org/wiki/Special:AddData/Ontology Element Form/Submissions:Invoice/priceCurrencyType "Submissions:Invoice/priceCurrencyType (not yet written)") 

[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[priceCurrencyType](http://ontologydesignpatterns.org/wiki/Special:AddData/Ontology Element Form/Submissions:Invoice/priceCurrencyType "Submissions:Invoice/priceCurrencyType (not yet written)") 
 page_ 



[Submissions:Invoice/referenceOrder](http://ontologydesignpatterns.org/wiki/Special:AddData/Ontology Element Form/Submissions:Invoice/referenceOrder "Submissions:Invoice/referenceOrder (not yet written)") 

[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[referenceOrder](http://ontologydesignpatterns.org/wiki/Special:AddData/Ontology Element Form/Submissions:Invoice/referenceOrder "Submissions:Invoice/referenceOrder (not yet written)") 
 page_ 



[Submissions:Invoice/sellerTransaction](http://ontologydesignpatterns.org/wiki/Special:AddData/Ontology Element Form/Submissions:Invoice/sellerTransaction "Submissions:Invoice/sellerTransaction (not yet written)") 

[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[sellerTransaction](http://ontologydesignpatterns.org/wiki/Special:AddData/Ontology Element Form/Submissions:Invoice/sellerTransaction "Submissions:Invoice/sellerTransaction (not yet written)") 
 page_ 



[Submissions:Invoice/subText](http://ontologydesignpatterns.org/wiki/Special:AddData/Ontology Element Form/Submissions:Invoice/subText "Submissions:Invoice/subText (not yet written)") 

[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[subText](http://ontologydesignpatterns.org/wiki/Special:AddData/Ontology Element Form/Submissions:Invoice/subText "Submissions:Invoice/subText (not yet written)") 
 page_ 



[Submissions:Invoice/taxCurrencyType](http://ontologydesignpatterns.org/wiki/Special:AddData/Ontology Element Form/Submissions:Invoice/taxCurrencyType "Submissions:Invoice/taxCurrencyType (not yet written)") 

[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[taxCurrencyType](http://ontologydesignpatterns.org/wiki/Special:AddData/Ontology Element Form/Submissions:Invoice/taxCurrencyType "Submissions:Invoice/taxCurrencyType (not yet written)") 
 page_ 



[Submissions:Invoice/taxPointDate](http://ontologydesignpatterns.org/wiki/Special:AddData/Ontology Element Form/Submissions:Invoice/taxPointDate "Submissions:Invoice/taxPointDate (not yet written)") 

[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[taxPointDate](http://ontologydesignpatterns.org/wiki/Special:AddData/Ontology Element Form/Submissions:Invoice/taxPointDate "Submissions:Invoice/taxPointDate (not yet written)") 
 page_ 




[![DatatypeProperty](images/thumb/a/a5/DatatypeProperty.gif/20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif "DatatypeProperty")
__ID__ 
 (owl:DatatypeProperty) The identifier for an invoice
 



[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[ID](../Submissions/Invoice/ID "Submissions:Invoice/ID") 
 page_ 




[![DatatypeProperty](images/thumb/a/a5/DatatypeProperty.gif/20px-DatatypeProperty.gif)](../Image/DatatypeProperty.gif "DatatypeProperty")
__line item count quantity__ 
 (owl:DatatypeProperty) a relation to express how many instances of a line item are involved in an order referred by an invoice
 



[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[lineItemCountQuantity](../Submissions/Invoice/lineItemCountQuantity "Submissions:Invoice/lineItemCountQuantity") 
 page_ 


# 

 Additional information



# 

 Scenarios




__Scenarios about Invoice__ 


 No scenario is added to this Content OP.
 




# 

 Reviews




__Reviews about Invoice__ 


 There is no review about this proposal.
This revision (revision ID
 __9096__ 
 ) takes in account the reviews: none
 



 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Invoice&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:Invoice&action=evaluation") 





  





# 

 Modeling issues




__Modeling issues about Invoice__ 


 There is no Modeling issue related to this proposal.
 




  





# 

 References
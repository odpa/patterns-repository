___expresses__ 
 has
 [Category:OntologyElement](../../Category/OntologyElement "Category:OntologyElement") 
 and is an
 [element of](../../Property/ElementOf "Property:ElementOf") 
[IntensionExtension](../../Submissions/IntensionExtension "Submissions:IntensionExtension")_




  





[![ObjectProperty](../public/images/thumb/c/c3/ObjectProperty.gif/45px-ObjectProperty.gif)](../../Image/ObjectProperty.gif "ObjectProperty")


__Name__ 
 : expresses
 



__Type:__ 
 owl:ObjectProperty
 



__Description__ 
 : The relation between an InformationObject and a 'meaning'.
 



 What is a meaning is dependent on the background approach/theory that one assumes. For example, lexicographers that write dictionaries, glossaries, etc. assume that the meaning of term is a paraphrase (or 'gloss', or 'definition'). Another approach is provided by concept schemes like thesauri and lexicons, which assume that the meaning of a term is a 'concept', possibly encoded as a 'lemma', 'synset', or 'descriptor'. Still another approach is that of psychologists and cognitive scientists, which often assume that the meaning of an information object is a concept encoded in the mind or cognitive system of an agent. A radically different approach is taken by social scientists and semioticians, who usually assume that meaning of an information object is spread across the members of a community that use that object. The logical approach to meaning is completely different, since it assumes that the meaning of e.g. a term is equivalent to the set of individuals that the term can be applied to; for example, the meaning of 'Ali' is e.g. an individual person called Ali, the meaning of 'Airplane' is e.g. the set of airplanes, etc. Finally, an approach taken by structuralist linguistics and frame semantics is that a meaning is the relational context in which an information object can be applied; for example, a meaning of 'Airplane' is situated e.g. in the context ('frame') of passenger airline flights.
 



  





 These different approaches are not necessarily conflicting, and they mostly talk about different aspects of so-called 'semantics'. They can be summarized, and modelled withih DOLCE-Ultralite, as follows:
 



 (1) Intensional meaning
 



 - Relational meaning (as for frame semantics). Here it is modelled as the expresses relation between instances of InformationObject and instances of Description
 



 - Conceptual meaning (as for psychological and 'concept scheme' semantics). Here it is modelled as the expresses relation between instances of InformationObject and instances of Concept
 



 - Paraphrase meaning (as for lexicographic semantics). Here it is modelled as the expresses relation between instances of InformationObject and different instances of InformationObject that act as 'paraphrases'
 



 - Cultural meaning (as for social science semantics). Here it is modelled as the expresses relation between instances of InformationObject and instances of SocialObject
 



  





 (2) Extensional meaning (as for logic and formal semantics)
 



 - Object-level formal meaning (as in the traditional first-order logic semantics). Here it is modelled as the expresses relation between instances of InformationObject and instances of Collection
 



 - Modal formal meaning (as in possible-world semantics). Here it is modelled as the expresses relation between instances of InformationObject and instances of Collections as located in another Collection that isFormallyRepresentedIn a PossibleWorld
 



  





 For example:
 



 - the term Beehive expresses the Concept Beehive
 



 - the term Beehive expresses the Description BeingABeehive, a relation that defines concepts such as Bee, Honey, Habitation, etc.
 



 - the text of Italian Constitution expresses the 'content' of the Constitution
 



 - your email expresses an aggressive attitude
__Description:__ 
 NameHistory3.0 is a (fictional) institution that keeps track of all the names of people, and stores them as an ABox of the FOAF ontology. In particular, each person is stored as an individual of the class foaf:Person with a specific first name (data property foaf:givenName) and family name (data property foaf:familyName). On 24/09/2010, Bruce Wayne formally applied for changing his first name to Jack. Since NameHistory3.0 has to keep track of everything concerning names of people, on that date “Jack” was added as Mr. Wayne's first name. It was then that NameHistory3.0 noticed that, without any additional information, it is not possible to know which of the two first names are legally valid at any given point in time. A solution to that scenario, which avoids any modification of the ontology model and consequently of the entire triple store (operation that is obviously time-consuming and error-prone), is to use the literal reification pattern in combination with the new expressivity for punning in OWL 2. Through them, it is possible to define a literal individual as also belonging to the class foaf:givenName – that is actually defined as a data property, but may be additionally be meta-modelled as a class. We can now associate a particular time interval to each literal, so as to represent when the literal itself, i.e., the given name, is legally valid.
 __Diagram__ 





[![Image:LiteralReificationExample_revised.png](../images/6/68/LiteralReificationExample_revised.png)](../../Image/LiteralReificationExample_revised.png "Image:LiteralReificationExample_revised.png")





__OWL file:__ 
[http://www.essepuntato.it/2010/06/sc2.ttl](http://www.essepuntato.it/2010/06/sc2.ttl "http://www.essepuntato.it/2010/06/sc2.ttl")
# Ontology Design Pattern Repository

## Contributing a new Pattern
To contribute a new pattern, please initiate a pull request that consists of the following:
* A new directory for the pattern, with an appropriate name
  * Currently, names of patterns follow a singleword in PascalCase 
* The directory should contain:
  * **Schema Diagram** for the pattern. We recommend that should adhere to visual specification as found in [Graffoo](https://essepuntato.it/graffoo/) or from the [Modular Ontology Modeling methodology](https://content.iospress.com/articles/semantic-web/sw222886).
  * **Formalization** for the pattern. We recommend that the pattern be serialized in TTL for maximizing human readability, but as long as it is a serialization recognized by the [OWLAPI](https://protege.stanford.edu/) or [Protégé](https://protege.stanford.edu/), it will be accepted.
    * Additionally, we request that the pattern be annotated with [OPLA-CP](https://ceur-ws.org/Vol-2459/short2.pdf).
  * **index.md** for the pattern entry. This should minimally display the schema diagram and link to the formalization. 
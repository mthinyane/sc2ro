_Vocabulary: [Smart Citizen Cyber Resilience Ontology (SC2RO)](index.md)_

---








## Property sc2r:hasDescription


#### Tree

* rdf:Property
    * sc2r:hasDescription





*NOTE* this is a leaf node.


#### URI
http://cs.unu.edu/sc2r#hasDescription

#### Description
--


#### Inherits from:
owl:Thing



#### Usage


[owl:Thing](class-owlthing.md)
=&gt;&nbsp;_sc2r:hasDescription_&nbsp;=&gt;&nbsp;[rdfs:Literal](class-rdfsliteral.md)

#### Implementation
```
@prefix owl: <http://www.w3.org/2002/07/owl#> .
@prefix rdfs: <http://www.w3.org/2000/01/rdf-schema#> .
@prefix sc2r: <http://cs.unu.edu/sc2r#> .

sc2r:hasDescription a owl:DatatypeProperty ;
    rdfs:domain owl:Thing ;
    rdfs:range rdfs:Literal .


```










---

_Documentation automatically generated on 25th August 2020 with [Ontospy](http://lambdamusic.github.io/Ontospy/ "Open") (v1.9.8.3)_

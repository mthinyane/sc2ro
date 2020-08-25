_Vocabulary: [Smart Citizen Cyber Resilience Ontology (SC2RO)](index.md)_

---








## Property sc2r:reduces


#### Tree

* rdf:Property
    * sc2r:reduces





*NOTE* this is a leaf node.


#### URI
http://cs.unu.edu/sc2r#reduces

#### Description
--


#### Inherits from:
owl:Thing



#### Usage


[sc2r:Response](class-sc2rresponse.md)
=&gt;&nbsp;_sc2r:reduces_&nbsp;=&gt;&nbsp;[sc2r:Vulnerability](class-sc2rvulnerability.md)

#### Implementation
```
@prefix owl: <http://www.w3.org/2002/07/owl#> .
@prefix rdfs: <http://www.w3.org/2000/01/rdf-schema#> .
@prefix sc2r: <http://cs.unu.edu/sc2r#> .

sc2r:reduces a owl:ObjectProperty ;
    rdfs:domain sc2r:Response ;
    rdfs:range sc2r:Vulnerability .


```










---

_Documentation automatically generated on 25th August 2020 with [Ontospy](http://lambdamusic.github.io/Ontospy/ "Open") (v1.9.8.3)_

_Vocabulary: [Smart Citizen Cyber Resilience Ontology (SC2RO)](index.md)_

---








## Property sc2r:damages


#### Tree

* rdf:Property
    * sc2r:damages





*NOTE* this is a leaf node.


#### URI
http://cs.unu.edu/sc2r#damages

#### Description
--


#### Inherits from:
owl:Thing



#### Usage


[sc2r:Threat](class-sc2rthreat.md)
=&gt;&nbsp;_sc2r:damages_&nbsp;=&gt;&nbsp;[sc2r:Resource](class-sc2rresource.md)

#### Implementation
```
@prefix owl: <http://www.w3.org/2002/07/owl#> .
@prefix rdfs: <http://www.w3.org/2000/01/rdf-schema#> .
@prefix sc2r: <http://cs.unu.edu/sc2r#> .

sc2r:damages a owl:ObjectProperty ;
    rdfs:domain sc2r:Threat ;
    rdfs:range sc2r:Resource ;
    owl:inverseOf sc2r:isDamagedBy .


```










---

_Documentation automatically generated on 25th August 2020 with [Ontospy](http://lambdamusic.github.io/Ontospy/ "Open") (v1.9.8.3)_

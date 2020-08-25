_Vocabulary: [Smart Citizen Cyber Resilience Ontology (SC2RO)](index.md)_

---








## Property sc2r:isMitigatedBy


#### Tree

* rdf:Property
    * sc2r:isMitigatedBy





*NOTE* this is a leaf node.


#### URI
http://cs.unu.edu/sc2r#isMitigatedBy

#### Description
--


#### Inherits from:
owl:Thing



#### Usage


[sc2r:Threat](class-sc2rthreat.md)
=&gt;&nbsp;_sc2r:isMitigatedBy_&nbsp;=&gt;&nbsp;[sc2r:Response](class-sc2rresponse.md)

#### Implementation
```
@prefix owl: <http://www.w3.org/2002/07/owl#> .
@prefix rdfs: <http://www.w3.org/2000/01/rdf-schema#> .
@prefix sc2r: <http://cs.unu.edu/sc2r#> .

sc2r:isMitigatedBy a owl:ObjectProperty ;
    rdfs:domain sc2r:Threat ;
    rdfs:range sc2r:Response ;
    owl:inverseOf sc2r:mitigates .


```










---

_Documentation automatically generated on 25th August 2020 with [Ontospy](http://lambdamusic.github.io/Ontospy/ "Open") (v1.9.8.3)_

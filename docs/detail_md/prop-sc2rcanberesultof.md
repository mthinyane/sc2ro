_Vocabulary: [Smart Citizen Cyber Resilience Ontology (SC2RO)](index.md)_

---








## Property sc2r:canBeResultOf


#### Tree

* rdf:Property
    * sc2r:canBeResultOf


        * [sc2r:isResultOf](prop-sc2risresultof.md)
        






#### URI
http://cs.unu.edu/sc2r#canBeResultOf

#### Description
--


#### Inherits from:
owl:Thing



#### Usage


[sc2r:Harm](class-sc2rharm.md)
=&gt;&nbsp;_sc2r:canBeResultOf_&nbsp;=&gt;&nbsp;[sc2r:Threat](class-sc2rthreat.md)

#### Implementation
```
@prefix owl: <http://www.w3.org/2002/07/owl#> .
@prefix rdfs: <http://www.w3.org/2000/01/rdf-schema#> .
@prefix sc2r: <http://cs.unu.edu/sc2r#> .

sc2r:canBeResultOf a owl:ObjectProperty ;
    rdfs:domain sc2r:Harm ;
    rdfs:range sc2r:Threat ;
    owl:inverseOf sc2r:canResultIn .


```










---

_Documentation automatically generated on 25th August 2020 with [Ontospy](http://lambdamusic.github.io/Ontospy/ "Open") (v1.9.8.3)_

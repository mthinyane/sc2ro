_Vocabulary: [Smart Citizen Cyber Resilience Ontology (SC2RO)](index.md)_

---








## Property sc2r:canResultIn


#### Tree

* rdf:Property
    * sc2r:canResultIn


        * [sc2r:resultsIn](prop-sc2rresultsin.md)
        






#### URI
http://cs.unu.edu/sc2r#canResultIn

#### Description
--


#### Inherits from:
owl:Thing



#### Usage


[sc2r:Threat](class-sc2rthreat.md)
=&gt;&nbsp;_sc2r:canResultIn_&nbsp;=&gt;&nbsp;[sc2r:Harm](class-sc2rharm.md)

#### Implementation
```
@prefix owl: <http://www.w3.org/2002/07/owl#> .
@prefix rdfs: <http://www.w3.org/2000/01/rdf-schema#> .
@prefix sc2r: <http://cs.unu.edu/sc2r#> .

sc2r:canResultIn a owl:ObjectProperty ;
    rdfs:domain sc2r:Threat ;
    rdfs:range sc2r:Harm .


```










---

_Documentation automatically generated on 25th August 2020 with [Ontospy](http://lambdamusic.github.io/Ontospy/ "Open") (v1.9.8.3)_

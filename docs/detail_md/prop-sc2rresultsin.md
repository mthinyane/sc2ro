_Vocabulary: [Smart Citizen Cyber Resilience Ontology (SC2RO)](index.md)_

---








## Property sc2r:resultsIn


#### Tree


* [sc2r:canResultIn](prop-sc2rcanresultin.md)

    * sc2r:resultsIn





*NOTE* this is a leaf node.


#### URI
http://cs.unu.edu/sc2r#resultsIn

#### Description
--


#### Inherits from (1)

- [sc2r:canResultIn](prop-sc2rcanresultin.md)




#### Usage


[sc2r:Threat](class-sc2rthreat.md)
=&gt;&nbsp;_sc2r:resultsIn_&nbsp;=&gt;&nbsp;[sc2r:Harm](class-sc2rharm.md)

#### Implementation
```
@prefix owl: <http://www.w3.org/2002/07/owl#> .
@prefix rdfs: <http://www.w3.org/2000/01/rdf-schema#> .
@prefix sc2r: <http://cs.unu.edu/sc2r#> .

sc2r:resultsIn a owl:ObjectProperty ;
    rdfs:domain sc2r:Threat ;
    rdfs:range sc2r:Harm ;
    rdfs:subPropertyOf sc2r:canResultIn .


```










---

_Documentation automatically generated on 25th August 2020 with [Ontospy](http://lambdamusic.github.io/Ontospy/ "Open") (v1.9.8.3)_

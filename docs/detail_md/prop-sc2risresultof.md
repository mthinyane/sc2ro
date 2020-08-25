_Vocabulary: [Smart Citizen Cyber Resilience Ontology (SC2RO)](index.md)_

---








## Property sc2r:isResultOf


#### Tree


* [sc2r:canBeResultOf](prop-sc2rcanberesultof.md)

    * sc2r:isResultOf





*NOTE* this is a leaf node.


#### URI
http://cs.unu.edu/sc2r#isResultOf

#### Description
--


#### Inherits from (1)

- [sc2r:canBeResultOf](prop-sc2rcanberesultof.md)




#### Usage


[sc2r:Harm](class-sc2rharm.md)
=&gt;&nbsp;_sc2r:isResultOf_&nbsp;=&gt;&nbsp;[sc2r:Threat](class-sc2rthreat.md)

#### Implementation
```
@prefix owl: <http://www.w3.org/2002/07/owl#> .
@prefix rdfs: <http://www.w3.org/2000/01/rdf-schema#> .
@prefix sc2r: <http://cs.unu.edu/sc2r#> .

sc2r:isResultOf a owl:ObjectProperty ;
    rdfs:domain sc2r:Harm ;
    rdfs:range sc2r:Threat ;
    rdfs:subPropertyOf sc2r:canBeResultOf ;
    owl:inverseOf sc2r:resultsIn .


```










---

_Documentation automatically generated on 25th August 2020 with [Ontospy](http://lambdamusic.github.io/Ontospy/ "Open") (v1.9.8.3)_

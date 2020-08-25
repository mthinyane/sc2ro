_Vocabulary: [Smart Citizen Cyber Resilience Ontology (SC2RO)](index.md)_

---





    


## Class sc2r:PsychologicalHarm


#### Tree


* [sc2r:Harm](class-sc2rharm.md)

    * sc2r:PsychologicalHarm


        * [sc2r:Addiction](class-sc2raddiction.md) 

        * [sc2r:CognitiveImpairement](class-sc2rcognitiveimpairement.md) 

        * [sc2r:Confusion](class-sc2rconfusion.md) 

        * [sc2r:Depressed](class-sc2rdepressed.md) 

        * [sc2r:Discomfort](class-sc2rdiscomfort.md) 

        * [sc2r:Disempowerment](class-sc2rdisempowerment.md) 

        * [sc2r:Distraction](class-sc2rdistraction.md) 

        * [sc2r:Embarrassed](class-sc2rembarrassed.md) 

        * [sc2r:FeelingUpset](class-sc2rfeelingupset.md) 

        * [sc2r:Frustration](class-sc2rfrustration.md) 

        * [sc2r:Gluttony](class-sc2rgluttony.md) 

        * [sc2r:Guilty](class-sc2rguilty.md) 

        * [sc2r:IdentityTheftLoss](class-sc2ridentitytheftloss.md) 

        * [sc2r:LossOfConfidence](class-sc2rlossofconfidence.md) 

        * [sc2r:LowMorale](class-sc2rlowmorale.md) 

        * [sc2r:LowSatisfaction](class-sc2rlowsatisfaction.md) 

        * [sc2r:Mistreatment](class-sc2rmistreatment.md) 

        * [sc2r:NegativePerception](class-sc2rnegativeperception.md) 

        * [sc2r:Overwhelmed](class-sc2roverwhelmed.md) 

        * [sc2r:Prosecution](class-sc2rprosecution.md) 

        * [sc2r:SelfCensorship](class-sc2rselfcensorship.md) 

        * [sc2r:Shameful](class-sc2rshameful.md) 

        * [sc2r:Worried](class-sc2rworried.md) 
        






#### URI
http://cs.unu.edu/sc2r#PsychologicalHarm

#### Description
Psychological harm is the harm which focuses on an individual and their mental well-being and psyche.



#### Inherits from (1)

- [sc2r:Harm](class-sc2rharm.md)





#### Implementation
```
@prefix owl: <http://www.w3.org/2002/07/owl#> .
@prefix rdfs: <http://www.w3.org/2000/01/rdf-schema#> .
@prefix sc2r: <http://cs.unu.edu/sc2r#> .

sc2r:PsychologicalHarm a owl:Class ;
    rdfs:label "Psychological Harm" ;
    rdfs:comment "Psychological harm is the harm which focuses on an individual and their mental well-being and psyche." ;
    rdfs:subClassOf sc2r:Harm .


```




#### Instances of sc2r:PsychologicalHarm can have the following properties:

<table border="1" cellspacing="3" cellpadding="5" class="classproperties table-hover ">

    <tr>
        <th height="40">Property</th><th>Description</th><th>Expected Type</th>
    </tr>

          

        
            
        
        <tr style="background: lightcyan;text-align: left;">
            <th colspan="3" height="10" class="treeinfo"><span style="font-size: 80%;">
            From <a title="sc2r:PsychologicalHarm" href="class-sc2rpsychologicalharm.md" class="rdfclass">sc2r:PsychologicalHarm</a></span>
            </th>
        </tr>       

            

        

          

        
            
        
        <tr style="background: lightcyan;text-align: left;">
            <th colspan="3" height="10" class="treeinfo"><span style="font-size: 80%;">
            From <a title="sc2r:Harm" href="class-sc2rharm.md" class="rdfclass">sc2r:Harm</a></span>
            </th>
        </tr>       

            
            <tr>
                <td class="firsttd">
                    <a class="propcolor" title="sc2r:canBeResultOf" href="prop-sc2rcanberesultof.md">sc2r:canBeResultOf</a>         
                </td>
                <td class="thirdtd">
                    <span></span>
                </td>
                <td class="secondtd">
                    
                    

                        <a title="sc2r:Threat" href="class-sc2rthreat.md" class="rdfclass">sc2r:Threat</a>

                    
                    
                </td>
            </tr>

            
            <tr>
                <td class="firsttd">
                    <a class="propcolor" title="sc2r:isResultOf" href="prop-sc2risresultof.md">sc2r:isResultOf</a>         
                </td>
                <td class="thirdtd">
                    <span></span>
                </td>
                <td class="secondtd">
                    
                    

                        <a title="sc2r:Threat" href="class-sc2rthreat.md" class="rdfclass">sc2r:Threat</a>

                    
                    
                </td>
            </tr>

            

        

          

        
            
        
        <tr style="background: lightcyan;text-align: left;">
            <th colspan="3" height="10" class="treeinfo"><span style="font-size: 80%;">
            From <a title="owl:Thing" href="class-owlthing.md" class="rdfclass">owl:Thing</a></span>
            </th>
        </tr>       

            
            <tr>
                <td class="firsttd">
                    <a class="propcolor" title="dc1:creator" href="prop-dc1creator.md">dc1:creator</a>         
                </td>
                <td class="thirdtd">
                    <span></span>
                </td>
                <td class="secondtd">
                    
                        <i>owl:Thing</i>
                    
                </td>
            </tr>

            
            <tr>
                <td class="firsttd">
                    <a class="propcolor" title="dc1:description" href="prop-dc1description.md">dc1:description</a>         
                </td>
                <td class="thirdtd">
                    <span></span>
                </td>
                <td class="secondtd">
                    
                        <i>owl:Thing</i>
                    
                </td>
            </tr>

            
            <tr>
                <td class="firsttd">
                    <a class="propcolor" title="dc1:rights" href="prop-dc1rights.md">dc1:rights</a>         
                </td>
                <td class="thirdtd">
                    <span></span>
                </td>
                <td class="secondtd">
                    
                        <i>owl:Thing</i>
                    
                </td>
            </tr>

            
            <tr>
                <td class="firsttd">
                    <a class="propcolor" title="dc:creator" href="prop-dccreator.md">dc:creator</a>         
                </td>
                <td class="thirdtd">
                    <span></span>
                </td>
                <td class="secondtd">
                    
                        <i>owl:Thing</i>
                    
                </td>
            </tr>

            
            <tr>
                <td class="firsttd">
                    <a class="propcolor" title="dc:description" href="prop-dcdescription.md">dc:description</a>         
                </td>
                <td class="thirdtd">
                    <span></span>
                </td>
                <td class="secondtd">
                    
                        <i>owl:Thing</i>
                    
                </td>
            </tr>

            
            <tr>
                <td class="firsttd">
                    <a class="propcolor" title="dc:rights" href="prop-dcrights.md">dc:rights</a>         
                </td>
                <td class="thirdtd">
                    <span></span>
                </td>
                <td class="secondtd">
                    
                        <i>owl:Thing</i>
                    
                </td>
            </tr>

            
            <tr>
                <td class="firsttd">
                    <a class="propcolor" title="sc2r:hasID" href="prop-sc2rhasid.md">sc2r:hasID</a>         
                </td>
                <td class="thirdtd">
                    <span></span>
                </td>
                <td class="secondtd">
                    
                        <i>owl:Thing</i>
                    
                </td>
            </tr>

            
            <tr>
                <td class="firsttd">
                    <a class="propcolor" title="sc2r:relatesTo" href="prop-sc2rrelatesto.md">sc2r:relatesTo</a>         
                </td>
                <td class="thirdtd">
                    <span></span>
                </td>
                <td class="secondtd">
                    
                        <i>owl:Thing</i>
                    
                </td>
            </tr>

            

        

    

</table>













---

_Documentation automatically generated on 25th August 2020 with [Ontospy](http://lambdamusic.github.io/Ontospy/ "Open") (v1.9.8.3)_

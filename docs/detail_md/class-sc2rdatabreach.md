_Vocabulary: [Smart Citizen Cyber Resilience Ontology (SC2RO)](index.md)_

---





    


## Class sc2r:DataBreach


#### Tree


* [sc2r:ConfidentialityThreat](class-sc2rconfidentialitythreat.md)

    * sc2r:DataBreach





*NOTE* this is a leaf node.


#### URI
http://cs.unu.edu/sc2r#DataBreach

#### Description
A data breach occurs when there is unauthorized access to data as a result of an attacker exploiting data systems which host individuals&#x27; confidential data. The source of data breaches is external.



#### Inherits from (3)

- [sc2r:ConfidentialityThreat](class-sc2rconfidentialitythreat.md)

- [sc2r:TechnologicalThreat](class-sc2rtechnologicalthreat.md)

- [sc2r:Threat](class-sc2rthreat.md)





#### Implementation
```
@prefix owl: <http://www.w3.org/2002/07/owl#> .
@prefix rdfs: <http://www.w3.org/2000/01/rdf-schema#> .
@prefix sc2r: <http://cs.unu.edu/sc2r#> .

sc2r:DataBreach a owl:Class ;
    rdfs:label "Data Breach"@en ;
    rdfs:comment "A data breach occurs when there is unauthorized access to data as a result of an attacker exploiting data systems which host individuals' confidential data. The source of data breaches is external."@en ;
    rdfs:seeAlso sc2r:DataLeak ;
    rdfs:subClassOf sc2r:ConfidentialityThreat .


```




#### Instances of sc2r:DataBreach can have the following properties:

<table border="1" cellspacing="3" cellpadding="5" class="classproperties table-hover ">

    <tr>
        <th height="40">Property</th><th>Description</th><th>Expected Type</th>
    </tr>

          

        
            
        
        <tr style="background: lightcyan;text-align: left;">
            <th colspan="3" height="10" class="treeinfo"><span style="font-size: 80%;">
            From <a title="sc2r:DataBreach" href="class-sc2rdatabreach.md" class="rdfclass">sc2r:DataBreach</a></span>
            </th>
        </tr>       

            

        

          

        
            
        
        <tr style="background: lightcyan;text-align: left;">
            <th colspan="3" height="10" class="treeinfo"><span style="font-size: 80%;">
            From <a title="sc2r:Threat" href="class-sc2rthreat.md" class="rdfclass">sc2r:Threat</a></span>
            </th>
        </tr>       

            
            <tr>
                <td class="firsttd">
                    <a class="propcolor" title="sc2r:canResultIn" href="prop-sc2rcanresultin.md">sc2r:canResultIn</a>         
                </td>
                <td class="thirdtd">
                    <span></span>
                </td>
                <td class="secondtd">
                    
                    

                        <a title="sc2r:Harm" href="class-sc2rharm.md" class="rdfclass">sc2r:Harm</a>

                    
                    
                </td>
            </tr>

            
            <tr>
                <td class="firsttd">
                    <a class="propcolor" title="sc2r:damages" href="prop-sc2rdamages.md">sc2r:damages</a>         
                </td>
                <td class="thirdtd">
                    <span></span>
                </td>
                <td class="secondtd">
                    
                    

                        <a title="sc2r:Resource" href="class-sc2rresource.md" class="rdfclass">sc2r:Resource</a>

                    
                    
                </td>
            </tr>

            
            <tr>
                <td class="firsttd">
                    <a class="propcolor" title="sc2r:exploits" href="prop-sc2rexploits.md">sc2r:exploits</a>         
                </td>
                <td class="thirdtd">
                    <span></span>
                </td>
                <td class="secondtd">
                    
                    

                        <a title="sc2r:Vulnerability" href="class-sc2rvulnerability.md" class="rdfclass">sc2r:Vulnerability</a>

                    
                    
                </td>
            </tr>

            
            <tr>
                <td class="firsttd">
                    <a class="propcolor" title="sc2r:isMitigatedBy" href="prop-sc2rismitigatedby.md">sc2r:isMitigatedBy</a>         
                </td>
                <td class="thirdtd">
                    <span></span>
                </td>
                <td class="secondtd">
                    
                    

                        <a title="sc2r:Response" href="class-sc2rresponse.md" class="rdfclass">sc2r:Response</a>

                    
                    
                </td>
            </tr>

            
            <tr>
                <td class="firsttd">
                    <a class="propcolor" title="sc2r:resultsIn" href="prop-sc2rresultsin.md">sc2r:resultsIn</a>         
                </td>
                <td class="thirdtd">
                    <span></span>
                </td>
                <td class="secondtd">
                    
                    

                        <a title="sc2r:Harm" href="class-sc2rharm.md" class="rdfclass">sc2r:Harm</a>

                    
                    
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
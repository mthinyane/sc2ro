<html lang="en">
<head>
    <title>Smart Citizen Cyber Resilience Ontology</title>
    <meta http-equiv="Content-Type" content="text/html; charset=utf-8"/>
    
    <style>
        #pylode {
            position: fixed;
            top: 130px;
            left: -60px;
            font-size: small;
            transform: rotate(-90deg);
            color: grey;
        }
        #pylode a {
            font-size: 2em;
            font-weight: bold;
            text-decoration: none;
            color: #005A9C;
        }
        #pylode a:hover {
            color: #333;
        }

        .cardinality {
            font-style: italic;
            color: #aa00aa;
        }

        dt {
            font-weight: bold;
            padding: 5px 0 5px 0;
        }

        ul.hlist {
            list-style-type: none;
            border: 1px solid navy;
            padding:5px;
            background-color: #F4FFFF;
        }

        ul.hierarchy {
            border: 1px solid navy;
            padding: 5px 25px 5px 25px;
            background-color: #F4FFFF;
        }


        ul.hlist li {
            display: inline;
            margin-right: 10px;
        }

        .entity {
            border: 1px solid navy;
            margin:5px 0 5px 0;
            padding: 5px;
        }

        .entity th {
            width: 150px;
            vertical-align: top;
        }

        .entity th,
        .entity td {
            padding-bottom: 20px;
        }

        .entity table th {
            text-align: left;
        }

        section#overview img {
            max-width: 1000px;
        }

        h1, h2, h3, h4, h5, h6 {
            text-align: left
        }
        h1, h2, h3 {
            color: #005A9C; background: white
        }
        h1 {
            font: 170% sans-serif;
            line-height: 110%;
        }
        h2 {
            font: 140% sans-serif;
            margin-top:40px;
        }
        h3 {
            font: 120% sans-serif;
            margin-top: 3px;
            padding-bottom: 5px;
            border-bottom: 1px solid navy;
        }
        h4 { font: bold 100% sans-serif }
        h5 { font: italic 100% sans-serif }
        h6 { font: small-caps 100% sans-serif }


        body {
            padding: 2em 70px 2em 70px;
            margin: 0;
            font-family: sans-serif;
            color: black;
            background: white;
            background-position: top left;
            background-attachment: fixed;
            background-repeat: no-repeat;
            text-align: justify;
        }

        section {
            max-width: 1500px;
        }

        .figure {
            margin-bottom: 20px;
        }

        :link { color: #00C; background: transparent }
        :visited { color: #609; background: transparent }
        a:active { color: #C00; background: transparent }

        .sup-c,
        .sup-op,
        .sup-fp,
        .sup-dp,
        .sup-ap,
        .sup-p,
        .sup-ni,
        .sup-cp,
        .sup-cl {
            cursor:help;
            margin-left: 3px;
        }

        .sup-c {
            color:orange;
        }

        .sup-op {
            color:navy;
        }

        .sup-fp {
            color:lightskyblue;
        }

        .sup-dp {
            color:green;
        }

        .sup-ap {
            color:darkred;
        }

        .sup-p {
            color:black;
        }

        .sup-ni {
            color:brown;
        }

        .sup-cp {
            color:orange;
        }

        .sup-cl {
            color:darkred;
        }

        code {
            font-size: large;
            color: darkred;
        }

        /* less prominent links for properties */
        .proplink {
            color: #336;
            text-decoration: none;
        }
    </style>
    
    <script type="application/ld+json">
      [
  {
    "@id": "http://cs.unu.edu/sc2r",
    "@type": [
      "https://schema.org/DefinedTermSet"
    ],
    "https://schema.org/description": [
      {
        "@value": "<p>The Smart Citizen Cyber Resilience Ontology (SC2RO) maps the cyber resilience landscape for individuals. It identifies cyber resources, vulnerabilities, threats, responses and harms associated with and specific to individual citizen's cyber functionings.</p>"
      }
    ],
    "https://schema.org/name": [
      {
        "@value": "Smart Citizen Cyber Resilience Ontology"
      }
    ]
  }
]
    </script>
</head>
<body>
  <div id="pylode">made by <a href="http://github.com/rdflib/pyLODE">
    <span style="color:#329545;">p</span><span style="color:#f9cb33;">y</span>LODE</a>
    <span style="font-size:smaller;">2.8.3</span>
  </div>
  <h1>Smart Citizen Cyber Resilience Ontology</h1>
<section id="metadata">
    <h2 style="display:none;">Metadata</h2>
    <dl>
        <dt>URI</dt>
        <dd><code>http://cs.unu.edu/sc2r</code></dd>
        <dt>Ontology RDF</dt>
        <dd><a href="https://github.com/UNU-Macau/sc2ro">RDF (xml)</a></dd>
    </dl>
    <h2>Description</h2>
    <div id="description">
        <p>The Smart Citizen Cyber Resilience Ontology (SC2RO) maps the cyber resilience landscape for individuals. It identifies cyber resources, vulnerabilities, threats, responses and harms associated with and specific to individual citizen's cyber functionings.</p>
    </div>
</section>
<section id="toc">
    <h2>Table of Contents</h2>
    <ol>
        <li><a href="#classes">Classes</a></li>
        <li><a href="#objectproperties">Object Properties</a></li>
        <li><a href="#datatypeproperties">Datatype Properties</a></li>
        <li><a href="#namespaces">Namespaces</a></li>
        <li><a href="#legend">Legend</a></li>
    </ol>
</section>
<section id="overview">
    <h2>Overview</h2>
        <p><img src="images/onto_elements.png" alt="SC2RO Overview" width="400"></p>
</section>
  <section id="classes">
    <h2>Classes <span style="float:right; font-size:smaller;"><a href="">&uparrow;</a></span></h2>
    <ul class="hlist">
        <li><a href="#AbsorbMeasure">Absorb Measure</a></li>
        <li><a href="#AbuseThreat">Abuse Threat</a></li>
        <li><a href="#AbusedHarm">Abused Harm</a></li>
        <li><a href="#AccessControl">Access Control</a></li>
        <li><a href="#AccountHijacking">Account Hijacking</a></li>
        <li><a href="#AccountRecovery">Account Recovery</a></li>
        <li><a href="#ActiveMediation">Active Mediation</a></li>
        <li><a href="#ActivityData">Activity Data</a></li>
        <li><a href="#AdaptMeasure">Adapt Measure</a></li>
        <li><a href="#Addiction">Addiction</a></li>
        <li><a href="#Agency">Agency</a></li>
        <li><a href="#AlternativeResourceMeasure">Alternative Resource Measure</a></li>
        <li><a href="#AnglerPhishing">Angler Phishing</a></li>
        <li><a href="#AnonymityThreat">Anonymity Threat</a></li>
        <li><a href="#AnonymousRouting">Anonymous Routing</a></li>
        <li><a href="#AnticipateMeasure">Anticipate Measure</a></li>
        <li><a href="#AssetInventoryManagement">Asset Inventory Management</a></li>
        <li><a href="#AttitudinalMeasure">Attitudinal Measure</a></li>
        <li><a href="#AuthenticationThreat">Authentication Threat</a></li>
        <li><a href="#AvailabilityThreat">Availability Threat</a></li>
        <li><a href="#Awareness">Awareness</a></li>
        <li><a href="#Baiting">Baiting</a></li>
        <li><a href="#BandwagonEffect">Bandwagon Effect</a></li>
        <li><a href="#BeCritical">Be Critical</a></li>
        <li><a href="#BeSuspicious">Be Suspicious</a></li>
        <li><a href="#BeVigilant">Be Vigilant</a></li>
        <li><a href="#BehavioralData">Behavioral Data</a></li>
        <li><a href="#BiometricToken">BiometricToken</a></li>
        <li><a href="#BlackPropaganda">Black Propaganda</a></li>
        <li><a href="#Blacklisted">Blacklisted</a></li>
        <li><a href="#BodilyInjury">Bodily Injury</a></li>
        <li><a href="#BodilyPain">Bodily Pain</a></li>
        <li><a href="#BoyfriendingandGirlfriending">Boyfriending and Girlfriending</a></li>
        <li><a href="#BreachofContract">Breach of Contract</a></li>
        <li><a href="#CapacityBuilding">Capacity Building</a></li>
        <li><a href="#Catphishing">Catphishing</a></li>
        <li><a href="#Censorship">Censorship</a></li>
        <li><a href="#Cheerleading">Cheerleading</a></li>
        <li><a href="#Coercion">Coercion</a></li>
        <li><a href="#CognitiveImpairement">Cognitive Impairement</a></li>
        <li><a href="#CognitiveThreat">Cognitive Threat</a></li>
        <li><a href="#CompensationPayment">Compensation Payment</a></li>
        <li><a href="#Compromised">Compromised</a></li>
        <li><a href="#Computer">Computer</a></li>
        <li><a href="#ComputingAsset">Computing Asset</a></li>
        <li><a href="#ConfidentialityThreat">Confidentiality Threat</a></li>
        <li><a href="#Conflict">Conflict</a></li>
        <li><a href="#ConfronttheThreat">Confront the Threat</a></li>
        <li><a href="#Confusion">Confusion</a></li>
        <li><a href="#Conscientiousness">Conscientiousness</a></li>
        <li><a href="#Corrupted">Corrupted</a></li>
        <li><a href="#Couriosity">Couriosity</a></li>
        <li><a href="#Credential">Credential</a></li>
        <li><a href="#CryptoCurrency">Crypto Currency</a></li>
        <li><a href="#CyberPredator">Cyber Predator</a></li>
        <li><a href="#CyberStalking">Cyber Stalking</a></li>
        <li><a href="#Cyberbullying">Cyberbullying</a></li>
        <li><a href="#Damage">Damage</a></li>
        <li><a href="#DamagedRelationship">Damaged Relationship</a></li>
        <li><a href="#DamagedSocialPerception">Damaged Social Perception</a></li>
        <li><a href="#DarkAdvertising">Dark Advertising</a></li>
        <li><a href="#Data">Data</a></li>
        <li><a href="#DataBreach">Data Breach</a></li>
        <li><a href="#DataCorruption">Data Corruption</a></li>
        <li><a href="#DataError">Data Error</a></li>
        <li><a href="#DataLeak">Data Leak</a></li>
        <li><a href="#DataRecovery">Data Recovery</a></li>
        <li><a href="#DataRedundancy">Data Redundancy</a></li>
        <li><a href="#DataVulnerability">Data Vulnerability</a></li>
        <li><a href="#DataToken">DataToken</a></li>
        <li><a href="#Deceit">Deceit</a></li>
        <li><a href="#DemocraphicInformation">Democraphic Information</a></li>
        <li><a href="#DenialofService">Denial of Service</a></li>
        <li><a href="#Depressed">Depressed</a></li>
        <li><a href="#Destroyed">Destroyed</a></li>
        <li><a href="#DeviceIdentification">Device Identification</a></li>
        <li><a href="#DiffusionofResponsibility">Diffusion of Responsibility</a></li>
        <li><a href="#DigitalFootprintManagement">Digital Footprint Management</a></li>
        <li><a href="#DigitalHoarding">Digital Hoarding</a></li>
        <li><a href="#DigitalResource">Digital Resource</a></li>
        <li><a href="#DigitalVulnerability">Digital Vulnerability</a></li>
        <li><a href="#Discomfort">Discomfort</a></li>
        <li><a href="#DisconnectMeasure">Disconnect Measure</a></li>
        <li><a href="#Disempowerment">Disempowerment</a></li>
        <li><a href="#Disinformation">Disinformation</a></li>
        <li><a href="#DisruptedIncome">Disrupted Income</a></li>
        <li><a href="#DisruptedWork">Disrupted Work</a></li>
        <li><a href="#Disruption">Disruption</a></li>
        <li><a href="#Distraction">Distraction</a></li>
        <li><a href="#Doxing">Doxing</a></li>
        <li><a href="#Eavesdropping">Eavesdropping</a></li>
        <li><a href="#EconomicHarm">Economic Harm</a></li>
        <li><a href="#Electricity">Electricity</a></li>
        <li><a href="#EmailHygiene">Email Hygiene</a></li>
        <li><a href="#Embarrassed">Embarrassed</a></li>
        <li><a href="#EngageMeasure">Engage Measure</a></li>
        <li><a href="#EngineeredContent">Engineered Content</a></li>
        <li><a href="#EnvironmentalThreat">Environmental Threat</a></li>
        <li><a href="#EvolveMeasure">Evolve Measure</a></li>
        <li><a href="#Exposed">Exposed</a></li>
        <li><a href="#ExternalHardDrive">External Hard Drive</a></li>
        <li><a href="#ExternalSupport">External Support</a></li>
        <li><a href="#ExtorsionPayment">Extorsion Payment</a></li>
        <li><a href="#Extortion">Extortion</a></li>
        <li><a href="#Fabrication">Fabrication</a></li>
        <li><a href="#FactChecking">Fact Checking</a></li>
        <li><a href="#FailureDetection">Failure Detection</a></li>
        <li><a href="#FakeGiveaways">Fake Giveaways</a></li>
        <li><a href="#FakeNews">Fake News</a></li>
        <li><a href="#Fear">Fear</a></li>
        <li><a href="#FeelingUpset">Feeling Upset</a></li>
        <li><a href="#FileResource">File Resource</a></li>
        <li><a href="#FinancialData">FinancialData</a></li>
        <li><a href="#FinePayment">Fine Payment</a></li>
        <li><a href="#Firehosing">Firehosing</a></li>
        <li><a href="#Firewall">Firewall</a></li>
        <li><a href="#Flaming">Flaming</a></li>
        <li><a href="#Flooding">Flooding</a></li>
        <li><a href="#Forging">Forging</a></li>
        <li><a href="#Fraud">Fraud</a></li>
        <li><a href="#Frustration">Frustration</a></li>
        <li><a href="#GishGalloping">Gish Galloping</a></li>
        <li><a href="#Gluttony">Gluttony</a></li>
        <li><a href="#Greed">Greed</a></li>
        <li><a href="#Grooming">Grooming</a></li>
        <li><a href="#Guilt">Guilt</a></li>
        <li><a href="#Guilty">Guilty</a></li>
        <li><a href="#HardwareVulnerability">Hardware Vulnerability</a></li>
        <li><a href="#Harm">Harm</a></li>
        <li><a href="#Helpfulness">Helpfulness</a></li>
        <li><a href="#HumorandMeme">Humor and Meme</a></li>
        <li><a href="#Identification">Identification</a></li>
        <li><a href="#IdentifyingData">Identifying Data</a></li>
        <li><a href="#Identity">Identity</a></li>
        <li><a href="#IdentityTheft">Identity Theft</a></li>
        <li><a href="#IdentityTheftHarm">Identity Theft Harm</a></li>
        <li><a href="#ImpairedPrivateSocialBoundary">Impaired Private Social Boundary</a></li>
        <li><a href="#Impulsiveness">Impulsiveness</a></li>
        <li><a href="#InadvertentInformationDisclosure">Inadvertent Information Disclosure</a></li>
        <li><a href="#InappropriateContent">Inappropriate Content</a></li>
        <li><a href="#IncidentReporting">Incident Reporting</a></li>
        <li><a href="#IncreaseResourceMeasure">Increase Resource Measure</a></li>
        <li><a href="#IndividualPersonalResource">Individual Personal Resource</a></li>
        <li><a href="#IndividualandPersonalThreat">Individual and Personal Threat</a></li>
        <li><a href="#IndividualandPersonalVulnerability">Individual and Personal Vulnerability</a></li>
        <li><a href="#Infected">Infected</a></li>
        <li><a href="#InfluenceOperation">Influence Operation</a></li>
        <li><a href="#InfluenceThreat">Influence Threat</a></li>
        <li><a href="#InformationFlooding">Information Flooding</a></li>
        <li><a href="#InformationOverload">Information Overload</a></li>
        <li><a href="#InfrastructureResource">Infrastructure Resource</a></li>
        <li><a href="#InstitutionalThreat">Institutional Threat</a></li>
        <li><a href="#IntegrityThreat">Integrity Threat</a></li>
        <li><a href="#Interception">Interception</a></li>
        <li><a href="#InternetConnectivity">Internet Connectivity</a></li>
        <li><a href="#IntimacyThreat">Intimacy Threat</a></li>
        <li><a href="#IntrusionDetection">Intrusion Detection</a></li>
        <li><a href="#IsolateMeasure">Isolate Measure</a></li>
        <li><a href="#Isolation">Isolation</a></li>
        <li><a href="#KnowledgeResource">Knowledge Resource</a></li>
        <li><a href="#Laptop">Laptop</a></li>
        <li><a href="#Laundering">Laundering</a></li>
        <li><a href="#LeastPrivilege">Least Privilege</a></li>
        <li><a href="#LocationData">Location Data</a></li>
        <li><a href="#LoggingandAudit">Logging and Audit</a></li>
        <li><a href="#LossofConfidence">Loss of Confidence</a></li>
        <li><a href="#LossofLife">Loss of Life</a></li>
        <li><a href="#LossofWork">Loss of Work</a></li>
        <li><a href="#LostCredentials">Lost Credentials</a></li>
        <li><a href="#LostDevices">Lost Devices</a></li>
        <li><a href="#LoveBombing">Love Bombing</a></li>
        <li><a href="#LowMorale">Low Morale</a></li>
        <li><a href="#LowSatisfaction">Low Satisfaction</a></li>
        <li><a href="#LuringSexualThreat">Luring Sexual Threat</a></li>
        <li><a href="#Malfunction">Malfunction</a></li>
        <li><a href="#MaliciousContactRemoval">Malicious Contact Removal</a></li>
        <li><a href="#MaliciousContentRemoval">Malicious Content Removal</a></li>
        <li><a href="#MaliciousSoftwareDetection">Malicious Software Detection</a></li>
        <li><a href="#MaliciousSoftwareRemoval">Malicious Software Removal</a></li>
        <li><a href="#MalignRhetoric">Malign Rhetoric</a></li>
        <li><a href="#Malinformation">Malinformation</a></li>
        <li><a href="#Malware">Malware</a></li>
        <li><a href="#Masquerading">Masquerading</a></li>
        <li><a href="#MediationMeasures">Mediation Measures</a></li>
        <li><a href="#MentalFaculties">Mental Faculties</a></li>
        <li><a href="#Microtargeting">Microtargeting</a></li>
        <li><a href="#Misconfiguration">Misconfiguration</a></li>
        <li><a href="#Misinformation">Misinformation</a></li>
        <li><a href="#MisleadingAdvertising">Misleading Advertising</a></li>
        <li><a href="#MisleadingInformation">Misleading Information</a></li>
        <li><a href="#Misled">Misled</a></li>
        <li><a href="#Mistreatment">Mistreatment</a></li>
        <li><a href="#MitigationCost">Mitigation Cost</a></li>
        <li><a href="#MobileDevice">Mobile Device</a></li>
        <li><a href="#MonitoringMeasure">Monitoring Measure</a></li>
        <li><a href="#Motivation">Motivation</a></li>
        <li><a href="#MultifactorAuthentication">Multifactor Authentication</a></li>
        <li><a href="#MutualAuthentication">Mutual Authentication</a></li>
        <li><a href="#NaturalDisasterThreat">Natural Disaster Threat</a></li>
        <li><a href="#NegativePerception">Negative Perception</a></li>
        <li><a href="#NetworkEquipment">Network Equipment</a></li>
        <li><a href="#NetworkIntrusion">Network Intrusion</a></li>
        <li><a href="#NetworkRedundancy">Network Redundancy</a></li>
        <li><a href="#NetworkVulnerability">Network Vulnerability</a></li>
        <li><a href="#Non-repudiationThreat">Non-repudiation Threat</a></li>
        <li><a href="#OffensiveLanguage">Offensive Language</a></li>
        <li><a href="#OnlineService">Online Service</a></li>
        <li><a href="#OpposingInformation">Opposing Information</a></li>
        <li><a href="#Overwhelmed">Overwhelmed</a></li>
        <li><a href="#ParasocialHacking">Parasocial Hacking</a></li>
        <li><a href="#Parody">Parody</a></li>
        <li><a href="#PasswordManagement">Password Management</a></li>
        <li><a href="#PersistenceSexualThreat">Persistence Sexual Threat</a></li>
        <li><a href="#PersonalData">Personal Data</a></li>
        <li><a href="#Phishing">Phishing</a></li>
        <li><a href="#PhysicalHarm">Physical Harm</a></li>
        <li><a href="#PhysicalResource">Physical Resource</a></li>
        <li><a href="#PhysicalRestriction">Physical Restriction</a></li>
        <li><a href="#PhysicalVulnerability">Physical Vulnerability</a></li>
        <li><a href="#PhysicalToken">PhysicalToken</a></li>
        <li><a href="#Piggybacking">Piggybacking</a></li>
        <li><a href="#PointandShriek">Point and Shriek</a></li>
        <li><a href="#Polarization">Polarization</a></li>
        <li><a href="#Pornography">Pornography</a></li>
        <li><a href="#PotemkinVillageEvidence">Potemkin Village Evidence</a></li>
        <li><a href="#PrepareMeasure">Prepare Measure</a></li>
        <li><a href="#Pretexting">Pretexting</a></li>
        <li><a href="#PreventionMeasure">Prevention Measure</a></li>
        <li><a href="#PrivacyThreat">Privacy Threat</a></li>
        <li><a href="#Profanity">Profanity</a></li>
        <li><a href="#ProfessionalSupport">Professional Support</a></li>
        <li><a href="#Propaganda">Propaganda</a></li>
        <li><a href="#Prosecution">Prosecution</a></li>
        <li><a href="#PsychographicHacking">Psychographic Hacking</a></li>
        <li><a href="#PsychologicalHarm">Psychological Harm</a></li>
        <li><a href="#QuidProQuo">Quid Pro Quo</a></li>
        <li><a href="#Radicalization">Radicalization</a></li>
        <li><a href="#Raiding">Raiding</a></li>
        <li><a href="#Ransomware">Ransomware</a></li>
        <li><a href="#Reconnaissance">Reconnaissance</a></li>
        <li><a href="#RecoverMeasure">Recover Measure</a></li>
        <li><a href="#RecoveryPlan">Recovery Plan</a></li>
        <li><a href="#ReducedOpportunities">Reduced Opportunities</a></li>
        <li><a href="#ReducedPerformance">Reduced Performance</a></li>
        <li><a href="#RedundancyMeasure">Redundancy Measure</a></li>
        <li><a href="#RemoteCodeExecution">Remote Code Execution</a></li>
        <li><a href="#RemovalMeasure">Removal Measure</a></li>
        <li><a href="#Replay">Replay</a></li>
        <li><a href="#ReportingMeasure">Reporting Measure</a></li>
        <li><a href="#ReputationResource">Reputation Resource</a></li>
        <li><a href="#ReputationalHarm">Reputational Harm</a></li>
        <li><a href="#ReserveThreat">Reserve Threat</a></li>
        <li><a href="#Resource">Resource</a></li>
        <li><a href="#Response">Response</a></li>
        <li><a href="#RestrictiveMediation">Restrictive Mediation</a></li>
        <li><a href="#RighttoAssembly">Right to Assembly</a></li>
        <li><a href="#RighttoExpression">Right to Expression</a></li>
        <li><a href="#RighttoInformation">Right to Information</a></li>
        <li><a href="#RighttoInformationPrivacy">Right to Information Privacy</a></li>
        <li><a href="#RighttoOpinion">Right to Opinion</a></li>
        <li><a href="#RighttoPhysicalPrivacy">Right to Physical Privacy</a></li>
        <li><a href="#RighttoPrivacy">Right to Privacy</a></li>
        <li><a href="#RighttoPsychologicalPrivacy">Right to Psychological Privacy</a></li>
        <li><a href="#RighttoSocialPrivacy">Right to Social Privacy</a></li>
        <li><a href="#RighttoTerritorialPrivacy">Right to Territorial Privacy</a></li>
        <li><a href="#Rights">Rights</a></li>
        <li><a href="#SDCard">SD Card</a></li>
        <li><a href="#Sandboxing">Sandboxing</a></li>
        <li><a href="#Satire">Satire</a></li>
        <li><a href="#Scam">Scam</a></li>
        <li><a href="#ScamCost">Scam Cost</a></li>
        <li><a href="#Scareware">Scareware</a></li>
        <li><a href="#Sealioning">Sealioning</a></li>
        <li><a href="#SelfHarm">Self Harm</a></li>
        <li><a href="#Self-Censorship">Self-Censorship</a></li>
        <li><a href="#Server">Server</a></li>
        <li><a href="#Sextortion">Sextortion</a></li>
        <li><a href="#SexualAbuseThreat">Sexual Abuse Threat</a></li>
        <li><a href="#SexualAssault">Sexual Assault</a></li>
        <li><a href="#Shameful">Shameful</a></li>
        <li><a href="#Shilling">Shilling</a></li>
        <li><a href="#Skills">Skills</a></li>
        <li><a href="#Skimming">Skimming</a></li>
        <li><a href="#Smishing">Smishing</a></li>
        <li><a href="#SocialCapitalResource">Social Capital Resource</a></li>
        <li><a href="#SocialContact">Social Contact</a></li>
        <li><a href="#SocialEngineering">Social Engineering</a></li>
        <li><a href="#SocialHacking">Social Hacking</a></li>
        <li><a href="#SocialHarm">Social Harm</a></li>
        <li><a href="#SocialMediaHygiene">Social Media Hygiene</a></li>
        <li><a href="#SocialMediaMonitoring">Social Media Monitoring</a></li>
        <li><a href="#SocialNetworkResource">Social Network Resource</a></li>
        <li><a href="#SocialSupport">Social Support</a></li>
        <li><a href="#SocialWithdrawal">Social Withdrawal</a></li>
        <li><a href="#SocietalandSocialThreat">Societal and Social Threat</a></li>
        <li><a href="#Socio-cognitiveHacking">Socio-cognitive Hacking</a></li>
        <li><a href="#SockPuppetry">Sock Puppetry</a></li>
        <li><a href="#Software">Software</a></li>
        <li><a href="#SoftwareRedundancy">Software Redundancy</a></li>
        <li><a href="#SoftwareVulnerability">Software Vulnerability</a></li>
        <li><a href="#SolitudeThreat">Solitude Threat</a></li>
        <li><a href="#SourceRedundancy">Source Redundancy</a></li>
        <li><a href="#SpamEmail">Spam Email</a></li>
        <li><a href="#SpearPhishing">Spear Phishing</a></li>
        <li><a href="#Spoofing">Spoofing</a></li>
        <li><a href="#StorageAsset">Storage Asset</a></li>
        <li><a href="#StrawmanAttack">Strawman Attack</a></li>
        <li><a href="#Surveillance">Surveillance</a></li>
        <li><a href="#SweepstakesScam">Sweepstakes Scam</a></li>
        <li><a href="#Sympathy">Sympathy</a></li>
        <li><a href="#SystemRecovery">System Recovery</a></li>
        <li><a href="#Tailgating">Tailgating</a></li>
        <li><a href="#TechnicalMediation">Technical Mediation</a></li>
        <li><a href="#TechnologicalThreat">Technological Threat</a></li>
        <li><a href="#TheftHarm">Theft Harm</a></li>
        <li><a href="#TheftThreat">Theft Threat</a></li>
        <li><a href="#TheftofFinances">Theft of Finances</a></li>
        <li><a href="#Threat">Threat</a></li>
        <li><a href="#ThreatMonitoringMeasure">Threat Monitoring Measure</a></li>
        <li><a href="#TimeWasted">Time Wasted</a></li>
        <li><a href="#Training">Training</a></li>
        <li><a href="#TransferInformationAttack">Transfer Information Attack</a></li>
        <li><a href="#Trolling">Trolling</a></li>
        <li><a href="#TrustedData">Trusted Data</a></li>
        <li><a href="#TrustedInformation">Trusted Information</a></li>
        <li><a href="#TrustedInfrastructure">Trusted Infrastructure</a></li>
        <li><a href="#TrustedNetworking">Trusted Networking</a></li>
        <li><a href="#TrustedSoftware">Trusted Software</a></li>
        <li><a href="#USBDrive">USB Drive</a></li>
        <li><a href="#UnauthorizedAccess">Unauthorized Access</a></li>
        <li><a href="#Unavailable">Unavailable</a></li>
        <li><a href="#UnderScrutiny">Under Scrutiny</a></li>
        <li><a href="#UnsolicitedCommunication">Unsolicited Communication</a></li>
        <li><a href="#UnsolicitedSocialRequest">Unsolicited Social Request</a></li>
        <li><a href="#Urgency">Urgency</a></li>
        <li><a href="#UserIdentification">User Identification</a></li>
        <li><a href="#User-GeneratedContent">User-Generated Content</a></li>
        <li><a href="#Vandalism">Vandalism</a></li>
        <li><a href="#Violation">Violation</a></li>
        <li><a href="#VirtualPrivateNetwork">Virtual Private Network</a></li>
        <li><a href="#Vishing">Vishing</a></li>
        <li><a href="#VoilentContent">Voilent Content</a></li>
        <li><a href="#Vulnerability">Vulnerability</a></li>
        <li><a href="#WebHygiene">Web Hygiene</a></li>
        <li><a href="#WhalingPhishing">Whaling Phishing</a></li>
        <li><a href="#WhatAboutism">WhatAboutism</a></li>
        <li><a href="#WithstandMeasure">Withstand Measure</a></li>
        <li><a href="#Worry">Worry</a></li>
        <li><a href="#YouAreNotImmune">You Are Not Immune</a></li>
    </ul>
    <div class="entity class" id="AbsorbMeasure">
        <h3>Absorb Measure<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#AbsorbMeasure</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Responses are framed around four resilience phases of Prepare, Absorb, Recover, and Adapt.</p>
<p>The Absorb phase is triggered by the occurrence of an adverse cyber event, which diminishes and degrades individuals’ overall core cyber functioning (i.e., harmful impact). The effectiveness of the Absorb measures adopted in this phase determines the extent of the impact of the adverse incident.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#Response">sc2r:Response</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
            <tr>
                <th>Sub-classes</th>
                <td>
                    <a href="#WithstandMeasure">sc2r:WithstandMeasure</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#EngageMeasure">sc2r:EngageMeasure</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#ReportingMeasure">sc2r:Reporting</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="AbuseThreat">
        <h3>Abuse Threat<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Abuse</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Abuse threats emanate from the harmful treatment of individuals online.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#IndividualandPersonalThreat">sc2r:PersonalThreat</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
            <tr>
                <th>Sub-classes</th>
                <td>
                    <a href="#SexualAbuseThreat">sc2r:SexualAbuse</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#Cyberbullying">sc2r:Cyberbullying</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#UnsolicitedCommunication">sc2r:UnsolicitedCommunication</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#Flaming">sc2r:Flaming</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#CyberPredator">sc2r:CyberPredator</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#CyberStalking">sc2r:CyberStalking</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#Trolling">sc2r:Trolling</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="AbusedHarm">
        <h3>Abused Harm<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Abused</code></td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#PhysicalHarm">sc2r:PhysicalHarm</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="AccessControl">
        <h3>Access Control<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#AccessControl</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Access control is the prevention measure that involves controlling and authorizing access to cyber resources</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#PreventionMeasure">sc2r:PreventionMeasure</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
            <tr>
                <th>Sub-classes</th>
                <td>
                    <a href="#Sandboxing">sc2r:Sandboxing</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#LeastPrivilege">sc2r:LeastPrivilege</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#Firewall">sc2r:Firewall</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#PhysicalRestriction">sc2r:PhysicalRestriction</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="AccountHijacking">
        <h3>Account Hijacking<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#AccountHijacking</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>This is the process where an individuals account is hijacked or stolen by someone else.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#AuthenticationThreat">sc2r:AuthenticationThreat</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="AccountRecovery">
        <h3>Account Recovery<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#AccountRecovery</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Account recovery measures involve restoring access and control of an account after an adverse cyber incident.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#RecoverMeasure">sc2r:RecoverMeasure</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="ActiveMediation">
        <h3>Active Mediation<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#ActiveMediation</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Active Mediation involves awareness-raising and discussion with potential victims of adverse cyber incidents.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#MediationMeasures">sc2r:MediationMeasures</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="ActivityData">
        <h3>Activity Data<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#ActivityData</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Activity Data is the record of any user action (online or in the physical world) that can be logged on a computer.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#PersonalData">sc2r:PersonalData</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="AdaptMeasure">
        <h3>Adapt Measure<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#AdaptMeasure</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Responses are framed around four resilience phases of Prepare, Absorb, Recover, and Adapt.</p>
<p>Once baseline cyber functioning has been restored, the Adapt phase can commence and Adapt measures can be put in the place, using the learnings and experience from the adverse event to inform the evolution and increase in cyber functioning and to “bounce forward better”</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#Response">sc2r:Response</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
            <tr>
                <th>Sub-classes</th>
                <td>
                    <a href="#CapacityBuilding">sc2r:CapacityBuilding</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#EvolveMeasure">sc2r:Evolve</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Addiction">
        <h3>Addiction<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Addiction</code></td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#PsychologicalHarm">sc2r:PsychologicalHarm</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Agency">
        <h3>Agency<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Agency</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Agency is the ability to define one’s goals and act upon them.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#IndividualPersonalResource">sc2r:IndividualResource</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
            <tr>
                <th>Sub-classes</th>
                <td>
                    <a href="#MentalFaculties">sc2r:MentalFaculties</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="AlternativeResourceMeasure">
        <h3>Alternative Resource Measure<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#AlternativeResource</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>This measure involves engaging alternative complementary cyber resources to deal with incidents that have deminished cyber functioning of primary resources.</p>
<p>For example, in cases of data corruption, the redundant backups of the data would be utilized. In cases where a computing device is damaged, an alternative device would be utilized.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#WithstandMeasure">sc2r:WithstandMeasure</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="AnglerPhishing">
        <h3>Angler Phishing<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#AnglerPhishing</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Angler Phishing occurs when individuals receive a message from a social media account masquerading as a corporate's customer support account that tricks them into handing over their sensitive information.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#Phishing">sc2r:Phishing</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="AnonymityThreat">
        <h3>Anonymity Threat<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#AnonymityThreat</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Anonimity Threat occurs when individuals' preference to remain anonymous or unnoticed online is threatened.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#PrivacyThreat">sc2r:PrivacyThreat</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="AnonymousRouting">
        <h3>Anonymous Routing<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#AnonymousRouting</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Anonymous routing is the use of computing networks in a way that protects communication from identification by third-party observers.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#TrustedNetworking">sc2r:TrustedNetworking</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="AnticipateMeasure">
        <h3>Anticipate Measure<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#AnticipateMeasure</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Anticipate Measure are put in place by individual to prepare for and anticipate the inevitability of adverse cyber incidents.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#PrepareMeasure">sc2r:PrepareMeasure</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
            <tr>
                <th>Sub-classes</th>
                <td>
                    <a href="#Training">sc2r:Training</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#RedundancyMeasure">sc2r:RedundancyMeasure</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#RecoveryPlan">sc2r:RecoveryPlan</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#AttitudinalMeasure">sc2r:AttitudinalMeasure</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#Awareness">sc2r:Awareness</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="RighttoAssembly">
        <h3>Right to Assembly<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Assembly</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>The Rght to Assemble (freedom of association) is individual's right to gather and meet, both publicly and privately.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#Rights">sc2r:Right</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="AssetInventoryManagement">
        <h3>Asset Inventory Management<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#AssetInventory</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Asset inventory Management involves maintaining a list of cyber resources and assets that individuals have access to.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#Awareness">sc2r:Awareness</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="AttitudinalMeasure">
        <h3>Attitudinal Measure<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#AttitudinalMeasure</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Attitudinal Measures are attitudes that individuals can adopt in the context of preparing and planning for adverse cyber incidents.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#AnticipateMeasure">sc2r:AnticipateMeasure</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
            <tr>
                <th>Sub-classes</th>
                <td>
                    <a href="#BeVigilant">sc2r:BeVigilant</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#YouAreNotImmune">sc2r:YouAreNotImmune</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#BeSuspicious">sc2r:BeSuspicious</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#BeCritical">sc2r:BeCritical</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="AuthenticationThreat">
        <h3>Authentication Threat<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#AuthenticationThreat</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Authentication threats compromise the Authentication cyber security goal.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#TechnologicalThreat">sc2r:TechnologicalThreat</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
            <tr>
                <th>Sub-classes</th>
                <td>
                    <a href="#UnauthorizedAccess">sc2r:UnauthorizedAccess</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#Masquerading">sc2r:Masquerading</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#Fabrication">sc2r:Fabrication</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#Spoofing">sc2r:Spoofing</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#AccountHijacking">sc2r:AccountHijacking</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="AvailabilityThreat">
        <h3>Availability Threat<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#AvailabilityThreat</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Availability Threats compromise the Availability cyber security goal.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#TechnologicalThreat">sc2r:TechnologicalThreat</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
            <tr>
                <th>Sub-classes</th>
                <td>
                    <a href="#LostCredentials">sc2r:LostCredentials</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#Disruption">sc2r:Disruption</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#DenialofService">sc2r:DenialOfService</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#Ransomware">sc2r:Ransomware</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#LostDevices">sc2r:LostDevices</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Awareness">
        <h3>Awareness<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Awareness</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Awareness measures enhance the ability of individuals to comprehend their cybersecurity landscape.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#AnticipateMeasure">sc2r:AnticipateMeasure</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
            <tr>
                <th>Sub-classes</th>
                <td>
                    <a href="#DigitalFootprintManagement">sc2r:DigitalFootprint</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#AssetInventoryManagement">sc2r:AssetInventory</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Baiting">
        <h3>Baiting<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Baiting</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Baiting occurs when individuals are tricked into handing their login credentials to the perpetrator who leverages the offer of free items or goods.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#SocialEngineering">sc2r:SocialEngineering</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="BandwagonEffect">
        <h3>Bandwagon Effect<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#BandwagonEffect</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Bandwagon Effect (contagion effect) refers to the creation of the illusion of group consensus to cause people to think or act in the same way as the group does.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#PsychographicHacking">sc2r:PsychographicHacking</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="BeCritical">
        <h3>Be Critical<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#BeCritical</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>This attitute emphasizes the need to be critical in online engagements. </p>
<p>For example being critical with regards to news and content consumed online.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#AttitudinalMeasure">sc2r:AttitudinalMeasure</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="BeSuspicious">
        <h3>Be Suspicious<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#BeSuspicious</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>This attitute emphasizes the importance of being suspicious online.</p>
<p>For example, being suspicious of unsolicited communication.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#AttitudinalMeasure">sc2r:AttitudinalMeasure</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="BeVigilant">
        <h3>Be Vigilant<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#BeVigilant</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>This attitute emphasizes the need to be vigilant online.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#AttitudinalMeasure">sc2r:AttitudinalMeasure</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="BehavioralData">
        <h3>Behavioral Data<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#BehaviouralData</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Behavioural Data refers to data collected from individual's online activities, typically commercial behaviour using a range of devices connected to the Internet. Behavioural data tracks the sites visited, the apps downloaded, or the games played.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#PersonalData">sc2r:PersonalData</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="BiometricToken">
        <h3>BiometricToken<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#BiometricToken</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Biometric Token is a biometric-based security token that is used for authentication or verification purpose.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#Credential">sc2r:Credential</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="BlackPropaganda">
        <h3>Black Propaganda<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#BlackPropaganda</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Where white propaganda clearly states its source and grey propaganda obscures its origins, black propaganda actively deceives about its origins</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#SocialHacking">sc2r:SocialHacking</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Blacklisted">
        <h3>Blacklisted<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Blacklisted</code></td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#ReputationalHarm">sc2r:ReputationalHarm</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="BodilyInjury">
        <h3>Bodily Injury<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#BodilyInjury</code></td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#PhysicalHarm">sc2r:PhysicalHarm</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
            <tr>
                <th>Sub-classes</th>
                <td>
                    <a href="#SelfHarm">sc2r:SelfHarm</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#BodilyPain">sc2r:Pain</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="BoyfriendingandGirlfriending">
        <h3>Boyfriending and Girlfriending<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#BoyfriendingGirlfriending</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Boyfriending/girlfriending occurs when individuals are manipulated into thinking that they are in a relationship with the perpetrator.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#SexualAbuseThreat">sc2r:SexualAbuse</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="CapacityBuilding">
        <h3>Capacity Building<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#CapacityBuilding</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>The capacity-building measures involve increasing the level of nominal cyber functioning of individuals.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#AdaptMeasure">sc2r:AdaptMeasure</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Catphishing">
        <h3>Catphishing<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Catphishing</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Catphishing occurs when individuals are targeted by the perpetrator who creates a fictitious online profile to seduce them into a fictitious online relationship in order to benefit from them. The perpetrator often uses social media or dating sites to get to their target.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#Phishing">sc2r:Phishing</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Censorship">
        <h3>Censorship<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Censorship</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Censorship occurs when individuals are suppressed or constrained by institutions from achieving specific cyber functionings - including consuming and producing information, accessing content, software, or media.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#InstitutionalThreat">sc2r:InstitutionalThreat</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Cheerleading">
        <h3>Cheerleading<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Cheerleading</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Using information influence techniques to crowd out dissent</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#SocialHacking">sc2r:SocialHacking</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Coercion">
        <h3>Coercion<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Coercion</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Coercion occurs when individuals are persuaded by threats or force to do something.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#InfluenceThreat">sc2r:InfluenceThreat</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="CognitiveImpairement">
        <h3>Cognitive Impairement<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#CognitiveImpairement</code></td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#PsychologicalHarm">sc2r:PsychologicalHarm</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="CognitiveThreat">
        <h3>Cognitive Threat<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#CognitiveThreat</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Cognitive and Influece Threats are adverse incidents that compromise or affect individuals cognitive functioning. They include efforts to influence the perceptions, behaviour, and decisions of individuals for the benefit of others.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#IndividualandPersonalThreat">sc2r:PersonalThreat</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
            <tr>
                <th>Sub-classes</th>
                <td>
                    <a href="#Disinformation">sc2r:Disinformation</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#DigitalHoarding">sc2r:DigitalHoarding</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#InformationFlooding">sc2r:InformationFlooding</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#InformationOverload">sc2r:InformationOverload</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#Misinformation">sc2r:Misinformation</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#Malinformation">sc2r:Malinformation</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="CompensationPayment">
        <h3>Compensation Payment<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#CompensationPayment</code></td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#EconomicHarm">sc2r:EconomicHarm</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Compromised">
        <h3>Compromised<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Compromised</code></td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#PhysicalHarm">sc2r:PhysicalHarm</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Computer">
        <h3>Computer<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Computer</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Computer is an electronic device that can store, retrieve, and process data.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#ComputingAsset">sc2r:ComputingAsset</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="ComputingAsset">
        <h3>Computing Asset<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#ComputingAsset</code></td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#PhysicalResource">sc2r:PhysicalResource</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
            <tr>
                <th>Sub-classes</th>
                <td>
                    <a href="#Laptop">sc2r:Laptop</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#Computer">sc2r:Computer</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#MobileDevice">sc2r:MobileDevice</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#Server">sc2r:Server</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="ConfidentialityThreat">
        <h3>Confidentiality Threat<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#ConfidentialityThreat</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Confidentiality Threats compromise the Confidentiality cybersecurity goal.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#TechnologicalThreat">sc2r:TechnologicalThreat</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
            <tr>
                <th>Sub-classes</th>
                <td>
                    <a href="#DataBreach">sc2r:DataBreach</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#Doxing">sc2r:Doxing</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#InadvertentInformationDisclosure">sc2r:InadvertentDisclosure</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#DataLeak">sc2r:DataLeak</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#Skimming">sc2r:Skimming</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#Interception">sc2r:Interception</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#Reconnaissance">sc2r:Reconnaissance</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Conflict">
        <h3>Conflict<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Conflict</code></td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#SocialHarm">sc2r:SocialHarm</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="ConfronttheThreat">
        <h3>Confront the Threat<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#ConfrontThreat</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Confronting the threat is an engage response that involves directly confronting the cyber threat. For examples, in the case of socio-technical threats, this involves direct engagement with the threat actors.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#EngageMeasure">sc2r:EngageMeasure</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Confusion">
        <h3>Confusion<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Confusion</code></td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#PsychologicalHarm">sc2r:PsychologicalHarm</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
            <tr>
                <th>Sub-classes</th>
                <td>
                    <a href="#Misled">sc2r:Misled</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Conscientiousness">
        <h3>Conscientiousness<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Conscientiousness</code></td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#IndividualandPersonalVulnerability">sc2r:Individual</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="BreachofContract">
        <h3>Breach of Contract<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#ContractBreach</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>A contract breach occurs when individuals break conditions of a contract in the course of utilizing cyber resources.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#Violation">sc2r:Violation</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Corrupted">
        <h3>Corrupted<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Corrupted</code></td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#PhysicalHarm">sc2r:PhysicalHarm</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Credential">
        <h3>Credential<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Credential</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>A Credential is the tool for authentication or verification. A credential may be part of a certificate or other authentication process that helps confirm a user’s identity in relation to a network address or other system ID.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#IdentifyingData">sc2r:IdentifyingData</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
            <tr>
                <th>Sub-classes</th>
                <td>
                    <a href="#PhysicalToken">sc2r:PhysicalToken</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#DataToken">sc2r:DataToken</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#BiometricToken">sc2r:BiometricToken</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Couriosity">
        <h3>Couriosity<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Curiosity</code></td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#IndividualandPersonalVulnerability">sc2r:Individual</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="CyberPredator">
        <h3>Cyber Predator<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#CyberPredator</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Cyber Predator refers to those who use the Internet to exploit others, usually young people, for emotional, sexual, and other purposes.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#AbuseThreat">sc2r:Abuse</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="CyberStalking">
        <h3>Cyber Stalking<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#CyberStalking</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Cyber Stalking occurs to individuals when they are being stalked online or through the use of digital technology. Motives for cyber stalking may be to control or intimidate the victim, or to gather information for use in other crimes.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#AbuseThreat">sc2r:Abuse</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Cyberbullying">
        <h3>Cyberbullying<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Cyberbullying</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Cyberbullying occurs when individuals are bullied, harassed, humiliated, threatened, embarrased, or targeted through the use of online communication methods.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#AbuseThreat">sc2r:Abuse</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="CryptoCurrency">
        <h3>Crypto Currency<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#CyptoCurrency</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>A Cryptocurrency is a digital or virtual currency that is secured by cryptography.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#FileResource">sc2r:File</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Damage">
        <h3>Damage<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Damage</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>These are damages to cyber resources, including data, software, and hard, that compromise the integrity and proper functioning of the resources.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#IntegrityThreat">sc2r:IntegrityThreat</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="DamagedRelationship">
        <h3>Damaged Relationship<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#DamagedRelationship</code></td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#SocialHarm">sc2r:SocialHarm</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="DamagedSocialPerception">
        <h3>Damaged Social Perception<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#DamagedSocialPerception</code></td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#ReputationalHarm">sc2r:ReputationalHarm</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="DarkAdvertising">
        <h3>Dark Advertising<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#DarkAdvertising</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Dark Advertising is a type of advertising where the message can only be seen by the advertiser and the specific target group. Other people with dissimilar interests or who fall outside of the target group will usually be completely unaware of their existence.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#PsychographicHacking">sc2r:PsychographicHacking</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Data">
        <h3>Data<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Data</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Data is information that has been translated into a form that is efficient for movement or processing.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#DigitalResource">sc2r:DigitalResource</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
            <tr>
                <th>Sub-classes</th>
                <td>
                    <a href="#PersonalData">sc2r:PersonalData</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#FileResource">sc2r:File</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="DataBreach">
        <h3>Data Breach<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#DataBreach</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>A data breach occurs when there is unauthorized access to data as a result of an attacker exploiting data systems which host individuals' confidential data. The source of data breaches is external.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#ConfidentialityThreat">sc2r:ConfidentialityThreat</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="DataCorruption">
        <h3>Data Corruption<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#DataCorruption</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Data Corruption occurs when there are errors to data which compromise the integrity of the data.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#IntegrityThreat">sc2r:IntegrityThreat</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="DataError">
        <h3>Data Error<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#DataError</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>These are data errors that compromise the integrity of data.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#IntegrityThreat">sc2r:IntegrityThreat</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="DataLeak">
        <h3>Data Leak<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#DataLeak</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>A data leak occurs when confidential information is made accessible to unauthorized individuals a a result of an internal factor.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#ConfidentialityThreat">sc2r:ConfidentialityThreat</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="DataRecovery">
        <h3>Data Recovery<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#DataRecovery</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Data recovery measures involve the recovery of data resources, from data backups, to enable continued use of a data after an adverse cyber incident, such as data corruption and loss.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#RecoverMeasure">sc2r:RecoverMeasure</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="DataRedundancy">
        <h3>Data Redundancy<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#DataRedundancy</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Data redundancy measure involves having data backups and redundant data storage.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#RedundancyMeasure">sc2r:RedundancyMeasure</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="DataToken">
        <h3>DataToken<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#DataToken</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Data Token is tokenized data access that is used to secure access to data.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#Credential">sc2r:Credential</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="DataVulnerability">
        <h3>Data Vulnerability<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#DataVulnerability</code></td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#DigitalVulnerability">sc2r:Digital</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Deceit">
        <h3>Deceit<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Deceit</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Threat of deceptive content and information</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#Disinformation">sc2r:Disinformation</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
            <tr>
                <th>Sub-classes</th>
                <td>
                    <a href="#Forging">sc2r:Forging</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#PotemkinVillageEvidence">sc2r:PotemkinVillageEvidence</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#Shilling">sc2r:Shilling</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="DemocraphicInformation">
        <h3>Democraphic Information<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#DemographicInformation</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Demographic Information is information about groups of people according to certain attributes, such as age, gender, place of residence, and socio-economic status.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#PersonalData">sc2r:PersonalData</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="DenialofService">
        <h3>Denial of Service<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#DenialOfService</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>A Denial of Service occurs when attackers maliciously restrict and limit access to information and services from legitimate users.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#AvailabilityThreat">sc2r:AvailabilityThreat</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Depressed">
        <h3>Depressed<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Depressed</code></td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#PsychologicalHarm">sc2r:PsychologicalHarm</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Destroyed">
        <h3>Destroyed<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Destroyed</code></td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#PhysicalHarm">sc2r:PhysicalHarm</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="DeviceIdentification">
        <h3>Device Identification<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#DeviceIdentification</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Device authentication is the process is verifying the identity of the devices that are used to connect to network resources.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#Identification">sc2r:Identification</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="DiffusionofResponsibility">
        <h3>Diffusion of Responsibility<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#DiffusionOfResponsibility</code></td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#IndividualandPersonalVulnerability">sc2r:Individual</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="DigitalVulnerability">
        <h3>Digital Vulnerability<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Digital</code></td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#Vulnerability">sc2r:Vulnerability</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
            <tr>
                <th>Sub-classes</th>
                <td>
                    <a href="#DataVulnerability">sc2r:DataVulnerability</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#SoftwareVulnerability">sc2r:SoftwareVulnerability</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#NetworkVulnerability">sc2r:NetworkVulnerability</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="DigitalFootprintManagement">
        <h3>Digital Footprint Management<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#DigitalFootprint</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Digital Footprint management involves understanding the digital resources, including the trail of data, that is involved and used in individuals Cyber functionings.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#Awareness">sc2r:Awareness</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="DigitalHoarding">
        <h3>Digital Hoarding<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#DigitalHoarding</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Digital hoarding (also known as e-hoarding, datahording or cyberhoarding) is excessive acquisition and reluctance to delete electronic material no longer valuable to the user</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#CognitiveThreat">sc2r:CognitiveThreat</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="DigitalResource">
        <h3>Digital Resource<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#DigitalResource</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Digital resources are resources that have been conceived and created digitally or by converting analogue materials to a digital format (digitised).</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#Resource">sc2r:Resource</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
            <tr>
                <th>Sub-classes</th>
                <td>
                    <a href="#Data">sc2r:Data</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#Software">sc2r:Software</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Discomfort">
        <h3>Discomfort<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Discomfort</code></td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#PsychologicalHarm">sc2r:PsychologicalHarm</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="DisconnectMeasure">
        <h3>Disconnect Measure<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#DisconnectMeasure</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>The Disconnect measure involves removal of connection and interaction between the threat and the affected cyber resource. While the threat remains, the affected resource is removed from the attack situation.</p>
<p>For example, in the case of a Remote Execution attack or Denial of Service attack, this could include physical disconnection of affected devices from the network. In the case of socio-technical threats, such as cyberbullying, it could include disconnecting from the relevant platform.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#EngageMeasure">sc2r:EngageMeasure</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Disempowerment">
        <h3>Disempowerment<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Disempowerment</code></td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#PsychologicalHarm">sc2r:PsychologicalHarm</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Disinformation">
        <h3>Disinformation<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Disinformation</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Disinformation is false or misleading information that is spread deliberately to cause harm. This is a subset of misinformation, which may also be unintentional.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#CognitiveThreat">sc2r:CognitiveThreat</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
            <tr>
                <th>Sub-classes</th>
                <td>
                    <a href="#EngineeredContent">sc2r:EngineeredContent</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#MalignRhetoric">sc2r:MalignRhetoric</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#Propaganda">sc2r:Propaganda</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#FakeNews">sc2r:FakeNews</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#Deceit">sc2r:Deceit</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#InfluenceOperation">sc2r:InfluenceOperation</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#OpposingInformation">sc2r:OpposingInformation</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="DisruptedIncome">
        <h3>Disrupted Income<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#DisruptedIncome</code></td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#EconomicHarm">sc2r:EconomicHarm</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="DisruptedWork">
        <h3>Disrupted Work<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#DisruptedWork</code></td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#EconomicHarm">sc2r:EconomicHarm</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Disruption">
        <h3>Disruption<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Disruption</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Disruption occurs when individuals access to information and resources is disrupted.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#AvailabilityThreat">sc2r:AvailabilityThreat</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Distraction">
        <h3>Distraction<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Distraction</code></td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#PsychologicalHarm">sc2r:PsychologicalHarm</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Doxing">
        <h3>Doxing<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Doxing</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Doxing is when private and confidential information about individuals is researched and published online with malicious intent.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#ConfidentialityThreat">sc2r:ConfidentialityThreat</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Eavesdropping">
        <h3>Eavesdropping<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Eavesdropping</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Eavesdropping occurs when attackes secretly and stealthly gain access to private and confidential communication without the consent of and the authorization from the communicating parties.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#Interception">sc2r:Interception</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="EconomicHarm">
        <h3>Economic Harm<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#EconomicHarm</code></td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#Harm">sc2r:Harm</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
            <tr>
                <th>Sub-classes</th>
                <td>
                    <a href="#CompensationPayment">sc2r:CompensationPayment</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#FinePayment">sc2r:Fine</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#TheftofFinances">sc2r:TheftOfFinances</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#ScamCost">sc2r:ScamCost</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#ExtorsionPayment">sc2r:ExtorsionPayment</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#LossofWork">sc2r:LossOfWork</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#MitigationCost">sc2r:MitigationCost</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#DisruptedWork">sc2r:DisruptedWork</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#DisruptedIncome">sc2r:DisruptedIncome</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#TimeWasted">sc2r:TimeWasted</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Electricity">
        <h3>Electricity<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Electricity</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Electricity is the flow of electrical power or charge that is used to power the infrastructures supporting our cyber functionings.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#InfrastructureResource">sc2r:InfrastructureResource</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="EmailHygiene">
        <h3>Email Hygiene<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#EmailHygiene</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Email hygiene are measures and practices that contribute to safe and secure use of email.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#WebHygiene">sc2r:WebHygiene</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Embarrassed">
        <h3>Embarrassed<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Embarrassed</code></td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#PsychologicalHarm">sc2r:PsychologicalHarm</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="EngageMeasure">
        <h3>Engage Measure<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#EngageMeasure</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Engage measures involve direct handling of and engagement with the adverse cyber incident.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#AbsorbMeasure">sc2r:AbsorbMeasure</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
            <tr>
                <th>Sub-classes</th>
                <td>
                    <a href="#DisconnectMeasure">sc2r:DisconnectMeasure</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#IsolateMeasure">sc2r:IsolateMeasure</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#RemovalMeasure">sc2r:RemovalMeasure</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#ConfronttheThreat">sc2r:ConfrontThreat</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="EngineeredContent">
        <h3>Engineered Content<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#EngineeredContent</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Engineered content is broadly information that is produced for specific influence and cognitive disinformation objectives.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#Disinformation">sc2r:Disinformation</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="EnvironmentalThreat">
        <h3>Environmental Threat<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#EnvironmentalThreat</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Environmental Threats emanate from individuals' wider environmental and institutional context.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#Threat">sc2r:Threat</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
            <tr>
                <th>Sub-classes</th>
                <td>
                    <a href="#InstitutionalThreat">sc2r:InstitutionalThreat</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#NaturalDisasterThreat">sc2r:NaturalDisaster</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="EvolveMeasure">
        <h3>Evolve Measure<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Evolve</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>The evolve measure involves an adaptation in the use of cyber resource through the adoption of complementary resources that enable higher nominal cyber functioning.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#AdaptMeasure">sc2r:AdaptMeasure</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Exposed">
        <h3>Exposed<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Exposed</code></td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#PhysicalHarm">sc2r:PhysicalHarm</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="RighttoExpression">
        <h3>Right to Expression<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Expression</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>The Right to Expression (freedom of expression) is individual's right to express their beliefs, thoughts, ideas, and emotions about different issues.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#Rights">sc2r:Right</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="ExternalHardDrive">
        <h3>External Hard Drive<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#ExternalHardDrive</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>External Hard Drive is a portable storage device located outside of a computer that is connected through a USB cable or wireless connection.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#StorageAsset">sc2r:StorageAsset</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="ExternalSupport">
        <h3>External Support<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#ExternalSupport</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>External support involves receiving external input and support towards recovering and restoring cyber functioning.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#RecoverMeasure">sc2r:RecoverMeasure</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
            <tr>
                <th>Sub-classes</th>
                <td>
                    <a href="#ProfessionalSupport">sc2r:ProfessionalSupport</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#SocialSupport">sc2r:SocialSupport</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="ExtorsionPayment">
        <h3>Extorsion Payment<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#ExtorsionPayment</code></td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#EconomicHarm">sc2r:EconomicHarm</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Extortion">
        <h3>Extortion<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Extortion</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Extortion refers to the use of threat or intimidation by a perpetrator to gain something from the target.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#InfluenceThreat">sc2r:InfluenceThreat</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Fabrication">
        <h3>Fabrication<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Fabrication</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Fabrication refers to an attack where illigitimate information is generated under the pretence of a false identity.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#AuthenticationThreat">sc2r:AuthenticationThreat</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="FactChecking">
        <h3>Fact Checking<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Fact-checking</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Fact-checking involves establishing the truth and validating the facts behind a specific adverse incident. </p>
<p>In the case of socio-technical threats such as misinformation attacks, fact-checking involves establishing the veracity of the information consumed. In the case of technical threat, it would involve understanding the documenting the experience adverse incident.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#RecoverMeasure">sc2r:RecoverMeasure</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="FailureDetection">
        <h3>Failure Detection<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#FailureDetection</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Failure detection is the monitoring measures that involves checking for the failure in the operation of specific cyber resources.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#ThreatMonitoringMeasure">sc2r:ThreatMonitoringMeasure</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="FakeGiveaways">
        <h3>Fake Giveaways<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#FakeGiveways</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Fake Giveaway scam occurs individuals are promised a prize in exchange for doing something beforehand, such as paying a fee.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#Scam">sc2r:Scam</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="FakeNews">
        <h3>Fake News<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#FakeNews</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Fake News is news that include deliberate disinformation content.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#Disinformation">sc2r:Disinformation</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Fear">
        <h3>Fear<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Fear</code></td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#IndividualandPersonalVulnerability">sc2r:Individual</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="FeelingUpset">
        <h3>Feeling Upset<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#FeelingUpset</code></td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#PsychologicalHarm">sc2r:PsychologicalHarm</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="FileResource">
        <h3>File Resource<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#File</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>A File is an object on a computer that stores data, information, settings, or commands used with a computer program.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#Data">sc2r:Data</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
            <tr>
                <th>Sub-classes</th>
                <td>
                    <a href="#CryptoCurrency">sc2r:CyptoCurrency</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="FinancialData">
        <h3>FinancialData<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#FinancialData</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Financial Data is data on individual's assets, liabilities, equity, income, expenses, and cash flow.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#IdentifyingData">sc2r:IdentifyingData</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="FinePayment">
        <h3>Fine Payment<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Fine</code></td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#EconomicHarm">sc2r:EconomicHarm</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Firehosing">
        <h3>Firehosing<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Firehosing</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Firehosing (firehose of falsehood) is a technique in which a large number of messages are broadcast rapidly, repetitively, and continuously over multiple channels without regard for truth or consistency. While Gish Gallop usually refers to a single online encounter, firehosing involves a strategy of massive disinformation over time and in multiple venues.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#MalignRhetoric">sc2r:MalignRhetoric</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Firewall">
        <h3>Firewall<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Firewall</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Firewall is a mechanisms for allowing and denying access to specific network resources.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#AccessControl">sc2r:AccessControl</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Flaming">
        <h3>Flaming<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Flaming</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Flaming is the online act of posting insults, often laced with profanity or other offensive language on social networking sites</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#AbuseThreat">sc2r:Abuse</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Flooding">
        <h3>Flooding<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Flooding</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Flooding involves the generation of fraudulent messages to increase traffic on the network for consuming server’s or network’s resources.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#SocialHacking">sc2r:SocialHacking</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Forging">
        <h3>Forging<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Forging</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Forging is the illegitimate dissemination of falsified evidence.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#Deceit">sc2r:Deceit</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Fraud">
        <h3>Fraud<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Fraud</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Online Fraud is a type of deception or fraud scheme that uses the Internet and digital communications technology to provide fraudulent solicitations to prospective targets to conduct fraudulent transactions, or to transmit the proceeds of fraud to those connected with the scheme. Online fraud may include identity theft, non-delivery payment, and online advertising fraud.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#TheftThreat">sc2r:TheftThreat</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Frustration">
        <h3>Frustration<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Frustration</code></td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#PsychologicalHarm">sc2r:PsychologicalHarm</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="GishGalloping">
        <h3>Gish Galloping<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#GishGalloping</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Gish Galloping is a rhetorical tactic used to flood individuals with as many arguments as possible (without regard for accuracy or strength of the argument) in a way that make them feel overwhelmed. Gish galloping usually refers to a single online encounter, for example in an online debate setting.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#MalignRhetoric">sc2r:MalignRhetoric</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Gluttony">
        <h3>Gluttony<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Gluttony</code></td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#PsychologicalHarm">sc2r:PsychologicalHarm</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Greed">
        <h3>Greed<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Greed</code></td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#IndividualandPersonalVulnerability">sc2r:Individual</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Grooming">
        <h3>Grooming<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Grooming</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Grooming occurs when the pepetrator uses tactics to gain the target's trust and to develop a relationship with the target by giving complimenets, attention, affection, or gifts.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#SexualAbuseThreat">sc2r:SexualAbuse</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Guilt">
        <h3>Guilt<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Guilt</code></td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#IndividualandPersonalVulnerability">sc2r:Individual</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Guilty">
        <h3>Guilty<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Guilty</code></td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#PsychologicalHarm">sc2r:PsychologicalHarm</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="HardwareVulnerability">
        <h3>Hardware Vulnerability<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#HardwareVulnerability</code></td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#PhysicalVulnerability">sc2r:Physical</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Harm">
        <h3>Harm<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Harm</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>A Harm, also called Impact, is the negative consequences of unmitigated Threats</p>
                </td>
            </tr>
            <tr>
                <th>Sub-classes</th>
                <td>
                    <a href="#EconomicHarm">sc2r:EconomicHarm</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#ReputationalHarm">sc2r:ReputationalHarm</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#PhysicalHarm">sc2r:PhysicalHarm</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#PsychologicalHarm">sc2r:PsychologicalHarm</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#SocialHarm">sc2r:SocialHarm</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
            <tr>
                <th>In domain of</th>
                <td>
                    <a href="#isResultOf">sc2r:isResultOf</a><sup class="sup-op" title="object property">op</sup><br/>
                    <a href="#canBeResultOf">sc2r:canBeResultOf</a><sup class="sup-op" title="object property">op</sup><br/>
                </td>
            </tr>
            <tr>
                <th>In range of</th>
                <td>
                    <a href="#canResultIn">sc2r:canResultIn</a><sup class="sup-op" title="object property">op</sup><br/>
                    <a href="#resultsIn">sc2r:resultsIn</a><sup class="sup-op" title="object property">op</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Helpfulness">
        <h3>Helpfulness<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Helpfulness</code></td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#IndividualandPersonalVulnerability">sc2r:Individual</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="HumorandMeme">
        <h3>Humor and Meme<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#HumorAndMeme</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Humor and Memes that are employed to influence individuals and shape narratives.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#InfluenceOperation">sc2r:InfluenceOperation</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Identification">
        <h3>Identification<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Identification</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Identification is a prevention measure that involves confirming claimed identity online.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#PreventionMeasure">sc2r:PreventionMeasure</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
            <tr>
                <th>Sub-classes</th>
                <td>
                    <a href="#MutualAuthentication">sc2r:MutualAuthentication</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#PasswordManagement">sc2r:PasswordManagement</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#DeviceIdentification">sc2r:DeviceIdentification</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#MultifactorAuthentication">sc2r:MultiFactorAuthentication</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#UserIdentification">sc2r:UserIdentification</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="IdentifyingData">
        <h3>Identifying Data<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#IdentifyingData</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Identifying Data includes all kinds of data that can be used to identify an individual and their personal information.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#PersonalData">sc2r:PersonalData</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
            <tr>
                <th>Sub-classes</th>
                <td>
                    <a href="#Credential">sc2r:Credential</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#FinancialData">sc2r:FinancialData</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Identity">
        <h3>Identity<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Identity</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Identity consists of individual personal attributes, such as gender, race, ethnicity, abilities, and socio-economic status.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#IndividualPersonalResource">sc2r:IndividualResource</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="IdentityTheft">
        <h3>Identity Theft<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#IdentityTheft</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Identity theft is the deliberate use of someone else's identity, usually as a method to gain a financial advantage or obtain credit and other benefits in the other person's name, and perhaps to the other person's disadvantage or loss.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#TheftThreat">sc2r:TheftThreat</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="IdentityTheftHarm">
        <h3>Identity Theft Harm<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#IdentityTheftLoss</code></td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#PsychologicalHarm">sc2r:PsychologicalHarm</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="ImpairedPrivateSocialBoundary">
        <h3>Impaired Private Social Boundary<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#ImpairedPrivateSocialBoundary</code></td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#SocialHarm">sc2r:SocialHarm</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Impulsiveness">
        <h3>Impulsiveness<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Impulsiveness</code></td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#IndividualandPersonalVulnerability">sc2r:Individual</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="InadvertentInformationDisclosure">
        <h3>Inadvertent Information Disclosure<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#InadvertentDisclosure</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Inadvertent information disclosure occurs when individuals disclose private and confidential information inadvertently.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#ConfidentialityThreat">sc2r:ConfidentialityThreat</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="InappropriateContent">
        <h3>Inappropriate Content<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#InappropriateContent</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Inappropriate information is content that causes harm to individuals who consume it.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#Malinformation">sc2r:Malinformation</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
            <tr>
                <th>Sub-classes</th>
                <td>
                    <a href="#OffensiveLanguage">sc2r:OffensiveLanguage</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#VoilentContent">sc2r:Violence</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#Pornography">sc2r:Pornography</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#Profanity">sc2r:Profanity</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="IncidentReporting">
        <h3>Incident Reporting<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#IncidentReporting</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Incident reporting is the formal documentation and reporting of adverse cyber incidents that are experienced by individuals.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#ReportingMeasure">sc2r:Reporting</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="IncreaseResourceMeasure">
        <h3>Increase Resource Measure<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#IncreaseResources</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>This measure involves increasing resources that are allocated towards maintaining the desired level of cyber functioning and supplementing the affected resources. </p>
<p>For example, in cases where the adverse cyber incident deminished the quality of functioning of specific cyber resources, this measure would involve adding more resources (e.g., computing resources) to enable continue desired functioning.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#WithstandMeasure">sc2r:WithstandMeasure</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="IndividualandPersonalVulnerability">
        <h3>Individual and Personal Vulnerability<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Individual</code></td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#Vulnerability">sc2r:Vulnerability</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
            <tr>
                <th>Sub-classes</th>
                <td>
                    <a href="#DiffusionofResponsibility">sc2r:DiffusionOfResponsibility</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#Impulsiveness">sc2r:Impulsiveness</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#Helpfulness">sc2r:Helpfulness</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#Fear">sc2r:Fear</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#Greed">sc2r:Greed</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#Conscientiousness">sc2r:Conscientiousness</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#Couriosity">sc2r:Curiosity</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#Urgency">sc2r:Urgency</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#Guilt">sc2r:Guilt</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#Sympathy">sc2r:Sympathy</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="IndividualPersonalResource">
        <h3>Individual Personal Resource<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#IndividualResource</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Individual resources are a combination of natural endowments and what is acquired through social relationships.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#Resource">sc2r:Resource</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
            <tr>
                <th>Sub-classes</th>
                <td>
                    <a href="#SocialCapitalResource">sc2r:SocialCapital</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#Rights">sc2r:Right</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#Identity">sc2r:Identity</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#Agency">sc2r:Agency</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Infected">
        <h3>Infected<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Infected</code></td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#PhysicalHarm">sc2r:PhysicalHarm</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="InfluenceOperation">
        <h3>Influence Operation<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#InfluenceOperation</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Influence Operations are efforts to influence the perceptions, behaviour, and decisions of individuals for the benefit of others.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#Disinformation">sc2r:Disinformation</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
            <tr>
                <th>Sub-classes</th>
                <td>
                    <a href="#Satire">sc2r:Satire</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#HumorandMeme">sc2r:HumorAndMeme</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#Parody">sc2r:Parody</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="InfluenceThreat">
        <h3>Influence Threat<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#InfluenceThreat</code></td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#IndividualandPersonalThreat">sc2r:PersonalThreat</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
            <tr>
                <th>Sub-classes</th>
                <td>
                    <a href="#PsychographicHacking">sc2r:PsychographicHacking</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#Coercion">sc2r:Coercion</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#Extortion">sc2r:Extortion</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#Scareware">sc2r:Scareware</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#SocialEngineering">sc2r:SocialEngineering</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="RighttoInformation">
        <h3>Right to Information<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Information</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>The Right to Information is individual's right to access personal and non-personal information held by government.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#Rights">sc2r:Right</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="InformationFlooding">
        <h3>Information Flooding<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#InformationFlooding</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Information flooding occurs when individuals are exposed to too much information and data.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#CognitiveThreat">sc2r:CognitiveThreat</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="InformationOverload">
        <h3>Information Overload<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#InformationOverload</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Information overload occurs when individuals are exposed to too much information and data.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#CognitiveThreat">sc2r:CognitiveThreat</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="RighttoInformationPrivacy">
        <h3>Right to Information Privacy<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#InformationalPrivacy</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Informational Privacy is individual's right to determine for themselves when, how, and to what extend information about them is communicated to others.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#RighttoPrivacy">sc2r:Privacy</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="InfrastructureResource">
        <h3>Infrastructure Resource<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#InfrastructureResource</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Infrastructure resources are physical and virtual resources that support the internet-enabled flow, storage, processing, and analysis of data.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#Resource">sc2r:Resource</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
            <tr>
                <th>Sub-classes</th>
                <td>
                    <a href="#Electricity">sc2r:Electricity</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#InternetConnectivity">sc2r:InternetConnectivity</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="InstitutionalThreat">
        <h3>Institutional Threat<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#InstitutionalThreat</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Institution Threats are adverse cyber incidents that are associated with institutions within individuals' context.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#EnvironmentalThreat">sc2r:EnvironmentalThreat</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
            <tr>
                <th>Sub-classes</th>
                <td>
                    <a href="#Censorship">sc2r:Censorship</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#Surveillance">sc2r:Surveillance</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#Violation">sc2r:Violation</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="IntegrityThreat">
        <h3>Integrity Threat<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#IntegrityThreat</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Integrity Threats compromise the Integrity cybersecurity goal.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#TechnologicalThreat">sc2r:TechnologicalThreat</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
            <tr>
                <th>Sub-classes</th>
                <td>
                    <a href="#Replay">sc2r:Replay</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#Misconfiguration">sc2r:Misconfiguration</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#DataCorruption">sc2r:DataCorruption</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#Damage">sc2r:Damage</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#DataError">sc2r:DataError</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#RemoteCodeExecution">sc2r:RemoteExecution</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#Malware">sc2r:Malware</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#Malfunction">sc2r:Malfunction</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#Vandalism">sc2r:Vandalism</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Interception">
        <h3>Interception<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Interception</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Interception occurs when unauthorized access is gained to private or confidential information.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#ConfidentialityThreat">sc2r:ConfidentialityThreat</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
            <tr>
                <th>Sub-classes</th>
                <td>
                    <a href="#Eavesdropping">sc2r:Eavesdropping</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="InternetConnectivity">
        <h3>Internet Connectivity<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#InternetConnectivity</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Internet Connectivity refers to the way people are connected to the Internet, and may include dial-up telephone lines, always-on broadband connections, and wireless devices.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#InfrastructureResource">sc2r:InfrastructureResource</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="IntimacyThreat">
        <h3>Intimacy Threat<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#IntimacyThreat</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Intimacy Threat occurs when individuals' preference to be alone with their significant others in their intimate online environments is threatened.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#PrivacyThreat">sc2r:PrivacyThreat</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="IntrusionDetection">
        <h3>Intrusion Detection<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#IntrusionDetection</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Intrusion detection involves monitoring and checking for unauthorized access to cyber resources including networking resources.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#ThreatMonitoringMeasure">sc2r:ThreatMonitoringMeasure</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="IsolateMeasure">
        <h3>Isolate Measure<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#IsolateMeasure</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>The isolate measure involves isolating the affected cyber resources from the connection with the threat. </p>
<p>While related to Disconnect measures, isolation measures involve the continual operation of the cyber resources in an isolated context.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#EngageMeasure">sc2r:EngageMeasure</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Isolation">
        <h3>Isolation<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Isolation</code></td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#SocialHarm">sc2r:SocialHarm</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="KnowledgeResource">
        <h3>Knowledge Resource<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Knowledge</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Knowledge is familiarity with, awareness, or understanding of various objects, events, ideas, or ways of doing things which is acquired through experience or education.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#MentalFaculties">sc2r:MentalFaculties</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Laptop">
        <h3>Laptop<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Laptop</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>A Laptop is a portable computer.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#ComputingAsset">sc2r:ComputingAsset</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Laundering">
        <h3>Laundering<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Laundering</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Laundering is a combination of several techniques, such as tainted leaks, fake news, and potemkin village to create the appearance of legitimate and significant controversy where there is none.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#SocialHacking">sc2r:SocialHacking</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="LeastPrivilege">
        <h3>Least Privilege<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#LeastPrivilege</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Least privilege is the principle and mechanism of giving the minimum required privileges necessary for performing specific functions.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#AccessControl">sc2r:AccessControl</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="LocationData">
        <h3>Location Data<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#LocationData</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Location data is geographial information about a specific device's whereabouts associated to a time identifier.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#PersonalData">sc2r:PersonalData</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="LoggingandAudit">
        <h3>Logging and Audit<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#LoggingAndAudit</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Logging and audit is a monitoring measures that involves keeping a record of relevant cyber activities, events, as well as states and operations of cyber resources.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#MonitoringMeasure">sc2r:MonitoringMeasure</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="LossofConfidence">
        <h3>Loss of Confidence<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#LossOfConfidence</code></td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#PsychologicalHarm">sc2r:PsychologicalHarm</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="LossofLife">
        <h3>Loss of Life<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#LossOfLife</code></td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#PhysicalHarm">sc2r:PhysicalHarm</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="LossofWork">
        <h3>Loss of Work<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#LossOfWork</code></td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#EconomicHarm">sc2r:EconomicHarm</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="LostCredentials">
        <h3>Lost Credentials<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#LostCredentials</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Lost Credentials is when access to information and services is not possible due to lost account creditials.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#AvailabilityThreat">sc2r:AvailabilityThreat</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="LostDevices">
        <h3>Lost Devices<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#LostDevices</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>This is a loss of computing devices that results in lack of access to the associated information and services.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#AvailabilityThreat">sc2r:AvailabilityThreat</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="LoveBombing">
        <h3>Love Bombing<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#LoveBombing</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Love Bombing occurs when the perpetrator gives the target an abundance of compliments and affection to gain their love and trust.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#SexualAbuseThreat">sc2r:SexualAbuse</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="LowMorale">
        <h3>Low Morale<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#LowMorale</code></td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#PsychologicalHarm">sc2r:PsychologicalHarm</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="LowSatisfaction">
        <h3>Low Satisfaction<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#LowSatisfaction</code></td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#PsychologicalHarm">sc2r:PsychologicalHarm</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="LuringSexualThreat">
        <h3>Luring Sexual Threat<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Luring</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Luring occurs when the perpetrator uses online communication to contact the target who they think is under 18, in order to make it easier for them to commit a sexual offence against them.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#SexualAbuseThreat">sc2r:SexualAbuse</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Malfunction">
        <h3>Malfunction<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Malfunction</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Malfunctions occurs when systems do not function as they are supposed to. This can be due to malicious factors or human errors.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#IntegrityThreat">sc2r:IntegrityThreat</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="MaliciousContactRemoval">
        <h3>Malicious Contact Removal<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#MaliciousContactRemoval</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>This measures involves the removal and elimination of contact with an individual who is a threat actor.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#RemovalMeasure">sc2r:RemovalMeasure</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="MaliciousContentRemoval">
        <h3>Malicious Content Removal<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#MaliciousContentRemoval</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>This measures involves the removal and elimination of content that is a cause of a cyber threat.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#RemovalMeasure">sc2r:RemovalMeasure</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="MaliciousSoftwareDetection">
        <h3>Malicious Software Detection<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#MaliciousSoftwareDetection</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Malicious software detection involves scanning computing equipment to check for the presence of malicious software.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#ThreatMonitoringMeasure">sc2r:ThreatMonitoringMeasure</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="MaliciousSoftwareRemoval">
        <h3>Malicious Software Removal<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#MaliciousSoftwareRemoval</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>This measures involves the removal and elimination of software, usually malware, that is a source of a cyber threat.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#RemovalMeasure">sc2r:RemovalMeasure</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="MalignRhetoric">
        <h3>Malign Rhetoric<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#MalignRhetoric</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Malign Rhetoric is an influence effort that aims to subvert and undermine specific narratives and views that individuals might hold.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#Disinformation">sc2r:Disinformation</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
            <tr>
                <th>Sub-classes</th>
                <td>
                    <a href="#Firehosing">sc2r:Firehosing</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#GishGalloping">sc2r:GishGalloping</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#WhatAboutism">sc2r:WhatAboutism</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#StrawmanAttack">sc2r:Strawman</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#TransferInformationAttack">sc2r:Transfer</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Malinformation">
        <h3>Malinformation<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Malinformation</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Malinformation occurs when individuals are exposed to content and information that is based on reality but taken out of context with malicious intent to inflict harm.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#CognitiveThreat">sc2r:CognitiveThreat</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
            <tr>
                <th>Sub-classes</th>
                <td>
                    <a href="#InappropriateContent">sc2r:InappropriateContent</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Malware">
        <h3>Malware<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Malware</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Malware is software that is created for malicious purposes to compromise and damage individuals' cyber resources.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#IntegrityThreat">sc2r:IntegrityThreat</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Masquerading">
        <h3>Masquerading<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Masquerading</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Masquerading is an attack where false identity is used to gain access to anuthorized information. The attacker pretends to be and masquerades as the victim.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#AuthenticationThreat">sc2r:AuthenticationThreat</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="MediationMeasures">
        <h3>Mediation Measures<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#MediationMeasures</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Mediation measures are measures that are put in place but other individuals to limit the impact of adverse cyber incidents.</p>
<p>For example, guardians and parents can put in place mediation measures that limit the negative outcomes of online gaming.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#PrepareMeasure">sc2r:PrepareMeasure</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
            <tr>
                <th>Sub-classes</th>
                <td>
                    <a href="#RestrictiveMediation">sc2r:RestrictiveMediation</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#ActiveMediation">sc2r:ActiveMediation</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#TechnicalMediation">sc2r:TechnicalMediation</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="MentalFaculties">
        <h3>Mental Faculties<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#MentalFaculties</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Mental Faculties are the various functions of the mind, or things the mind can "do". Mental faculties comprise cognitive, affective, and conative skills that are crucial to human’s conscious experience and decision-making process.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#Agency">sc2r:Agency</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
            <tr>
                <th>Sub-classes</th>
                <td>
                    <a href="#KnowledgeResource">sc2r:Knowledge</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#Skills">sc2r:Skills</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#Motivation">sc2r:Motivation</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Microtargeting">
        <h3>Microtargeting<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Microtargeting</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Microtargeting (or niche-tageting) occurs when individuals are targeted by marketing content that is personalised to attract the attention of the members of the sub-group the individuals are segmented in, to influence their actions.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#PsychographicHacking">sc2r:PsychographicHacking</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Misconfiguration">
        <h3>Misconfiguration<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Misconfiguration</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Misconfiguration occurs when systems have been configured in a way compromises their functioning and integrity. Misconfiguration exposes resources to vulnerabilities that can be avoided through better configuration.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#IntegrityThreat">sc2r:IntegrityThreat</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Misinformation">
        <h3>Misinformation<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Misinformation</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Misinformation is false or inaccurate information. Examples of misinformation include false rumours, or insults and pranks, while examples of more deliberate disinformation include malicious content such as hoaxes, spearphishing, andd computational propaganda.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#CognitiveThreat">sc2r:CognitiveThreat</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
            <tr>
                <th>Sub-classes</th>
                <td>
                    <a href="#MisleadingInformation">sc2r:MisleadingInformation</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="MisleadingAdvertising">
        <h3>Misleading Advertising<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#MisleadingAdvertising</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>This is advertising content that is meant to mislead consumers.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#MisleadingInformation">sc2r:MisleadingInformation</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="MisleadingInformation">
        <h3>Misleading Information<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#MisleadingInformation</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Misleading Information is content that is meant to mislead or misinform.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#Misinformation">sc2r:Misinformation</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
            <tr>
                <th>Sub-classes</th>
                <td>
                    <a href="#MisleadingAdvertising">sc2r:MisleadingAdvertising</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Misled">
        <h3>Misled<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Misled</code></td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#Confusion">sc2r:Confusion</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Mistreatment">
        <h3>Mistreatment<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Mistreatment</code></td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#PsychologicalHarm">sc2r:PsychologicalHarm</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="MitigationCost">
        <h3>Mitigation Cost<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#MitigationCost</code></td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#EconomicHarm">sc2r:EconomicHarm</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="MobileDevice">
        <h3>Mobile Device<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#MobileDevice</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Mobile Device is any portable computing device, such as a smartphone or tablet computer.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#ComputingAsset">sc2r:ComputingAsset</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="MonitoringMeasure">
        <h3>Monitoring Measure<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#MonitoringMeasure</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Monitoring measure involves observing and checking the state of individual cyber functions as well as the operation of relevant cyber resources.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#PrepareMeasure">sc2r:PrepareMeasure</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
            <tr>
                <th>Sub-classes</th>
                <td>
                    <a href="#LoggingandAudit">sc2r:LoggingAndAudit</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#ThreatMonitoringMeasure">sc2r:ThreatMonitoringMeasure</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Motivation">
        <h3>Motivation<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Motivation</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Motivation is the internal needs, desires, wants or drives of individuals.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#MentalFaculties">sc2r:MentalFaculties</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="MultifactorAuthentication">
        <h3>Multifactor Authentication<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#MultiFactorAuthentication</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Multi-factor authentication is the process of using multiple authentication methods to verify claimed identity.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#Identification">sc2r:Identification</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="MutualAuthentication">
        <h3>Mutual Authentication<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#MutualAuthentication</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Mutual authentication is a process of two-way authentication between the communicating entities.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#Identification">sc2r:Identification</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="NaturalDisasterThreat">
        <h3>Natural Disaster Threat<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#NaturalDisaster</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Natural disasters affect the cyber resources that support individuals' cyber functionings.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#EnvironmentalThreat">sc2r:EnvironmentalThreat</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="NegativePerception">
        <h3>Negative Perception<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#NegativePerception</code></td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#PsychologicalHarm">sc2r:PsychologicalHarm</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="NetworkEquipment">
        <h3>Network Equipment<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#NetworkEquipment</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Network Equipment (networking hardware; networking device) comprises electronic devices which are required for communication and interaction between devices on a computer network.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#PhysicalResource">sc2r:PhysicalResource</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="NetworkIntrusion">
        <h3>Network Intrusion<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#NetworkIntrusion</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Network intrusion occurs when there is unauthorized access to a digital network.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#UnauthorizedAccess">sc2r:UnauthorizedAccess</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="NetworkRedundancy">
        <h3>Network Redundancy<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#NetworkRedundancy</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Network redundancy involves having redundant network connectivity to allow for alternative connection to the internet in cases where the primary connectivity is negatively affected by adverse cyber incidents.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#RedundancyMeasure">sc2r:RedundancyMeasure</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="NetworkVulnerability">
        <h3>Network Vulnerability<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#NetworkVulnerability</code></td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#DigitalVulnerability">sc2r:Digital</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Non-repudiationThreat">
        <h3>Non-repudiation Threat<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#NonRepudiationThreat</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Non-repudiation Threats compromise the non-repudiation cybersecurity goal.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#TechnologicalThreat">sc2r:TechnologicalThreat</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="OffensiveLanguage">
        <h3>Offensive Language<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#OffensiveLanguage</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>This is information and content that uses language that is offensive to individuals under specific contexts.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#InappropriateContent">sc2r:InappropriateContent</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="OnlineService">
        <h3>Online Service<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#OnlineServices</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>An Online Service refers to any information and services provided over the Internet.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#Software">sc2r:Software</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="RighttoOpinion">
        <h3>Right to Opinion<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Opinion</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>The Right to Opinion (freedom of opinion) is individual's right to hold opinions without interference, and cannot be subject to any exception or restriction.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#Rights">sc2r:Right</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="OpposingInformation">
        <h3>Opposing Information<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#OpposingInformation</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>This is part of disinformation and influence campaign in which content is distributed to counter specific narratives and perspectives.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#Disinformation">sc2r:Disinformation</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Overwhelmed">
        <h3>Overwhelmed<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Overwhelmed</code></td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#PsychologicalHarm">sc2r:PsychologicalHarm</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="BodilyPain">
        <h3>Bodily Pain<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Pain</code></td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#BodilyInjury">sc2r:BodilyInjury</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="ParasocialHacking">
        <h3>Parasocial Hacking<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#ParasocialHacking</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Parasocial Hacking exploits the biases arising from individual's parasocial relationships.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#SocialHacking">sc2r:SocialHacking</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Parody">
        <h3>Parody<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Parody</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Parody used in the context of an influence campaign to shape narratives and influence individuals.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#InfluenceOperation">sc2r:InfluenceOperation</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="PasswordManagement">
        <h3>Password Management<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#PasswordManagement</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Password management is the use of password of authentication in a safe and secure manner.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#Identification">sc2r:Identification</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="PersistenceSexualThreat">
        <h3>Persistence Sexual Threat<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Persistence</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Persistence occurs when someone keeps asking for something, even when the victim repeatedly say “no.”</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#SexualAbuseThreat">sc2r:SexualAbuse</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="PersonalData">
        <h3>Personal Data<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#PersonalData</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Personal data is any data relating to an identified or identifiable natural person (‘data subject’).</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#Data">sc2r:Data</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
            <tr>
                <th>Sub-classes</th>
                <td>
                    <a href="#User-GeneratedContent">sc2r:UserGeneratedContent</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#LocationData">sc2r:LocationData</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#BehavioralData">sc2r:BehaviouralData</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#DemocraphicInformation">sc2r:DemographicInformation</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#IdentifyingData">sc2r:IdentifyingData</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#SocialContact">sc2r:SocialContact</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#ActivityData">sc2r:ActivityData</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="IndividualandPersonalThreat">
        <h3>Individual and Personal Threat<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#PersonalThreat</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Personal Threats are associated with individuals' personal attributes and endowments. They include cognitive and influence threats, as well as privacy and identity threats.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#Threat">sc2r:Threat</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
            <tr>
                <th>Sub-classes</th>
                <td>
                    <a href="#TheftThreat">sc2r:TheftThreat</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#CognitiveThreat">sc2r:CognitiveThreat</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#InfluenceThreat">sc2r:InfluenceThreat</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#PrivacyThreat">sc2r:PrivacyThreat</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#AbuseThreat">sc2r:Abuse</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Phishing">
        <h3>Phishing<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Phishing</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Phishing is a broader term for any attempt to trick individuals to share sensitive information, such as passwords, usernames, and credit card details for malicious reasons using a message sent via email, text, phone call, or direct-chat message that appears to be from a trusted source.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#SocialEngineering">sc2r:SocialEngineering</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
            <tr>
                <th>Sub-classes</th>
                <td>
                    <a href="#Smishing">sc2r:Smishing</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#Catphishing">sc2r:Catphishing</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#AnglerPhishing">sc2r:AnglerPhishing</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#SpearPhishing">sc2r:SpearPhishing</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#Vishing">sc2r:Vishing</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="PhysicalVulnerability">
        <h3>Physical Vulnerability<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Physical</code></td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#Vulnerability">sc2r:Vulnerability</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
            <tr>
                <th>Sub-classes</th>
                <td>
                    <a href="#HardwareVulnerability">sc2r:HardwareVulnerability</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="PhysicalHarm">
        <h3>Physical Harm<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#PhysicalHarm</code></td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#Harm">sc2r:Harm</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
            <tr>
                <th>Sub-classes</th>
                <td>
                    <a href="#Compromised">sc2r:Compromised</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#Unavailable">sc2r:Unavailable</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#TheftHarm">sc2r:Theft</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#BodilyInjury">sc2r:BodilyInjury</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#Exposed">sc2r:Exposed</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#LossofLife">sc2r:LossOfLife</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#Corrupted">sc2r:Corrupted</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#ReducedPerformance">sc2r:ReducedPerformance</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#Destroyed">sc2r:Destroyed</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#AbusedHarm">sc2r:Abused</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#Infected">sc2r:Infected</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="RighttoPhysicalPrivacy">
        <h3>Right to Physical Privacy<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#PhysicalPrivacy</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Physical Privacy is individual's right to determine the degree of their physical inaccessibility to others and to prevent intrusion into their physical place or solitude.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#RighttoPrivacy">sc2r:Privacy</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="PhysicalResource">
        <h3>Physical Resource<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#PhysicalResource</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Physical resources are technological resources in material form.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#Resource">sc2r:Resource</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
            <tr>
                <th>Sub-classes</th>
                <td>
                    <a href="#ComputingAsset">sc2r:ComputingAsset</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#StorageAsset">sc2r:StorageAsset</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#NetworkEquipment">sc2r:NetworkEquipment</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="PhysicalRestriction">
        <h3>Physical Restriction<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#PhysicalRestriction</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>This is the measure for restricting and limiting access to physical resources.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#AccessControl">sc2r:AccessControl</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="PhysicalToken">
        <h3>PhysicalToken<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#PhysicalToken</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Physical Token (hardware token) is a security token that is in the form of hardware device that the user carries to authorise access to a network service.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#Credential">sc2r:Credential</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Piggybacking">
        <h3>Piggybacking<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Piggybacking</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Piggybacking is when individuals gain unauthorized free access to a network. Piggybacking is usually not for malicious intent besides gaining free access to a network.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#UnauthorizedAccess">sc2r:UnauthorizedAccess</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="PointandShriek">
        <h3>Point and Shriek<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#PointAndShriek</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Exploiting existing sensitivities, such as using misleading evidence to depict a military attack as having taking place at a place of worship to influence opinion</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#SocialHacking">sc2r:SocialHacking</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Polarization">
        <h3>Polarization<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Polarization</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Influence techniques can be applied to discredit moderate views and force narratives to focus on extreme positions</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#SocialHacking">sc2r:SocialHacking</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Pornography">
        <h3>Pornography<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Pornography</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Pornography is visual content depicting sexual subject matter that may be inappropriate to individuals.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#InappropriateContent">sc2r:InappropriateContent</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="PotemkinVillageEvidence">
        <h3>Potemkin Village Evidence<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#PotemkinVillageEvidence</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Potemkin villages of evidence refer to the attempt to set up intricate institutional networks that are controlled and used by actors as a fact-producing apparatus for the promotion and amplification of specific narratives. Potemkin villages can, for instance, consist of an array of illegitimate or fake research, (online) journals, NGOs or thinktanks that produce studies, working papers, conferences, etc. to present the respective narrative as a product of careful scholarly consideration.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#Deceit">sc2r:Deceit</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="PrepareMeasure">
        <h3>Prepare Measure<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#PrepareMeasure</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Responses are framed around four resilience phases of Prepare, Absorb, Recover, and Adapt.</p>
<p>The Prepare phase represents the baseline level of individuals’ cyber functioning during which Prepare measures are undertaken for facilitate responses in the subsequent phases.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#Response">sc2r:Response</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
            <tr>
                <th>Sub-classes</th>
                <td>
                    <a href="#AnticipateMeasure">sc2r:AnticipateMeasure</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#MonitoringMeasure">sc2r:MonitoringMeasure</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#MediationMeasures">sc2r:MediationMeasures</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#PreventionMeasure">sc2r:PreventionMeasure</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Pretexting">
        <h3>Pretexting<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Pretexting</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Pretexting occurs when individuals are targeted by an attempt to trick them into handing sensitive data or login credentials to the perpetrator who uses a good pretext or fabricated scenario to build a false sense of trust.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#SocialEngineering">sc2r:SocialEngineering</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="PreventionMeasure">
        <h3>Prevention Measure<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#PreventionMeasure</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Prevention measures are put in place to limit and stop the occurance of specific cyber threats.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#PrepareMeasure">sc2r:PrepareMeasure</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
            <tr>
                <th>Sub-classes</th>
                <td>
                    <a href="#Identification">sc2r:Identification</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#TrustedData">sc2r:TrustedData</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#TrustedInformation">sc2r:TrustedInformation</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#TrustedInfrastructure">sc2r:TrustedInfrastructure</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#AccessControl">sc2r:AccessControl</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#TrustedSoftware">sc2r:TrustedSoftware</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#WebHygiene">sc2r:WebHygiene</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="RighttoPrivacy">
        <h3>Right to Privacy<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Privacy</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>beyond what is guaranteed by the structure </p>
<p>The Right to Privacy is individual's right to be free from intrusion into or publicity concerning matters of a personal nature.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#Rights">sc2r:Right</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
            <tr>
                <th>Sub-classes</th>
                <td>
                    <a href="#RighttoPhysicalPrivacy">sc2r:PhysicalPrivacy</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#RighttoTerritorialPrivacy">sc2r:TerritorialPrivacy</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#RighttoPsychologicalPrivacy">sc2r:PsychologicalPrivacy</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#RighttoSocialPrivacy">sc2r:SocialPrivacy</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#RighttoInformationPrivacy">sc2r:InformationalPrivacy</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="PrivacyThreat">
        <h3>Privacy Threat<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#PrivacyThreat</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Privacy threat is an adverse cyber incident that negatively impacts and violates individuals' various dimensions of privacy.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#IndividualandPersonalThreat">sc2r:PersonalThreat</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
            <tr>
                <th>Sub-classes</th>
                <td>
                    <a href="#IntimacyThreat">sc2r:IntimacyThreat</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#ReserveThreat">sc2r:ReserveThreat</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#AnonymityThreat">sc2r:AnonymityThreat</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#SolitudeThreat">sc2r:SolitudeThreat</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Profanity">
        <h3>Profanity<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Profanity</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>This is information and content that uses language that is offensive to individuals under specific contexts.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#InappropriateContent">sc2r:InappropriateContent</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="ProfessionalSupport">
        <h3>Professional Support<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#ProfessionalSupport</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>This is receiving professional input to assist in dealing with an adverse incident and recovering the lost cyber functioning.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#ExternalSupport">sc2r:ExternalSupport</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Propaganda">
        <h3>Propaganda<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Propaganda</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Propaganda is information that is used to promote and advance a specific political perspective or point of view.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#Disinformation">sc2r:Disinformation</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Prosecution">
        <h3>Prosecution<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Prosecution</code></td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#PsychologicalHarm">sc2r:PsychologicalHarm</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="PsychographicHacking">
        <h3>Psychographic Hacking<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#PsychographicHacking</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Psychographic hacking refers to the covert targeting and influencing of individuals using messages created to appeal to precisely identified groups or individuals based on their psychographic profiles.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#InfluenceThreat">sc2r:InfluenceThreat</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
            <tr>
                <th>Sub-classes</th>
                <td>
                    <a href="#BandwagonEffect">sc2r:BandwagonEffect</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#Microtargeting">sc2r:Microtargeting</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#DarkAdvertising">sc2r:DarkAdvertising</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="PsychologicalHarm">
        <h3>Psychological Harm<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#PsychologicalHarm</code></td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#Harm">sc2r:Harm</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
            <tr>
                <th>Sub-classes</th>
                <td>
                    <a href="#Overwhelmed">sc2r:Overwhelmed</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#FeelingUpset">sc2r:FeelingUpset</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#NegativePerception">sc2r:NegativePerception</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#LowSatisfaction">sc2r:LowSatisfaction</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#Gluttony">sc2r:Gluttony</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#Depressed">sc2r:Depressed</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#IdentityTheftHarm">sc2r:IdentityTheftLoss</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#LossofConfidence">sc2r:LossOfConfidence</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#Disempowerment">sc2r:Disempowerment</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#Confusion">sc2r:Confusion</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#Frustration">sc2r:Frustration</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#Mistreatment">sc2r:Mistreatment</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#Distraction">sc2r:Distraction</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#Shameful">sc2r:Shameful</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#Self-Censorship">sc2r:SelfCensorship</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#Guilty">sc2r:Guilty</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#Prosecution">sc2r:Prosecution</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#CognitiveImpairement">sc2r:CognitiveImpairement</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#Discomfort">sc2r:Discomfort</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#Addiction">sc2r:Addiction</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#LowMorale">sc2r:LowMorale</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#Worry">sc2r:Worry</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#Embarrassed">sc2r:Embarrassed</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="RighttoPsychologicalPrivacy">
        <h3>Right to Psychological Privacy<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#PsychologicalPrivacy</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Psychological Privacy is individual's right to control cognitive and affective inputs and outputs, to form values, and to determine with whom and under what circumstances their thoughts will be shared or intimate information revealed.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#RighttoPrivacy">sc2r:Privacy</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="QuidProQuo">
        <h3>Quid Pro Quo<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#QuidProQuo</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Quid Pro Quo occurs when individuals are targeted by an attempt to trick them into handing their login credentials to the perpetrator who leverages the offer of free services.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#SocialEngineering">sc2r:SocialEngineering</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Radicalization">
        <h3>Radicalization<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Radicalization</code></td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#SocialHarm">sc2r:SocialHarm</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Raiding">
        <h3>Raiding<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Raiding</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Rapid and coordinated influence attacks</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#SocialHacking">sc2r:SocialHacking</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Ransomware">
        <h3>Ransomware<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Ransomware</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Ransomware is malicious software that limits or restricts access to information and services with a demand for a ransom fee to be paid.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#AvailabilityThreat">sc2r:AvailabilityThreat</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Reconnaissance">
        <h3>Reconnaissance<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Reconnaissance</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Reconnaissance occurs when an attacker engages in both passive and active collection of information that can be used to execute an attack on individuals' cyber resources.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#ConfidentialityThreat">sc2r:ConfidentialityThreat</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="RecoverMeasure">
        <h3>Recover Measure<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#RecoverMeasure</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Responses are framed around four resilience phases of Prepare, Absorb, Recover, and Adapt.</p>
<p>The Recover phase starts the moment the adverse incident stops or is halted, and when restoration of lost cyber functioning begins. Timely and effective recover measures are necessary to reduce the compounded negative impacts of disrupted cyber functioning.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#Response">sc2r:Response</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
            <tr>
                <th>Sub-classes</th>
                <td>
                    <a href="#AccountRecovery">sc2r:AccountRecovery</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#FactChecking">sc2r:Fact-checking</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#DataRecovery">sc2r:DataRecovery</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#SystemRecovery">sc2r:SystemRecovery</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#ExternalSupport">sc2r:ExternalSupport</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="RecoveryPlan">
        <h3>Recovery Plan<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#RecoveryPlan</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Recovery planning is the process of putting in place plans to restore and recover cyber functioning when adverse incidents do occur.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#AnticipateMeasure">sc2r:AnticipateMeasure</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="ReducedOpportunities">
        <h3>Reduced Opportunities<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#ReducedOpportunities</code></td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#ReputationalHarm">sc2r:ReputationalHarm</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="ReducedPerformance">
        <h3>Reduced Performance<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#ReducedPerformance</code></td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#PhysicalHarm">sc2r:PhysicalHarm</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="RedundancyMeasure">
        <h3>Redundancy Measure<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#RedundancyMeasure</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Redundancy measure is a preparation measure that involves putting in place redundant resources, to be utilized in cases where core resources are compromised and affected by adverse cyber incidents.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#AnticipateMeasure">sc2r:AnticipateMeasure</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
            <tr>
                <th>Sub-classes</th>
                <td>
                    <a href="#NetworkRedundancy">sc2r:NetworkRedundancy</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#SourceRedundancy">sc2r:SourceRedundancy</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#DataRedundancy">sc2r:DataRedundancy</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#SoftwareRedundancy">sc2r:SoftwareRedundancy</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="RemoteCodeExecution">
        <h3>Remote Code Execution<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#RemoteExecution</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Remote Execution occurs when an attacker exploits a vulnerability in networking and computing systems to run commands and software on individuals computing resources.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#IntegrityThreat">sc2r:IntegrityThreat</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="RemovalMeasure">
        <h3>Removal Measure<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#RemovalMeasure</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Removal measure involve the direct removal and elimination of the cyber threat.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#EngageMeasure">sc2r:EngageMeasure</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
            <tr>
                <th>Sub-classes</th>
                <td>
                    <a href="#MaliciousContactRemoval">sc2r:MaliciousContactRemoval</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#MaliciousContentRemoval">sc2r:MaliciousContentRemoval</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#MaliciousSoftwareRemoval">sc2r:MaliciousSoftwareRemoval</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Replay">
        <h3>Replay<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Replay</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Replay attacks occur when legitimate information and network transactions are repeated and retransmitted for malicious purposes.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#IntegrityThreat">sc2r:IntegrityThreat</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="ReportingMeasure">
        <h3>Reporting Measure<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Reporting</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Reporting measure is the reporting of an adverse cyber incident to external responders.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#AbsorbMeasure">sc2r:AbsorbMeasure</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
            <tr>
                <th>Sub-classes</th>
                <td>
                    <a href="#IncidentReporting">sc2r:IncidentReporting</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="ReputationResource">
        <h3>Reputation Resource<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Reputation</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Reputation is the overall quality or character as recognised by other people.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#SocialCapitalResource">sc2r:SocialCapital</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="ReputationalHarm">
        <h3>Reputational Harm<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#ReputationalHarm</code></td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#Harm">sc2r:Harm</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
            <tr>
                <th>Sub-classes</th>
                <td>
                    <a href="#ReducedOpportunities">sc2r:ReducedOpportunities</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#DamagedSocialPerception">sc2r:DamagedSocialPerception</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#UnderScrutiny">sc2r:UnderScrutiny</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#Blacklisted">sc2r:Blacklisted</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="ReserveThreat">
        <h3>Reserve Threat<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#ReserveThreat</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Reserve Threat occurs when individuals' preference to not interact or remain strangers with others online is threatened.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#PrivacyThreat">sc2r:PrivacyThreat</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Resource">
        <h3>Resource<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Resource</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>A Resource is a capability input that contributes to individuals cyber activities. Resources are framed much broader that technological computing assets (i.e., hardware, software, data) and include individual and social resources.</p>
                </td>
            </tr>
            <tr>
                <th>Sub-classes</th>
                <td>
                    <a href="#InfrastructureResource">sc2r:InfrastructureResource</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#IndividualPersonalResource">sc2r:IndividualResource</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#DigitalResource">sc2r:DigitalResource</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#PhysicalResource">sc2r:PhysicalResource</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
            <tr>
                <th>In domain of</th>
                <td>
                    <a href="#isDamagedBy">sc2r:isDamagedBy</a><sup class="sup-op" title="object property">op</sup><br/>
                    <a href="#hasVulnerability">sc2r:hasVulnerability</a><sup class="sup-op" title="object property">op</sup><br/>
                </td>
            </tr>
            <tr>
                <th>In range of</th>
                <td>
                    <a href="#damages">sc2r:damages</a><sup class="sup-op" title="object property">op</sup><br/>
                    <a href="#isAVulnerabilityOf">sc2r:isAVulnerabilityOf</a><sup class="sup-op" title="object property">op</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Response">
        <h3>Response<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Response</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>A Response, also called Countermeasure, is an intervention that can be employed to mitigate Threats and reduce Vulnerabilities. Responses are framed around the four phases of resilience: prepare, absorb, recover, and adapt.</p>
                </td>
            </tr>
            <tr>
                <th>Sub-classes</th>
                <td>
                    <a href="#AbsorbMeasure">sc2r:AbsorbMeasure</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#AdaptMeasure">sc2r:AdaptMeasure</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#PrepareMeasure">sc2r:PrepareMeasure</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#RecoverMeasure">sc2r:RecoverMeasure</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
            <tr>
                <th>In domain of</th>
                <td>
                    <a href="#reduces">sc2r:reduces</a><sup class="sup-op" title="object property">op</sup><br/>
                    <a href="#mitigates">sc2r:mitigates</a><sup class="sup-op" title="object property">op</sup><br/>
                </td>
            </tr>
            <tr>
                <th>In range of</th>
                <td>
                    <a href="#isReducedBy">sc2r:isReducedBy</a><sup class="sup-op" title="object property">op</sup><br/>
                    <a href="#isMitigatedBy">sc2r:isMitigatedBy</a><sup class="sup-op" title="object property">op</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="RestrictiveMediation">
        <h3>Restrictive Mediation<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#RestrictiveMediation</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Restrictive mediation are a set of rules and limits that are placed on individuals to minimize the negative impacts in use of cyber resources.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#MediationMeasures">sc2r:MediationMeasures</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Rights">
        <h3>Rights<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Right</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Rights are non-negotiable entitlements grounded in the idea of justice.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#IndividualPersonalResource">sc2r:IndividualResource</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
            <tr>
                <th>Sub-classes</th>
                <td>
                    <a href="#RighttoAssembly">sc2r:Assembly</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#RighttoInformation">sc2r:Information</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#RighttoOpinion">sc2r:Opinion</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#RighttoExpression">sc2r:Expression</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#RighttoPrivacy">sc2r:Privacy</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="SDCard">
        <h3>SD Card<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#SDCard</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>SD Card (Secure Digital Card) is an ultra small flash memory card designed to provide high-capacity memory in a small size.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#StorageAsset">sc2r:StorageAsset</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Sandboxing">
        <h3>Sandboxing<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Sandboxing</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Sandboxing is a mechanism of isolating the operation of cyber resources that may otherwise cause wide spreading adverse incidents.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#AccessControl">sc2r:AccessControl</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Satire">
        <h3>Satire<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Satire</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Satire used as part of an influence campaign.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#InfluenceOperation">sc2r:InfluenceOperation</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Scam">
        <h3>Scam<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Scam</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Scam is the broader term for the use of internet services or software to defraud or take advantage of targets, typically financial gain or other valuable information. Scam types include romance scam, the overpayment scam, quick-money promise, impersonation scam, and tech support online scam.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#TheftThreat">sc2r:TheftThreat</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
            <tr>
                <th>Sub-classes</th>
                <td>
                    <a href="#SweepstakesScam">sc2r:SweepstakesScam</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#FakeGiveaways">sc2r:FakeGiveways</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="ScamCost">
        <h3>Scam Cost<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#ScamCost</code></td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#EconomicHarm">sc2r:EconomicHarm</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Scareware">
        <h3>Scareware<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Scareware</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Scareware is a form of malware that is designed to manipulate individuals to buy or download unnecessary and potentially dangerous software, such as fake antivirus protection.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#InfluenceThreat">sc2r:InfluenceThreat</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Sealioning">
        <h3>Sealioning<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Sealioning</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Sealioning is a type of troll tactic which consists of pursuing people with persistent requests for evidence or repeated questions, while maintaining a pretense of civility and sincerity.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#Trolling">sc2r:Trolling</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Self-Censorship">
        <h3>Self-Censorship<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#SelfCensorship</code></td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#PsychologicalHarm">sc2r:PsychologicalHarm</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="SelfHarm">
        <h3>Self Harm<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#SelfHarm</code></td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#BodilyInjury">sc2r:BodilyInjury</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Server">
        <h3>Server<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Server</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>A Server is a computer or system that provides resources, data services, or programs to other computers.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#ComputingAsset">sc2r:ComputingAsset</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Sextortion">
        <h3>Sextortion<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Sextortion</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Sextortion occurs when the perpetrator uses unwanted sexually explicit material of the target to blackmail or coerce the target into extorting sexual favors.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#SexualAbuseThreat">sc2r:SexualAbuse</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="SexualAbuseThreat">
        <h3>Sexual Abuse Threat<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#SexualAbuse</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Sexual Abuse occurs to individuals when they are targeted by a virtual, distanced sexual abuse or exploitation through the use of online communication.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#AbuseThreat">sc2r:Abuse</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
            <tr>
                <th>Sub-classes</th>
                <td>
                    <a href="#Grooming">sc2r:Grooming</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#LuringSexualThreat">sc2r:Luring</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#PersistenceSexualThreat">sc2r:Persistence</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#SexualAssault">sc2r:SexualAssault</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#Sextortion">sc2r:Sextortion</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#LoveBombing">sc2r:LoveBombing</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#BoyfriendingandGirlfriending">sc2r:BoyfriendingGirlfriending</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="SexualAssault">
        <h3>Sexual Assault<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#SexualAssault</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Sexual Assault occurs when the perpetrator constantly threats the target with sexual assault online.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#SexualAbuseThreat">sc2r:SexualAbuse</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Shameful">
        <h3>Shameful<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Shameful</code></td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#PsychologicalHarm">sc2r:PsychologicalHarm</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Shilling">
        <h3>Shilling<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Shilling</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Shilling involves a person engaging with a particular subject (e.g. through marketing or a review) jointly with the actor concerned, for example someone writing a glowing customer review or answering their own questions under different identities to simulate a debate.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#Deceit">sc2r:Deceit</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Skills">
        <h3>Skills<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Skills</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>A Skill is the ability and capacity to perform an action with determined results.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#MentalFaculties">sc2r:MentalFaculties</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Skimming">
        <h3>Skimming<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Skimming</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Skimming occurs when attackers steal and capture private and confidential information, such as credit card details, in the course of a 'legitimate' use of services.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#ConfidentialityThreat">sc2r:ConfidentialityThreat</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Smishing">
        <h3>Smishing<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Smishing</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Smishing occurs when individuals receive a convincing yet fraudulent text message (instead of email) from the perpetrator that attempts to trick into handing over personal information.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#Phishing">sc2r:Phishing</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="SocialCapitalResource">
        <h3>Social Capital Resource<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#SocialCapital</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Social capital is the accumulation of actual and potential resources linked to the possession of a social network.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#IndividualPersonalResource">sc2r:IndividualResource</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
            <tr>
                <th>Sub-classes</th>
                <td>
                    <a href="#ReputationResource">sc2r:Reputation</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#SocialNetworkResource">sc2r:SocialNetwork</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="SocialContact">
        <h3>Social Contact<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#SocialContact</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Social Contact refers to individual's contact list and the conversation they have with others that occur through the use of a digital device.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#PersonalData">sc2r:PersonalData</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="SocialEngineering">
        <h3>Social Engineering<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#SocialEngineering</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Social Engineering is the use of deception to manipulate individuals into divulging confidential or personal information that may be used for fraudulent purposes.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#InfluenceThreat">sc2r:InfluenceThreat</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
            <tr>
                <th>Sub-classes</th>
                <td>
                    <a href="#Baiting">sc2r:Baiting</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#Tailgating">sc2r:Tailgating</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#Phishing">sc2r:Phishing</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#Pretexting">sc2r:Pretexting</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#QuidProQuo">sc2r:QuidProQuo</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="SocialHacking">
        <h3>Social Hacking<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#SocialHacking</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Social hacking is the act of attempting to manipulate outcomes of social behaviour through orchestrated actions.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#SocietalandSocialThreat">sc2r:SocialThreat</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
            <tr>
                <th>Sub-classes</th>
                <td>
                    <a href="#SockPuppetry">sc2r:SockPuppetry</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#Socio-cognitiveHacking">sc2r:SociocognitiveHacking</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#Cheerleading">sc2r:Cheerleading</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#Flooding">sc2r:Flooding</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#ParasocialHacking">sc2r:ParasocialHacking</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#BlackPropaganda">sc2r:BlackPropaganda</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#Raiding">sc2r:Raiding</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#Polarization">sc2r:Polarization</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#PointandShriek">sc2r:PointAndShriek</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#Laundering">sc2r:Laundering</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="SocialHarm">
        <h3>Social Harm<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#SocialHarm</code></td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#Harm">sc2r:Harm</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
            <tr>
                <th>Sub-classes</th>
                <td>
                    <a href="#Conflict">sc2r:Conflict</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#ImpairedPrivateSocialBoundary">sc2r:ImpairedPrivateSocialBoundary</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#DamagedRelationship">sc2r:DamagedRelationship</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#SocialWithdrawal">sc2r:SocialWithdrawal</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#Radicalization">sc2r:Radicalization</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#Isolation">sc2r:Isolation</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="SocialMediaHygiene">
        <h3>Social Media Hygiene<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#SocialMediaHygiene</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Email hygiene are measures and practices that contribute to safe and secure use of social media.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#WebHygiene">sc2r:WebHygiene</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="SocialMediaMonitoring">
        <h3>Social Media Monitoring<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#SocialMediaMonitoring</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Social media monitoring involves observing and checking social media resources for signs of adverse incidents.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#ThreatMonitoringMeasure">sc2r:ThreatMonitoringMeasure</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="SocialNetworkResource">
        <h3>Social Network Resource<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#SocialNetwork</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Social Network refers to individual's network of social interactions and personal relationships.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#SocialCapitalResource">sc2r:SocialCapital</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="RighttoSocialPrivacy">
        <h3>Right to Social Privacy<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#SocialPrivacy</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Social Privacy is individual's right to keep their social network to themselves to protect the privacy of others within the network.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#RighttoPrivacy">sc2r:Privacy</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="SocialSupport">
        <h3>Social Support<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#SocialSupport</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>This involves leveraging individuals social capital towards recovery to the lost cyber functioning. </p>
<p>For example, in the case of socio-technical threats, social support can enable individuals to deal with the adverse incident and to recover from its impacts.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#ExternalSupport">sc2r:ExternalSupport</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="SocietalandSocialThreat">
        <h3>Societal and Social Threat<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#SocialThreat</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Social Threats are associated with individuals' social and societal context.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#Threat">sc2r:Threat</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
            <tr>
                <th>Sub-classes</th>
                <td>
                    <a href="#SocialHacking">sc2r:SocialHacking</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="SocialWithdrawal">
        <h3>Social Withdrawal<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#SocialWithdrawal</code></td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#SocialHarm">sc2r:SocialHarm</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Socio-cognitiveHacking">
        <h3>Socio-cognitive Hacking<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#SociocognitiveHacking</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Socio-cognitive hacking seeks to manipulate the perception of people by exploiting their psychosocial vulnerabilities with the purpose of changing people's behaviour. The most common tool used is weaponised information.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#SocialHacking">sc2r:SocialHacking</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="SockPuppetry">
        <h3>Sock Puppetry<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#SockPuppetry</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Sock Puppetry is a form of deception that involves the misleading use of online identities to to manipulate public opinion, or to circumvent restrictions, suspension or an outright ban from a website.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#SocialHacking">sc2r:SocialHacking</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Software">
        <h3>Software<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Software</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>A Software is a set of programs, procedures, and routines used to operate computers and execute specific tasks.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#DigitalResource">sc2r:DigitalResource</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
            <tr>
                <th>Sub-classes</th>
                <td>
                    <a href="#OnlineService">sc2r:OnlineServices</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="SoftwareRedundancy">
        <h3>Software Redundancy<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#SoftwareRedundancy</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Software redundancy involves having redundant software in place to be utilized in cases where primary software is affected by adverse cyber incidents.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#RedundancyMeasure">sc2r:RedundancyMeasure</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="SoftwareVulnerability">
        <h3>Software Vulnerability<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#SoftwareVulnerability</code></td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#DigitalVulnerability">sc2r:Digital</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="SolitudeThreat">
        <h3>Solitude Threat<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#SolitudeThreat</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Solitude Threat occurs when individuals' preference to be alone by themselves and free from observations by others is threatened.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#PrivacyThreat">sc2r:PrivacyThreat</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="SourceRedundancy">
        <h3>Source Redundancy<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#SourceRedundancy</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Source redundancy involves having alternative sources of information, content and services to be utilized in cases where primary sources are affected by adverse cyber incidents.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#RedundancyMeasure">sc2r:RedundancyMeasure</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="SpamEmail">
        <h3>Spam Email<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#SpamEmail</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Spam Email (junk email) are unsolicited messages sent in bulk through email with commercial, fraudulent, or malicious intent.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#UnsolicitedCommunication">sc2r:UnsolicitedCommunication</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="SpearPhishing">
        <h3>Spear Phishing<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#SpearPhishing</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Spear Phishing occurs when individuals receive a convincing yet fraudulent message from the perpetrator who poses as a familiar person or entity to the individual in an attempt to trick them into sharing sensitive information.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#Phishing">sc2r:Phishing</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
            <tr>
                <th>Sub-classes</th>
                <td>
                    <a href="#WhalingPhishing">sc2r:Whaling</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Spoofing">
        <h3>Spoofing<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Spoofing</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Spoofing is an attack where fake and falsified identity is provided by individuals or machines. For example, a roque website pretending to be another legitimate website by spoofing the address.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#AuthenticationThreat">sc2r:AuthenticationThreat</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="StorageAsset">
        <h3>Storage Asset<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#StorageAsset</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Storage Asset comprises any recording media used to retain data using computers or other devices.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#PhysicalResource">sc2r:PhysicalResource</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
            <tr>
                <th>Sub-classes</th>
                <td>
                    <a href="#USBDrive">sc2r:USBDrive</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#ExternalHardDrive">sc2r:ExternalHardDrive</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#SDCard">sc2r:SDCard</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="StrawmanAttack">
        <h3>Strawman Attack<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Strawman</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Strawman attack is a technique that is used to undermine a specific position by summarising the position inaccurately so as to weaken it and then by refuting that inaccurate rendition.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#MalignRhetoric">sc2r:MalignRhetoric</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Surveillance">
        <h3>Surveillance<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Surveillance</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Surveillance occurs when individuals are observed and monitored for the purposes of collecting information, influencing or managing.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#InstitutionalThreat">sc2r:InstitutionalThreat</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="SweepstakesScam">
        <h3>Sweepstakes Scam<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#SweepstakesScam</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Sweepstakes scam occurs individuals are told that they have won a prize and that they need to pay a fee before receiving their prize</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#Scam">sc2r:Scam</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Sympathy">
        <h3>Sympathy<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Sympathy</code></td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#IndividualandPersonalVulnerability">sc2r:Individual</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="SystemRecovery">
        <h3>System Recovery<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#SystemRecovery</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>System recovery involves the restoration of a system, including services and configuration, to the level of nominal functioning equivalent to that before an adverse cyber incident.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#RecoverMeasure">sc2r:RecoverMeasure</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Tailgating">
        <h3>Tailgating<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Tailgating</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Tailgating (or piggybacking) occurs when individuals are targeted by an attempt to trick them to help the perpetrator gain unauthorised access into a secure, restricted area.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#SocialEngineering">sc2r:SocialEngineering</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="TechnicalMediation">
        <h3>Technical Mediation<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#TechnicalMediation</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Technical mediation is the use of technology solutions to limit the impact of adverse cyber incidents.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#MediationMeasures">sc2r:MediationMeasures</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="TechnologicalThreat">
        <h3>Technological Threat<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#TechnologicalThreat</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Technological threats are associated with and affect individuals' computing resources.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#Threat">sc2r:Threat</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
            <tr>
                <th>Sub-classes</th>
                <td>
                    <a href="#Non-repudiationThreat">sc2r:NonRepudiationThreat</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#IntegrityThreat">sc2r:IntegrityThreat</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#AuthenticationThreat">sc2r:AuthenticationThreat</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#AvailabilityThreat">sc2r:AvailabilityThreat</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#ConfidentialityThreat">sc2r:ConfidentialityThreat</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="RighttoTerritorialPrivacy">
        <h3>Right to Territorial Privacy<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#TerritorialPrivacy</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>The right to protect personal space, property, and objects.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#RighttoPrivacy">sc2r:Privacy</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="TheftHarm">
        <h3>Theft Harm<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Theft</code></td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#PhysicalHarm">sc2r:PhysicalHarm</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="TheftofFinances">
        <h3>Theft of Finances<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#TheftOfFinances</code></td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#EconomicHarm">sc2r:EconomicHarm</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="TheftThreat">
        <h3>Theft Threat<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#TheftThreat</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Theft threats aim to steal of defraud individuals of certain resources.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#IndividualandPersonalThreat">sc2r:PersonalThreat</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
            <tr>
                <th>Sub-classes</th>
                <td>
                    <a href="#IdentityTheft">sc2r:IdentityTheft</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#Scam">sc2r:Scam</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#Fraud">sc2r:Fraud</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Threat">
        <h3>Threat<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Threat</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>A Threat is a potential adverse cyber incident that has an impact on individuals. Threats are framed around individuals' personal, social, and environmental conversion factors which consitute their personal utilization function.</p>
                </td>
            </tr>
            <tr>
                <th>Sub-classes</th>
                <td>
                    <a href="#SocietalandSocialThreat">sc2r:SocialThreat</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#EnvironmentalThreat">sc2r:EnvironmentalThreat</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#IndividualandPersonalThreat">sc2r:PersonalThreat</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#TechnologicalThreat">sc2r:TechnologicalThreat</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
            <tr>
                <th>In domain of</th>
                <td>
                    <a href="#damages">sc2r:damages</a><sup class="sup-op" title="object property">op</sup><br/>
                    <a href="#exploits">sc2r:exploits</a><sup class="sup-op" title="object property">op</sup><br/>
                    <a href="#canResultIn">sc2r:canResultIn</a><sup class="sup-op" title="object property">op</sup><br/>
                    <a href="#isMitigatedBy">sc2r:isMitigatedBy</a><sup class="sup-op" title="object property">op</sup><br/>
                    <a href="#resultsIn">sc2r:resultsIn</a><sup class="sup-op" title="object property">op</sup><br/>
                </td>
            </tr>
            <tr>
                <th>In range of</th>
                <td>
                    <a href="#isResultOf">sc2r:isResultOf</a><sup class="sup-op" title="object property">op</sup><br/>
                    <a href="#isDamagedBy">sc2r:isDamagedBy</a><sup class="sup-op" title="object property">op</sup><br/>
                    <a href="#isExploitedBy">sc2r:isExploitedBy</a><sup class="sup-op" title="object property">op</sup><br/>
                    <a href="#mitigates">sc2r:mitigates</a><sup class="sup-op" title="object property">op</sup><br/>
                    <a href="#canBeResultOf">sc2r:canBeResultOf</a><sup class="sup-op" title="object property">op</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="ThreatMonitoringMeasure">
        <h3>Threat Monitoring Measure<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#ThreatMonitoringMeasure</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Threat monitoring is the process of continually monitoring and observing the operation and use of cyber resources for signs of adverse cyber incidents and threats.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#MonitoringMeasure">sc2r:MonitoringMeasure</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
            <tr>
                <th>Sub-classes</th>
                <td>
                    <a href="#MaliciousSoftwareDetection">sc2r:MaliciousSoftwareDetection</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#IntrusionDetection">sc2r:IntrusionDetection</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#FailureDetection">sc2r:FailureDetection</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#SocialMediaMonitoring">sc2r:SocialMediaMonitoring</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="TimeWasted">
        <h3>Time Wasted<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#TimeWasted</code></td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#EconomicHarm">sc2r:EconomicHarm</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Training">
        <h3>Training<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Training</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Training is a capability building measure that enhances individuals skills and competencies to be able to deal with and handle adverse cyber incidents.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#AnticipateMeasure">sc2r:AnticipateMeasure</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="TransferInformationAttack">
        <h3>Transfer Information Attack<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Transfer</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Transfer information attack occurs when information, content, and arguments are associated with partisan and controversial themes for influence and distortion purposes.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#MalignRhetoric">sc2r:MalignRhetoric</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Trolling">
        <h3>Trolling<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Trolling</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Trolling is the deliberate act of making random unsolicited, inflammatory, and/or controversial comments online with the intent to provoke emotional responses from unsuspecting readers to engage in a fight or argument.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#AbuseThreat">sc2r:Abuse</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
            <tr>
                <th>Sub-classes</th>
                <td>
                    <a href="#Sealioning">sc2r:Sealioning</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="TrustedData">
        <h3>Trusted Data<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#TrustedData</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Trusted data is the use of measures that ensure the safety, security and veracity of data.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#PreventionMeasure">sc2r:PreventionMeasure</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="TrustedInformation">
        <h3>Trusted Information<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#TrustedInformation</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Trusted information is the use of information that is verified and safe, and from trusted sources.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#PreventionMeasure">sc2r:PreventionMeasure</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="TrustedInfrastructure">
        <h3>Trusted Infrastructure<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#TrustedInfrastructure</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Trusted infrastructure involves the use of safe, secure, verified and trusted cyber infrastructure.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#PreventionMeasure">sc2r:PreventionMeasure</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
            <tr>
                <th>Sub-classes</th>
                <td>
                    <a href="#TrustedNetworking">sc2r:TrustedNetworking</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="TrustedNetworking">
        <h3>Trusted Networking<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#TrustedNetworking</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Trusted Networking is the use of networking resources in a safe, secure, and trusted manner.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#TrustedInfrastructure">sc2r:TrustedInfrastructure</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
            <tr>
                <th>Sub-classes</th>
                <td>
                    <a href="#AnonymousRouting">sc2r:AnonymousRouting</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#VirtualPrivateNetwork">sc2r:VirtualPrivateNetwork</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="TrustedSoftware">
        <h3>Trusted Software<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#TrustedSoftware</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Trusted software involves the use of software that is safe, secure, verified and trusted. It involves using software from legitimate sources.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#PreventionMeasure">sc2r:PreventionMeasure</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="USBDrive">
        <h3>USB Drive<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#USBDrive</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>USB Drive is an external hard disk drive or optical disc drive that plugs into the USB port.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#StorageAsset">sc2r:StorageAsset</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="UnauthorizedAccess">
        <h3>Unauthorized Access<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#UnauthorizedAccess</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Unauthorized access occurs when individuals or machines gain access to information or services that they are not authorized to.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#AuthenticationThreat">sc2r:AuthenticationThreat</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
            <tr>
                <th>Sub-classes</th>
                <td>
                    <a href="#Piggybacking">sc2r:Piggybacking</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#NetworkIntrusion">sc2r:NetworkIntrusion</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Unavailable">
        <h3>Unavailable<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Unavailable</code></td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#PhysicalHarm">sc2r:PhysicalHarm</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="UnderScrutiny">
        <h3>Under Scrutiny<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#UnderScrutiny</code></td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#ReputationalHarm">sc2r:ReputationalHarm</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="UnsolicitedCommunication">
        <h3>Unsolicited Communication<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#UnsolicitedCommunication</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Unsolicited communication occurs when individuals receive communication that they haven't requested or solicited.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#AbuseThreat">sc2r:Abuse</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
            <tr>
                <th>Sub-classes</th>
                <td>
                    <a href="#SpamEmail">sc2r:SpamEmail</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#UnsolicitedSocialRequest">sc2r:UnsolicitedSocialRequest</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="UnsolicitedSocialRequest">
        <h3>Unsolicited Social Request<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#UnsolicitedSocialRequest</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Unsolicited Social Request occur when individuals receive a request for information from a person or an entity that is unknown to or has no connection with them.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#UnsolicitedCommunication">sc2r:UnsolicitedCommunication</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Urgency">
        <h3>Urgency<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Urgency</code></td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#IndividualandPersonalVulnerability">sc2r:Individual</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="User-GeneratedContent">
        <h3>User-Generated Content<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#UserGeneratedContent</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>User Generated Content (UGC) is any content, including text, audio, videos, images, and reviews, that are created by users/people and posted on online platforms.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#PersonalData">sc2r:PersonalData</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="UserIdentification">
        <h3>User Identification<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#UserIdentification</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Use identification is the confirmation of the claimed identify of users.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#Identification">sc2r:Identification</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Vandalism">
        <h3>Vandalism<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Vandalism</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Digital Vandalism occurs when individuals' digital resources, for example websites, are maliciously defaced or permanently damaged.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#IntegrityThreat">sc2r:IntegrityThreat</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Violation">
        <h3>Violation<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Violation</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Violations occur when individual break the stipulated and expected conditions in the use of cyber resources. These include violations of policies and contracts.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#InstitutionalThreat">sc2r:InstitutionalThreat</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
            <tr>
                <th>Sub-classes</th>
                <td>
                    <a href="#BreachofContract">sc2r:ContractBreach</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="VoilentContent">
        <h3>Voilent Content<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Violence</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>This is content of violent nature that may be inappropriate to individuals.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#InappropriateContent">sc2r:InappropriateContent</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="VirtualPrivateNetwork">
        <h3>Virtual Private Network<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#VirtualPrivateNetwork</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>A virtual private network is a networking measure that extends a private network over a public network, in a manner that ensures safety and security.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#TrustedNetworking">sc2r:TrustedNetworking</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Vishing">
        <h3>Vishing<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Vishing</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Vishing occurs when individuals receive a phone call that appears to be from a trusted source aiming to trick them to share sensitive information.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#Phishing">sc2r:Phishing</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Vulnerability">
        <h3>Vulnerability<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Vulnerability</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>A Vulnerability is a weakness of Cyber Resources, that can be exploited by a Threat.</p>
                </td>
            </tr>
            <tr>
                <th>Sub-classes</th>
                <td>
                    <a href="#DigitalVulnerability">sc2r:Digital</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#IndividualandPersonalVulnerability">sc2r:Individual</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#PhysicalVulnerability">sc2r:Physical</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
            <tr>
                <th>In domain of</th>
                <td>
                    <a href="#isAVulnerabilityOf">sc2r:isAVulnerabilityOf</a><sup class="sup-op" title="object property">op</sup><br/>
                    <a href="#isReducedBy">sc2r:isReducedBy</a><sup class="sup-op" title="object property">op</sup><br/>
                    <a href="#isExploitedBy">sc2r:isExploitedBy</a><sup class="sup-op" title="object property">op</sup><br/>
                </td>
            </tr>
            <tr>
                <th>In range of</th>
                <td>
                    <a href="#reduces">sc2r:reduces</a><sup class="sup-op" title="object property">op</sup><br/>
                    <a href="#exploits">sc2r:exploits</a><sup class="sup-op" title="object property">op</sup><br/>
                    <a href="#hasVulnerability">sc2r:hasVulnerability</a><sup class="sup-op" title="object property">op</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="WebHygiene">
        <h3>Web Hygiene<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#WebHygiene</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Web hygiene are measures and steps that individuals undertake to improve their cyber security and safety.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#PreventionMeasure">sc2r:PreventionMeasure</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
            <tr>
                <th>Sub-classes</th>
                <td>
                    <a href="#SocialMediaHygiene">sc2r:SocialMediaHygiene</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#EmailHygiene">sc2r:EmailHygiene</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="WhalingPhishing">
        <h3>Whaling Phishing<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Whaling</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Whaling occurs when individuals receive fraudulent message from a perpetrator that masquarades as a senior or important individual at an organisation aiming to trick into sharing sensitive information.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#SpearPhishing">sc2r:SpearPhishing</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="WhatAboutism">
        <h3>WhatAboutism<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#WhatAboutism</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>WhatAboutism is a disinformation techniques that involves distracting individuals from one issue to another.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#MalignRhetoric">sc2r:MalignRhetoric</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="WithstandMeasure">
        <h3>Withstand Measure<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#WithstandMeasure</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>Withstand measures aim to stand against and resist the adverse incidents to maintain a level of cyber funtioning.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#AbsorbMeasure">sc2r:AbsorbMeasure</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
            <tr>
                <th>Sub-classes</th>
                <td>
                    <a href="#AlternativeResourceMeasure">sc2r:AlternativeResource</a><sup class="sup-c" title="class">c</sup><br/>
                    <a href="#IncreaseResourceMeasure">sc2r:IncreaseResources</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="Worry">
        <h3>Worry<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#Worry</code></td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#PsychologicalHarm">sc2r:PsychologicalHarm</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity class" id="YouAreNotImmune">
        <h3>You Are Not Immune<sup title="class" class="sup-c">c</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#YouAreNotImmune</code></td>
            </tr>
            <tr>
                <th>Description</th>
                <td>
                    <p>This attitute emphasizes the fact that everyone is susceptible to adverse cyber incidents.</p>
                </td>
            </tr>
            <tr>
                <th>Super-classes</th>
                <td>
                    <a href="#AttitudinalMeasure">sc2r:AttitudinalMeasure</a><sup class="sup-c" title="class">c</sup><br/>
                </td>
            </tr>
        </table>
    </div>
</section>
<section id="objectproperties">
    <h2>Object Properties <span style="float:right; font-size:smaller;"><a href="">&uparrow;</a></span></h2>
    <ul class="hlist">
        <li><a href="#canBeResultOf">canBeResultOf</a></li>
        <li><a href="#canResultIn">canResultIn</a></li>
        <li><a href="#damages">damages</a></li>
        <li><a href="#exploits">exploits</a></li>
        <li><a href="#hasVulnerability">hasVulnerability</a></li>
        <li><a href="#isAVulnerabilityOf">isAVulnerabilityOf</a></li>
        <li><a href="#isDamagedBy">isDamagedBy</a></li>
        <li><a href="#isExploitedBy">isExploitedBy</a></li>
        <li><a href="#isMitigatedBy">isMitigatedBy</a></li>
        <li><a href="#isReducedBy">isReducedBy</a></li>
        <li><a href="#isResultOf">isResultOf</a></li>
        <li><a href="#mitigates">mitigates</a></li>
        <li><a href="#reduces">reduces</a></li>
        <li><a href="#relatesTo">relatesTo</a></li>
        <li><a href="#resultsIn">resultsIn</a></li>
    </ul>
    <div class="entity property" id="canBeResultOf">
        <h3>canBeResultOf<sup title="object property" class="sup-op">op</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#canBeResultOf</code></td>
            </tr>
            <tr>
                <th>Inverse properties</th>
                <td>
                    <a href="#canResultIn">sc2r:canResultIn</a><sup class="sup-op" title="object property">op</sup>
                </td>
            </tr>
            <tr>
                <th>Domain(s)</th>
                <td>
                    <a href="#Harm">sc2r:Harm</a><sup class="sup-c" title="class">c</sup>
                </td>
            </tr>
            <tr>
                <th>Range(s)</th>
                <td>
                    <a href="#Threat">sc2r:Threat</a><sup class="sup-c" title="class">c</sup>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity property" id="canResultIn">
        <h3>canResultIn<sup title="object property" class="sup-op">op</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#canResultIn</code></td>
            </tr>
            <tr>
                <th>Domain(s)</th>
                <td>
                    <a href="#Threat">sc2r:Threat</a><sup class="sup-c" title="class">c</sup>
                </td>
            </tr>
            <tr>
                <th>Range(s)</th>
                <td>
                    <a href="#Harm">sc2r:Harm</a><sup class="sup-c" title="class">c</sup>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity property" id="damages">
        <h3>damages<sup title="object property" class="sup-op">op</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#damages</code></td>
            </tr>
            <tr>
                <th>Inverse properties</th>
                <td>
                    <a href="#isDamagedBy">sc2r:isDamagedBy</a><sup class="sup-op" title="object property">op</sup>
                </td>
            </tr>
            <tr>
                <th>Domain(s)</th>
                <td>
                    <a href="#Threat">sc2r:Threat</a><sup class="sup-c" title="class">c</sup>
                </td>
            </tr>
            <tr>
                <th>Range(s)</th>
                <td>
                    <a href="#Resource">sc2r:Resource</a><sup class="sup-c" title="class">c</sup>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity property" id="exploits">
        <h3>exploits<sup title="object property" class="sup-op">op</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#exploits</code></td>
            </tr>
            <tr>
                <th>Inverse properties</th>
                <td>
                    <a href="#isExploitedBy">sc2r:isExploitedBy</a><sup class="sup-op" title="object property">op</sup>
                </td>
            </tr>
            <tr>
                <th>Domain(s)</th>
                <td>
                    <a href="#Threat">sc2r:Threat</a><sup class="sup-c" title="class">c</sup>
                </td>
            </tr>
            <tr>
                <th>Range(s)</th>
                <td>
                    <a href="#Vulnerability">sc2r:Vulnerability</a><sup class="sup-c" title="class">c</sup>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity property" id="hasVulnerability">
        <h3>hasVulnerability<sup title="object property" class="sup-op">op</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#hasVulnerability</code></td>
            </tr>
            <tr>
                <th>Inverse properties</th>
                <td>
                    <a href="#isAVulnerabilityOf">sc2r:isAVulnerabilityOf</a><sup class="sup-op" title="object property">op</sup>
                </td>
            </tr>
            <tr>
                <th>Domain(s)</th>
                <td>
                    <a href="#Resource">sc2r:Resource</a><sup class="sup-c" title="class">c</sup>
                </td>
            </tr>
            <tr>
                <th>Range(s)</th>
                <td>
                    <a href="#Vulnerability">sc2r:Vulnerability</a><sup class="sup-c" title="class">c</sup>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity property" id="isAVulnerabilityOf">
        <h3>isAVulnerabilityOf<sup title="object property" class="sup-op">op</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#isAVulnerabilityOf</code></td>
            </tr>
            <tr>
                <th>Domain(s)</th>
                <td>
                    <a href="#Vulnerability">sc2r:Vulnerability</a><sup class="sup-c" title="class">c</sup>
                </td>
            </tr>
            <tr>
                <th>Range(s)</th>
                <td>
                    <a href="#Resource">sc2r:Resource</a><sup class="sup-c" title="class">c</sup>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity property" id="isDamagedBy">
        <h3>isDamagedBy<sup title="object property" class="sup-op">op</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#isDamagedBy</code></td>
            </tr>
            <tr>
                <th>Domain(s)</th>
                <td>
                    <a href="#Resource">sc2r:Resource</a><sup class="sup-c" title="class">c</sup>
                </td>
            </tr>
            <tr>
                <th>Range(s)</th>
                <td>
                    <a href="#Threat">sc2r:Threat</a><sup class="sup-c" title="class">c</sup>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity property" id="isExploitedBy">
        <h3>isExploitedBy<sup title="object property" class="sup-op">op</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#isExploitedBy</code></td>
            </tr>
            <tr>
                <th>Domain(s)</th>
                <td>
                    <a href="#Vulnerability">sc2r:Vulnerability</a><sup class="sup-c" title="class">c</sup>
                </td>
            </tr>
            <tr>
                <th>Range(s)</th>
                <td>
                    <a href="#Threat">sc2r:Threat</a><sup class="sup-c" title="class">c</sup>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity property" id="isMitigatedBy">
        <h3>isMitigatedBy<sup title="object property" class="sup-op">op</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#isMitigatedBy</code></td>
            </tr>
            <tr>
                <th>Inverse properties</th>
                <td>
                    <a href="#mitigates">sc2r:mitigates</a><sup class="sup-op" title="object property">op</sup>
                </td>
            </tr>
            <tr>
                <th>Domain(s)</th>
                <td>
                    <a href="#Threat">sc2r:Threat</a><sup class="sup-c" title="class">c</sup>
                </td>
            </tr>
            <tr>
                <th>Range(s)</th>
                <td>
                    <a href="#Response">sc2r:Response</a><sup class="sup-c" title="class">c</sup>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity property" id="isReducedBy">
        <h3>isReducedBy<sup title="object property" class="sup-op">op</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#isReducedBy</code></td>
            </tr>
            <tr>
                <th>Inverse properties</th>
                <td>
                    <a href="#reduces">sc2r:reduces</a><sup class="sup-op" title="object property">op</sup>
                </td>
            </tr>
            <tr>
                <th>Domain(s)</th>
                <td>
                    <a href="#Vulnerability">sc2r:Vulnerability</a><sup class="sup-c" title="class">c</sup>
                </td>
            </tr>
            <tr>
                <th>Range(s)</th>
                <td>
                    <a href="#Response">sc2r:Response</a><sup class="sup-c" title="class">c</sup>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity property" id="isResultOf">
        <h3>isResultOf<sup title="object property" class="sup-op">op</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#isResultOf</code></td>
            </tr>
            <tr>
                <th>Super-properties</th>
                <td>
                    <a href="#canBeResultOf">sc2r:canBeResultOf</a><sup class="sup-op" title="object property">op</sup>
                </td>
            </tr>
            <tr>
                <th>Inverse properties</th>
                <td>
                    <a href="#resultsIn">sc2r:resultsIn</a><sup class="sup-op" title="object property">op</sup>
                </td>
            </tr>
            <tr>
                <th>Domain(s)</th>
                <td>
                    <a href="#Harm">sc2r:Harm</a><sup class="sup-c" title="class">c</sup>
                </td>
            </tr>
            <tr>
                <th>Range(s)</th>
                <td>
                    <a href="#Threat">sc2r:Threat</a><sup class="sup-c" title="class">c</sup>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity property" id="mitigates">
        <h3>mitigates<sup title="object property" class="sup-op">op</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#mitigates</code></td>
            </tr>
            <tr>
                <th>Domain(s)</th>
                <td>
                    <a href="#Response">sc2r:Response</a><sup class="sup-c" title="class">c</sup>
                </td>
            </tr>
            <tr>
                <th>Range(s)</th>
                <td>
                    <a href="#Threat">sc2r:Threat</a><sup class="sup-c" title="class">c</sup>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity property" id="reduces">
        <h3>reduces<sup title="object property" class="sup-op">op</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#reduces</code></td>
            </tr>
            <tr>
                <th>Domain(s)</th>
                <td>
                    <a href="#Response">sc2r:Response</a><sup class="sup-c" title="class">c</sup>
                </td>
            </tr>
            <tr>
                <th>Range(s)</th>
                <td>
                    <a href="#Vulnerability">sc2r:Vulnerability</a><sup class="sup-c" title="class">c</sup>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity property" id="relatesTo">
        <h3>relatesTo<sup title="object property" class="sup-op">op</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#relatesTo</code></td>
            </tr>
        </table>
    </div>
    <div class="entity property" id="resultsIn">
        <h3>resultsIn<sup title="object property" class="sup-op">op</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#resultsIn</code></td>
            </tr>
            <tr>
                <th>Super-properties</th>
                <td>
                    <a href="#canResultIn">sc2r:canResultIn</a><sup class="sup-op" title="object property">op</sup>
                </td>
            </tr>
            <tr>
                <th>Domain(s)</th>
                <td>
                    <a href="#Threat">sc2r:Threat</a><sup class="sup-c" title="class">c</sup>
                </td>
            </tr>
            <tr>
                <th>Range(s)</th>
                <td>
                    <a href="#Harm">sc2r:Harm</a><sup class="sup-c" title="class">c</sup>
                </td>
            </tr>
        </table>
    </div>
</section>

<section id="datatypeproperties">
    <h2>Datatype Properties <span style="float:right; font-size:smaller;"><a href="">&uparrow;</a></span></h2>
    <ul class="hlist">
        <li><a href="#hasDescription">hasDescription</a></li>
        <li><a href="#hasID">hasID</a></li>
    </ul>
    <div class="entity property" id="hasDescription">
        <h3>hasDescription<sup title="datatype property" class="sup-dp">dp</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#hasDescription</code></td>
            </tr>
            <tr>
                <th>Domain(s)</th>
                <td>
                    <a href="http://www.w3.org/2002/07/owl#Thing">owl:Thing</a><sup class="sup-c" title="class">c</sup>
                </td>
            </tr>
            <tr>
                <th>Range(s)</th>
                <td>
                    <a href="http://www.w3.org/2000/01/rdf-schema#Literal">rdfs:Literal</a><sup class="sup-c" title="class">c</sup>
                </td>
            </tr>
        </table>
    </div>
    <div class="entity property" id="hasID">
        <h3>hasID<sup title="datatype property" class="sup-dp">dp</sup></h3>
        <table>
            <tr>
                <th>URI</th>
                <td><code>http://cs.unu.edu/sc2r#hasID</code></td>
            </tr>
        </table>
    </div>
</section>

  
  <section id="namedindividuals">
    <h2>Named Individuals <span style="float:right; font-size:smaller;"><a href="">&uparrow;</a></span></h2>
    <ul class="hlist">
    </ul>
</section>
  
  <section id="namespaces">
    <h2>Namespaces <span style="float:right; font-size:smaller;"><a href="">&uparrow;</a></span></h2>
    <dl>
        <dt>:</dt>
        <dd><code>http://www.semanticweb.org/mamello/ontologies/2020/5/sc2r#</code></dd>
        <dt>owl</dt>
        <dd><code>http://www.w3.org/2002/07/owl#</code></dd>
        <dt>prov</dt>
        <dd><code>http://www.w3.org/ns/prov#</code></dd>
        <dt>rdf</dt>
        <dd><code>http://www.w3.org/1999/02/22-rdf-syntax-ns#</code></dd>
        <dt>rdfs</dt>
        <dd><code>http://www.w3.org/2000/01/rdf-schema#</code></dd>
        <dt>sc2r</dt>
        <dd><code>http://cs.unu.edu/sc2r#</code></dd>
        <dt>sdo</dt>
        <dd><code>https://schema.org/</code></dd>
        <dt>skos</dt>
        <dd><code>http://www.w3.org/2004/02/skos/core#</code></dd>
        <dt>xsd</dt>
        <dd><code>http://www.w3.org/2001/XMLSchema#</code></dd>
    </dl>
</section>
  <section id="legend">
      <h2>Legend</h2>
      <table class="entity">
          <tr><td><sup class="sup-c" title="Classes">c</sup></td><td>Classes</td></tr>
          <tr><td><sup class="sup-op" title="Object Properties">op</sup></td><td>Object Properties</td></tr>
          <tr><td><sup class="sup-fp" title="Functional Properties">fp</sup></td><td>Functional Properties</td></tr>
          <tr><td><sup class="sup-dp" title="Data Properties">dp</sup></td><td>Data Properties</td></tr>
          <tr><td><sup class="sup-ap" title="Annotation Properties">dp</sup></td><td>Annotation Properties</td></tr>
          <tr><td><sup class="sup-p" title="Properties">p</sup></td><td>Properties</td></tr>
          <tr><td><sup class="sup-ni" title="Named Individuals">ni</sup></td><td>Named Individuals</td></tr>
      </table>
  </section>
</body>
</html>
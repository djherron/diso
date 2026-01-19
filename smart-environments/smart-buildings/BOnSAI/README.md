# BOnSAI

## Overview 

**BOnSAI: Smart Building Ontology for Ambient Intelligence**

**BOnSAI** is an example of an ontology that fits in more than one DISO cluster. It fits here, in the DISO `smart-buildings` cluster within the `smart-environments` cluster, but it also fits in the `ambient-intelligence` cluster.

BOnSAI ontology
* http://lpis.csd.auth.gr/ontologies/ontolist.html#bonsai
* see `BOnSAI.owl`
* BOnSAI imports and extends an aspect (dimension) of OWL-S (Web Services ontology)
  - see `Service.owl` component of OWL-S
  - from: `http://www.daml.org/services/owl-s/1.2/Service.owl`. (same as our source for OWL-S)
* BOnSAI imports and extends the CoDAMoS ontology
  - see `CoDAMoS.owl`
  - CoDAMoS context ontology
  - from `http://lpis.csd.auth.gr/ontologies/CoDAMoS/CoDAMoS.owl`

We created a merged version of the BOnSAI ontology files, in Protege:
* loaded `BOnSAI.owl` into Protege
* Protege imports `Service.owl` and `CoDAMoS.owl`
* created merged ontology
* save merged ontology to `bonsaiFull.ttl`



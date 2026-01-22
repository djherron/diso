# SOUPA

## Overview

**SOUPA: Standard Ontology for Ubiquitous and Pervasive Applications**

Paper:
* `The SOUPA Ontology for Pervasive Computing` (Chen, 2004)

Abstract:
> This paper describes **SOUPA** (Standard Ontology for Ubiquitous and Pervasive Applications) **and** the use of this ontology in building the *Context Broker Architecture* (**CoBrA**). **CoBrA** is a new agent architecture **for supporting pervasive context-aware systems in a smart space environment**. The **SOUPA** ontology is expressed using the Web Ontology Language OWL and includes modular component **vocabularies to represent intelligent agents with associated beliefs, desire, and intentions, time, space, events, user profiles, actions, and policies for security and privacy**.

website for paper:
* https://ebiquity.umbc.edu/paper/html/id/165/The-SOUPA-Ontology-for-Pervasive-Computing

Context Broker Architecture (CoBrA) and **COBRA-ONT**
* https://cobra.umbc.edu/ontologies.html
* the CoBrA has a set of associated ontologies called **COBRA-ONT**
* this page provides a link to a tarball `soupa-ont.tar.gz` which contains both the **SOUPA** ontology, from 2004-01 and 2004-06, and the **COBRA-ONT** ontologies
* the **COBRA-ONT** ontologies import and extend **SOUPA**
* DISO contains only the 2004-06 version

**SOUPA** 2004-06 is distributed as a network of 18 component ontologies. The **COBRA-ONT** ontologies import different subsets of these component ontologies and extend them, so we need to keep the SOUPA components intact. But it may be desirable to create a merged version of the 18 component ontologies as well, so we have one file for **SOUPA**.

**COBRA-ONT** defines typical concepts that describe an **intelligent meeting room environment**.

Per https://cobra.umbc.edu/ontologies-2004-05.html:
* The ontologies of **COBRA-ONT** are focused on supporting use case scenarios that evolve around the **eBiquity group meetings**.

3 ontologies are provided with **COBRA-ONT**:
* `ebiquity-geo.xml`
  - Defines useful geographical ontologies for describing the location of eBiquity group meeting and UMBC
* `ebiquity-meetings.xml`
  - Defines the ontology of eBiquity group meetings
* `ebiquity-actions.xml`
  - Defines a set of action classes to be used in expressing user privacy policy.

there is also an example privacy policy
* `harrychen-policy.xml`


**NOTE**: Due to the close association between **SOUPA** and the **COBRA-ONT** ontologies, DISO treats them as one ontology: **SOUPA**. Also, it's not clear that the **COBRA-ONT** extensions of **SOUPA** will be of interest.


## Merged ontology

Using Protege, we created a **merged** version of the many component ontologies in the SOUPA network of ontologies. We called this merge `soupa-merged.ttl`.  Note that the **COBRA-ONT** extensions of **SOUPA** are NOT part of this merged ontology.




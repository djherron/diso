# Digital Twins

DISO does not yet contain ontologies that explicitly target the domain of **digital twins**. But some of the DISO clusters clearly overlap strongly with the notion of **digital twins**. For example, the `smart-environments` cluster of ontologies, which model things like cities, buildings and homes, clearly are very close to the concept of a **digital twin**. Indeed, these undoubtedly are technology enablers of **digital twins**.

## What are digital twins?

Digital twins, as defined by the UK's **National Digital Twin Programme**:
* https://ndtp.co.uk/digital-twin-definition/

A digital twin:
> is a **digital representation of a physical-world entity or environment or a process** that includes a **two-way data flow** into and out of the physical world; (ie to/from the physical thing and its digital twin)

> replicates its physical-world counterpart to a known tolerance, performs without statistical bias, and is **able to predict what the associated physical-world entity would do given a stimulus**; and

> provides a level of **prediction confidence** within specified validation envelope and an associated **assumption set**


## The UK's National Digital Twin Programme

NDTP website:
* https://ndtp.co.uk/

The following diagram (a cross between a knowledge graph and a mind-map) describes the UK's National Digital Twin Programme:

![NDTP](NDTP-KG-Mindmap.png "UK National Digital Twin Programme")

It is clear from the NDTP diagram that it is not only DISO `smart-environment` ontologies that have relevance to the concept of **digital twins** and the UK **national digital twin** vision. The **IES** ontology, in the DISO `information-exchange` cluster, plays a key role in enabling the **IMF** (Information Management Framework) component of the **NDTP**.

The diagram also shows that the **IMF** needs its own **top-level** (upper-level) ontology, as well as **mid-level** ontology (the FDM and RDL depected in the diagram). With version 5 of **IES**, released in November 2025, these **IMF-specific** top-level and mid-level ontologies have been delivered.  The **IMF-specific** **top-level** ontology is called `ies-top`; the **mid-level** ontology (corresponding roughly to the FDM/RDL) is called `ies-core`.  See the **IES** entry in DISO cluster `information-exchange` for these ontologies.

## The IMF (Information Management Framework)

The following diagram, from the Digital Twin Hub website [1], provides a conceptual view of the architecture of the NDTP's **IMF** (Information Management Framework).

![IMF](The_7_circles_of_Information_Management_(NDTP).png "The 7 circles of Information Management (NDTP)")

As of version 5 of **IES**,:
* the **IES-top** ontology corresponds to the IMF layer 2: **Top Level Ontology**
* the **IES-core** ontology corresponds roughly to the IMF layer 3:  **Foundation Data Model**
* and **IES** itself is a component of the IMF layer 5: **Integration Architecture**

## NDTP analysis of upper-level ontologies

The following diagram, from an NDTP publication [2], shows the set of **upper-level** ontologies reviewed and considered by the team responsible for designing the **IMF's** top-level ontology.  The diagram classifies this set of top-level ontologies according to the requirements for the **IMF's** top-level ontology, as identified by the **IMF** team.

![top-level-onto-classification](top-level_ontology_classification_(NDTP).png "Top-level ontology classification for IMF by NDTP")

At the heart of the diagram we see the 4 top-level ontologies that satisify all of the NDTP's requirements for the **IMF's** top-level ontology. These are all variants of **BORO** which is proprietary. DISO does not contain any of these 4 ontologies.

However, DISO contains several of the nearby ontologies that satisfy many or most of the NDTP's requirements, such as: BFO, a version of UFO called gUFO, GFO and DOLCE.

---
[1] https://digitaltwinhub.co.uk/information-management-framework-imf/7-circles-of-information-management/

[2] `The Approach to Develop the Foundation Data Model for the Information Management Framework (NDTP, 2020)`




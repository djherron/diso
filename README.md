# Defence and Security Ontologies

This repository contains a collection of OWL ontologies relating to the domains of defence and security. 

## Overview

The ontologies in this collection were identified and obtained during an **ontology search** exercise undertaken during Nov/Dec of 2025.  The search exercise was largely literature-driven. Most of the ontologies are accompanied by one or more **academic papers** that can be cited in relation to the ontology.  Each ontology is accompanied by some amount of documentation providing information such as: a short description, relevant context, and the source from which a physical copy of the ontology was ultimately obtained.

Some ontologies are distributed as networks of component ontologies, woven together with `owl:imports` statements. For many of these, we have created **merged** versions of the ontology, using the Protege ontology editor, sometimes together with ontology catalog (`catalog-v001.xml`) files to redirect URLs to local files to overcome accessibility issues.  Details of the merge strategy employed are recorded in the documentation accompanying such ontologies.

The motivation for establishing this collection of ontologies has to do with the research problem of OWL **ontology alignment**.  The ambition is to use this collection to help create a **defence & security track** for the [Ontology Alignment Evaluation Initiative (OAEI)](https://oaei.ontologymatching.org/).  OAEI tracks contain one or more **ontology alignment tasks** --- pairs of ontologies with domain overlaps that pose interesting ontology alignment challenges, accompanied by a reference alignment.

Most of the ontologies in the collection naturally cluster into categories. The structure of this repository reflects this clustering. Sometimes, an ontology fits more than one cluster. Each ontology appears only once in the repository, however --- in the cluster where the fit was deemed strongest.

Anticipated next steps towards the goal of creating a **defence & security** OAEI track:
* analyse and evaluate the ontologies in this collection
* conduct exploratory alignments
* identify candidate pairs of ontologies for alignment tasks
* select a short-list of ontology pairs
* select a final (small) set of alignment tasks (ontology pairs)
* establish **reference alignments** for the final set of alignment tasks
* formally establish the defence & security OAEI track

## Relaxed domain definitions

The domains of defence and security have been **interpreted broadly**. The connection between some of the categories (subdomains) and the domains of defence and security may appear tenuous. Where appropriate, the documentation accompanying a category (subdomain/cluster) refers to this issue and provides arguments and/or justification for the categories inclusion in the collection. 




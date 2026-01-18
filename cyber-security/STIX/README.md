# STIX

## Overview 

**STIX: Structured Threat Information eXpression**

The official STIX specification, managed by the OASIS Cyber Threat Intelligence (CTI) Technical Committee, uses a data model better suited for property graphs and is primarily published in JSON schemas

OASIS Threat Actor Context (TAC) technical committee GitHub repo:
* https://github.com/oasis-tcs/tac-ontology
> The purpose of this repository is to manage Ontology Web Language (OWL) representations of the Threat Actor Context Technical Committee's (TAC-TC) work
* the repo provides *an OWL representation of the STIX 2.1 specification*
* this is where we obtained STIX for the DISO collection
* see folder `stix-spec`
* see folder `stix-semex`

`./stix-spec/stix-spec.owl`
* the STIX 2.1 Specification ontolgy
> is meant to be as true of a ontology representation to the OASIS STIX 2.1 Specification document as possible.
* however, the documentation for this representation STIX (see `./docs/stix-spec.md`) highlights that this representation of the STIX 2.1 specification is suited to **property graphs** rather than **semantic graphs**
* it cautions that:
> A Description Logics Reasoner is meant to interpret semantic graphs, not property graphs.
* in other words, this representation of STIX may be awkward to work with for some **matching systems**

`./stix-semex/stix-semex.owl`
* this is the STIX 2.1 specification represented as a **semantic graph** rather than a **property graph**
* it's called the STIX Semantic Extension ontology
* so, if we have problems working with `stix-spec.owl` we can try `stix-semex.owl`

STIX documentation
* https://oasis-open.github.io/cti-documentation/
> The OASIS Cyber Threat Intelligence (CTI) TC supports automated information sharing for cybersecurity situational awareness, real-time network defense, and sophisticated threat analysis.

OASIS Cyber Threat Intelligence (CTI) TC
* https://www.oasis-open.org/committees/tc_home.php?wg_abbrev=cti
> Supporting automated information sharing for cybersecurity situational awareness, real-time network defense, and sophisticated threat analysis


# SNORT

## Overview 

**SNORT: Network Intrusion Detection & Prevention**

website:
* https://www.snort.org/
> Snort is the foremost Open Source Intrusion Prevention System (IPS) in the world. Snort IPS uses a series of rules that help define malicious network activity and uses those rules to find packets that match against them and generates alerts for users.

SNORT is not normally available in OWL format. We obtained our SNORT ontology files from the SEPSES (Semantic Processing of Security Event Streams) research group at Technical University Vienna (https://sepses.ifs.tuwien.ac.at/) in relation to their **ICS Security KG**. 

The SNORT ontology files were created by the SEPSES team. They are **expressions** of the SNORT IPS described on the SNORT website.

`snort.ttl`
* `dc:title` "SEPSES SNORT Ontology"
* `dc:creator` "SEPSES team"
* `dc:description` "A reference ontology to describe common terms related to SNORT."

`snortalert.ttl`
* `dc:title` "SEPSES IDS Snort Alert Log Ontology"
* `dc:description` "An ontology to describe IDS Snort Alert log structure"

[Note: Here, 'IDS' refers to Intrusion Detection System, presumably]

`snortrule.ttl`
* `dc:title` "SEPSES SNORT rule ontology"
* `dc:description` "An ontology to describe SNORT rule information"

Although created by the SEPSE team in relation to their **ICS-SEC KG**, the SEPSES SNORT ontologies gathered here on DISO are NOT part of the SEPSES integrated **ICS-SEC-KG** ontology, `ics-sec-kg-onto.ttl`.  See the DISO entry for **ICS-SEC-KG-ONTO** for more information on SEPSES and the **ICS Security KG**, and on the repo from where we obtained the SEPSIS SNORT ontology files.

Using Protege, we created a **merged** version of the 3 snort ontology files and called it `snortMerged.ttl`




# CAPEC

## Overview 

**CAPEC: Common Attack Pattern Enumerations and Classifications**

website:
* https://capec.mitre.org/
* cyber attack patterns
> Understanding how the adversary operates is essential to effective cybersecurity. CAPEC™ helps by providing a comprehensive dictionary of known patterns of attack employed by adversaries to exploit known weaknesses in cyber-enabled capabilities.

CAPEC is not normally available in OWL format. The SEPSES (Semantic Processing of Security Event Streams) research group at Technical University Vienna (https://sepses.ifs.tuwien.ac.at/) created an OWL version of CAPEC for their **ICS Security KG**. 

The OWL ontology file for CAPEC that we have obtained for DISO, `capec.ttl`, was created by the SEPSES team by rendering the **then existing** definition of CAPEC into OWL. It's not clear whether CAPEC as currently defined (on the MITRE website) is ahead of the version of CAPEC rendered in `capec.ttl` from SEPSES. It may be well ahead.

For safety, DISO users should regard the `capec.ttl` ontology file as an expression of CAPEC, but not necessarily fully up-to-date with the latest version of CAPEC.

The DISO `capec.ttl` is one component of the integrated ontology for the SEPSES **ICS Security KG**. See the DISO entry for **ICS-SEC-KG-ONTO** for more information on SEPSES and the **ICS Security KG**, and on the repo from where we obtained the DISO `capec.ttl`.




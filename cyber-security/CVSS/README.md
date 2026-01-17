# CVSS

## Overview 

**CVSS: Common Vulnerability Scoring System**

Wikipedia:
* https://en.wikipedia.org/wiki/Common_Vulnerability_Scoring_System
> an open framework for rating the severity of security vulnerabilities in computing systems

CVSS SIG
* https://www.first.org/cvss/

CVSS is not normally available in OWL format. We obtained our copy of the `cvss.ttl` file from the SEPSES (Semantic Processing of Security Event Streams) research group at Technical University Vienna (https://sepses.ifs.tuwien.ac.at/) in relation to their **ICS Security KG**. 

The OWL ontology file for CVSS that we have obtained for DISO, `cvss.ttl`, was created by the SEPSES team. The ontology file itself declares that this is an ontology to **represent CVSS**. It also says:
> This ontology is developed based on the NVD resources extracted from NVD (https://nvd.nist.gov/vuln/ 
* NVD is the U.S. National Vulnerability Database, managed by NIST: https://nvd.nist.gov/

For safety, DISO users should regard the `cvss.ttl` ontology file as an expression of CVSS, but not necessarily fully up-to-date with the latest version of CVSS.

The DISO `cvss.ttl` is one component of the integrated ontology for the SEPSES **ICS Security KG**. See the DISO entry for **ICS-SEC-KG-ONTO** for more information on SEPSES and the **ICS Security KG**, and on the repo from where we obtained the DISO `cvss.ttl`.




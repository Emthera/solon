# The Solon Architecture

[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

Solon is a schema standard for managing Electronic Medical Records. It decouples **identity** from **clinical evidence** and serves as the **source of truth** for downstream applications that consume the schema data to provide automation — scheduling, alerting, analytics, decision support, and more.

The patient owns a master index (Profile) that points to decentralized Tracks stored anywhere on the web, remaining the sole gatekeeper of their health history.

## Core Principles

| Principle | Description |
|---|---|
| **Discovery Manifest** | History items act as flags that resolve to detailed data in external tracks |
| **Multi-Ref Redundancy** | Events point to multiple storage nodes or schema versions for availability and verification |
| **Tool Provenance** | Every data point carries a URI to the hardware or software that produced it |


## References

| Standard | Link |
|---|---|
| JSON Schema 2020-12 | https://json-schema.org/draft/2020-12/schema |
| ICD-11 | https://icd.who.int/en |
| LOINC | https://loinc.org |
| SNOMED CT | https://www.snomed.org |
| ATC Classification | https://www.who.int/tools/atc-ddd-toolkit |
| RxNorm | https://www.nlm.nih.gov/research/umls/rxnorm |
| EDQM Standard Terms | https://standardterms.edqm.eu |
| W3C DIDs | https://www.w3.org/TR/did-core |
| IPFS | https://docs.ipfs.tech |
| eIDAS Regulation | https://digital-strategy.ec.europa.eu/en/policies/eidas-regulation |

## License

Solon Architecture © 2025 by TheLazzziest is licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/).

- **Attribution** — Credit Emthera.
- **NonCommercial** — Commercial use requires a separate agreement.
- **ShareAlike** — Derivatives must use the same license.

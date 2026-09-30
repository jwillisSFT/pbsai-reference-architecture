# The Practitioner’s Blueprint for Secure AI (PBSAI)

[![DOI](https://zenodo.org/badge/DOI/<ZENODO_DOI>.svg)](https://doi.org/<ZENODO_DOI>)
![License: CC BY 4.0](https://img.shields.io/badge/License-CC--BY--4.0-lightgrey.svg)

---

## 1. Overview

The Practitioner’s Blueprint for Secure AI (PBSAI) is a multi-domain, evidence-centric reference architecture for securing AI-enabled enterprise systems.

It defines a structured governance and execution framework for:

* AI-enabled cybersecurity systems
* Multi-agent operational environments
* Enterprise AI estates
* Hybrid cloud and HPC defensive infrastructures

PBSAI is a reference architecture, not a software implementation.

---

## 2. Architectural Foundation

PBSAI is built on four core principles:

### 2.1 Deterministic Governance Mediation

All AI outputs are treated as governance-mediated proposals, not direct execution commands.

### 2.2 Evidence-Centric Operations

All actions produce structured, queryable evidence artifacts supporting auditability and traceability.

### 2.3 Domain-Decomposed Multi-Agent Architecture

The system is organized into 12 security domains:

* Domain A — Governance, Risk, and Compliance
* Domain B — Asset, Configuration, and Change Management
* Domain C — Identity, Credential, and Access Management
* Domain D — Threat Intelligence & Situational Awareness
* Domain E — Protective Technologies & Hardening
* Domain F — Data Security & Privacy
* Domain G — Incident Response & Forensics
* Domain H — Resilience & Continuity
* Domain I — Security Architecture & Systems Engineering
* Domain J — Physical & Environmental Security
* Domain K — Supply Chain & Lifecycle Security
* Domain L — Security Program Enablement

### 2.4 MCP-Style Context Governance

All agents operate via:

* Context Envelopes
* Output Contracts
* Provenance metadata
* Policy constraints
* Human-in-the-loop authorization

---

## 3. Repository Contents

```text
.
├── README.md
├── CONTRIBUTING.md
├── SECURITY.md
├── LICENSE.txt
├── NOTICE.md
├── .github/
│   ├── CODEOWNERS
│   └── ISSUE_TEMPLATE/
│       ├── architecture-review.yml
│       └── config.yml
│
├── architecture/
│   ├── arXiv 2602.11301 - The_PBSAI_Governance_Ecosystem-A_Multi-Agent_AI_Reference_Architecture_for_Securing_Enterprise_AI_Estates.pdf
│   └── PBSAI V2 - Main.pdf
│
├── controls/
│   ├── PBSAI Control Catalog v1.0
│   ├── PBSAI NIST SP 800-53 Rev. 5 Mapping
│   ├── PBSAI NIST SP 800-160 Volume 2 Mapping
│   └── PBSAI NIST AI Risk Management Framework (AI RMF) Mapping
│
├── domains/
│   ├── PBSAI V2 - Domain A - GRC & Oversight.pdf
│   ├── PBSAI V2 - Domain B - Asset, Configuration & Change Management.pdf
│   ├── PBSAI V2 - Domain C - ICAM.pdf
│   ├── PBSAI V2 - Domain D - Threat Intelligence & Situational Awareness.pdf
│   ├── PBSAI V2 - Domain E - Protective Technologies & Hardening.pdf
│   ├── PBSAI V2 - Domain F - Data Security & Privacy.pdf
│   ├── PBSAI V2 - Domain G - Incident Response & Forensics.pdf
│   ├── PBSAI V2 - Domain H - Resilience & Continuity.pdf
│   ├── PBSAI V2 - Domain I - Security Architecture & Systems Engineering.pdf
│   ├── PBSAI V2 - Domain J - Physical & Environmental Security.pdf
│   ├── PBSAI V2 - Domain K - Supply Chain & Lifecycle Security.pdf
│   └── PBSAI V2 - Domain L - Security Program Enablement.pdf
```

---

## 4. Control System

The PBSAI Control Catalog defines the canonical control system.

It includes:

* Deterministic control identifiers
* Global governance controls
* Domain-specific control families
* MCP context enforcement
* Evidence and provenance mechanisms

---

## 5. Standards Alignment Documents

### 5.1 NIST SP 800-53 Rev. 5 Mapping

Direct control-to-control alignment with PBSAI catalog controls.

### 5.2 NIST SP 800-160 Volume 2 Mapping

Systems security engineering alignment layer.

**Note:**
The NIST SP 800-160 mapping introduces a secondary interpretive taxonomy for systems engineering alignment and does not redefine PBSAI control identifiers.

### 5.3 NIST AI Risk Management Framework (AI RMF)

Maps PBSAI across:

* GOVERN
* MAP
* MEASURE
* MANAGE

and trustworthiness characteristics:

* accountability
* transparency
* explainability
* safety
* resilience
* traceability
* human oversight

---

## 6. Versioning

This repository represents the PBSAI v1.0 initial public release.

PBSAI was developed before the Agent2Agent (A2A) protocol had been sufficiently formalized for incorporation into the architecture. A future PBSAI revision will add an explicit A2A interoperability profile while preserving PBSAI's governance and execution-boundary semantics.

The planned A2A integration will define how A2A interactions map to PBSAI architectural constructs, including:

* Context Envelope semantics for governed agent-to-agent input
* Output Contract semantics for governed agent-to-agent output
* agent and interaction identity
* provenance and evidence requirements
* authority and delegation boundaries
* authorization requirements for consequential actions
* mapping between A2A messages and PBSAI governance artifacts
* integration with AGCP-mediated execution and commit controls

A2A interoperability does not change the PBSAI principle that communication between agents is distinct from authority to commit externally consequential actions.

Future versions may also extend:

* control catalog
* domain specifications
* mapping layers
* interoperability profiles
* reference implementations

---

## 7. Public Review and Governance

PBSAI is published for public technical review, implementation evaluation, and interoperability discussion.

Public review is advisory. Submission, discussion, or acknowledgement of an issue does not alter the authoritative PBSAI architecture or confer governance, maintainer, approval, or change authority.

Authoritative changes to PBSAI architecture documents, domain specifications, control catalogs, mappings, interoperability artifacts, and other controlled repository content are made through the authorized project-maintainer change process.

Public feedback may identify matters for consideration in a future PBSAI revision, but a proposed change becomes authoritative only when incorporated into the maintained repository and applicable project release.

See [CONTRIBUTING.md](CONTRIBUTING.md) for the complete public-review and contribution model.

### Feedback Categories

GitHub Issues may be used for:

* Architecture Defect
* Architecture Ambiguity
* Domain or Control Gap
* Control Mapping Concern
* A2A Interoperability Concern
* Interoperability Concern
* Context / Output Contract Concern
* Evidence or Provenance Concern
* Security Architecture Concern
* Governance / Execution Boundary Concern
* Implementation Experience

Reviewers should identify, where applicable:

* the relevant PBSAI architecture document or domain
* section or control identifier
* mapping or interoperability artifact
* architectural or implementation impact
* proposed resolution

External review and feedback are conducted through GitHub Issues. Pull requests affecting PBSAI architecture or controlled repository content are restricted to authorized collaborators and maintainers.

---

## 8. Security Disclosures

Do not report exploitable vulnerabilities or sensitive security information through public GitHub Issues.

Use GitHub Private Vulnerability Reporting for this repository whenever possible.

If private vulnerability reporting is unavailable, contact:

[research@agcp.ai](mailto:research@agcp.ai)

See [SECURITY.md](SECURITY.md) for the complete security reporting policy.

Public architectural, control-design, interoperability, and specification-level security concerns that do not disclose an exploitable vulnerability may be submitted through the PBSAI Architecture Review issue form.

---

## 9. Intellectual Property and Project Independence

Copyright, licensing, patent, and related intellectual-property rights remain as stated in [LICENSE.txt](LICENSE.txt) and [NOTICE.md](NOTICE.md).

Participation in public PBSAI review does not transfer ownership, governance, project assets, repositories, architectural authority, copyright, patent rights, or other intellectual-property rights to reviewers, participating organizations, standards bodies, alliances, or other third parties.

Specific materials separately contributed by a PBSAI rights holder or authorized maintainer to another project or organization are governed by the terms applicable to those specific contributions.

Public review of PBSAI and participation by PBSAI maintainers or rights holders in external standards, research, or industry organizations do not, by themselves, constitute contribution or transfer of the PBSAI project, repository, architecture, or governance to those organizations.

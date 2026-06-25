# The Practitioner’s Blueprint for Secure AI (PBSAI)

[![DOI](https://zenodo.org/badge/DOI/<ZENODO_DOI>.svg)](https://doi.org/<ZENODO_DOI>)
![License: CC BY 4.0](https://img.shields.io/badge/License-CC--BY--4.0-lightgrey.svg)

---

## 1. Overview

The Practitioner’s Blueprint for Secure AI (PBSAI) is a multi-domain, evidence-centric reference architecture for securing AI-enabled enterprise systems.

It defines a structured governance and execution framework for:
- AI-enabled cybersecurity systems
- Multi-agent operational environments
- Enterprise AI estates
- Hybrid cloud and HPC defensive infrastructures

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

Domain A — Governance, Risk, and Compliance  
Domain B — Asset, Configuration, and Change Management  
Domain C — Identity, Credential, and Access Management  
Domain D — Threat Intelligence & Situational Awareness  
Domain E — Protective Technologies & Hardening  
Domain F — Data Security & Privacy  
Domain G — Incident Response & Forensics  
Domain H — Resilience & Continuity  
Domain I — Security Architecture & Systems Engineering  
Domain J — Physical & Environmental Security  
Domain K — Supply Chain & Lifecycle Security  
Domain L — Security Program Enablement  

### 2.4 MCP-Style Context Governance
All agents operate via:
- Context Envelopes
- Output Contracts
- Provenance metadata
- Policy constraints
- Human-in-the-loop authorization

---

## 3. Repository Contents

.
├── README.md
├── LICENSE
├── NOTICE.md
│
├── architecture/
│   ├── arXiv 2602.11301 - The_PBSAI_Governance_Ecosystem-A_Multi-Agent_AI_Reference_Architecture_for_Securing_Enterprise_AI_Estates.pdf
│   ├── PBSAI V2 - Main.pdf
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

---

## 4. Control System

The PBSAI Control Catalog defines the canonical control system.

It includes:
- Deterministic control identifiers
- Global governance controls
- Domain-specific control families
- MCP context enforcement
- Evidence and provenance mechanisms

---

## 5. Standards Alignment Documents

### 5.1 NIST SP 800-53 Rev. 5 Mapping
Direct control-to-control alignment with PBSAI catalog controls.

### 5.2 NIST SP 800-160 Volume 2 Mapping
Systems security engineering alignment layer.

NOTE:
The NIST SP 800-160 mapping introduces a secondary interpretive taxonomy for systems engineering alignment and does not redefine PBSAI control identifiers.

### 5.3 NIST AI Risk Management Framework (AI RMF)
Maps PBSAI across:
- GOVERN
- MAP
- MEASURE
- MANAGE

and trustworthiness characteristics:
- accountability
- transparency
- explainability
- safety
- resilience
- traceability
- human oversight

---

## 6. Versioning

This repository represents PBSAI v1.0 initial public release.

Future versions may extend:
- control catalog
- domain specifications
- mapping layers
- reference implementations



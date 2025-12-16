# Cyber Knowledge Share (CKS)

The Cyber Knowledge Share (CKS) is an enterprise-wide cybersecurity knowledge base designed to support consistent, accurate, and policy-aligned execution of cybersecurity governance, operations, and inspection activities.

CKS serves as a centralized reference platform for cybersecurity practitioners, auditors, and engineering staff by consolidating authoritative guidance, enterprise policy, tooling references, and standardized workflows into a single, structured system.

---

## Repository Structure

This repository contains representative, sanitized artifacts demonstrating the architecture, governance, and operational intent of the Cyber Knowledge Share (CKS).

cks/
├── README.md
│
├── screenshots/
│   ├── navigation_tiles.png
│   └── example_domain_pages.png
│
├── architecture/
│   ├── cks_overview_diagram.png
│   └── ai_rag_high_level_flow.png
│
├── templates/
│   ├── domain_page_template.md
│   └── inspection_preparation_template.md
│
└── scope_notice.md

---

## Purpose

The primary objective of CKS is to reduce knowledge fragmentation and improve execution quality across cybersecurity functions by:

- Providing a single source of truth for governance, compliance, and operational guidance
- Enabling inspection readiness through repeatable, well-documented processes
- Supporting personnel at varying experience levels with curated, role-relevant content
- Preserving institutional knowledge and reducing reliance on informal tribal knowledge

---

## Knowledge Domains

CKS content is organized into topic-based domains, including but not limited to:

- Classified Cybersecurity Governance  
- Incident Response  
- Continuous Monitoring (ConMon)  
- Inspection Preparation  
- System Hardening (SCAP & STIGs)  
- Auditing Information & Best Practices  
- Anti-Virus & Anti-Malware Management  
- Splunk Enterprise  
- Tenable Nessus  
- Enterprise Policies & Procedures  
- New Hire Resources  
- Templates & Helpful Resources  
- DoD-Related Documentation Repositories

Each domain follows standardized page structures to promote clarity, consistency, and maintainability.

---

## Embedded Control & Policy Alignment

CKS integrates direct references to applicable regulatory and policy frameworks to support traceability and defensibility, including:

- NIST SP 800-53 (Security & Privacy Controls)
- NIST SP 800-37 (Risk Management Framework)
- NIST SP 800-39 (Enterprise Risk Management)
- NIST SP 800-30 (Risk Assessment)
- Applicable DoD guidance and overlays
- Enterprise-specific cybersecurity policies and procedures

Where applicable, control references are embedded contextually alongside procedures and guidance to support real-world application rather than theoretical compliance.

---

## AI-Assisted Knowledge Access (RAG-LM)

CKS is augmented by a dedicated Retrieval-Augmented Generation Language Model (RAG-LM) built on the **LLaMA-3.3-70B-Instruct** model, selected for its strong instruction-following capability, reasoning consistency, and operational efficiency for governance-focused use cases.

The model is integrated with a curated knowledge corpus consisting of authoritative NIST publications, DoD guidance, and enterprise policy. Intentional knowledge guardrails (“AI-Barrier”) are implemented to constrain responses to validated sources and approved context, reducing the risk of speculation, hallucination, or policy misalignment.

The AI capability is designed to provide accurate, standards-aligned guidance and assist users in navigating complex regulatory and procedural topics, while explicitly complementing, and not replacing the authoritative documentation and human judgment.

---

## Governance & Content Management

CKS is designed with long-term sustainability in mind and incorporates:

- Defined ownership and stewardship for content areas
- Standardized templates and formatting conventions
- Version awareness and periodic review expectations
- Clear separation between authoritative guidance and supporting reference material

All content included in this repository is sanitized and representative in nature.

---

## Scope Notice

This repository contains structural examples, templates, and representative artifacts only.  
No proprietary, classified, or sensitive enterprise information is included.

CKS is presented here as an architectural and governance reference demonstrating how enterprise cybersecurity knowledge bases can be structured, governed, and operationalized.

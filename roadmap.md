# CAVAL Layer Roadmap

This roadmap describes the planned development of the CAVAL Layer specification, schema, and governance infrastructure. Versioning follows semantic versioning (MAJOR.MINOR.PATCH).

---

## Current: v0.1 — Provenance & Category Definition
*Published April 2026*

- Public release of the CAVAL Layer specification
- CAAS (Clinical AI Attribution Schema) v0.1.1 published
- CC BY 4.0 open license established
- Core architecture defined:
  - Centralized authority layer for AI governance
  - Universal attribution substrate
  - Cross-workflow lineage graph
  - Policy-driven validation and routing engine

---

## v0.2 — Schema Formalization
*Target: Q3 2026*

- JSON/YAML schemas for:
  - Attribution events
  - Validation policy objects
  - Lineage nodes
  - Governance decisions
- Reference vocabulary for override reason codes (judgment_capture)
- Inference pattern controlled vocabulary expansion
- review_record block evaluation for Level 2 conformance promotion
- HL7 FHIR R4 alignment review
- Public comment period opens

---

## v0.3 — Jurisdiction Expansion
*Target: Q4 2026*

- EU AI Act August 2026 compliance deadline alignment
- Expanded regulatory mapping:
  - EU AI Act Articles 9–15
  - Health Canada Digital Health guidelines
  - TGA Software as a Medical Device framework
  - CDSCO AI/ML Medical Device guidance
- Multi-jurisdiction conformance testing framework
- CAAS event validator (open source)

---

## v0.4 — Implementation Reference
*Target: Q4 2026*

- Reference implementation of CAVAL Layer API
- Sample integration patterns for major EHR platforms and ambient scribe vendors
- Certified CAAS-compatible governance store specification
- Level 3 Network Conformant certification framework draft

---

## v1.0 — Stable Release
*Target: Q1 2027*

- First stable, production-ready release
- HL7 Clinical Decision Support Work Group review complete
- Full conformance test suite
- Migration guide from v0.x
- Certification program specification (separate from open schema)
- Multi-language documentation (EN, FR, DE, JA)

---

## Guiding Principles

- **Open schema, always.** The specification remains CC BY 4.0. Certification programs and hosted infrastructure are separate commercial offerings.
- **Jurisdiction-configurable.** A single attribution event satisfies requirements across all supported regulatory frameworks.
- **Human decision primacy.** The schema captures AI influence. It does not capture or imply that AI made the decision.
- **Append-only and immutable.** Events are legally defensible records, not editable logs.

---

## Contributing

To propose a field for promotion to core schema, open a GitHub issue with a completed field proposal.  
To submit feedback on the specification, open a GitHub issue or email securtright@gmail.com.

CAVAL™ and CAVAL Layer™ are trademarks of Sarah Curtright.  
This specification is licensed under CC BY 4.0: https://creativecommons.org/licenses/by/4.0/legalcode


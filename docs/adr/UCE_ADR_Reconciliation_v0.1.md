# UCE — Architecture Decision Record Reconciliation

**Document ID:** UCE-ADR-RECON-001
**Version:** 0.1
**Status:** Proposed
**Numbering Policy:** Approved
**Related Documents:**

- UCE Software Requirements Specification v0.1
- UCE V0 Technical Design Specification v0.1
- UCE ADR Pack v0.1

## 1. Problem Statement

The SRS Appendix B and the existing ADR Pack assign different architectural subjects to ADR-008, ADR-009, and ADR-010.

This discrepancy creates ambiguity in architecture references, implementation planning, and technical reviews.

## 2. Identified Conflicts

| ADR ID  | SRS Appendix B                       | Existing ADR Pack           |
| ------- | ------------------------------------ | --------------------------- |
| ADR-008 | Signed capability manifests          | Worker isolation            |
| ADR-009 | Testing, privacy, and security gates | Signed capability manifests |
| ADR-010 | Deterministic/manual controls        | Testing gates               |

## 3. Approved Numbering Policy

The existing UCE ADR Pack v0.1 is the canonical source for ADR identifiers.

The original SRS and ADR Pack must remain unchanged.

Where identifiers conflict, implementation documentation must reference the canonical ADR identifier and preserve traceability to the original SRS reference.

This policy does not change the acceptance status or technical meaning of any architectural decision.

## 4. Cross-Reference Mapping

| Architectural Subject                | SRS Reference                                    | Canonical ADR Reference                   |
| ------------------------------------ | ------------------------------------------------ | ----------------------------------------- |
| Worker isolation                     | Technical architecture and security requirements | ADR-008                                   |
| Signed capability manifests          | Appendix B: ADR-008                              | ADR-009                                   |
| Testing, privacy, and security gates | Appendix B: ADR-009                              | ADR-010                                   |
| Deterministic/manual controls        | Appendix B: ADR-010                              | Separate ADR proposed; identifier pending |

## 5. Existing Proposed Decisions

The following decisions retain their existing status:

- ADR-011: Desktop framework — Proposed
- ADR-012: Implementation language split — Proposed

Neither decision is accepted by this reconciliation.

## 6. Outstanding Actions

1. Review whether deterministic/manual controls require a separate ADR.
2. Assign an identifier after verifying the complete ADR register.
3. Determine whether a future SRS revision should update Appendix B references.
4. Preserve traceability between requirements and architectural decisions.

## 7. Change Control

- Do not modify original specification PDFs.
- Do not silently renumber existing ADRs.
- Do not mark proposed architectural decisions as accepted without approval.
- Record subsequent architectural decisions through the approved ADR process.

## 8. Implementation Impact

This document records an approved numbering policy but does not authorize implementation changes.

**Document Status:** Proposed — further reconciliation actions remain pending.

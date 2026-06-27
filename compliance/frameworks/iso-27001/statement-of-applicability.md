# ISO/IEC 27001 Statement of Applicability (SoA)

| Field | Value |
| --- | --- |
| Document ID | COMP-ISO-001 |
| Standard | ISO/IEC 27001:2022 (Annex A) |
| Owner | CISO |
| Status | Draft |
| Version | 1.0 |

## Purpose

The SoA records which Annex A controls apply, whether they are implemented, and the justification for inclusion or exclusion. Annex A:2022 has 93 controls across four themes: Organizational (5), People (6), Physical (7), and Technological (8).

## Control Theme Summary

| Theme | Clause | Count | Examples |
| --- | --- | --- | --- |
| Organizational | A.5 | 37 | Policies, roles, supplier security, incident management |
| People | A.6 | 8 | Screening, awareness, disciplinary process |
| Physical | A.7 | 14 | Secure areas, equipment, clear desk |
| Technological | A.8 | 34 | Access control, cryptography, logging, secure development |

## Statement of Applicability

| Control | Title | Applicable | Status | Justification | Reference |
| --- | --- | --- | --- | --- | --- |
| A.5.1 | Policies for information security | Yes | Implemented | Information Security Policy in place | governance/policies/information-security-policy.md |
| A.5.15 | Access control | Yes | Implemented | Access Control Policy in place | governance/policies/access-control-policy.md |
| A.5.12 | Classification of information | Yes | Implemented | Data Classification Policy in place | governance/policies/data-classification-policy.md |
| A.6.3 | Awareness, education and training | Yes | Partial | Awareness program being formalized | |
| A.7.4 | Physical security monitoring | Yes | Planned | Pending facility controls review | |
| A.8.5 | Secure authentication | Yes | Implemented | MFA and Password Standard | governance/standards/password-standard.md |
| A.8.8 | Management of technical vulnerabilities | Yes | Partial | Patching SLA being tightened (see R-002) | risk/risk-register.csv |
| A.8.15 | Logging | Yes | Partial | Centralized logging in progress | |

## Exclusions

Record any excluded controls here with justification. Example: a control may be excluded if the organization does not perform the related activity (e.g. no in-house software development).

## Review

The SoA is reviewed at least annually and whenever controls change.

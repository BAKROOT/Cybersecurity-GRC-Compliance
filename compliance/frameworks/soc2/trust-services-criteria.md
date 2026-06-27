# SOC 2 Trust Services Criteria Mapping

| Field | Value |
| --- | --- |
| Document ID | COMP-SOC2-001 |
| Framework | AICPA SOC 2 (Trust Services Criteria) |
| Owner | CISO |
| Status | Draft |
| Version | 1.0 |

## Trust Services Categories

| Category | Always Required | Focus |
| --- | --- | --- |
| Security (Common Criteria) | Yes | Protection against unauthorized access |
| Availability | Optional | System uptime and resilience |
| Processing Integrity | Optional | Complete, accurate, timely processing |
| Confidentiality | Optional | Protection of confidential information |
| Privacy | Optional | Handling of personal information |

## Common Criteria (CC) Overview

| Series | Topic |
| --- | --- |
| CC1 | Control environment |
| CC2 | Communication and information |
| CC3 | Risk assessment |
| CC4 | Monitoring activities |
| CC5 | Control activities |
| CC6 | Logical and physical access controls |
| CC7 | System operations |
| CC8 | Change management |
| CC9 | Risk mitigation |

## Criteria Mapping

| Criteria | Description | Status | Internal Control | Evidence |
| --- | --- | --- | --- | --- |
| CC1.1 | Commitment to integrity and ethics | Implemented | Charter and policies | governance/charters/security-program-charter.md |
| CC3.1 | Specifies objectives to assess risk | Implemented | Risk management framework | risk/risk-management-framework.md |
| CC6.1 | Logical access security | Implemented | Access Control Policy | governance/policies/access-control-policy.md |
| CC6.2 | Registration and authorization of users | Implemented | Access provisioning process | governance/procedures/access-review-procedure.md |
| CC6.3 | Access removal | Partial | Deprovisioning process | governance/procedures/access-review-procedure.md |
| CC7.2 | Monitoring for anomalies | Partial | Logging and monitoring | |
| CC8.1 | Change management | Planned | Change management process | |

## Type I vs Type II

Type I assesses control design at a point in time. Type II assesses operating effectiveness over a period (typically 3-12 months). Maintain evidence in audit/evidence/evidence-tracker.csv to support a Type II examination.

## Review

Reviewed before each audit period and at least annually.

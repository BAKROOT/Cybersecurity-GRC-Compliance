# Audit

The audit domain supports **internal and external audits**. It centralizes the evidence that proves controls are operating and provides a template for reporting audit results.

## Files

| Path | Purpose |
| --- | --- |
| evidence/evidence-tracker.csv | Index of control evidence collected for audits |
| templates/audit-report-template.md | Standard structure for an internal audit report |

## Audit Lifecycle

1. Plan - define scope, objectives, and criteria (frameworks and controls).
2. Fieldwork - gather and test evidence against control requirements.
3. Report - document findings, ratings, and recommendations.
4. Remediate - assign and track corrective actions.
5. Follow-up - verify that actions were completed and effective.

## Finding Ratings

| Rating | Meaning |
| --- | --- |
| Critical | Control absent or failed; immediate action required |
| High | Significant weakness; prompt remediation |
| Medium | Improvement needed within a defined period |
| Low | Minor issue or recommendation |

## Evidence Principles

Evidence should be sufficient, reliable, relevant, and timely. Each item links to the control it supports (see compliance/control-mappings/control-crosswalk.csv) and is retained per the retention policy.

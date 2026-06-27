# Contributing

Thank you for helping maintain this GRC repository. Because this content governs security and compliance, all changes follow a controlled process.

## Principles

- Every document has an Owner and an Approver.
- Changes are proposed via pull request, not committed directly to main.
- Approved policies and standards are only changed with the Approver's sign-off.

## Workflow

1. Create a branch named for your change (for example, policy/update-access-control).
2. Make your edits using the appropriate template where one exists.
3. Update the relevant folder README and, if the change maps to a control, update compliance/control-mappings/control-crosswalk.csv.
4. Open a pull request describing what changed and why.
5. Request review from the document Owner (see CODEOWNERS).
6. Merge only after approval.

## Document Standards

- Use Markdown for documents and CSV for registers and trackers.
- Include the metadata table (Document ID, Owner, Approver, Status, Version) at the top of each policy, standard, and procedure.
- Use the status values: Draft, Review, Approved, Published, Retired.
- Keep statements clear and testable.

## Review Cadence

Policies and standards are reviewed at least annually. The risk register and evidence tracker are updated continuously.

## Security Note

Never commit secrets, credentials, personal data, or real customer data to this repository. Registers should reference systems and owners, not store sensitive values.

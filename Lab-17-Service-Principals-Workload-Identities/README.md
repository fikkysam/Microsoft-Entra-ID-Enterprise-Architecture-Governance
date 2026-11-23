# Lab Service Principals and Workload Identities

**Status:** Not started  
**Difficulty:** Advanced

## 1. Scenario

Describe the business environment, identity problem, stakeholders, and constraints for this lab.

## 2. Objective

Inspect application objects and service principals, then apply secure workload identity configuration.

## 3. Prerequisites

- Non-production Microsoft Entra tenant with required features and licensing confirmed.
- Test users and groups appropriate to the scenario.
- Required application, endpoint, or second tenant identified before implementation.
- Administrative permissions limited to what the lab requires.
- No production credentials or identities.

Add lab-specific prerequisites and licensing details before starting.

## 4. Architecture and design

Document:
- Components and trust boundaries.
- Authentication and authorization flows.
- Roles, permissions, and ownership.
- Design alternatives and rationale.
- Expected security controls.

Add an architecture diagram under `Architecture/`.

## 5. Implementation

Record the actual portal navigation, configuration, and commands used. Explain the purpose of each important setting. Store sanitized scripts in `Scripts/` and configuration examples in `Configuration/`.

Do not invent successful results: record only actions performed in the test environment.

## 6. Validation and test cases

| Test | Expected result | Actual result | Status |
|---|---|---|---|
| Positive test | Authorized scenario succeeds | Pending | Not run |
| Negative test | Unauthorized scenario is blocked | Pending | Not run |
| Edge case | Document expected behaviour | Pending | Not run |

Add protocol-specific, lifecycle, or role-based tests relevant to this lab.

## 7. Troubleshooting

Document at least two realistic failure scenarios where applicable.

For each issue, record:
- Symptom and impact.
- Relevant logs or error details (redacted).
- Root cause.
- Corrective action.
- Retest result.

See [Troubleshooting.md](Troubleshooting.md).

## 8. Security assessment

Assess least privilege, credential protection, access boundaries, monitoring, recovery, and operational risks. Record mitigations and residual risks in [Security-Assessment.md](Security-Assessment.md).

## 9. Evidence

Add focused, redacted screenshots and logs under `Screenshots/`. Include an evidence index explaining what each item proves.

## 10. Outcome and lessons learned

Summarize what was implemented, what tests passed or failed, known limitations, and production considerations.

## 11. Completion checklist

- [ ] Prerequisites and licensing confirmed
- [ ] Architecture documented
- [ ] Implementation completed
- [ ] Positive and negative tests executed
- [ ] Troubleshooting documented
- [ ] Security assessment completed
- [ ] Evidence reviewed and redacted
- [ ] README reflects actual results

**Do not mark this lab Completed until all applicable criteria are satisfied.**

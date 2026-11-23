# Licensing and Prerequisites

Licensing and feature availability can change and may differ by tenant, cloud, and subscription. Verify the current Microsoft licensing terms and the capabilities displayed in the actual test tenant before beginning each lab.

## General prerequisites

- Access to a non-production Microsoft Entra tenant.
- A test administrator account protected with MFA.
- At least two test users and suitable test groups.
- Permission to create and manage the resources required by the lab.
- Microsoft Graph PowerShell SDK or an API client where specified.
- A secure place to store temporary test credentials outside Git.

## Tenant and licensing considerations

| Capability | Pre-lab verification |
|---|---|
| Enterprise application SSO | Confirm application supports the selected protocol and test users can be assigned |
| App registrations and Graph permissions | Confirm required app-registration permissions and admin-consent authority |
| SCIM provisioning | Confirm the application or test endpoint supports the SCIM version and authentication method required |
| Conditional Access | Confirm applicable Entra licensing and avoid locking out test administrators |
| PIM | Confirm required Entra ID governance/P2 licensing and role eligibility |
| Access reviews | Confirm Identity Governance licensing for the selected review scenario |
| Cross-tenant access and synchronization | Confirm both tenants, required roles, licensing, and supported synchronization prerequisites |

## Safety controls

- Use test tenants and test users, not production identities.
- Maintain emergency access according to a documented and tested plan.
- Do not publish secrets, private keys, tokens, or personal data.
- Remove temporary permissions and credentials after testing.

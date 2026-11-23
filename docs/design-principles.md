# Design Principles

These principles guide the architecture and implementation decisions across this repository.

## Identity and access

- Apply least privilege to users, applications, service principals, and administrators.
- Prefer managed identities or certificate-based credentials over long-lived client secrets when the target scenario supports them.
- Separate authentication from authorization and document both.
- Make identity lifecycle events explicit: joiner, mover, leaver, and external-user lifecycle.

## Application integration

- Select SAML or OIDC based on application capability and protocol requirements.
- Use OAuth 2.0 for delegated or application authorization; do not treat OAuth access tokens as proof of user authentication.
- Distinguish app registrations (application objects) from tenant-local service principals.
- Restrict API permissions to the minimum required and govern admin consent.

## Governance and operations

- Use Conditional Access as layered policy enforcement, with emergency access and recovery considerations documented.
- Use PIM and time-bound activation for privileged roles where available.
- Use access reviews to validate continued access rather than assuming assignments remain appropriate.
- Monitor sign-ins, provisioning activity, audit events, and workload identity usage.

## Cross-tenant collaboration

- Define inbound and outbound trust boundaries.
- Scope synchronization and external collaboration to required users and applications.
- Validate external identity claims and trust settings before granting access.
- Test the impact of changes in a controlled environment.

## Documentation

For each significant decision, record context, alternatives, rationale, security implications, and operational impact.

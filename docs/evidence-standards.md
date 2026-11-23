# Evidence Standards

Capture only evidence that proves a meaningful configuration or test result.

## Recommended evidence

- Architecture or identity-flow diagram.
- Relevant configuration screen with sensitive values hidden.
- Test result showing successful expected behaviour.
- Negative test demonstrating a control blocks or restricts access as designed.
- Relevant audit, sign-in, or provisioning log.
- Troubleshooting evidence showing the cause and verified resolution.

## Screenshot naming

Use descriptive, sequential names, for example:

```text
01-enterprise-app-overview.png
02-saml-basic-configuration.png
03-test-user-assignment.png
04-successful-sso-test.png
05-failed-sso-troubleshooting.png
```

## Redaction checklist

Before committing evidence, verify that it does not expose:
- Passwords, client secrets, private keys, or bearer tokens.
- QR codes, recovery codes, or authentication enrollment secrets.
- Personal information unrelated to the lab.
- Sensitive tenant details that are not necessary to demonstrate the implementation.

Keep screenshots focused. Evidence should support the README rather than duplicate every click.

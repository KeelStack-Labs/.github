# KeelStack Security Policy

At KeelStack, we take security seriously across all repositories in the organization, including public repositories, private repositories, internal repositories, and template repositories.

This policy applies to every repository that is maintained by the KeelStack organization unless a more specific repository-level security policy is provided.

We welcome security researchers and community members who help us improve the security of KeelStack software. This policy is designed to make responsible reporting clear, private, and actionable.

---

## Supported Versions

We actively maintain and provide security updates only for the latest major version of each KeelStack product or repository line.

| Version | Supported |
| :--- | :--- |
| Latest major version | ✅ |
| Older major versions | ❌ |

Security fixes are not backported to unsupported versions unless explicitly stated in a repository-specific policy or release announcement.

---

## Reporting a Vulnerability

If you discover a security vulnerability in any KeelStack repository, please do not open a public issue.

Instead, report it privately through one of the following channels:

- **GitHub Private Vulnerability Reporting** (recommended): Use the **Security** tab of the affected repository and select **Report a vulnerability**.
- **Email**: [security@keelstack.me](mailto:security@keelstack.me)

If the repository does not have private vulnerability reporting enabled, use the email address above.

Please include, if possible:
- A clear description of the issue.
- The affected repository and version.
- Steps to reproduce.
- The security impact.
- Any proof of concept or relevant logs, if safe to share.

---

## Coordinated Disclosure

We follow a Coordinated Vulnerability Disclosure process.

| Step | Timeline |
| :--- | :--- |
| Acknowledgement | Within 24 hours |
| Triage and confirmation | Within 5 business days |
| Status updates | Weekly during investigation |
| Fix and release | Typically within 90 days |

If we cannot resolve the issue within 90 days, we will work with the reporter to agree on a revised disclosure timeline. If necessary, we will also discuss whether public disclosure should proceed.

---

## Safe Harbor

We will not pursue legal action against researchers who report vulnerabilities responsibly and in good faith, in accordance with this policy.

Authorized research includes:
- Testing KeelStack repositories for security issues.
- Reviewing repository code and configuration.
- Validating a vulnerability with the minimum proof needed to demonstrate impact.
- Coordinating privately with maintainers before public disclosure.

Please do not:
- Access, modify, delete, or exfiltrate data beyond what is necessary to demonstrate the issue.
- Perform denial-of-service attacks or degrade service availability.
- Introduce malware, backdoors, or malicious code.
- Use social engineering or phishing.
- Publicly disclose the vulnerability before we have had a reasonable opportunity to investigate and remediate it.

---

## Scope

### In Scope

Security issues in the following areas are in scope when they affect KeelStack-maintained code, templates, or infrastructure:

- Authentication and session management.
- Authorization and access control.
- Tenant isolation and data leakage.
- Injection flaws.
- Insecure configuration.
- Webhook verification and signing.
- Billing and subscription logic.
- Secrets handling and environment configuration.
- Infrastructure scaffolding and deployment logic.
- Template logic that is shipped as part of a KeelStack repository.

### Out of Scope

The following are out of scope:
- Vulnerabilities in third-party dependencies, unless caused by KeelStack integration code.
- Theoretical attacks without a proof of concept.
- Social engineering, phishing, or physical attacks.
- Denial-of-service attacks that do not demonstrate a security impact.
- Automated scanner reports without manual verification and impact.
- Issues in custom implementations built by users on top of KeelStack templates unless the issue is caused by KeelStack-provided code.

---

## What to Expect

We aim to handle reports professionally and transparently.

- We may request additional information or clarification.
- We may ask you not to disclose the issue publicly until a fix is available.
- We may coordinate on a temporary mitigation if a full fix will take time.
- We may publish a security advisory after the fix is released.

If you prefer anonymity, please let us know and we will respect that where possible.

---

## Acknowledgments

If you are the first to report a unique, valid security issue, we may:
- Credit you in release notes or advisories, unless you prefer to remain anonymous.
- Offer a complimentary Premium License or similar courtesy reward at our discretion.

We do not currently operate a formal bug bounty program.

---

## Security Hardening

KeelStack repositories should use security best practices appropriate to the project, including:
- Input validation.
- Secret scanning and push protection.
- Dependency review and updates.
- Secure defaults.
- Environment-based configuration.
- Signed webhooks where applicable.
- Rate limiting where applicable.
- Audit logging where applicable.

For repository-specific guidance, see that repository’s documentation.

# Security Policy

Lofa takes the security of its platform, customer data, and partner brands
seriously. We appreciate responsible disclosure from the security community.

## Supported Versions

Only the `main` branch is actively supported. Security patches are not
backported to historical tags.

| Component | Version    | Supported          |
| --------- | ---------- | ------------------ |
| Web       | latest     | :white_check_mark: |
| API       | latest     | :white_check_mark: |
| Mobile    | latest     | :white_check_mark: |
| Older     | any        | :x:                |

## Reporting a Vulnerability

**Please do NOT open a public GitHub issue for security vulnerabilities.**

Email: **security@lofa.tn**

Include:

1. A clear description of the vulnerability and its impact.
2. Steps to reproduce (proof-of-concept code, screenshots, HTTP requests).
3. The affected URL, endpoint, or commit hash.
4. Your name / handle if you would like public credit (optional).

We will:

- Acknowledge receipt within **2 business days**.
- Provide an initial assessment within **7 business days**.
- Keep you informed of progress until resolution.
- Credit you in our public security advisories (unless you ask not to).

## Scope

In scope:

- `lofa.tn` and `*.lofa.tn`
- `api.lofa.tn`
- The Expo mobile app distributed via official stores
- Source code in this repository

Out of scope:

- Denial-of-service / volumetric attacks
- Findings exclusively from automated scanners without demonstrable impact
- Social engineering of Lofa staff or partner brands
- Physical security
- Third-party services we depend on (please report upstream)

## Safe Harbor

Lofa will not pursue legal action against researchers who:

- Make a good-faith effort to comply with this policy.
- Avoid privacy violations, data destruction, or service disruption.
- Give us reasonable time to remediate before public disclosure.

Thank you for helping keep Lofa and its community safe.

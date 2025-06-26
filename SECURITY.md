# Security Policy

## Supported Versions

| Version         | Supported          |
| --------------- | ----------------- |
| 2025.x.x (main) | :white_check_mark:|
| Earlier         | :x:               |

## Reporting a Vulnerability

If you discover a security vulnerability, **do not create a public issue**. Instead:

1. **Email:** security@mstarrobotics.com  
2. **PGP:** [Download our public key](https://mstarrobotics.com/security/pgp-key.asc) to encrypt sensitive information.
3. Provide:
    - Versions affected
    - Step-by-step reproduction instructions
    - Potential impact
    - Your contact information

We will respond within **72 hours**. If you do not receive a response, please resend your email or contact a project maintainer via [GitHub Discussions](https://github.com/MStarRobotics/RSS2025/discussions).

## Security Best Practices

- **Update Regularly:** Keep all dependencies, ROS 2 packages, and OS components up to date.
- **Access Control:** Use strong, unique passwords and enable 2FA for all accounts and APIs.
- **Network Security:** Restrict access using firewalls, VPNs, and secure communication protocols (TLS 1.3+).
- **Data Protection:** Encrypt sensitive data at rest and in transit.
- **Secrets Management:** Never commit secrets, credentials, or sensitive keys to the repository. Use secrets managers and environment variables.
- **Least Privilege:** Grant only the minimum permissions necessary to users, services, and robots.

## Automated Code Scanning and CI/CD

- All code changes are automatically scanned for vulnerabilities using [GitHub Advanced Security](https://docs.github.com/en/code-security).
- Use [Dependabot](https://github.com/dependabot) for automatic dependency updates.
- All pull requests must pass security and static analysis checks before merging.

## Supply Chain Security

- Only trusted, verified sources for dependencies are permitted.
- All third-party code must be reviewed and logged in [THIRD_PARTY.md](./THIRD_PARTY.md).
- Signed commits and [SLSA Level 3](https://slsa.dev/spec/v0.1/requirements) compliance are strongly recommended.

## Vulnerability Management

- Critical vulnerabilities will trigger an immediate embargo, patch, and responsible disclosure process.
- Patches are prioritized based on CVSS severity and exploitability.
- Users will be notified via [GitHub Security Advisories](https://github.com/MStarRobotics/RSS2025/security/advisories).

## Responsible Disclosure Timeline

| Action                        | Timeline            |
|-------------------------------|---------------------|
| Acknowledgement of report     | Within 72 hours     |
| Initial assessment            | Within 7 days       |
| Patch release (if required)   | As soon as possible |
| Public disclosure             | After patch release |

## Compliance and Certifications

- Follows [OWASP ASVS](https://owasp.org/www-project-application-security-verification-standard/) and [NIST CSF](https://www.nist.gov/cyberframework).
- GDPR, CCPA, and other privacy regulations are supported where applicable.
- All contributors are required to follow project [Code of Conduct](./CODE_OF_CONDUCT.md).

## Security Resources

- [ROS 2 Security Best Practices](https://docs.ros.org/en/rolling/Guide/Security.html)
- [GitHub Security Documentation](https://docs.github.com/en/code-security)

---

For urgent matters, please use the contact methods above. Thank you for helping keep RSS2025 and its users safe!

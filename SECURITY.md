# Security

## Reporting a vulnerability

If you believe you have found a security issue in this repository (e.g. malicious or unsafe query logic, dependency vulnerability), please report it responsibly:

- **Do not** open a public issue for security-sensitive findings.
- Contact the maintainer privately (e.g. via GitHub Security Advisories: **Security** tab → **Advisory**).
- Provide a clear description and steps to reproduce; we will respond and coordinate disclosure.

## Scope

- This repo contains **generic KQL snippets and reference material only**. No secrets, credentials, or environment-specific data belong here.
- Queries are intended for use in your own tenant; validate and tune before use in production.

## Best practices (this repo)

- No API keys, connection strings, or tenant IDs in queries or README.
- No real IOCs, internal hostnames, or customer data.
- Dependencies: this repo has no runtime dependencies; if you fork and add tooling, pin versions and run `dependabot` or similar.

## License

This project is in the **public domain** (CC0 1.0). See [LICENSE](LICENSE).

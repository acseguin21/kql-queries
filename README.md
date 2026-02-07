# KQL Queries

Personal collection of KQL (Kusto Query Language) snippets for detection and hunting. Use with Microsoft Defender, Sentinel, or Log Analytics.

**Status:** WIP — adding queries as I standardize and sanitize them.

## Structure

- `hunting/` — exploratory and hunt queries
- `detection/` — detection rule–style queries
- `utilities/` — reusable snippets and helpers

## Example focus

- **hunting/case-triage-priority-events.kql** — High-priority alerts by device/severity for triage.
- **detection/sign-in-risk-entra.kql** — Entra ID (Azure AD) sign-in risk for identity investigations.
- **detection/suspicious-powershell.kql** — PowerShell encoded/hidden patterns.
- **utilities/common-time-window.kql** — Reusable time-range snippet.

## Usage

Paste into Advanced hunting (Microsoft 365 Defender / Defender for Endpoint) or Azure Monitor / Sentinel as needed. Adjust table names and time ranges for your environment.

## License

MIT

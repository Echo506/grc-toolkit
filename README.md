# ISO 27001 Suite — Security & Compliance Portfolio

A full-stack GRC toolkit built in HTML/CSS/JS (no dependencies, no server). Designed to demonstrate hands-on experience across the competencies required for Senior Security Associate and GRC roles.

---

## Modules

| # | Module | Frameworks / Standards |
|---|--------|----------------------|
| 01 | **Gap Analysis** | ISO 27001:2022 Annex A (93 controls) |
| 02 | **Risk Management** | ISO 27005 · 5×5 probability/impact matrix |
| 03 | **Internal Audit** | ISO 27001 Clauses 4–10 |
| 04 | **Evidence Management** | 18 mandatory SGSI documents |
| 05 | **Vendor Risk Assessment (TPRM)** | SIG Lite · SOC 2 · SSAE 18 |
| 06 | **Multi-Framework Compliance** | ISO 27001 · HITRUST · PCI DSS · HIPAA · GDPR · SOC 2 |
| 07 | **Cloud Security Architecture Review** | CCSP domains · AWS · Azure · GCP |

---

## Usage

```bash
git clone https://github.com/YOUR_USERNAME/iso27001-suite.git
cd iso27001-suite
open index.html   # or just double-click it
```

No installation. No server. All data persists in `localStorage`. Each module has a CSV export.

Enable GitHub Pages (`Settings → Pages → main branch`) for browser access from any device.

---

## Module highlights

### Module 05 — Vendor Risk Assessment (TPRM)
- Vendor registry with criticality tier (Critical / High / Medium / Low)
- SIG Lite questionnaire across 10 security domains (AC, RM, DP, IR, BCP, VM, HR, PM, CM, TP)
- Automatic risk scoring (0–100%) and risk tier classification
- Per-vendor report with domain breakdown and CSV export

### Module 06 — Multi-Framework Compliance Tracker
- 22 controls mapped simultaneously across 6 frameworks
- Control crosswalk with reference IDs per framework (e.g. A.8.24 / PCI 3.4 / HIPAA 164.312)
- Compliance score per framework with progress tracking
- Filter by framework or status; export full crosswalk to CSV

### Module 07 — Cloud Security Architecture Review
- 34 checks across 6 CCSP domains (Data Security, Infrastructure, IAM, AppSec, SecOps, Compliance)
- Provider-specific guidance for AWS, Azure, GCP and multi-cloud
- Radar chart showing domain coverage; critical findings panel
- One-click report generation; CSV export of all findings

---

## Skills demonstrated

- ISO 27001 implementation and auditing
- Third-party risk management (SIG, SOC 2, SSAE)
- Multi-framework compliance (HITRUST, PCI DSS, HIPAA, GDPR)
- Cloud security architecture review (CCSP domains)
- Risk assessment methodology (ISO 27005)
- GRC tooling and control testing

---

## Standards reference

- ISO/IEC 27001:2022 · ISO/IEC 27002:2022 · ISO/IEC 27005
- HITRUST CSF v11 · PCI DSS v4.0 · HIPAA Security Rule
- GDPR 2016/679 · SOC 2 (AICPA TSC) · CCSP (ISC²)
- SIG Lite (Shared Assessments) · SSAE 18

---

## License

MIT — free for personal and commercial use.

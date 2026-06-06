# ISO 27001 Suite — Security & Compliance Portfolio

> A full-stack GRC toolkit built in HTML/CSS/JS — no dependencies, no server, no installation required.

![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)
![Standard: ISO 27001:2022](https://img.shields.io/badge/Standard-ISO%2027001%3A2022-blue.svg)
![Stack: HTML CSS JS](https://img.shields.io/badge/Stack-HTML%20%7C%20CSS%20%7C%20JS-orange.svg)
![Status: Active](https://img.shields.io/badge/Status-Active-brightgreen.svg)

---

## 🎯 What is this project?

ISO 27001 Suite is a **hands-on GRC portfolio toolkit** designed to demonstrate practical experience across the competencies required for **Senior Security Associate**, **GRC Analyst**, and **Information Security** roles.

Built entirely in HTML/CSS/JS with no external dependencies or backend — every module runs directly in the browser.

**Key highlights:**
- ✅ 7 integrated security and compliance modules
- ✅ Covers ISO 27001, ISO 27005, HITRUST, PCI DSS, HIPAA, GDPR, SOC 2, CCSP
- ✅ All data persists in `localStorage` — no server needed
- ✅ Every module includes CSV export for reporting
- ✅ Deployable via GitHub Pages in one click

---

## 🚀 Quick start

```bash
# Clone the repo
git clone https://github.com/Echo506/grc-toolkit.git

cd grc-toolkit

# Open in your browser (no server needed)
open index.html   # macOS
start index.html  # Windows
```

> 💡 Tip: Enable **GitHub Pages** (`Settings → Pages → main branch`) to access the full suite from any device via browser.

---

## 🧩 Modules

| # | Module | Frameworks / Standards |
|---|--------|------------------------|
| 01 | **Gap Analysis** | ISO 27001:2022 Annex A (93 controls) |
| 02 | **Risk Management** | ISO 27005 · 5×5 probability/impact matrix |
| 03 | **Internal Audit** | ISO 27001 Clauses 4–10 |
| 04 | **Evidence Management** | 18 mandatory SGSI documents |
| 05 | **Vendor Risk Assessment (TPRM)** | SIG Lite · SOC 2 · SSAE 18 |
| 06 | **Multi-Framework Compliance** | ISO 27001 · HITRUST · PCI DSS · HIPAA · GDPR · SOC 2 |
| 07 | **Cloud Security Architecture Review** | CCSP domains · AWS · Azure · GCP |

---

## 🔍 Module highlights

### Module 01 — Gap Analysis
- Full ISO 27001:2022 Annex A with all 93 controls
- Implementation level scoring (1–5 maturity scale)
- Evidence and owner fields per control
- Gap summary and remediation plan export

### Module 02 — Risk Management
- Risk register aligned to ISO 27005
- 5×5 probability/impact matrix with heat map visualization
- Risk treatment options (Accept, Mitigate, Transfer, Avoid)
- CSV export of full risk register

### Module 03 — Internal Audit
- Audit checklist covering ISO 27001 Clauses 4–10
- Finding classification (Conformity, Minor NC, Major NC, Observation)
- Corrective action tracking per finding
- Audit report generation

### Module 04 — Evidence Management
- Tracker for all 18 mandatory ISMS documents
- Document status, owner, review date, and version control
- Compliance percentage dashboard
- Export to CSV for audit readiness

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

## 🛠 Tech stack

| Area | What is used |
|------|--------------|
| Frontend | HTML, CSS, JavaScript |
| Storage | Browser `localStorage` + CSV export |
| Charts | Built-in canvas / radar charts (no libraries) |
| Deployment | GitHub Pages (static, no server) |
| Dependencies | None — 100% self-contained |

---

## 📊 Skills demonstrated

- ISO 27001 implementation and auditing
- Third-party risk management (SIG Lite, SOC 2, SSAE 18)
- Multi-framework compliance mapping (HITRUST, PCI DSS, HIPAA, GDPR)
- Cloud security architecture review (CCSP domains)
- Risk assessment methodology (ISO 27005)
- GRC tooling design and control testing
- Evidence management and audit readiness

---

## 📚 Standards reference

- **ISO/IEC 27001:2022** · ISO/IEC 27002:2022 · ISO/IEC 27005
- **HITRUST CSF v11** · PCI DSS v4.0 · HIPAA Security Rule
- **GDPR 2016/679** · SOC 2 (AICPA TSC) · CCSP (ISC²)
- **SIG Lite** (Shared Assessments) · SSAE 18

---

## 📅 Status & roadmap

- [x] Module 01 — Gap Analysis
- [x] Module 02 — Risk Management
- [x] Module 03 — Internal Audit
- [x] Module 04 — Evidence Management
- [x] Module 05 — Vendor Risk Assessment (TPRM)
- [x] Module 06 — Multi-Framework Compliance Tracker
- [x] Module 07 — Cloud Security Architecture Review
- [ ] Module 08 — Incident Response Tracker (planned)
- [ ] Module 09 — Business Continuity / BIA (planned)
- [ ] Dashboard view aggregating all module scores (planned)

---

## 🤝 Contributing

Contributions are welcome! You can help by:

- Adding or improving controls, questionnaires, or framework mappings.
- Improving UI/UX across modules.
- Adding new modules (e.g., Incident Response, BIA, BCMS).
- Translating documentation to Spanish or other languages.

How to contribute:

1. Fork this repository.
2. Create a feature branch: `git checkout -b feature/my-improvement`
3. Commit your changes and push the branch.
4. Open a Pull Request describing what you changed and why.

---

## 🌍 Language

- Primary language: **English**
- Contributions and issues in **Spanish** are welcome.

---

## ⚠️ Disclaimer

This project is for **educational, portfolio, and internal use**.
It does not replace a formal ISO/IEC 27001 certification audit or official GRC tooling.

Always consult the official standards and, where required, a qualified auditor or consultant.

---

## 📄 License

[MIT](LICENSE) — free for personal and commercial use.

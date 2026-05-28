<div align="center">

# ForgeGRC

**GRC Compliance Platform · Automated Evidence & Audit Workflows**

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Status](https://img.shields.io/badge/Status-Active%20Development-brightgreen.svg)](#)
[![FIPS 140-3](https://img.shields.io/badge/Standard-FIPS%20140--3-blue.svg)](https://csrc.nist.gov/publications/detail/fips/140/3/final)
[![Frameworks](https://img.shields.io/badge/Frameworks-SOC2%20%7C%20CMMC%20%7C%20ISO%2027001%20%7C%20PCI%20DSS-orange.svg)](#frameworks)

[📦 Download Latest Release](../../releases/latest) · [🌐 Project Page](https://iawiz87.github.io/ForgeGRC) · [📋 Issues](../../issues)

</div>

---

## Overview

ForgeGRC is a compliance automation platform built for security engineers and GRC practitioners operating in **federal and regulated environments**. It bridges hands-on cryptographic assurance with Governance, Risk, and Compliance (GRC) objectives — turning what is normally a manual, documentation-heavy process into a structured, repeatable workflow.

Designed from the ground up for:
- **Multi-framework GRC** — SOC 2, CMMC v2, ISO 27001, PCI DSS 4.0.1, NIST CSF 2.0
- **Automated scanning** — OpenSCAP, Anchore, CISA KEV integration
- **Evidence collection** — structured artifact gathering for audits and ATOs

---

## Key Features

| Feature | Description |
|---|---|
| **Compliance Scanning** | OpenSCAP, Anchore, and KEV-integrated automated scanning |
| **Evidence Collection** | Structured artifact collection mapped to control families |
| **Multi-Framework** | SOC 2, CMMC v2, ISO 27001, PCI DSS 4.0.1, NIST CSF 2.0, FedRAMP |
| **Policy Generator** | Compliance-aligned policy and documentation templates |
| **Audit Dashboard** | Control status, gap analysis, and remediation tracking |
| **Offline-Capable** | Designed to run in air-gapped and high-security environments |

---

## Frameworks

ForgeGRC provides coverage across the following standards and frameworks:

- [NIST SP 800-53 Rev 5](https://csrc.nist.gov/publications/detail/sp/800-53/rev-5/final) — Security and Privacy Controls
- [NIST CSF 2.0](https://www.nist.gov/cyberframework) — Cybersecurity Framework
- [CMMC v2](https://www.acq.osd.mil/cmmc/) — Cybersecurity Maturity Model Certification
- [SOC 2 Type I/II](https://www.aicpa-cima.com/topic/audit-assurance/audit-and-assurance-greater-than-soc-2) — Service Organization Controls
- [ISO/IEC 27001:2022](https://www.iso.org/isoiec-27001-information-security.html) — Information Security Management
- [PCI DSS 4.0.1](https://www.pcisecuritystandards.org/) — Payment Card Industry Data Security Standard
- [FedRAMP](https://www.fedramp.gov/) — Federal Risk and Authorization Management Program

---

## Download

> 📦 **[Download Latest Release →](../../releases/latest)**

Each release includes:
- Platform source code (ZIP)
- Compliance module documentation
- Policy and procedure templates
- Framework mapping reference sheets
- Installation and configuration guide

See [CHANGELOG](CHANGELOG.md) for version history and release notes.

---

## Quick Start

```bash
# Clone the repository
git clone https://github.com/IAwiz87/ForgeGRC.git
cd ForgeGRC

# See docs/ for full installation and configuration guide
cat docs/INSTALL.md
```

Full setup documentation is included in each [release package](../../releases/latest).

---

## Repository Structure

```
ForgeGRC/
├── docs/                    # Documentation and framework guides
│   ├── INSTALL.md           # Installation and configuration
│   ├── frameworks/          # Per-framework implementation guides
│   └── templates/           # Policy and procedure templates
├── index.html               # GitHub Pages project page
├── CHANGELOG.md             # Version history
├── LICENSE
└── README.md
```

---

## About the Author

Built by **Andrew P. Largent** — Security Engineer specializing in FIPS 140-3 cryptographic assurance, GRC framework implementation, and federal compliance engineering.

- [GitHub: @IAwiz87](https://github.com/IAwiz87)
- [CyberForge — Open-Source Compliance Tools](https://github.com/IAwiz87/CyberForge)

---

## Disclaimer

ForgeGRC is an independent project. It is not affiliated with, endorsed by, or produced by NIST, CISA, or the U.S. Government. Always refer to official sources for authoritative compliance and security guidance.

---

<div align="center">

**Bridging cryptographic assurance with GRC — for the federal compliance community**

[📦 Download](../../releases/latest) · [🌐 Project Page](https://iawiz87.github.io/ForgeGRC) · [🛡️ CyberForge](https://github.com/IAwiz87/CyberForge)

</div>

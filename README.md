# Awesome-Employee-Self-Service-Internal-Helpdesk

## Top Employee Self-Service & Internal Helpdesk Ecosystem

**Curated List of SaaS Platforms & Open-Source GitHub Projects**  
*Focused on HR Service Delivery, Employee Ticketing & Knowledge-Powered Self-Service*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Employee Self-Service & Internal Helpdesk**. These tools give employees a single place to request HR support, find answers to common questions, and track the status of their requests—covering everything from enterprise service management suites to open-source HRMS platforms with built-in helpdesk modules.

**Examples** include ServiceNow Employee Center, Freshworks Employee Center, Workday, BambooHR, Rippling, Personio, and open-source alternatives like Horilla HR and FreeITSM (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted HR helpdesk, open-source employee portals, and community-driven service management—ideal for organizations seeking data sovereignty and avoiding per-employee pricing that compounds across headcount. The open-source landscape is genuinely functional: **Horilla HR** bundles a helpdesk module directly into a full HRMS , and **FreeITSM** provides a complete ITSM tool with self-service portal and asset management .

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|-------------|-------------------|--------------------------|
| **[ServiceNow Employee Center](https://www.servicenow.com/)** | Enterprise service management portal unifying IT, HR, legal, finance, and workplace services. **Enterprise Service Management Foundation** (May 2026) delivers multi-department services within weeks for mid-size organizations . North America held 42.31% of the employee helpdesk market in 2025; ServiceNow targets $30B+ subscription revenue by 2030 with AI exceeding 30% of ACV . | Quote-only (enterprise contract) | No free tier; demo via sales |
| **[Freshworks Employee Center (Freshservice)](https://www.freshworks.com/)** | AI-first service delivery with employee portal, knowledge base, and ticketing. **Freshservice from $19/agent/month**. Freshworks expanded AI-first HR service delivery in 2026 for faster, lower-complexity adoption . | From **$19/agent/month** | Free trial available; no permanent free tier |
| **[Workday Employee Self Service](https://www.workday.com/)** | Enterprise HCM with comprehensive ESS for pay, benefits, time, and personal data. FSE-based pricing model weights worker types—count overages of 8–18% above clean census are common. | Quote-only (FSE-based enterprise contract) | No free tier; demo via sales |
| **[BambooHR](https://www.bamboohr.com/)** | SMB-focused HRIS with self-service, time-off tracking, and document storage. Core: **$10/employee/month**; Pro: $17; Elite: $25. Month-to-month available with automatic volume discounts. | Core: **$10/employee/month**; Pro: $17; Elite: $25 | No free tier; demo via sales |
| **[Rippling](https://www.rippling.com/)** | Unified HR, payroll, benefits, devices, and apps. **Starting at $8/user/month**; modular pricing means you pay for what you enable. | **$8/user/month** (base) | No free tier; demo via sales |
| **[Personio](https://www.personio.com/)** | European HRIS with ESS for SMBs. Core tier several dollars PEPM; 15–30% discounts achievable for 100–200 employees with multi-year terms. | Quote-only (Core/Professional/Enterprise) | No free tier; demo via sales |
| **[UKG Pro](https://www.ukg.com/)** | Enterprise HCM with ESS, payroll, and workforce management. Positioned for mid-market and enterprise organizations. | Quote-only (enterprise contract) | No free tier; demo via sales |
| **[Paylocity](https://www.paylocity.com/)** | Mid-market HCM with ESS, payroll, and time tracking. Typical PEPM mid-teens to low twenties for 200–500 employees. Implementation $5K–$40K. | Quote-only (mid-teens to low-$20s PEPM) | No free tier; demo via sales |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Horilla HR](https://github.com/horilla/horilla-hr)** | [![Stars](https://img.shields.io/github/stars/horilla/horilla-hr?style=social&color=white)](https://github.com/horilla/horilla-hr/stargazers) | **The most complete open-source HRMS with a built-in employee helpdesk.** LGPL-2.1, Django/Python. **Helpdesk module is one of 12 core HR modules** alongside recruitment, attendance, leave, payroll, performance, and asset management . **Employee self-service** covers profile, leave, attendance, payslips, document requests, and **centralized HR support ticketing**. REST API for mobile app, LDAP integration, role-based dashboards, and scheduled reports. Docker deployment (PostgreSQL required; first boot ~3–4 minutes for migrations). **Security**: optional 2FA, brute-force protection, audit trails across modules, and XSS input validation . **Best for organizations wanting an integrated HR + helpdesk platform without per-employee fees.** |
| **[FreeITSM](https://github.com/edmozley/freeitsm)** | [![Stars](https://img.shields.io/github/stars/edmozley/freeitsm?style=social&color=white)](https://github.com/edmozley/freeitsm/stargazers) | **Complete open-source ITSM tool with self-service portal and asset management.** Ranked #1 in a 2026 AI IT service desk comparison with a score of **7.9** . Features: **self-service portal**, task management (Kanban/list/calendar/timeline), **asset register with custody tracking and QR labels**, checklists/SOPs, knowledge base with AI chat, change management with CAB voting, problem management, cross-module workflow automation (138+ triggers), and **CMDB with impact analysis** . **Best for IT teams wanting a full ITSM suite with employee self-service included.** |
| **[iTop](https://github.com/Combodo/iTop)** | [![Stars](https://img.shields.io/github/stars/Combodo/iTop?style=social&color=white)](https://github.com/Combodo/iTop/stargazers) | **Open-source ITIL-aligned ITSM and CMDB platform with employee portal.** Web-based, self-hosted. Provides structured service management workflows including incident, request, change, and problem management alongside a configuration management database (CMDB). **Best for organizations wanting ITIL-compliant service management with self-service capabilities** . |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[KIX](https://github.com/raumbasis/kix)** | — | **Open-source service management software for ITSM, enterprise service management, and technical customer support.** Ranked #1 in a 2026 IT help desk comparison (score 7.8) alongside Znuny. Supports Linux, Windows, Android, iOS, and web deployment. Paid from €33/month with a 30-day trial . **Best for organizations wanting a proven open-source service desk with broad platform support.** |
| **[Znuny](https://github.com/znuny/Znuny)** | — | **Open-source ticket management software for Linux and web, self-hosted or Znuny-hosted.** Ranked #2 in the same 2026 comparison (score 7.3). LTS fork of OTRS Community Edition with audit-proof ticketing and SAML authentication. Paid from $799/month with a free plan available . **Best for IT teams needing audit-proof ticket trails and OTRS-style workflows.** |
| **[Digital Workplace Employee Hub](https://github.com/WRVish/digital-workplace-employee-hub)** | — | **Free open-source employee portal for Microsoft 365.** SPFx and Power Apps Code Apps versions with SharePoint backend—no extra infrastructure. Features: **user management, leave administration, asset management, expense & travel management, and ticketing**. Role-based rendering for HR Admin, IT Admin, Manager, and Employee. React/TypeScript with glassmorphism design and dark mode support . **Best for Microsoft 365 organizations wanting a lightweight employee portal without additional infrastructure.** |

**Frameworks for building custom systems**: Choose **Horilla HR** for an integrated HRMS with built-in helpdesk, payroll, and ESS , **FreeITSM** for a full ITSM suite with self-service portal and CMDB , or **Digital Workplace Employee Hub** for a Microsoft 365-native employee portal with ticketing —all without per-employee pricing that scales with headcount.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Employee self-service and helpdesk platforms handle sensitive employee PII, support tickets, and potentially payroll data; enforce encryption at rest and in transit, role-based access, and compliance with applicable employment and data protection regulations.
- **Pricing and deployment models vary significantly.** ServiceNow and Workday are enterprise quote-only platforms with FSE-based pricing that can overage on worker-type weighting . Freshworks publishes **$19/agent/month** for Freshservice . Open-source options eliminate per-employee fees but require infrastructure: **Horilla HR** needs PostgreSQL and Docker (first boot ~3–4 minutes) , **FreeITSM** provides a complete ITSM suite with 138+ workflow triggers , and **Digital Workplace Employee Hub** requires only existing Microsoft 365/SharePoint infrastructure . **Validate integration requirements** (LDAP, SSO, payroll systems) and **helpdesk scope** (IT-only vs. multi-department HR/Finance/Legal) against your actual service delivery model before committing.

---

**Made for HR service delivery teams, IT support managers, and organizations building employee self-service infrastructure.**  
Let's make employee self-service and internal helpdesk more open, integrated, and employee-friendly.

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
- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The global employee self-service (ESS) and internal helpdesk software market is estimated at approximately **$6.4B to $9.8B** (scaling upward to **$14B–$26B** when factoring in adjacent enterprise IT service desk suites), expanding at a CAGR of 8.5%–11%. The sector is **moderately to highly fragmented** rather than winner-take-all: while enterprise giants (like ServiceNow and Workday) capture large enterprise core deployments, organizations frequently operate multi-vendor stacks where mid-market suites, agile AI-native ticketing disrupters (like Freshworks and Rippling), and specialized HR portals coexist.

## SaaS/Hosted Platforms

| Product | Scale (Valuation / Revenue) | Description | Pricing (Starting Tier) | Free Tier / Trial Limits |
|---------|-----------------------------|-------------|-------------------------|--------------------------|
| **[ServiceNow Employee Center](https://www.servicenow.com/)** | **~$104B–$159B Market Cap** (~$13.3B–$15.4B TTM revenue) | Enterprise service management portal unifying IT, HR, legal, finance, and workplace services. North America held 42.31% of the employee helpdesk market in 2025; targets $30B+ subscription revenue by 2030 with AI exceeding 30% of ACV. | From **$70/fulfiller/month** (Foundation tier; ~$10k–$20k/yr min contract) | No free tier; demo & guided test drives via sales only (no self-serve free trial) |
| **[Workday Employee Self Service](https://www.workday.com/)** | **~$46B–$51B Market Cap** (~$10.15B TTM revenue) | Enterprise HCM with comprehensive ESS for pay, benefits, time, and personal data. FSE-based pricing model weights worker types—count overages of 8–18% above clean census are common. | From **$35–$100/employee/year** (~$3–$8.33/emp/mo; typical $100k/yr min contract) | No free tier; interactive online video tours & custom demo via sales only (no self-serve free trial) |
| **[UKG Pro](https://www.ukg.com/)** | **~$22B Valuation** (~$4.5B–$4.7B annual revenue) | Enterprise HCM with ESS, payroll, and workforce management. Positioned for mid-market and enterprise organizations. | From **$26/employee/month** (core UKG Pro tier; PEPM model) | No free tier; interactive test environments & guided sales demo only (no self-serve free trial) |
| **[Rippling](https://www.rippling.com/)** | **~$16.8B Valuation** (~$1.0B ARR) | Unified HR, payroll, benefits, devices, and apps. Modular pricing means you pay for what you enable. | From **$8/user/month** (base platform fee plus selected app add-ons) | No free tier; customized sales demo required (occasional 14-day trials limited to select IT/device modules) |
| **[Paylocity](https://www.paylocity.com/)** | **~$9.3B–$10.0B Market Cap** (~$1.77B annual revenue) | Mid-market HCM with ESS, payroll, and time tracking. Typical comprehensive mid-market implementations average $22–$32 PEPM. | From **$2–$5/employee/month** (base core setup; typical bundles start ~$200/mo base) | No free tier; interactive self-paced web tours & guided sales demo only (no self-serve free trial) |
| **[Personio](https://www.personio.com/)** | **~$8.5B Valuation** (~$350M–$435M annual revenue) | European HRIS with ESS for SMBs. Core tier several dollars PEPM; 15–30% discounts achievable for 100–200 employees with multi-year terms. | From **€7.60 (~$8.00)/employee/month** (Core plan, 12-month annual commitment) | **14-day free trial** with sample data and demo employees (caps: max 3 e-signatures, 50 survey participants, outbound emails disabled; no credit card required) |
| **[Freshworks Employee Center (Freshservice)](https://www.freshworks.com/)** | **~$3.15B–$3.5B Market Cap** (~$904M TTM revenue) | AI-first service delivery with employee portal, knowledge base, and ticketing. Freshworks expanded AI-first HR service delivery in 2026 for faster, lower-complexity adoption. | From **$19/agent/month** (Starter tier, billed annually) | **14-day free trial** (full unrestricted access to features, no credit card required; no permanent free tier) |
| **[BambooHR](https://www.bamboohr.com/)** | **Est. ~$274M–$358M Annual Revenue** (PE-backed private) | SMB-focused HRIS with self-service, time-off tracking, and document storage. Month-to-month available with automatic volume discounts. | From **$10/employee/month** (Core package; Pro: $17, Elite: $25) | **7-day free trial** (full platform access with sample employee data, no credit card required; no permanent free tier) |

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

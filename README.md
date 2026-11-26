# Ali Badran

Python and Odoo developer at Odoo Middle East in Dubai. I trace customer issues in production Odoo databases to their root cause and fix them in Odoo's core source, with a regression test for each fix.

My Odoo contributions are made under my work account, [@albd-odoo](https://github.com/albd-odoo). This account holds my personal and university projects.

## Experience

**Odoo Middle East, Dubai**

- **Technical Support** (July 2026 to present). I restore copies of customer databases, reproduce the reported behavior, and find whether the cause is custom code, configuration and data, or a standard bug. Standard bugs get fixed upstream in Odoo Community and Enterprise. I also benchmark slow flows on databases with up to 24M journal items and submit PostgreSQL and core performance patches.
- **Technical Consultant** (April 2025 to May 2026). I built custom modules for Sales, Accounting, Purchase, Invoicing, CRM and HR, migrated modules from Odoo 15 up to 19, built QWeb reports, and integrated a payment provider for a school management system. Projects ranged from 1 to 20 users up to implementations with hundreds of users.

**Earlier.** Backend developer intern at Suplyd, Cairo, building NestJS and GraphQL APIs on MongoDB and PostgreSQL with Prisma. Network security intern at iEight Technologies, Cairo, configuring FortiGate firewalls (Fortinet NSE 4).

## Selected Odoo contributions

Merged into [odoo/odoo](https://github.com/odoo/odoo):

- [stock_account, sale_stock: do not flip the sign of COGS adjustments](https://github.com/odoo/odoo/pull/299128)
- [mrp: over-production inflates finished qty](https://github.com/odoo/odoo/pull/289816)
- [website: filter fuzzy candidates before ranking](https://github.com/odoo/odoo/pull/286155)
- [account: send the invoice PDF first in the invoice email](https://github.com/odoo/odoo/pull/305311)
- [hr_attendance: no absence on unscheduled days](https://github.com/odoo/odoo/pull/290509)
- [sale_purchase_stock: vendor-lang dropship PO desc](https://github.com/odoo/odoo/pull/292734)

The full list is on [@albd-odoo](https://github.com/albd-odoo).

## Other work

- **AI-assisted support workflow.** I built a Claude Code setup with skills, hooks and subagents for ticket triage, local reproduction and fix validation, and my team adopted it. Part of it is a Python tool that pseudonymizes customer data in restored databases and audits the result before any AI agent works on the copy.
- **CI/CD.** I test core fixes on runbot, Odoo's CI, before they ship. As a consultant I tested client modules on psxrunbot, Odoo Dubai's internal CI, then deployed them. I've also run SaaS to Odoo.sh migrations and production database restorations.
- **[Hookline](https://github.com/aBadran0/hookline-releases).** A 2D team shooter I'm building in Godot 4, with 5v5 grapple-hook combat and mid-match body swapping. It runs a deterministic simulation with rollback netcode over ENet/UDP. Windows and Linux playtest builds are on the releases page. The source is private during development.

## Skills

- **Languages:** Python, SQL (PostgreSQL), JavaScript, XML, HTML, CSS, Java, C++, C#
- **Frameworks:** Odoo (ORM, OWL, QWeb), Flask, Node.js, NestJS, GraphQL, Prisma, REST APIs
- **Databases:** PostgreSQL, MongoDB, Oracle SQL, Google Firebase, Azure Cosmos DB
- **Tools:** Git, GitHub, Linux, Odoo.sh, runbot, Claude Code, Azure

## Education and certifications

- BSc in Computer Science (ABET accredited), American University of Sharjah, 2020 to 2024. University Merit Scholarship.
- Microsoft Certified: Azure Fundamentals (AZ-900)
- Coursework in Cisco CCNA and CompTIA Security+ (SY0-601)

## Contact

[LinkedIn](https://www.linkedin.com/in/ali-badran-2584b4223/) · ali.badran53@yahoo.com

English and Arabic, both native proficiency.

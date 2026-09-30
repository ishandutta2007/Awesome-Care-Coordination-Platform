# Awesome-Care-Coordination-Platform

## Top Care Coordination Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Cross-Organizational Referrals, Closed-Loop Communication, Community Health Work & Population Health Management*
**Last updated: September 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Care Coordination**. These tools help healthcare organizations, payers, and community-based organizations coordinate patient care across settings, enabling closed-loop referrals, shared care plans, and cross-organizational data exchange.

**Examples** include Innovaccer, Unite Us, Findhelp, Arcadia, Aidin, WellSky, CarePort Health, Lightbeam Health, Bamboo Health (PatientPing), ZeOmega, and HealthEC (the category leaders).

**Open-source emphasis**: The open-source ecosystem for care coordination is **mature at the population health management and community care coordination layers**. **SPICE** (Medtronic LABS) is a Digital Public Good deployed across 6 countries in sub-Saharan Africa, screening 500,000 patients . **Community Health Toolkit (CHT)** supports approximately 40,000 community health workers across 15 countries, with over 85 million care activities completed . **AHRQ eCare Plan** provides SMART-on-FHIR shared care plan applications with both patient-facing and clinician-facing apps . **ORCA** delivers a reference implementation for Dutch care coordination, implementing FHIR Workflow Task and Shared Care Planning .

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Innovaccer](https://innovaccer.com/)**
  Healthcare data platform and care coordination solution. Unifies payer and provider data to support population health management, risk stratification, and care gap closure.

- **[Unite Us](https://uniteus.com/)**
  Community care coordination platform connecting healthcare providers and community-based organizations. Supports social needs screening, closed-loop referrals, and outcome tracking.

- **[Findhelp](https://findhelp.org/)**
  Social care network and referral platform. Connects patients with community resources for food assistance, housing, transportation, and more, with closed-loop referral support.

- **[Arcadia](https://arcadia.io/)**
  Healthcare data analytics and population health management platform. Provides risk stratification, care gap identification, and provider performance analytics.

- **[Aidin](https://aidin.com/)**
  Care transitions management platform. Supports referrals and coordination from hospital to post-acute care.

- **[WellSky](https://wellsky.com/)**
  Care coordination and post-acute care technology platform. Spans home health, hospice, rehabilitation, and community care.

- **[CarePort Health](https://careporthealth.com/)**
  Care coordination platform under WellSky. Connects hospitals, post-acute care providers, and payers to support real-time patient referrals and care transitions.

- **[Lightbeam Health](https://lightbeamhealth.com/)**
  Population health management platform. Provides risk stratification, care coordination, and patient engagement tools.

- **[Bamboo Health (PatientPing)](https://bamboohealth.com/)**
  Care coordination and patient event notification platform. Supports cross-provider care coordination through real-time patient event notifications (admission, discharge, transfer).

- **[ZeOmega](https://zeomega.com/)**
  Population health management and care coordination platform. Provides care management, utilization management, and risk adjustment tools for payers and providers.

## Open-Source GitHub Projects

### Community Care Coordination Platforms

- **[SPICE (Medtronic LABS)](https://github.com/Medtronic-LABS)**
  **The most mature open-source community care coordination platform, recognized as a Digital Public Good.** Designed specifically for health systems and communities, focused on data-driven care at the community and primary care level . **Core capabilities**: Community health worker screening and risk stratification; **closed-loop referrals and counter-referrals** linking community care bidirectionally with facility services; longitudinal patient management based on clinical algorithms; facility-level medical review, prescribing, and lab ordering; SMS patient reminders; customized treatment plans based on WHO Hearts algorithms . **Deployment scale**: Deployed in 6 countries, screened 500,000 patients, referred 146,646 patients, enrolled 222,000 patients, and improved the lives of over 130,000 patients . **FHIR compatible**, supporting interoperability with national reporting systems such as DHIS2. **BSD-3-Clause license** .

- **[Community Health Toolkit (CHT)](https://github.com/medic/cht-core)**
  **The most widely deployed open-source platform for supporting community health workers, a Digital Public Good.** Comprises an open-source framework and collection of applications that help partners design and deploy digital tools for care teams . **Supports approximately 40,000 community health workers** across 15 countries in Africa and Asia . **Functional modules**: messaging, task and schedule management, decision support workflows, longitudinal person profiles, and analytics. Supports **offline-first** operation and is accessible via SMS (feature phones), Android apps, tablets, and computers . **Compliance**: manually configurable to align with HL7 FHIR standards . **Scale**: Health workers have completed over **85 million care activities**. Six countries (Kenya, Mali, Nepal, Niger, Uganda, and Zanzibar) have selected CHT as their national community platform . **AGPL-3.0 license**.

### Shared Care Planning & Referrals

- **[AHRQ eCare Plan](https://github.com/AHRQ-eCare-Plan)**
  **Open-source shared care plan applications developed by the U.S. Agency for Healthcare Research and Quality (AHRQ) and NIDDK.** Comprises two SMART-on-FHIR applications : **MyCarePlanner** (patient-facing) — patients and caregivers set goals, complete questionnaires, and share priorities with the care team; **eCarePlanner** (clinician-facing) — aggregates data from multiple EHR vendors and presents goals, social needs, and care team information. **Based on FHIR and USCDI standards**, supporting interoperability with Epic, VistA, and other EHRs . **Pilot results**: 90% goal authoring success, 67% of caregivers reported it made their work easier, 63% reported improved care coordination . **Open source**.

- **[ORCA (Santeon)](https://github.com/SanteonNL/orca)**
  **Open-source care plan reference implementation, implementing the Shared Care Planning specification.** Supports initiating and handling tasks between care organizations via FHIR Workflow Task . **Features**: UI for care professionals to complete questionnaires; proxy for care organizations' EHRs to access the care plan service FHIR API; handles authentication, localization, and data aggregation . **Architecture**: Each ORCA instance acts as an SCP node, capable of communicating with other nodes using different EHR systems . Designed for the Dutch healthcare system, adaptable to other regions. **Open source**.

- **[careplan-service (REAN Foundation)](https://github.com/REAN-Foundation/careplan-service)**
  **Care plan management service supporting authoring, scheduling, enrollment, and task distribution.** Written in **TypeScript** . Provides APIs for the full care plan lifecycle: creating care plans, scheduling tasks, enrolling participants, and distributing tasks to participants. Can serve as a foundational component for custom care coordination systems. **Open source**.

### FHIR Infrastructure & Interoperability

- **[Microsoft FHIR Server](https://github.com/microsoft/fhir-server)**
  **Microsoft's open-source FHIR server, the foundation of Azure Health Data Services FHIR service.** Supports the FHIR R4 specification with a complete RESTful API . Can serve as the underlying data store and interoperability layer for care coordination platforms. **Open source**.

- **[Microsoft FHIR-Converter](https://github.com/microsoft/FHIR-Converter)**
  **Data conversion tool for transforming legacy healthcare data formats to FHIR.** Supports both CLI and the `$convert-data` endpoint . Helps migrate legacy system data into FHIR-compatible care coordination platforms. **Open source**.

- **[TPT Healthcare NZ](https://github.com/tpt-solutions/tpt-healthcare-nz)**
  **New Zealand open-source healthcare platform with FHIR R5 REST API supporting NHI/HPI/ACC/NES/PHARMAC integration.** Go backend, React frontend, multi-tenant, audit trails, consent management . **Features**: FHIR R5 resource storage (PostgreSQL JSONB); patient lookup, practitioner verification, PHO enrollment, ACC claims; SNOMED CT, LOINC, ICD-10-AM terminology loading; FHIR R5 subscriptions (rest-hook, WebSocket, email); consent management (HIPC Rule 10/11); AES-256-GCM field encryption; OpenTelemetry tracing . **Compliance**: Privacy Act 2020 and HIPC 2020. **Open source**.

### Clinical Communication & Team Collaboration

- **[Matrix for Healthcare Communication (Nuts Foundation)](https://github.com/nuts-foundation/toepassing-instante-communicatie)**
  **Specification for instant messaging and care team collaboration based on Matrix.org.** Uses a federated communication protocol to enable secure messaging between care organizations . **Core design**: **Matrix Space = care team**; **Matrix Room = conversation**; permission levels (100 = care team lead, 50 = medical practitioner, 25 = related person, 10 = client); integration with healthcare identity providers; practitioner discovery via mCSD . **Use cases**: network management, new conversations, message management, cross-platform integration, multi-organizational collaboration . **CC BY-SA 4.0 license**.

### Additional Strong Open-Source Options

- **Community Care Coordination**: **SPICE** (Digital Public Good, 6 countries), **CHT** (40,000 CHWs, 15 countries).
- **Shared Care Planning**: **AHRQ eCare Plan** (SMART-on-FHIR, patient + clinician apps), **ORCA** (FHIR Workflow Task).
- **FHIR Infrastructure**: **Microsoft FHIR Server**, **FHIR-Converter**, **TPT Healthcare NZ** .
- **Clinical Communication**: **Matrix for Healthcare** (federated communication, care team spaces).

**Frameworks for building custom systems**: Combine **Microsoft FHIR Server** or **TPT Healthcare NZ** as the FHIR data store and interoperability layer, **AHRQ eCare Plan** or **ORCA** as the shared care planning engine, **SPICE** or **CHT** as the community care coordination frontend, and **Matrix for Healthcare** as the clinical communication layer. Add **PostgreSQL** for persistence and **Docker** for deployment.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Care coordination platforms handle sensitive patient health data; ensure compliance with HIPAA, GDPR, and applicable healthcare data protection regulations.
- **Open-source reality**: The open-source ecosystem for care coordination is **mature and production-ready** at the **community care coordination** (SPICE, CHT) and **FHIR interoperability** (Microsoft FHIR Server, TPT Healthcare NZ) layers. **AHRQ eCare Plan** provides validated shared care planning applications . **ORCA** provides an adaptable care plan reference implementation . However, **enterprise-grade population health management** (Innovaccer, Arcadia, Lightbeam) and **social care networks** (Unite Us, Findhelp) offer significant advantages in risk stratification algorithms, social services resource directories, and payer integrations that open-source alternatives require substantial integration and custom development to match.

---

**Made for care coordinators, population health managers, community health organizations, and healthcare IT teams.**
Let's make care coordination more open, transparent, and patient-centered.

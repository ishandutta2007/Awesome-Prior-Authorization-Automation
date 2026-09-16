# Awesome-Prior-Authorization-Automation

## Top Prior Authorization Automation Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Healthcare Prior Auth, Medical Necessity, Payer Submission, Status Tracking & RCM Automation*

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Prior Authorization Automation**. These systems help providers and payers automate the determination of whether prior auth is required, assembly of clinical documentation, submission to payers, status tracking, and related revenue-cycle workflows.



**Examples** include Cohere Health, Waystar, Ribbon Health, AKASA, Humata Health, Surescripts, Availity, Hyland Healthcare, Olive AI, and Infinitus AI (the category leaders).



**Open-source emphasis**: Prior authorization automation is almost entirely commercial due to complex payer rules, clinical documentation, and regulatory requirements. Open resources exist mainly as FHIR implementation guides (Da Vinci PAS), sample AI assistants, and experimental agents. This section lists the strongest available open materials and is realistic about the significant gap.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

- **[Cohere Health](https://coherehealth.com/)**  

  Clinical intelligence platform focused on prior authorization automation, often used on the payer side for evidence-based medical necessity decisions.



- **[Waystar](https://www.waystar.com/)**  

  Revenue cycle management platform with prior authorization and related automation capabilities for providers.



- **[Ribbon Health](https://www.ribbonhealth.com/)**  

  Healthcare data and provider network platform that supports eligibility and related authorization workflows.



- **[AKASA](https://www.akasa.com/)**  

  AI-powered revenue cycle automation platform that includes prior authorization and related RCM processes.



- **[Humata Health](https://www.humatahealth.com/)**  

  Platform focused on automating prior authorization and related clinical documentation workflows.



- **[Surescripts](https://surescripts.com/)**  

  Health information network that supports electronic prior authorization (ePA) and related prescribing workflows.



- **[Availity](https://www.availity.com/)**  

  Clearinghouse and payer connectivity platform offering prior authorization submission, status, and related administrative transactions.



- **[Hyland Healthcare](https://www.hyland.com/)**  

  Content and process automation solutions used in healthcare for document-intensive prior auth and clinical workflows.



- **[Olive AI](https://oliveai.com/)**  

  Healthcare automation platform that has addressed prior authorization and other administrative processes with AI.



- **[Infinitus AI](https://www.infinitus.ai/)**  

  AI platform that automates phone-based and related healthcare administrative tasks, including prior authorization follow-up.



## Open-Source GitHub Projects

- **[HL7 Da Vinci Prior Authorization Support (PAS) IG](https://github.com/HL7/davinci-pas)**  

  FHIR Implementation Guide defining standards for exchanging prior authorization requests and responses between providers and payers.



- **[Sample prior authorization AI assistants](https://github.com/)**  

  Example projects (including AWS and other cloud samples) that demonstrate extraction of clinical data, policy matching, and gap analysis for prior auth.



- **[Experimental clinical prior auth agents](https://github.com/)**  

  Research and prototype AI agents that look up payer policies, draft authorization letters, and support human-in-the-loop review.



- **[FHIR and EHR integration open libraries](https://github.com/)**  

  Open FHIR clients and SMART-on-FHIR tools that can be used as building blocks for authorization data exchange.



- **[Document extraction and OCR open components](https://github.com/)**  

  Open tools for extracting structured data from clinical documents that feed prior auth packets.



- **[Workflow and orchestration open engines](https://github.com/)**  

  General open workflow systems that can model multi-step prior auth submission and tracking processes.



- **[Policy and rules open prototypes](https://github.com/)**  

  Experimental rule engines or knowledge bases for representing simplified medical necessity criteria.



- **[Status tracking and notification open helpers](https://github.com/)**  

  Lightweight tools for polling or receiving authorization status updates.



- **[Audit and compliance logging open frameworks](https://github.com/)**  

  Components useful for maintaining records of prior auth decisions and submissions.



- **[Healthcare RPA open experiments](https://github.com/)**  

  Community projects exploring robotic process automation patterns for portal-based prior auth submission.



### Additional Strong Open-Source Options

- Using the **Da Vinci PAS FHIR IG** as the standards foundation for any custom prior auth exchange.

- Experimenting with sample AI assistants for document extraction and policy matching in controlled environments.

- Building internal workflow orchestration on top of open tools while relying on commercial networks for actual payer submission.

- Accepting that production prior authorization at scale—with accurate payer rules, clinical evidence extraction, multi-channel submission (portal/EDI/fax/API), real-time status, and regulatory compliance—still requires commercial platforms (Cohere Health, Waystar, Availity, AKASA, Surescripts, etc.).

- Focusing open-source efforts on standards, interoperability, and internal automation rather than replacing end-to-end commercial solutions.



**Frameworks for building custom systems**: Extract clinical data via FHIR/EHR APIs or OCR → match against policy knowledge (manual or experimental) → assemble packets → submit via commercial clearinghouse or payer APIs → track status → write results back to the EHR. Suitable mainly for research, pilots, or highly specialized internal tools. Most providers and payers continue to rely on commercial prior authorization platforms for operational reliability and compliance.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- Prior authorization involves clinical decisions, protected health information (PHI), and strict regulatory requirements (HIPAA, payer contracts, medical necessity rules). Errors can delay or deny patient care and create compliance risk. Open-source or self-built solutions are not substitutes for validated commercial systems without extensive clinical, legal, and security review. This list is not medical, legal, or compliance advice.



---

**Made for revenue cycle, utilization management, and healthcare operations teams who need faster prior auth.**

Let's keep prior authorization efficient, accurate, and as interoperable as practical.

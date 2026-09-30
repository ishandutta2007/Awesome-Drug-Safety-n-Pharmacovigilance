# Awesome-Drug-Safety-n-Pharmacovigilance

## Top Drug Safety & Pharmacovigilance Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Adverse Event Case Processing, Signal Detection & Regulatory Compliance*  

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Drug Safety & Pharmacovigilance**. These tools manage the collection, processing, analysis, and reporting of adverse event data throughout a drug's lifecycle, ensuring patient safety and regulatory compliance.



**Examples** include Oracle Argus Safety, Veeva Vault Safety, ArisGlobal LifeSphere Safety, Ennov Vigilance, SAP Pharmacovigilance, AB Cube, Celegence, EXTEDO, Sparta Systems, and IQVIA Vigilance (the category leaders).



**Open-source emphasis**: This section is expanded with active projects for self-hosting, custom signal detection, and transparent adverse event workflows — ideal for researchers, regulatory authorities, and developers building vendor-independent pharmacovigilance tools. The open-source ecosystem is anchored by **faers** (R interface for FDA data), **pvEBayes** (empirical Bayes signal detection), and **E2B4Free** (E2B(R3) case management), with strong coverage in statistical signal detection and regulatory data pipelines.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Oracle Argus Safety](https://www.oracle.com/life-sciences/safety-solutions/)**  

  Industry-leading pharmacovigilance platform used by the majority of top pharmaceutical companies and regulatory agencies. Modules include Argus Safety (case intake, triage, duplicate checking, medical review, E2B messaging), Argus Affiliate (global regulatory compliance), Argus Interchange (electronic exchange with regulators), Argus Dossier (periodic safety report lifecycle), and Argus Insight (multidimensional safety data analysis) .



- **[Veeva Vault Safety](https://www.veeva.com/)**  

  Modern ICSR management system on the Veeva Vault platform. Manages intake, processing, and submission of adverse events for clinical and post-marketed products across drug, biologic, vaccine, device, and combination products. Built-in gateway connections and reporting rules streamline submissions to health authorities. Central coding dictionary management automates semi-annual MedDRA, WHODrug, and EDQM updates .



- **[ArisGlobal LifeSphere Safety](https://www.arisglobal.com/)**  

  AI-first pharmacovigilance platform with MultiVigilance (end-to-end case processing), Reporter (multilingual field reporting), and Advanced Signals powered by NavaX. Used by regulators and big pharma, signaling that cloud solutions have matured for risk-averse stakeholders .



- **[Ennov Vigilance](https://www.ennov.com/)**  

  Pharmacovigilance software with emphasis on intuitive interfaces, role-based views, and reducing clicks and manual steps .



- **[SAP Pharmacovigilance](https://www.sap.com/)**  

  Enterprise pharmacovigilance solution integrated with SAP's life sciences suite.



- **[AB Cube](https://www.abcube.com/)**  

  Pharmacovigilance and safety database solutions for case management and regulatory reporting .



- **[Celegence](https://www.celegence.com/)**  

  Regulatory and pharmacovigilance services with technology solutions for safety case management.



- **[EXTEDO](https://www.extedo.com/)**  

  Regulatory information management with pharmacovigilance capabilities. SafetyEasy offers E2B(R3) support, AI modules, and compliance features .



- **[Sparta Systems (Honeywell)](https://www.spartasystems.com/)**  

  Quality management software (TrackWise) used in life sciences for complaint management, CAPA, audit management, and adverse event reporting. Supports global electronic reporting standards including eMDR and E2B .



- **[IQVIA Vigilance](https://www.iqvia.com/)**  

  Pharmacovigilance platform and services for adverse event management, signal detection, and regulatory reporting.



## Open-Source GitHub Projects



- **[faers (R/Bioconductor)](https://github.com/WangLabCSU/faers)**  

  The most comprehensive open-source R interface for the FDA Adverse Event Reporting System (FAERS), published on Bioconductor . Provides a high-fidelity framework for precision adverse event surveillance, addressing data heterogeneity, reporting redundancies, and inconsistent medical terminology that constrain FAERS utility . Offers a standardized approach for performing pharmacovigilance analysis with end-to-end workflows . MIT licensed with active development .



- **[pvEBayes (R/CRAN)](https://github.com/YihaoTancn/pvEBayes)**  

  Open-source R package implementing a suite of nonparametric empirical Bayes methods for pharmacovigilance, including Gamma-Poisson Shrinker (GPS), K-gamma, general-gamma, Koenker-Mizera (KM), and Efron models . Provides the **first implementation of K-gamma and general-gamma methods** for signal detection and signal strength estimation . Offers a fully open-source KM implementation using CVXR, avoiding the commercial Mosek solver required by REBayes . Supports AIC/BIC-based hyperparameter tuning and includes built-in FAERS datasets for examples . Published in *Statistics in Medicine* (2025) .



- **[E2B4Free](https://github.com/)**  

  Open-source web application for managing adverse event reports using the E2B(R3) standard. The first and only project offering free and open-source software to enhance drug safety . Details architecture and technologies for processing pharmacovigilance data, with special attention to integration of dictionaries such as MedDRA, UCUM, EDQM, SMS, and country/language codes. Supports data export in CIOMS I format .



- **[OpenRIMS-PV](https://github.com/MSH/OpenRIMS-PV)**  

  Web-based application focused on Active Monitoring for the safety of medicines, created by the USAID-funded Medicines, Technologies and Pharmaceutical Services (MTaPS) Project . Part of the OpenRIMS Free and Open Source Software (FOSS) suite to assist National Medicines Regulatory Authorities in routine tasks. GPL-3.0 licensed .



- **[PViMS-2](https://github.com/MSH/PViMS-2)**  

  PharmacoVigilance Monitoring System 2, a web-based application focused on Active Monitoring for the safety of medicines . GPL-3.0 licensed, part of the MSH (Management Sciences for Health) open-source portfolio.



- **[MDDC (R/CRAN)](https://github.com/niuniular/MDDC)**  

  Modified Detecting Deviating Cells algorithm for pharmacovigilance signal detection. Provides methods for detecting signals related to (adverse event, medical product) pairs, data generation for simulating pharmacovigilance datasets, and various utility functions . Published in arXiv (2024) with GPL-3 license .



- **[pvm (R)](https://github.com/bips-hb/pvm)**  

  A collection of signal detection methods used in the field of pharmacovigilance. Provides implementations of various disproportionality analysis algorithms .



- **[srsim (R)](https://github.com/bips-hb/srsim)**  

  An R package for simulating spontaneous reports for pharmacovigilance research and method validation .



### Additional Strong Open-Source Options



- **openEBGM** — R package implementing the Gamma-Poisson Shrinker (GPS) method for pharmacovigilance signal detection .

- **deconvolveR** — R package implementing Efron's nonparametric empirical Bayes method, adapted in pvEBayes for pharmacovigilance .

- **REBayes** — R package with general nonparametric empirical Bayes implementation for Koenker-Mizera method (requires commercial Mosek solver) .

- **kidsides** — Database for pediatric drug safety signals .

- **BiDEX** — Large-scale biomedical adverse drug event extraction for real-world pharmacovigilance .

- **rankv** — Rank aggregated signal detection for VAERS (vaccine adverse event) data .

- **E2B (FreeVigilance)** — JavaScript implementation of E2B standard for pharmacovigilance data exchange .



**Frameworks for building custom pharmacovigilance solutions**: Combine **faers** for standardized FAERS data ingestion and analysis, **pvEBayes** for advanced empirical Bayes signal detection with signal strength estimation, and **E2B4Free** for E2B(R3)-compliant case management. Use **MDDC** for deviating cell detection algorithms, **pvm** for multiple signal detection method comparison, and **srsim** for method validation through simulation. Note that true enterprise pharmacovigilance platforms with global regulatory gateway connectivity (FDA FAERS, EMA EudraVigilance), MedDRA/WHODrug licensing, and validated audit trails remain primarily commercial territory; open-source stacks provide strong statistical signal detection, FAERS data processing, and E2B case management foundations that require integration for complete safety operations.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Drug safety tools must comply with regulatory requirements (21 CFR Part 11, EU GVP, ICH E2B(R3)) and validated system requirements for GxP compliance. MedDRA and WHODrug dictionaries are licensed and user-supplied.

- Self-hosted open-source solutions require proper infrastructure, validation protocols, and ongoing maintenance. Statistical signal detection requires domain expertise and should complement, not replace, human safety review.

- The open-source ecosystem provides strong statistical foundations, FAERS data processing, and E2B case management, but full enterprise pharmacovigilance platforms with global regulatory gateway connectivity and validated audit trails remain primarily a commercial offering.



---



**Made for pharmacovigilance professionals, drug safety officers, clinical researchers, and regulatory affairs teams.**  

Let's make drug safety management more open, transparent, and statistically rigorous.

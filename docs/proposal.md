# Research Proposal
**Title:** Enhancing Data Protection in Nigeria’s Social Media Ecosystem: Privacy Risks, User Awareness, and NDPA 2023 Compliance  
**Author:** Folajimi Igbekoyi (igbekoyifolajimi@gmail.com)  
**Date:** 21 August 2025

## 1. Background & Rationale
Social media platforms (e.g., Facebook, Instagram, TikTok, X/Twitter, YouTube, Snapchat, Threads, WhatsApp) are central to communication, business, and civic life in Nigeria. These services process large volumes of personal data (identifiers, contact details, photos, biometrics, behavioral and location data). Nigeria’s **Data Protection Act 2023 (NDPA)** mandates lawful, fair, and transparent processing; purpose limitation; data minimization; accuracy; storage limitation; integrity and confidentiality; and accountability. However, practical compliance by global platforms operating in Nigeria is uneven, especially for **data subject rights (DSAR)** such as access and erasure, and for clear disclosures about cross‑border transfers and third‑party sharing. User awareness of rights is also variable.

## 2. Problem Statement
There is limited empirical evidence on how well major social platforms serving Nigerians comply with **NDPA 2023**, and how aware Nigerian users are of their data protection rights. Without such evidence, regulators, civil society, and platform operators lack a baseline to improve compliance, enforcement, and user protection.

## 3. Objectives
1. Evaluate the extent to which major social media platforms used in Nigeria comply with **NDPA 2023**, with emphasis on **data subject rights (DSAR)**.  
2. Assess Nigerian users’ **awareness** and exercise of NDPA rights (access, rectification, erasure, portability, objection, restriction).  
3. Identify gaps in disclosures (lawful basis, cross‑border transfers, retention, third parties, profiling/ADM, breach notices, children’s data).  
4. Provide practical **recommendations** for platforms, regulators (NDPC), and the public.  
5. Deliver an applied **mini‑project** (open‑source scorecard and templates) to translate findings into practice.

## 4. Research Questions (RQs) & Hypotheses (H)
- **RQ1:** To what extent do platforms comply with NDPA DSAR obligations?  
  - **H1:** Platforms will vary widely in DSAR response time and completeness for Nigerian data subjects.
- **RQ2:** How clear are platforms’ privacy disclosures for Nigerian users (lawful basis, transfers, retention)?  
  - **H2:** Disclosures are less explicit for Nigeria than for EU users.
- **RQ3:** What is the level of NDPA rights awareness among Nigerian users?  
  - **H3:** Fewer than 40% of respondents can correctly name two or more NDPA rights.
- **RQ4:** Which factors (education, tech literacy, platform use) predict higher awareness and DSAR exercise?  
  - **H4:** Higher education and security training correlate with greater awareness and DSAR usage.

## 5. Scope, Assumptions & Limitations
- **Scope:** Publicly documented platform practices; user self‑reports (survey); DSAR tests using standard, platform‑provided channels.  
- **Assumptions:** Platforms maintain a single global process for DSAR with some localization.  
- **Limitations:** Terms of service may limit automation; DSAR timelines may extend beyond study window; self‑selection bias in survey.

## 6. Literature & Legal Framework (brief plan)
- NDPA 2023: principles, lawfulness, consent, children’s data, controller obligations, cross‑border transfers, breach notification.  
- NDPR (2019) vs NDPA (2023): key shifts.  
- Comparative: GDPR (EU), UK AADC (children), and global DSAR practices.  
- Theoretical lenses: **Privacy Calculus**, **Protection Motivation Theory** (drivers of DSAR usage).

## 7. Methodology
**Design:** Mixed‑methods, cross‑sectional.  
**Population:** Adult social media users in Nigeria; major platforms (≥6): Facebook, Instagram, TikTok, X, YouTube, Snapchat/Threads/WhatsApp (choose 6–8).

### 7.1 DSAR Compliance Assessment
- **Accounts:** Create study‑specific accounts (no real personal data beyond what is necessary).  
- **Requests:** Submit **Access (Art. access)** and **Erasure** requests via official portals.  
- **Measures:** Receipt confirmation time; identity verification requirements; response time (calendar days); completeness (data categories provided, file format); reasons for denial; guidance provided.  
- **Evidence:** Save request IDs, emails, timestamps, and redacted outputs.  
- **Scoring:** Apply **docs/compliance_rubric.md** (0–2 scale per item; weighted category totals).

### 7.2 Privacy Policy & UI/UX Disclosure Coding
- **Artifacts:** Privacy notice sections for Nigeria; cookie banners; in‑app privacy settings.  
- **Coding:** Use **data/templates/consent_notice_coding_template.csv** for rubric items (lawful basis, transfers, retention, DPO contact, children safeguards, profiling).

### 7.3 User Survey
- **Sample:** n = 150–300 (convenience + snowball across Lagos/Abuja/PH and online groups).  
- **Instrument:** **docs/survey.md** (Likert + knowledge checks).  
- **Analysis:** Descriptives; chi‑square for association; logistic regression for predictors of NDPA awareness and DSAR usage.  
- **Tools:** Excel/SPSS/R/Python.

### 7.4 Ethics
- Informed consent on the survey intro; anonymity; voluntary participation; option to withdraw.  
- No scraping or circumvention; only platform‑supported DSAR channels.  
- Store DSAR artifacts securely; redact identifiers before sharing.

## 8. Data Analysis Plan
- **DSAR:** Compute per‑platform KPIs (mean response time; fulfillment rate; completeness score). Rank with confidence intervals.  
- **Disclosures:** Percentage of required items satisfied per platform/category.  
- **Survey:** Awareness index; behavior index; regression models for predictors; visualize with bar charts and forest plots.

## 9. Timeline (indicative)
- Week 1–2: Instrument finalization & pilot.  
- Week 3–6: Data collection (survey + DSAR requests + policy coding).  
- Week 7–8: Analysis & scorecards.  
- Week 9–10: Report writing, dashboard, and public release.

## 10. Deliverables
- Final report (PDF + repo docs).  
- Open **Scorecard** and DSAR log templates.  
- Public summary for non‑technical readers.

## 11. Budget (indicative)
- Data/hosting, modest incentives for respondents, optional software subscriptions.

## 12. Risk Management
- DSAR delays: track continuously; extend collection window if needed.  
- Platform refusal: document reasons; include qualitative analysis.  
- Low survey response: broaden channels; modest incentives.

## 13. References (to be populated during write‑up)
- NDPA 2023; NDPR 2019; GDPR; academic papers on DSAR, privacy literacy, and dark patterns.

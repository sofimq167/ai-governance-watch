# AI Governance Watch — Research Tracker

Daily tracker of new findings across 6 topics. Each entry should include a **date logged**, a **source/link**, and a **1–2 sentence summary**. Do not duplicate anything already logged below — dedupe by source URL and by substantive claim.

---

## 1. AI used to produce climate/sustainability disclosures, and how to govern/control it

Scope: Use of AI/LLMs to draft, calculate, or assemble climate & sustainability disclosures (e.g., CSRD/ESRS, IFRS S1/S2, SEC climate rule); governance frameworks, model risk management, and controls over that AI.

### Findings
- **2026-06-15** — [Workiva Launches Agentic AI Sustainability Reporting Solution](https://www.esgtoday.com/workiva-launches-agentic-ai-sustainability-reporting-solution/) — New "Sustainability Disclosure Agent" scans prior-cycle disclosures against ESRS/IFRS S1/S2 requirements to flag present/partial/missing content and draft a first pass, but is designed to run inside Workiva's governed platform with audit trails/version control and to leave interpretation and final sign-off to human teams — a concrete example of guardrails being built around AI-drafted climate disclosures.

---

## 2. "AI governance is a controls problem" — applying standard compliance controls to AI

Scope: The thesis that AI governance should be treated as an internal-controls / GRC discipline rather than a novel problem; mapping AI risks to established control frameworks (COSO, SOX, SOC 2, NIST AI RMF, ISO/IEC 42001), three-lines-of-defense models.

### Findings
- **2026-02-23** — [Achieving Effective Internal Control Over Generative AI](https://www.coso.org/generative-ai) — COSO's first formal extension of its 2013 Internal Control–Integrated Framework to GenAI: maps the five components/17 principles onto eight GenAI capability types (ingestion, transformation, posting, orchestration, judgment, monitoring, regulatory intelligence, human-AI interaction) and lays out a six-step govern/inventory/assess/design/implement/monitor roadmap — the clearest primary-source articulation to date of "AI governance as a controls problem."
- **2026-06-24** — [Typeform Achieves ISO/IEC 42001 Certification for Responsible AI Management](https://www.prnewswire.com/news-releases/typeform-achieves-isoiec-42001-certification-for-responsible-ai-management-302808030.html) — Typeform (June 24) and Emburse (June 12) both achieved ISO/IEC 42001 AI-management-system certification this cycle, continuing a steady drumbeat of companies using the standard as an externally-audited controls framework to demonstrate AI governance rather than relying on internal policy alone.

---

## 3. Evidence that AI governance controls/programs actually operated (not just that they exist on paper)

Scope: Operating effectiveness vs. design effectiveness; evidence, testing, and metrics that show AI controls ran as intended over a period — not merely that policies/committees exist. Case studies, audit findings, regulator expectations on demonstrable operation.

### Findings
- **2026-04-13** — [A widening 'AI proof gap' is emerging](https://www.grantthornton.com/insights/press-releases/2026/april/grant-thornton-survey-on-ai-proof-gap) — Grant Thornton's 2026 AI Impact Survey (950 executives, Feb–Mar 2026) found 78% of leaders lack strong confidence they could pass an independent AI governance audit within 90 days, and only 1 in 5 organizations running/piloting autonomous AI has actually tested a response plan for AI failures — direct quantitative evidence of the design-vs-operating-effectiveness gap in AI governance.

---

## 4. Assurance levels for AI — limited vs reasonable assurance, ISSA 5000, ISAE 3410, what the Big Four verify

Scope: Assurance standards and their application to AI-produced data/disclosures; ISSA 5000 (sustainability assurance), ISAE 3410 (GHG statements), ISAE 3000; distinction between limited and reasonable assurance; what Deloitte/PwC/EY/KPMG actually attest to for AI and ESG.

### Findings
- **2026-02-10** — [IAASB to pursue non-authoritative guidance for AI](https://www.accountingtoday.com/news/iaasb-to-pursue-non-authoritative-guidance-for-ai) — After eight global roundtables with 240+ stakeholders, the IAASB decided to address AI's practical challenges to existing assurance standards via non-authoritative guidance rather than new authoritative standards for now, with a formal action plan discussed at its March 2026 meeting — signals how (and how fast) assurance standard-setters intend to formalize what "AI assurance" requires.

---

## 5. AI audit trails — tamper-proof logging, human sign-off on AI output

Scope: Technical and control mechanisms for AI auditability — immutable/tamper-evident logs, provenance and lineage of AI outputs, human-in-the-loop review and sign-off, evidence retention for auditors.

### Findings
- **2026-04-16** — [What the EU AI Act requires for AI agent logging](https://www.helpnetsecurity.com/2026/04/16/eu-ai-act-logging-requirements/) — Article 12 requires high-risk AI systems to have automatic event logging built into core design (not bolted on afterward), with logs structured, searchable, and attributable to a specific agent/action; Article 19 sets a minimum 6-month retention period; two draft technical standards (prEN 18229-1, ISO/IEC DIS 24970) are in progress ahead of the August 2, 2026 Annex III enforcement date.
- **2026-01-05** — [The C2PA Launches Content Credentials 2.3](https://c2pa.org/the-c2pa-launches-content-credentials-2-3-and-celebrates-5-years-of-impact-across-the-digital-ecosystem/) — New spec version adds provenance support for live video and cross-platform credential portability; C2PA's AI-assertion type is positioned to help satisfy the EU AI Act's AI-generated-content transparency/labeling requirement taking effect August 2026, making it a candidate provenance/lineage standard for AI audit trails.

---

## 6. ESG controllers/auditors and their real-world climate data challenges

Scope: Practitioner (ESG controller, sustainability controller, external auditor) perspectives on climate/ESG data quality, completeness, Scope 3, estimation, data lineage, and controllership challenges encountered in practice.

### Findings
- **2026-06-03** — [More Disclosures, Less Clarity: The Scope 3 Data Quality Challenge](https://www.iss-stoxx.com/insights/articles/more-disclosures-less-clarity-the-scope-3-data-quality-challenge/) — Despite Scope 3 disclosure volume growing >12%/year since 2020, a significant share of reported Scope 3 data still fails quality review and must be replaced with modeled estimates; incomplete coverage/inconsistent boundaries are the top rejection drivers in Financials, Energy, and Industrials, and financed emissions (Category 15) are frequently omitted by banks — understating true climate risk exposure.
- **2026-06-01** — [Why is Scope 3 so complicated for financial services?](https://www.icaew.com/insights/viewpoints-on-the-news/2026/jun-2026/why-is-scope-3-so-complicated-for-financial-services) — ICAEW, working with the Partnership for Carbon Accounting Financials, published Scope 3 case studies across retail banking, investment banking, insurance, and asset management, highlighting that financed emissions depend on activities firms fund rather than control, driving data gaps, timing mismatches, and double-counting risk that controllers must manage.

---

_Last updated: 2026-07-03 — 9 new findings added (initial population of all 6 topics)_

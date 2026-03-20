# AI Business Expert — Article History Log

This log is the institutional memory of the AIBE pipeline. It is read before every new run (Phase 0) to prevent argument repetition and to surface calibration signals. It is appended after every completed run (Phase 7).

## Log Format

Each entry follows this structure:
- **Article ID**: Sequential (001, 002, ...)
- **Date**: YYYY-MM-DD
- **Topic**: Research prompt summary
- **Folder**: Path to article folder
- **Core Thesis**: 1–2 sentence summary of the central argument
- **Key Arguments**: 3–5 bullet points of the main claims made
- **AI Tools Featured**: Named AI products/platforms covered
- **Industries Covered**: Which sectors were analysed
- **Companies Featured**: Named organisations cited as examples
- **What is NEW**: What was novel about this analysis (anti-repetition field)
- **What is KNOWN Context**: Background facts established; can be referenced but not re-argued
- **Key Metrics Cited**: Specific numbers, percentages, dollar figures used
- **Pipeline Execution Grade**: 0–100% with letter grade
- **Pipeline Retrospective**:
  - Skill Utilisation Review
  - Gate Performance (retry counts per gate)
  - Calibration Signals
  - Recommendations for Next Run

---

## Article 001 — 2026-03-20

- **Article ID**: 001
- **Date**: 2026-03-20
- **Topic**: Intelligent Automation Business Wins — Before/After/Benefits
- **Folder**: Articles/2026/03/20_Intelligent_Automation_Wins_1/
- **Core Thesis**: Intelligent automation is already delivering material, measurable returns across financial services, manufacturing, logistics, and telecoms — but value is concentrated in a small cohort of organisations that redesigned underlying processes before deploying technology, while the majority of automation investment has not translated into enterprise-level financial impact.
- **Key Arguments**:
  - The adoption-value gap is stark: 88% of organisations deploy AI in at least one function, but only 6% can attribute more than 5% of EBIT to AI (McKinsey, November 2025, n=1,993)
  - The differentiator between high performers and the field is not technology access — it is whether the organisation redesigned processes before deploying automation (55% of high performers did; only ~19% of others did)
  - Named-company before/after-benefit evidence now spans multiple industries at sufficient scale to draw conclusions about which value mechanisms are real (Aviva, IBM, JPMorgan, Siemens, Iron Mountain, BT Group)
  - The cost of waiting has a structural component: process redesign is the long-lead item, and organisations starting that work now will reach deployable designs months ahead of those waiting for technology maturity
  - Platform convergence (Gartner: 40% of enterprise apps embedding AI agents by end of 2026) means AI capability in tools already owned will expand materially regardless of active deployment decisions
- **AI Tools Featured**: IBM watsonx (AskHR, AskIT, AskSales, watsonx Orchestrate), Salesforce Einstein Service Cloud, ServiceNow Now Assist, Dynatrace AIOps, JPMorgan COiN, Bank of America Erica, Siemens AI-driven predictive analytics, Harvey/Luminance/Litera Kira (contract AI), Celonis process mining
- **Industries Covered**: Financial services (banking, insurance), cross-industry enterprise IT, industrial manufacturing, information management/document services, telecoms/infrastructure, semiconductor equipment (ASML)
- **Companies Featured**: JPMorgan Chase, Aviva, IBM, Iron Mountain, Siemens, BT Group/Openreach, ASML, Bank of America, SS&C Blue Prism (Forrester TEI composite — directional)
- **What is NEW**:
  - Process redesign framed as the long-lead item (not technology readiness) as the structural reason to begin diagnostic work now — derived from McKinsey November 2025 survey
  - Gartner 40% enterprise app AI agent embedding projection framed as a platform renewal/licensing decision, not an abstract technology forecast
  - Three-mechanism value framework (labour deflection, quality improvement, cycle time compression) as an alternative to headline ROI figures
  - Calibrated confidence tiering across all cited metrics (investor-disclosed, IBM-stated, vendor-commissioned composite, Salesforce-reported)
- **What is KNOWN Context**:
  - JPMorgan COiN operational since 2017 — established and widely referenced
  - EY 50% RPA project failure rate — established industry finding
  - EU AI Act regulatory framework — public record
  - Gartner fewer than 20% measurement excellence finding — previously published
  - Aviva £60M savings — investor-disclosed, McKinsey published case study
- **Key Metrics Cited**:
  - JPMorgan COiN: 360,000 hours/year eliminated; 12,000 agreements processed annually
  - Aviva: 23-day reduction in complex case assessment; 30% routing accuracy improvement; 65% complaint reduction; £60M (AU$115M) documented savings
  - IBM Client Zero: US$4.5B annual run-rate (IBM-stated); 3.9M hours saved in 2024; 94% AskHR autonomy; 56% AskIT ticket reduction; 86% IT queries resolved without human involvement
  - Iron Mountain: 80% AI case close rate; 76% AI responses sent unedited; 5% → 1.5% chat abandonment
  - Siemens: 50% unplanned stoppage reduction; 45% unplanned downtime reduction; 28% maintenance spend reduction
  - BT Group: 10% repair volume reduction; 4% energy reduction; £28M projected cumulative saving by 2027
  - McKinsey November 2025 (n=1,993): 88% deploy AI; 6% attribute >5% EBIT; 55% high performers redesigned processes first
  - Gartner: 40% enterprise apps with AI agents by end of 2026; <20% companies excel at hyperautomation measurement; >40% agentic AI projects cancelled by 2027
  - Forrester: 330% three-year ROI / US$53.4M NPV (SS&C Blue Prism TEI, vendor-commissioned composite); <15% firms will activate agentic features by end of 2026
  - EU AI Act: €35M or 7% global revenue penalties for high-risk AI non-compliance
- **Pipeline Execution Grade**: 97% A
- **Pipeline Retrospective**:
  - Skill Utilisation: Internal article only produced (user requested internal article); article.md, case_study.md, executive_content.md not produced this run
  - Gate Performance: All gates passed first attempt — zero retries required across all 9 gates
  - Calibration Signals: Bloomberg 2017 JPMorgan COiN source technically aged but allowable for establishing origin; two citation fixes applied in Gate 6 (Bloomberg reference list entry missing; IEN abbreviation mismatch)
  - Recommendations for Next Run: If this topic is revisited, lead with a newer COiN source and avoid Bloomberg 2017 as primary citation; consider adding an Australian-headquartered company case study to improve local relevance; if internal article writer is invoked again, remind it to open Section 3 with a named company example rather than an evidence-base overview sentence

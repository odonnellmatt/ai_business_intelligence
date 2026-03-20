# Research Summary — Intelligent Automation Delivering Real Business Wins
**Summariser**: aibe_summarizer
**Date**: 2026-03-20
**Research prompt**: How is intelligent automation delivering real business wins? Focus on companies that had specific operational problems and solved them with intelligent automation — covering what broke before, what changed after, and the measurable benefits now flowing through.
**Source document**: process_files/research_findings.md (27 sources, Gate 1 APPROVED)
**Verification document**: process_files/source_verification.md

---

## 1. AI Tools and Platforms Identified

The following named products appear in verified implementations across the research base:

**Enterprise AI / Agent Platforms**
- **IBM watsonx** — IBM's proprietary AI platform underpinning all Client Zero deployments, including domain-specific agents: AskHR (employee HR queries), AskIT (IT support), AskSales (seller research), and watsonx Orchestrate (cross-functional workflow automation). Generally available in production across IBM's global operations as at 2025.
- **Salesforce Einstein AI / Service Cloud** — AI-generated reply drafting, article recommendations, work summaries, and case routing within Salesforce's CRM platform. Deployed by Iron Mountain and adopted across Salesforce's enterprise customer base.
- **ServiceNow Now Assist** — AI capabilities embedded in ServiceNow's ITSM and workflow platform, including intelligent virtual agents, case summarisation, and ticket routing. Deployed by ASML and documented in enterprise benchmarks.

**RPA and Intelligent Automation Platforms**
- **SS&C Blue Prism** — Enterprise RPA and intelligent automation platform; Forrester TEI (vendor-commissioned, 2024) modelled a composite financial services organisation achieving 330% three-year ROI and US$53.4 million NPV.
- **Microsoft Power Automate** — Microsoft's low-code automation platform; Forrester TEI (vendor-commissioned, 2024) found 248% three-year ROI for a composite enterprise.

**Process Intelligence**
- **Celonis** — Leader in the 2025 Gartner Magic Quadrant for Process Mining Platforms. Provides a "living digital twin" of business operations; Orchestration Engine (generally available 2025) enables automated Action Flows. Customer community has documented US$8.1 billion in combined value across enterprise workflows.

**AIOps / Infrastructure Automation**
- **Dynatrace** — Deployed by BT Group for AIOps across IT operations; targeting self-healing systems with an estimated cumulative saving of £28 million by 2027.
- **Janus** — Comcast's proprietary AI-enabled cloud network monitoring system for traffic pattern prediction and power consumption optimisation.

**Virtual Assistants**
- **Bank of America Erica** — Conversational AI virtual assistant; 3 billion total client interactions by August 2025; 58 million interactions per month across nearly 50 million users; 98%+ respond within 44 seconds.
- **Erica for Employees** — Internal enterprise version of Erica; used by over 90% of Bank of America's 213,000 staff; cut IT service desk calls by more than 50%.
- **FedEx Nina** — Virtual agent; handled over 6.7 million conversations in North America; 80–81% first-contact resolution rate.

**Computer Vision / Manufacturing AI**
- Tesla computer vision (quality control, Fremont plant): real-time defect detection 50% faster than manual inspection.
- BMW AI vision (Spartanburg plant): component placement verification; US$1 million+ annual savings.
- Siemens predictive maintenance AI: 50% reduction in unplanned line stoppages; 45% reduction in unplanned downtime; 28% reduction in maintenance spend.

**Banking-Specific**
- **JPMorgan COiN** (Contract Intelligence): Processes 12,000 commercial loan agreements annually; formerly 360,000 legal hours per year. Operational since 2017; continuously expanded.
- **JPMorgan LLM Suite**: Deployed to all 200,000+ JPMorgan employees in 2024; AI tools applied to operations, fraud detection, sanctions screening, and credit decisioning; expected to realise US$1.5 billion+ in value.

**Logistics Robotics**
- **DHL + Robust.AI Carter robot**: Collaborative picking and replenishment robot; 60%+ productivity improvements in North American pilot environments. Five-year strategic alliance announced December 2025 for Mexico deployment.
- **Amazon Proteus**: Autonomous mobile robots deployed across 50+ fulfilment centres; part of a 1.5 million robot fleet; 20% productivity gain attributed to robotics programme.

---

## 2. Real-World Implementations

| Company | Industry | AI Tool / Platform | Before State | After State | Measurable Outcome | Source |
|---------|----------|--------------------|--------------|-------------|-------------------|--------|
| IBM (Client Zero) | Cross-industry enterprise | IBM watsonx (AskHR, AskIT, AskSales, Orchestrate) | Fragmented HR, IT, procurement, sales operations across 175+ countries; 40+ disconnected procurement systems; manual supply chain decisions across 10M shipments | 155 AI use cases deployed across all major functions; 2-week agile deployment cycles; CEO-level steering | US$4.5B annual run-rate productivity savings (IBM-stated, end-2025); 3.9M hours saved in 2024 alone; 94% HR queries resolved autonomously; 56% IT support ticket reduction; 74% reduction in calls/chats; 91.6% CSAT (up 11.6pp); 26,000 procurement hours saved annually | IBM case studies, 2025; Benzinga, 2025 |
| JPMorgan Chase | Banking | COiN (Contract Intelligence) | 360,000 legal/loan officer hours annually to review commercial loan agreements | AI processes same volume in seconds; near-zero error rate | 360,000 hours/year eliminated from contract review; near-zero error rate | Bloomberg, Feb 2017; klover.ai, 2025 |
| JPMorgan Chase | Banking | LLM Suite + 450+ AI use cases | Manual fraud, sanctions, credit workflows | AI tools deployed to all 200,000+ employees; "viral" internal adoption | US$1.5B+ expected value from AI operations; US$17B technology budget (2024) | klover.ai, 2025 |
| Bank of America | Banking | Erica (client) + Erica for Employees | Call centre volume-driven wait times; IT service desk load across 213,000 staff | Erica handles 58M+ interactions/month; employee Erica embedded across workforce | 3B total client interactions (Aug 2025); 98%+ respond within 44 seconds; IT service desk calls cut by 50%+; software developers 20%+ efficiency gain | BofA newsroom, Aug 2025; Apr 2025 |
| Aviva | Insurance | 80 AI models (McKinsey QuantumBlack) | Manual liability assessment; inconsistent claims routing; high complaint volumes | Automated liability assessment; AI-driven routing; real-time complaint pattern detection | Liability assessment time: -23 days for complex cases; routing accuracy: +30%; customer complaints: -65%; documented savings: £60M (AU$115M) — investor-disclosed | McKinsey Aviva case study, 2025 |
| Nationwide (US) | Insurance | Generative AI summarisation (proprietary) + multiple AI claims tools | CSRs spent 3–4 minutes manually reading log notes per customer record; high after-call admin load | AI surfaces claim histories instantly; call transcript tool pre-populates after-call work | Pets claims: 80% projected to be automated, 25% instant settlement; farm/agricultural claims review time: -20% projected | Claims Journal, Dec 2025; Fortune, Oct 2025 |
| Iron Mountain | Information management | Salesforce Einstein Service Cloud | Agents switched between multiple applications; manual knowledge base searches; growing inquiry backlog | AI-generated replies, article recommendations, work summaries | 80% case close rate with AI responses; 76% of AI replies sent unedited; 85% of agents rated responses as extremely helpful; repeat calls -8%; average handle time -10%; chat abandonment -70% (5% → 1.5%) | Salesforce customer story, 2024 |
| ASML | Semiconductor equipment | ServiceNow intelligent virtual agent | High IT ticket volume handled manually | AI virtual agent handles first-line IT queries | User satisfaction above 80% within weeks of deployment | ServiceNow blog, 2023 |
| Tesla | Automotive | Computer vision (proprietary) | Labour-intensive manual visual inspection; inconsistent defect detection throughput | Real-time AI defect detection on production lines | Defect detection 50% faster than manual inspection | IEN, 2024 |
| BMW | Automotive | AI vision systems (Spartanburg) | Manual component placement checking; misalignment discovered late | AI checks component placement and flags misaligned parts in real time | US$1M+ annual savings at Spartanburg plant alone | IEN, 2024 |
| Siemens | Industrial manufacturing | AI-driven predictive analytics | Reactive maintenance — failures discovered after production impact | Continuous sensor monitoring; ML flags failure risk windows before breakdown | Unplanned line stoppages: -50%; unplanned downtime: -45%; maintenance spend: -28% | IEN, 2024 |
| DHL Supply Chain | Logistics | Proprietary AI + Robust.AI Carter robot | Manual warehouse operations; high staff travel distances; slow site deployment | AI orchestration layer; 7,000+ robots across 2,000+ sites | Staff travel distance: -50%; site productivity: +up to 30%; picking productivity: +60%+ (Carter pilots); new automation deployment time: -60% | DHL press release, 2024; BusinessWire, Dec 2025 |
| Amazon | E-commerce / logistics | Proteus AMRs + 1.5M robot fleet | High manual fulfilment labour requirements | Autonomous mobile robots across 50+ fulfilment centres | 20% productivity gain attributed to robotics programme | DHL/IEN secondary references, 2024 |
| BT Group (Openreach) | Telecoms | Dynatrace AIOps | Manual IT operations; high network repair volumes; energy inefficiency | AIOps self-healing systems targeting automated remediation by 2025 | Repair volumes: -10%; energy use: -4%; AIOps programme estimated saving: £28M by 2027; total cost savings programme: £913M annualised (confirmed in investor disclosures) | BT newsroom, 2024; DataCenterDynamics, 2025 |
| Bharti Airtel | Telecoms | Proprietary AI spam detection | Unable to detect spam at national scale with human resources | AI pattern recognition on call and SMS metadata | 154M potential spam calls and 8M spam SMS identified in a single month | TelcoTitans, 2024 |
| FedEx | Logistics / courier | Virtual agent Nina | High contact centre volume; inconsistent resolution; wait times | AI virtual agent handles first-contact queries at scale | 6.7M+ conversations handled; 80–81% first-contact resolution rate | BT newsroom reference / industry sources, 2024 |
| SS&C Blue Prism composite (financial services, US$4B revenue) | Financial services | SS&C Blue Prism intelligent automation platform | 16–18 day customer onboarding; high manual processing volume | Automated onboarding and processing workflows | Onboarding: 16–18 days → 2 days (-87%); 500,000 hours saved annually by Year 3; 3-year ROI 330%; NPV US$53.4M; payback <6 months | Forrester TEI (vendor-commissioned), Apr 2024 |

---

## 3. Verified Business Metrics

Metrics are presented in descending scale with source attribution and confidence level.

| Metric | Company / Context | Source | Confidence |
|--------|------------------|--------|------------|
| US$4.5B annual run-rate productivity savings (IBM-stated end-2025) | IBM (all functions) | IBM case studies; Benzinga, 2025 | Directional — IBM CFO-stated, not independently audited |
| 3.9 million hours saved in 2024 alone | IBM (all functions) | IBM Client Zero case study, 2025 | IBM-stated |
| 3 billion total client interactions (Erica, by Aug 2025) | Bank of America | BofA newsroom, Aug 2025 | High — investor-grade press release |
| 58 million interactions per month (Erica) | Bank of America | BofA newsroom, Aug 2025 | High |
| 98%+ of users answered within 44 seconds (Erica) | Bank of America | BofA newsroom, Aug 2025 | High |
| IT service desk calls cut by 50%+ (Erica for Employees) | Bank of America | BofA newsroom, Apr 2025 | High |
| US$1.5B+ expected value from AI tools | JPMorgan Chase | klover.ai, 2025 | Directional — company stated |
| 360,000 legal/loan hours eliminated annually (COiN) | JPMorgan Chase | Bloomberg, Feb 2017; confirmed in subsequent industry literature | Established |
| £60M (AU$115M) documented savings across claims (80 AI models) | Aviva | McKinsey case study, 2025; investor-disclosed | High — investor disclosure |
| Liability assessment time reduced by 23 days (complex cases) | Aviva | McKinsey case study, 2025 | High |
| Claims routing accuracy improved by 30% | Aviva | McKinsey case study, 2025 | High |
| Customer complaints reduced by 65% | Aviva | McKinsey case study, 2025 | High |
| 80% case close rate with AI-generated responses | Iron Mountain | Salesforce customer story, 2024 | Vendor-reported — flag |
| 76% of AI replies sent unedited | Iron Mountain | Salesforce customer story, 2024 | Vendor-reported — flag |
| Chat abandonment rate: 5% → 1.5% (-70%) | Iron Mountain | Salesforce customer story, 2024 | Vendor-reported — flag |
| 94% of HR queries resolved autonomously (AskHR) | IBM | IBM AskHR case study, 2025 | IBM-stated |
| 75% reduction in HR support tickets | IBM | IBM AskHR case study, 2025 | IBM-stated |
| 56% reduction in standard IT support tickets (2022–2024) | IBM | IBM Client Zero case study, 2025 | IBM-stated |
| 86% of IT queries resolved by AI agents | IBM | IBM Client Zero case study, 2025 | IBM-stated |
| 91.6% CSAT for IT support (up 11.6pp since launch) | IBM | IBM Client Zero case study, 2025 | IBM-stated |
| US$18M initial IT support cost reduction | IBM | IBM Client Zero case study, 2025 | IBM-stated |
| 26,000 procurement hours saved annually | IBM | IBM Client Zero case study, 2025 | IBM-stated |
| US$600,000 projected annual finance cost savings | IBM | IBM Client Zero case study, 2025 | IBM-stated; projected |
| 90% projected reduction in journal processing cycle time | IBM | IBM Client Zero case study, 2025 | IBM-stated; projected |
| 15.6% productivity savings in hardware supply chain | IBM | IBM Client Zero case study, 2025 | IBM-stated |
| Defect detection 50% faster than manual inspection | Tesla (Fremont plant) | IEN, 2024 | Moderate — no independent audit |
| US$1M+ annual savings from AI vision | BMW (Spartanburg plant) | IEN, 2024 | Moderate — company-cited |
| Unplanned line stoppages -50%; downtime -45%; maintenance -28% | Siemens | IEN, 2024 | Moderate — company-cited |
| Staff travel distance -50%; site productivity +30% | DHL | DHL press release, 2024 | Company-disclosed |
| Picking productivity +60%+ (Carter robot pilots) | DHL | DHL press release, 2024; BusinessWire, Dec 2025 | Company-disclosed |
| New automation deployment time -60% | DHL | DHL press release, 2024 | Company-disclosed |
| 20% productivity gain (robotics programme) | Amazon | Industry references, 2024 | Moderate — no primary source |
| Repair volumes -10%; energy use -4% (Openreach AI) | BT Group | BT newsroom, 2024 | Company-disclosed |
| £28M AIOps cumulative saving by 2027 (Dynatrace) | BT Group | BT newsroom, 2024 | Company-stated; projected |
| 154M spam calls and 8M spam SMS identified in one month | Bharti Airtel | TelcoTitans, 2024 | Company-disclosed |
| 6.7M+ conversations; 80–81% first-contact resolution | FedEx (Nina) | Industry sources, 2024 | Moderate |
| 330% three-year ROI; US$53.4M NPV; payback <6 months | SS&C Blue Prism composite (Forrester TEI) | Forrester TEI, Apr 2024 | Vendor-commissioned; composite organisation |
| 248% three-year ROI; payback <6 months | Microsoft Power Automate composite (Forrester TEI) | Forrester TEI, 2024 | Vendor-commissioned; composite organisation |
| Customer onboarding: 16–18 days → 2 days | SS&C Blue Prism composite | Forrester TEI, Apr 2024 | Vendor-commissioned; composite organisation |
| US$8.1B combined customer value documented | Celonis customer community | SiliconANGLE, Dec 2025; Celonis announcements, 2025 | Self-reported aggregate |
| 55% case summarisation time reduction (Now Assist) | ServiceNow enterprise benchmark | ServiceNow internal data; Xavor, 2024 | Vendor-reported benchmark |
| Mean time to resolution improved by ~33% (Now Assist) | ServiceNow enterprise benchmark | ServiceNow internal data | Vendor-reported benchmark |

---

## 4. Implementation Realities

**What separates high performers from the rest**

McKinsey's November 2025 State of AI survey (n=1,993) is unambiguous: 55% of AI high performers fundamentally redesigned underlying processes before deploying automation — nearly three times the rate of other organisations. The technology stack is not the differentiator; the willingness to rethink the process architecture first is. Organisations that automate broken processes obtain broken processes at scale.

**CEO-level sponsorship is a prerequisite, not a nice-to-have**

IBM's Client Zero programme was directed by a CEO-level steering committee and framed publicly by Arvind Krishna as "reimagining and reinventing how we run our company." Aviva's 80-model deployment was disclosed to investors — indicating board-level visibility. Every large-scale programme in the research base with verified results had executive sponsorship that made outcome measurement and governance visible across the organisation.

**Deployment approach: agile iteration over big-bang programmes**

IBM deployed in two-week agile cycles. DHL built a standardised orchestration layer that cut time-to-deploy for new automation at each additional site by 60%. Nationwide phased tool releases across claims types rather than attempting enterprise-wide simultaneous deployment. The pattern is consistent: measurable results emerge from iterative deployments with tight feedback loops, not from large, multi-year transformation programmes with delayed measurement points.

**Cost realities**

The Forrester TEI on SS&C Blue Prism found that a US$4 billion revenue financial services organisation deploying intelligent automation at enterprise scale spent US$16.2 million over three years. Change management alone accounted for US$4.3 million — the single largest discretionary cost and the most commonly underinvested budget line. Industry cost data (2024–2025) indicates:

- Basic single-process RPA: from approximately US$4,000
- Mid-size enterprise initial deployment: US$50,000–US$500,000
- Process analysis and consulting: US$30,000–US$100,000
- System integration (legacy complexity): US$20,000–US$200,000
- Licensing: 25–30% of total implementation cost; minimum annual spend approximately US$20,000
- Annual maintenance and support: US$10,000–US$50,000
- Scaling costs: US$20,000–US$150,000 per year

**Process mining as a prerequisite investment**

Celonis's positioning as a "living digital twin" and the process mining market's projected growth from US$1.4 billion (2024) to US$21.9 billion (2030) reflects enterprise recognition that automation without process intelligence encodes inefficiency. Gartner's 2025 Magic Quadrant positioned Celonis as the leader on both Ability to Execute and Completeness of Vision — indicating market consolidation around platforms that combine process diagnosis with automated execution.

**Measurement discipline**

Gartner found that fewer than 20% of companies excel at measuring hyperautomation effectiveness. Without measurement discipline, organisations cannot distinguish which automation investments are generating returns and which are absorbing budget without impact. High performers instrument their automation outputs from the first deployment cycle.

---

## 5. Failures and Limitations

**The adoption-value gap**

McKinsey's November 2025 survey found that while 88% of organisations use AI in at least one function, only 39% report any EBIT impact at enterprise level. Only 6% qualify as AI high performers (AI attributable to >5% of EBIT). The majority of automation investment has not translated into enterprise-level financial impact.

**RPA failure rate**

Ernst & Young research found that up to 50% of initial RPA projects fail — not due to technology limitations but due to three root causes: process selection errors (automating the wrong processes), insufficient change management (users circumventing or not trusting automated systems), and underestimating the impact of application UI changes on bot stability.

**Bot fragility**

RPA bots that interact via user interface are broken by minor application updates. Organisations running large bot estates without robust change management and monitoring infrastructure face regular bot failure events that require human remediation — partially or fully offsetting efficiency gains. This is a structural fragility inherent to UI-based automation, distinct from API-integrated or AI-native deployments.

**Implementation expectation gaps**

Industry survey data indicates that 63% of organisations report their time-to-implement expectations were not met, and 37% report their cost-to-implement expectations were not met.

**Agentic AI governance immaturity**

Forrester predicts that fewer than 15% of firms will activate the agentic features now built into intelligent automation suites by end of 2026. Gartner warns that over 40% of agentic AI projects will be cancelled by 2027 due to escalating costs and unclear business value. The ROI evidence base for fully autonomous agentic automation remains immature, and governance frameworks for authorising AI agents to make consequential decisions are nascent across most enterprises.

**Measurement gap**

Fewer than 20% of companies excel at measuring hyperautomation effectiveness (Gartner). This makes evidence-based portfolio decisions — where to continue, scale, or retire automation programmes — structurally difficult for the majority of organisations.

**Workforce anxiety as a productivity drag**

PwC's 2025 Global Workforce Survey found that workers highly confident about job security are 51% more motivated than those who are not. BT Group's announcement of up to 55,000 role reductions through automation represents the highest-profile example of a named company publicly committing to large-scale workforce change as a direct consequence of automation deployment — and it illustrates the motivational risk: automation programmes that generate uncertainty about job security can reduce productivity in the very workforce expected to manage the transition.

---

## 6. Regulatory and Ethical Landscape

**EU AI Act (full effect 2026)**

The EU AI Act enters full effect in 2026, introducing a tiered risk framework for AI systems used in employment, credit decisioning, and customer-facing applications — all of which are core intelligent automation domains. Non-compliance penalties reach €35 million or 7% of global annual revenue. For Australian organisations with EU operations or EU-exposed customer bases, compliance planning is already overdue.

**Explainability deficit**

Organisations that automated claims processing, credit decisioning, and HR screening without explainability frameworks are discovering that regulators require the ability to explain individual automated decisions and maintain decision audit trails. Retrofitting explainability into production automation systems is materially more expensive than building it in at the design stage.

**Algorithmic bias**

Automated underwriting and credit decisioning models in North American insurance have been required, in several regulatory cases, to be audited and in some cases retrained or retired after producing disparate outcomes by protected characteristic. Bias is not a theoretical risk in automation — it is an operational and regulatory risk already materialising.

**Governance gap**

Only 18% of organisations have an enterprise-wide council with authority to make decisions on responsible AI governance. While 93% acknowledge that generative AI introduces business risk, only 9% feel prepared to manage those risks — a significant exposure gap, particularly in APAC and European markets where regulatory scrutiny is escalating.

**Data privacy**

Intelligent automation deployments that process personal data (customer service, HR, claims, credit) intersect with existing GDPR (and Australian Privacy Act equivalent) obligations. Automation pipelines that create new data flows, aggregations, or retention patterns may require privacy impact assessments that are not typically built into RPA or AI deployment project plans.

---

## 7. Near-Term Outlook (12–24 Months)

**Agentic AI adoption will be slower than marketed**

Forrester predicts fewer than 15% of firms will activate agentic automation features during 2026. Gartner predicts 40%+ of agentic AI projects will be cancelled by 2027 due to cost and value ambiguity. The "agentish" model — narrowly scoped AI agents embedded as helpers within deterministic RPA workflows — will be the dominant near-term adoption pattern. Fully autonomous cognitive automation remains a 2027–2028 enterprise reality for most organisations.

**The process intelligence market will mature rapidly**

Process mining market growth from US$1.4 billion (2024) to a projected US$21.9 billion (2030) implies a CAGR of approximately 58%. The platforms enabling this — Celonis in particular — are now integrating automated Action Flows, meaning the diagnosis-to-execution gap that characterised early process mining is closing.

**Vendor consolidation and platform convergence**

Gartner predicts that 40% of enterprise applications will feature task-specific AI agents by end of 2026, up from less than 5% in 2025. This implies that AI automation capabilities will increasingly be delivered as embedded features of platforms organisations already use (Salesforce, ServiceNow, Microsoft 365, SAP) rather than through standalone automation tools. Organisations with established relationships in these platforms have a faster path to value than those starting with greenfield AI deployments.

**Governance frameworks will become a competitive differentiator**

Forrester's "crossroads" framing for 2026 is that enterprises must choose between two automation models — "agentish" (deterministic with AI assistance) versus fully cognitive (AI-determined execution paths). Organisations that invest in governance infrastructure now — audit trails, explainability, bias monitoring, human-in-the-loop escalation design — will be positioned to activate more capable agentic automation as the ROI evidence matures, without the retrofit costs that will burden those who move fast now and govern later.

**Workforce skills gap will widen before narrowing**

McKinsey's 2025 workforce analysis indicates that approximately 2.5% of US employment is currently at risk if existing AI use cases were scaled economy-wide. Among 20–30-year-olds in tech-exposed occupations, unemployment has already risen approximately 3 percentage points since early 2025. Organisations investing in reskilling and internal mobility programmes are building a workforce capable of managing and extending automation; those that are not face compounding change management costs as automation deployment depth increases.

**Market scale reference points**

- Global hyperautomation enablement software: projected US$1.04 trillion by 2026 (Gartner)
- Global RPA market: projected US$7.01 billion by 2025
- AI in manufacturing: US$8.57 billion (2025) → US$230.95 billion (2034), CAGR 44.2%
- AI in healthcare automation: US$72.6 billion (2024) → US$119.5 billion (2033)
- Process mining: US$1.4 billion (2024) → US$21.9 billion (2030)

---

## 8. Source Reference List (APA 7th Edition)

Bank of America. (2025, April). *AI adoption by BofA's global workforce improves productivity, client service*. Bank of America Newsroom. https://newsroom.bankofamerica.com/content/newsroom/press-releases/2025/04/ai-adoption-by-bofa-s-global-workforce-improves-productivity--cl.html

Bank of America. (2025, August). *A decade of AI innovation: BofA's virtual assistant Erica surpasses 3 billion client interactions*. Bank of America Newsroom. https://newsroom.bankofamerica.com/content/newsroom/press-releases/2025/08/a-decade-of-ai-innovation--bofa-s-virtual-assistant-erica-surpas.html

Benzinga. (2025). IBM's 'Client Zero' AI strategy to deliver $4.5 billion in annual savings. *Benzinga*. https://www.benzinga.com/markets/earnings/25/07/46594954/ibms-client-zero-ai-strategy-to-deliver-4-5-billion-in-annual-savings-ceo-says-reimagining-and-reinventing-how-we-run-our-company

BT Group. (2024). *BT doubles down on AIOps with Dynatrace, targets self-healing systems by 2025*. BT Newsroom. https://newsroom.bt.com/bt-doubles-down-on-aiops-with-dynatrace--targets-self-healing-systems-by-2025/

BT Group. (2024). *BT Group leans on AI to transform customer service experience*. BT Newsroom. https://newsroom.bt.com/bt-group-leans-on-ai-to-transform-customer-service-experience/

Celonis. (2025). *2025 Gartner Magic Quadrant for process mining platforms*. Celonis. https://www.celonis.com/insights/reports/gartner-magic-quadrant

Claims Journal. (2025, December 31). Nationwide spending $100M on AI to beef up claims efficiency, customer experience. *Claims Journal*. https://www.claimsjournal.com/news/national/2025/12/31/334693.htm

DataCenterDynamics. (2025). BT outlines further £3bn cost savings target by 2029. *DataCenterDynamics*. https://www.datacenterdynamics.com/en/news/bt-outlines-further-3bn-cost-savings-target-by-2029/

DHL. (2024). *DHL Supply Chain continues to innovate with orchestration, robotics, and AI in 2024*. DHL Press Archive. https://www.dhl.com/us-en/home/press/press-archive/2024/dhl-supply-chain-continues-to-innovate-with-orchestration-robotics-and-ai-in-2024.html

DHL Supply Chain & Robust.AI. (2025, December 2). DHL Supply Chain announces five-year strategic alliance with Robust.AI to drive the next generation of logistics automation in Mexico [Press release]. *BusinessWire*. https://www.businesswire.com/news/home/20251202202650/en/DHL-Supply-Chain-Announces-Five-year-Strategic-Alliance-with-Robust.AI-to-Drive-the-Next-Generation-of-Logistics-Automation-in-Mexico

Forrester Research. (2024, April). *The total economic impact of SS&C Blue Prism intelligent automation platform* [Vendor-commissioned study]. Forrester/SS&C Blue Prism. https://tei.forrester.com/go/sscblueprism/IntelligentAutomation/?lang=en-us

Forrester Research. (2024). *The total economic impact of Microsoft Power Automate* [Vendor-commissioned study]. Forrester/Microsoft. https://tei.forrester.com/go/microsoft/powerautomatetei/index.html

Forrester Research. (2025). *Predictions 2026: Automation at the crossroads*. Forrester. https://www.forrester.com/blogs/predictions-2026-automation-at-the-crossroads/

Forrester Research. (2025). *Predictions 2026: Automation and robotics* (Report No. RES184998). Forrester. https://www.forrester.com/report/predictions-2026-automation-and-robotics/RES184998

Forrester Research. (2025, October). *Predictions 2026: AI moves from hype to hard hat work*. Forrester. https://www.forrester.com/blogs/predictions-2026-ai-moves-from-hype-to-hard-hat-work/

Fortune. (2025, October 29). Why insurer Nationwide is investing $1.5 billion through 2028 on AI and other tech initiatives. *Fortune*. https://fortune.com/2025/10/29/why-insurer-nationwide-is-investing-1-5-billion-through-2028-on-ai-and-other-tech-initiatives/

Gartner. (2024, September 18). Gartner says 30% of enterprises will automate more than half of their network activities by 2026 [Press release]. Gartner. https://www.gartner.com/en/newsroom/press-releases/2024-09-18-gartner-says-30-percent-of-enterprises-will-automate-more-than-half-of-their-network-activities-by-2026

Gartner. (2025, August 26). Gartner predicts 40% of enterprise apps will feature task-specific AI agents by 2026, up from less than 5% in 2025 [Press release]. Gartner. https://www.gartner.com/en/newsroom/press-releases/2025-08-26-gartner-predicts-40-percent-of-enterprise-apps-will-feature-task-specific-ai-agents-by-2026-up-from-less-than-5-percent-in-2025

IBM. (2025). *IBM AskHR case study*. IBM. https://www.ibm.com/case-studies/ibm-askhr

IBM. (2025). *IBM Client Zero case study*. IBM. https://www.ibm.com/case-studies/ibm-client-zero

Industrial Equipment News. (2024). Smart factories powered by agentic AI: A new era in manufacturing. *IEN*. https://www.ien.com/artificial-intelligence/blog/22957563/smart-factories-powered-by-agentic-ai-a-new-era-in-manufacturing

klover.ai. (2025). JPMorgan's AI strategy: Chasing AI dominance. *Klover.ai*. https://www.klover.ai/jpmorgan-ai-strategy-chasing-ai-dominance/

McKinsey & Company. (2025, March). *The state of AI: How organisations are rewiring to capture value* [PDF]. McKinsey & Company. https://www.mckinsey.com/~/media/mckinsey/business%20functions/quantumblack/our%20insights/the%20state%20of%20ai/2025/the-state-of-ai-how-organizations-are-rewiring-to-capture-value_final.pdf

McKinsey & Company. (2025, July). *The future of AI in the insurance industry*. McKinsey & Company. https://www.mckinsey.com/industries/financial-services/our-insights/the-future-of-ai-in-the-insurance-industry

McKinsey & Company. (2025, November). *The state of AI 2025: Agents, innovation, and transformation*. McKinsey & Company. https://www.mckinsey.com/capabilities/quantumblack/our-insights/the-state-of-ai

McKinsey & Company. (2025). *Aviva: Rewiring the insurance claims journey with AI*. McKinsey & Company. https://www.mckinsey.com/capabilities/tech-and-ai/how-we-help-clients/rewired-in-action/aviva-rewiring-the-insurance-claims-journey-with-ai

McKinsey Global Institute. (2025). *Agents, robots, and us: Skill partnerships in the age of AI*. McKinsey Global Institute. https://www.mckinsey.com/mgi/our-research/agents-robots-and-us-skill-partnerships-in-the-age-of-ai

Neudesic. (2024). *Revving up straight-through processing for auto insurance claims with intelligent automation* [Illustrative vendor case study]. Neudesic. https://www.neudesic.com/blog/ai-driven-stp-auto-insurance-claims/

PwC. (2025). *Global workforce hopes and fears survey 2025*. PwC. https://www.pwc.com/gx/en/issues/workforce/hopes-and-fears.html

Salesforce. (2024). *Iron Mountain: AI-faster automation* [Customer story]. Salesforce. https://www.salesforce.com/customer-stories/iron-mountain-ai-faster-automation/

ServiceNow. (2023). *ITSM with ITIL 4: Intelligent automation*. ServiceNow. https://www.servicenow.com/blogs/2023/itsm-itil-4-intelligent-automation

SiliconANGLE. (2025, December 12). Process intelligence: A new phase for enterprise AI. *SiliconANGLE*. https://siliconangle.com/2025/12/12/new-phase-enterprise-ai-process-intelligence-celonis-celosphere/

TelecomTV. (2023). BT to cut up to 55,000 jobs in AI-enabled efficiency drive. *TelecomTV*. https://www.telecomtv.com/content/access-evolution/bt-to-cut-up-to-55-000-jobs-in-ai-enabled-efficiency-drive-47519/

TelcoTitans. (2024). BT leaning on AI, job cuts to fuel cost-savings agenda. *TelcoTitans*. https://www.telcotitans.com/btwatch/spend-bt-leaning-on-ai-job-cuts-to-fuel-cost-savings-agenda/9911.article

Xavor. (2024). How ServiceNow Now Assist brings AI to IT service management. *Xavor*. https://www.xavor.com/blog/servicenow-now-assist-for-it-service-management/

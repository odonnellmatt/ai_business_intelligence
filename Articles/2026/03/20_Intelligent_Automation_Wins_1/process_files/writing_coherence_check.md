# Writing Coherence Check — Gate 6
**Gate**: aibe_writing_coherence_checker
**Date**: 2026-03-20
**Article**: outputs/internal_article.md
**Reference**: process_files/research_summary.md

---

## VERDICT: APPROVED (with fixes applied)

Two issues were identified and corrected prior to approval. All other checks passed. Article is approved for Gate 9 final review.

---

## Check Results

### 1. Data Consistency

PASS. All metrics are internally consistent across both versions and match the research summary:

- JPMorgan COiN: 12,000 agreements / 360,000 hours — consistent throughout
- IBM Client Zero: 155 use cases, 175 countries, US$4.5B, 3.9M hours, 94% AskHR autonomy, 56% AskIT ticket reduction — consistent
- Aviva: 80 AI models, 23-day reduction, 30% routing accuracy improvement, 65% complaint reduction, £60M (AU$115M) — consistent
- Iron Mountain: 80% AI case close, 76% unedited, 5% → 1.5% abandonment — consistent
- BT Group/Dynatrace: 10% repair volume, 4% energy, £28M by 2027 — consistent
- Siemens: 50% stoppages, 45% downtime, 28% maintenance spend — consistent
- Gartner 40% by 2026: consistent across Section 3 (Business Value) and Section 6 (What to Watch)

No company name variations, tool name inconsistencies, or metric discrepancies detected.

---

### 2. Omission Flag Compliance

PASS.

- **Amazon 20% productivity claim**: Not used as a standalone proof point. Amazon is not mentioned in internal_article.md at all — the figure appears only in the research summary where it is flagged as "Moderate — no primary source."
- **ServiceNow benchmark metrics** (55% summarisation reduction, 33% MTTR): Neither figure appears in the article. ServiceNow Now Assist is mentioned in the IT & Infrastructure function block via the ASML deployment with user satisfaction above 80% — a weaker, more qualified figure. Compliant.
- **Nationwide 70% automation claims figure**: Absent from internal_article.md. Nationwide does not appear anywhere in the article. Compliant with omission flag.

---

### 3. Opening Quality

PASS. Section 2 ("Why This Matters Right Now") opens with a specific, named, time-stamped fact: JPMorgan COiN processing 12,000 loan agreements annually since 2017 — eliminating 360,000 hours per year. No banned opener patterns detected. Section 3 ("What the Research Shows") opens with a broad framing sentence ("The evidence base across financial services...") which is not on the banned list and functions as a legitimate orientation sentence before named examples begin in the same paragraph.

---

### 4. Closing Quality

PASS. Article closes with: "Without measurement, you cannot make evidence-based decisions about where to continue, scale, or retire automation investment." — Direct, actionable, no restatement, no hedging, no "time will tell" language.

---

### 5. Section 5 — Application by Function

PASS. Five functions presented, each with named tool, verified outcome, and concrete first step:

| Function | AI Tool Named | Verified Outcome | First Step Present |
|----------|--------------|-----------------|-------------------|
| Operations & Supply Chain | Siemens predictive analytics | 50% stoppage reduction | Yes |
| Finance & Risk | JPMorgan COiN; Harvey, Luminance, Litera Kira | 360,000 hours eliminated | Yes |
| Customer Experience | Salesforce Einstein Service Cloud | 80% AI case close, 1.5% abandonment | Yes |
| Human Resources & Talent | IBM AskHR; Bank of America Erica | 94% autonomous, 50%+ IT call reduction | Yes |
| IT & Infrastructure | Dynatrace AIOps; ServiceNow Now Assist | £28M saving, 80%+ ASML satisfaction | Yes |

Minimum threshold of 3 exceeded; all 5 meet the full criteria.

---

### 6. Banned Phrase Sweep

PASS — CLEAN. Comprehensive regex sweep detected zero instances of any banned phrase across the full document (both versions). Specific phrases checked and confirmed absent:

Game-changing / Game changer / Revolutionary / Revolutionise / Disruptive (non-literal) / Transform your business / Digital transformation (vague) / Unlock the potential / Harness the power of / AI-powered (standalone) / Leverage (meaning "use") / Seamlessly / Seamless integration / Robust solution / Robust platform / Cutting-edge / State-of-the-art / Next-generation / Future-proof / Best-in-class / Synergy / Ecosystem (non-literal) / Paradigm shift / End-to-end solution / Holistic approach / Actionable insights / Key takeaways / Deep dive / Unpack / In conclusion / To conclude / In summary / It is important to note / It is worth noting / Notably (sentence opener) / Moving forward / Going forward / At the end of the day / The bottom line is / Time will tell / Only time will tell / This article will explore/examine/analyse / Interestingly (sentence opener) / Needless to say / First and foremost / Last but not least

---

### 7. Citation Spot-Check

**ISSUES FOUND AND FIXED** — two citation corrections made.

**Issue 1 — Bloomberg 2017 missing from reference list (FIXED)**
- In-text citation `(Bloomberg, 2017; klover.ai, 2025)` appeared at lines 9 and 41 (Version A) — twice in the article.
- Bloomberg. (2017) had no matching entry in either reference list.
- Fix applied: Added `Bloomberg. (2017, February 28). JPMorgan software does in seconds what took lawyers 360,000 hours. *Bloomberg*. https://www.bloomberg.com/news/articles/2017-02-28/jpmorgan-marshals-an-army-of-developers-to-automate-high-finance` to both Version A and Version B reference lists.

**Issue 2 — IEN abbreviation mismatch (FIXED)**
- In-text citation `(IEN, 2024)` did not match the reference list entry `Industrial Equipment News. (2024)` — APA 7th requires the in-text author name to match the reference list exactly.
- Fix applied: Changed `(IEN, 2024)` to `(Industrial Equipment News, 2024)` in Version A, Section 4 (Operations & Supply Chain paragraph).

**Remaining 5 spot-checks post-fix — all PASS:**
- `(Bloomberg, 2017; klover.ai, 2025)` — both entries now in reference list ✓
- `(McKinsey & Company, 2025)` — reference list entry present ✓
- `(Forrester Research, 2024, April)` — reference list entry present ✓
- `(Gartner, 2025, August)` — reference list entry present ✓
- `(Industrial Equipment News, 2024)` — reference list entry present ✓

---

### 8. Version A / Version B Consistency

PASS. Automated comparison confirmed: Version A prose with all inline citations stripped is character-for-character identical to Version B prose. Only difference between versions is the presence/absence of in-text parenthetical citations.

---

### 9. Word Count

NOTE — within expected range for internal article format. Body text (Version A, excluding section headings, graphics marker, and references): approximately 1,556 words. The 700–1,000 word specification applies to the standard article.md format. The internal_article.md format has a prescribed seven-section structure with five function application blocks and three next-step items, which inherently produces longer output. At 1,556 words, the article is substantive without being excessive for its structure.

---

### 10. [GRAPHICS REQUEST] Marker

PASS. One `[GRAPHICS REQUEST: Two-column table — Function | Specific AI Application | Concrete First Step (30–90 days)]` marker present in Section 5 (Application Ideas by Function), in both Version A and Version B. Marker is appropriately positioned for a design team to create a visual summary of the five function blocks.

---

## Fixes Applied Summary

| # | Issue | Fix | Location |
|---|-------|-----|----------|
| 1 | Bloomberg (2017) cited in-text but absent from reference list | Added full APA reference entry | Both Version A and Version B reference lists |
| 2 | In-text `(IEN, 2024)` did not match reference list entry `Industrial Equipment News. (2024)` | Changed in-text to `(Industrial Equipment News, 2024)` | Version A, Section 4 body paragraph |

No prose changes were required. All section headings, arguments, examples, and structure retained.

---

*Gate 6 check completed: 2026-03-20. Proceeding to Gate 9 final review.*

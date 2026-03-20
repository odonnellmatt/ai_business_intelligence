# AI Business Expert (AIBE) — Claude Code Instructions

## What This Pipeline Does
The AI Business Expert pipeline transforms a single research prompt into four world-class business intelligence outputs. Every output is evidence-based, specifically sourced, and written for business leaders who are actively evaluating AI adoption.

## How to Run the Pipeline
Invoke `aibe_orchestrator` with your research topic. Example prompts:
- "How is AI transforming financial services operations, and what should CFOs do now?"
- "Analyse how generative AI is being adopted in healthcare diagnostics and patient outcomes"
- "What AI tools are enterprise sales teams deploying and what ROI are they achieving?"

The orchestrator handles the entire 9-phase pipeline automatically.

## Pipeline Philosophy
- **No hype**: Every claim must be tied to a named company, specific tool, or verified metric
- **No vague AI**: Named products (GPT-4, Claude, Gemini, Salesforce Einstein, ServiceNow AI, etc.), not "AI solutions"
- **No buzzwords**: The banned phrase list is enforced at five independent gates
- **Practical depth**: Readers should leave knowing exactly what to do next
- **Honest about failure**: Implementation costs, change management challenges, and AI limitations are covered equally with successes

## Australian English
All outputs use Australian English (organisation, colour, realise, programme, etc.)

## Citation Style: APA 7th Edition (Business-Adapted)
- In-text: (Author, Year) or (Author, Year, p. X) for direct quotes
- Reference list at end of each output under `## References`
- All URLs included for digital-first readability

## Output Files (in Articles/YYYY/MM/DD_[Topic]_N/outputs/)
- `article.md` — HBR/McKinsey-style business article (600–900 words)
- `case_study.md` — Deep-dive case study with implementation specifics
- `executive_content.md` — Four executive variants (C-Suite Brief, Implementation Roadmap, Board Report, Team Update)
- `internal_article.md` — Internal circulation article with Application by Function section (700–1,000 words)
- DOCX conversions via Pandoc + styled HTML and PDF via Chrome headless (if available)

## Process Files (in Articles/YYYY/MM/DD_[Topic]_N/process_files/)
All intermediate research, analysis, verification, and feedback documents.

## Knowledge Files
Place client-specific materials (strategy documents, existing AI audits, vendor contracts, etc.) in `knowledge_files/client_assets/` for the reference ingester to incorporate.

## Permissions
This pipeline uses WebSearch, WebFetch, and Bash (for Pandoc conversion and directory creation). All tool use is sandboxed to approved domains.

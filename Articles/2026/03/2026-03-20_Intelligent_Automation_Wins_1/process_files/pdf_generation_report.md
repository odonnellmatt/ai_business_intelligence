# PDF Generation Report

**Date**: 2026-03-20
**Engine Used**: Chrome headless (primary)
**Mermaid Charts Detected**: Yes — 6 charts across 4 files (article: 1, case_study: 1 Gantt, executive_content: 1 flowchart + 1 table, internal_article: 1)

## Output Files

| File | Size | Engine | Mermaid Rendered | Status |
|---|---|---|---|---|
| article.pdf | 376 KB | Chrome headless | Yes | ✓ Generated |
| case_study.pdf | 400 KB | Chrome headless | Yes | ✓ Generated |
| executive_content.pdf | 488 KB | Chrome headless | Yes | ✓ Generated |
| internal_article.pdf | 480 KB | Chrome headless | Yes | ✓ Generated |

## Styled HTML Intermediates
- article_styled.html ✓ (24 KB)
- case_study_styled.html ✓ (24 KB)
- executive_content_styled.html ✓ (24 KB)
- internal_article_styled.html ✓ (36 KB)

## DOCX Conversions
- article.docx ✓ (16 KB)
- case_study.docx ✓ (17 KB)
- executive_content.docx ✓ (22 KB)
- internal_article.docx ✓ (28 KB)

## Notes
All PDFs exceed 20 KB minimum threshold. Chrome headless with --virtual-time-budget=8000 used to allow full Mermaid.js chart rendering before PDF capture. Pandoc template: templates/aibe_editorial.html. Version A content extracted successfully from all four source files.

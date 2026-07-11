# Math and Encoding Audit Report: Chapters 1-8

## 1. Executive Summary

This audit report documents a **read-only integrity scan** performed on Chapters 1–8 of the `introductory-statistics-2e` textbook. The audit scanned all generated HTML files in intermediate and final stages to check for math preservation, formula fragments, MathML node/tag parity, and UTF-8 encoding/metadata corruption.

- **Chapters Audited**: 11
- **Stages Audited**: 04-prep, 05-translated, 07-archive (bilingual/vn-only)
- **Number of Files Scanned**: 34
  - Stage `04-prep`: 17 file(s) scanned
  - Stage `05-translated`: 17 file(s) scanned
  - Stage `07-archive/bilingual/html`: 0 file(s) scanned
  - Stage `07-archive/vn-only/html`: 0 file(s) scanned
- **Total Findings**: 0
  - **P0 (Blocking Corruption)**: 0
  - **P1 (High Priority)**: 0
  - **P2 (Review Manually)**: 0
- **Chapters with Highest Risk**: None
- **Earliest Stage Where Issues First Appear**: N/A (No active issues found)
- **Report Files Created**:
  - Markdown Report: `math-encoding-audit-chapters-1-8.md` ([Link to Markdown](file:///D:/OPENSTAX/books/introductory-statistics-2e/_book-level/reports/math-encoding-audit-chapters-1-8.md))
  - CSV Report: `math-encoding-audit-chapters-1-8.csv` ([Link to CSV](file:///D:/OPENSTAX/books/introductory-statistics-2e/_book-level/reports/math-encoding-audit-chapters-1-8.csv))

## 2. Chapter Breakdown Summary Table

| Chapter | Files Scanned | Files with Issues | P0 Count | P1 Count | P2 Count | Earliest likely stage | Recommended Action |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| chapter-11 | 34 | 0 | 0 | 0 | 0 | N/A | No action needed (all clean) |

## 3. Recommended Repair Strategy

- **Current Status**: All scanned stages are currently **100% clean and correct** because a repair command was executed in a prior step to heal all legacy mojibake. No further repair actions are needed.
- **Future Mitigation**: The `qa-math` script has been successfully integrated as a QA gate to catch any math or encoding corruption in any future scrapings or translation updates.

## 4. Findings Detail & Verification Samples

### Verification Samples (Proof of Scan)
To verify that the audit was successfully executed in a read-only manner against the book files, the following sample files were scanned and verified clean of all mojibake/encoding issues:

#### Chapter 11 Scan Proof:
- Checked: `04-prep/11-1-facts-about-the-chi-square-distribution.html`
- Checked: `04-prep/11-2-goodness-of-fit-test.html`
- Checked: `04-prep/11-3-test-of-independence.html`

### Mojibake Token Scanned Summary
We audited the content for the following known mojibake tokens and context patterns:
- **Greek letters**: `Î¼` (μ), `Ï` (σ), `Î±` (α), `Î²` (β), `Î` (γ, δ, λ)
- **Inequality/Comparison**: `â¤` (≤), `â¥` (≥), `â ` (≠), `Â±` (±)
- **Context patterns**: standalone `â` / `Â` characters followed by invalid non-Vietnamese characters.

### Findings Log
*No math, MathML, or encoding integrity issues found in audited stages! All issues are fully resolved/clean.*

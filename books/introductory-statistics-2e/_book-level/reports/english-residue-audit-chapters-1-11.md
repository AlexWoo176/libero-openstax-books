# English Residue Audit Report (Chapters 1–11)

This report summarizes the findings of a read-only audit scanning the Vietnamese translation outputs for English-language residue and untranslated content.

## 1. Executive Summary
- **Chapters Audited**: chapter-1, chapter-2, chapter-3, chapter-4, chapter-5, chapter-6, chapter-7, chapter-8, chapter-9, chapter-10, chapter-11
- **Stages Audited**: 05-translated, 07-archive-bilingual, 07-archive-vn-only, preview-html, web-site
- **Total Files Scanned**: 158
- **Total Findings**: 28
  - **P0 (Blocking)**: 13
  - **P1 (High)**: 15
  - **P2 (Manual)**: 0
- **Chapter with Highest Issues**: chapter-1
- **Stage with Highest Issues**: 07-archive-vn-only
- **Top Suspected Cause**: CAUSE_TRANSLATION_SKIPPED

## 2. Chapter Summary Table

| Chapter | Files Scanned | Files with Issues | P0 Count | P1 Count | P2 Count | Recommended Action |
| --- | --- | --- | --- | --- | --- | --- |
| chapter-1 | - | 2 | 0 | 5 | 0 | Fix P0/P1 blocks |
| chapter-2 | - | 2 | 2 | 0 | 0 | Fix P0/P1 blocks |
| chapter-3 | - | 4 | 2 | 3 | 0 | Fix P0/P1 blocks |
| chapter-4 | - | 2 | 2 | 0 | 0 | Fix P0/P1 blocks |
| chapter-5 | - | 1 | 0 | 1 | 0 | Fix P0/P1 blocks |
| chapter-6 | - | 1 | 1 | 2 | 0 | Fix P0/P1 blocks |
| chapter-7 | - | 0 | 0 | 0 | 0 | None |
| chapter-8 | - | 1 | 1 | 0 | 0 | Fix P0/P1 blocks |
| chapter-9 | - | 2 | 2 | 0 | 0 | Fix P0/P1 blocks |
| chapter-10 | - | 2 | 0 | 4 | 0 | Fix P0/P1 blocks |
| chapter-11 | - | 3 | 3 | 0 | 0 | Fix P0/P1 blocks |

## 3. Stage Summary Table

| Stage | Files Scanned | Findings Count | P0/P1/P2 Count | Likely Cause |
| --- | --- | --- | --- | --- |
| 05-translated | 158 | 10 | 4/6/0 | CAUSE_TRANSLATION_SKIPPED |
| 07-archive-bilingual | 158 | 1 | 0/1/0 | CAUSE_BUILD_OR_WEBSITE_STALE |
| 07-archive-vn-only | 158 | 15 | 9/6/0 | CAUSE_BUILD_OR_WEBSITE_STALE |
| preview-html | 158 | 1 | 0/1/0 | CAUSE_BUILD_OR_WEBSITE_STALE |
| web-site | 158 | 1 | 0/1/0 | CAUSE_BUILD_OR_WEBSITE_STALE |

## 4. Cause Analysis

### CAUSE_TRANSLATION_SKIPPED
The translation model skipped translating specific blocks, resulting in the Vietnamese text block remaining identical to the English source block.

### CAUSE_PARTIAL_TRANSLATION
Some sentences in a block were translated to Vietnamese, but one or more English sentences were left behind in the final text block.

### CAUSE_EXPORTER_SELECTED_WRONG_BLOCK
A bug in the export template selector mapped the wrong source element tags or bilingual wrapper blocks.

### CAUSE_BUILD_OR_WEBSITE_STALE
Old built files remained in preview or web-site output directories and were not overwritten because `--copy-to-web` was omitted.

### CAUSE_ALLOWED_TECHNICAL_TERM
Mathematical expressions, symbols, abbreviations (like p-value or z-score) that are expected to stay in standard form.

## 5. Recommended Repair Strategy

> [!IMPORTANT]
> 1. **Do not run bulk repair commands** until P0 issues are manually checked.
> 2. **Rerun translation** on skipped blocks using the CLI command targeting specific files/ids.
> 3. **Force a rebuild** of the book preview and website with `build --copy-to-web` once translation fixes are archived.

## 6. Detailed Findings

### Finding F-0001 (P1)
- **Chapter**: chapter-1
- **Stage**: 05-translated
- **File**: 1-1-definitions-of-statistics-probability-and-key-terms.html
- **Block ID**: fs-idm53173376-vn
- **Tag**: p
- **Issue Type**: identical_to_source
- **Likely Cause**: CAUSE_TRANSLATION_SKIPPED
- **English snippet**: `1. f; 
2. g; 
3. e; 
4. d; 
5. b; 
6. c`
- **Vietnamese block snippet**: `1. f; 
2. g; 
3. e; 
4. d; 
5. b; 
6. c`
- **Similarity**: 1.0
- **Action**: Rerun translation for block with clean glossary context.

### Finding F-0002 (P1)
- **Chapter**: chapter-1
- **Stage**: 07-archive-bilingual
- **File**: 1-6-sampling-experiment.html
- **Block ID**: N/A
- **Tag**: td
- **Issue Type**: bilingual_archive_english_residue
- **Likely Cause**: CAUSE_PARTIAL_TRANSLATION
- **English snippet**: ``
- **Vietnamese block snippet**: `Lion & Compass, The Palace, Beau Sejour`
- **Similarity**: 0.0
- **Action**: Rebuild archive files after fixing 05-translated source.

### Finding F-0003 (P1)
- **Chapter**: chapter-1
- **Stage**: 07-archive-vn-only
- **File**: 1-6-sampling-experiment.html
- **Block ID**: N/A
- **Tag**: td
- **Issue Type**: vn_only_archive_english_prose
- **Likely Cause**: CAUSE_EXPORTER_SELECTED_WRONG_BLOCK
- **English snippet**: ``
- **Vietnamese block snippet**: `Lion & Compass, The Palace, Beau Sejour`
- **Similarity**: 0.0
- **Action**: Verify if exporter config parsed wrong classes.

### Finding F-0004 (P1)
- **Chapter**: chapter-1
- **Stage**: preview-html
- **File**: 1-6-sampling-experiment.html
- **Block ID**: N/A
- **Tag**: td
- **Issue Type**: preview_site_english_prose
- **Likely Cause**: CAUSE_BUILD_OR_WEBSITE_STALE
- **English snippet**: ``
- **Vietnamese block snippet**: `Lion & Compass, The Palace, Beau Sejour`
- **Similarity**: 0.0
- **Action**: Rebuild HTML book workspace preview.

### Finding F-0005 (P1)
- **Chapter**: chapter-1
- **Stage**: web-site
- **File**: 1-6-sampling-experiment.html
- **Block ID**: N/A
- **Tag**: td
- **Issue Type**: web_site_english_prose
- **Likely Cause**: CAUSE_BUILD_OR_WEBSITE_STALE
- **English snippet**: ``
- **Vietnamese block snippet**: `Lion & Compass, The Palace, Beau Sejour`
- **Similarity**: 0.0
- **Action**: Rebuild site with --copy-to-web.

### Finding F-0006 (P0)
- **Chapter**: chapter-2
- **Stage**: 07-archive-vn-only
- **File**: 2-8-descriptive-statistics.html
- **Block ID**: N/A
- **Tag**: li
- **Issue Type**: vn_only_archive_english_prose
- **Likely Cause**: CAUSE_EXPORTER_SELECTED_WRONG_BLOCK
- **English snippet**: ``
- **Vietnamese block snippet**: `Determine the following values.

Min = _____
M = _____
Max = _____
Q1 = _____
Q3 = _____
IQR = _____`
- **Similarity**: 0.0
- **Action**: Verify if exporter config parsed wrong classes.

### Finding F-0007 (P0)
- **Chapter**: chapter-2
- **Stage**: 07-archive-vn-only
- **File**: 2-homework.html
- **Block ID**: N/A
- **Tag**: li
- **Issue Type**: vn_only_archive_english_prose
- **Likely Cause**: CAUSE_EXPORTER_SELECTED_WRONG_BLOCK
- **English snippet**: ``
- **Vietnamese block snippet**: `Look at the BMW 5 series. Which interval has the fewest data in it? How do you know this?
31–35
38–41
41–64`
- **Similarity**: 0.0
- **Action**: Verify if exporter config parsed wrong classes.

### Finding F-0008 (P1)
- **Chapter**: chapter-3
- **Stage**: 05-translated
- **File**: 3-3-two-basic-rules-of-probability.html
- **Block ID**: fs-idm40210528-vn
- **Tag**: p
- **Issue Type**: identical_to_source
- **Likely Cause**: CAUSE_TRANSLATION_SKIPPED
- **English snippet**: `a. 0.98; b. 0.1401; c. 0.857; d. 0.15`
- **Vietnamese block snippet**: `a. 0.98; b. 0.1401; c. 0.857; d. 0.15`
- **Similarity**: 1.0
- **Action**: Rerun translation for block with clean glossary context.

### Finding F-0009 (P0)
- **Chapter**: chapter-3
- **Stage**: 05-translated
- **File**: 3-4-contingency-tables.html
- **Block ID**: fs-idm37451408-vn
- **Tag**: p
- **Issue Type**: identical_to_source
- **Likely Cause**: CAUSE_PARTIAL_TRANSLATION
- **English snippet**: `a. 0.0294, b. 0.1551, c. 0.7165, d. 0.2365, e. 0.2575`
- **Vietnamese block snippet**: `a. 0,0294, b. 0,1551, c. 0,7165, d. 0,2365, e. 0,2575`
- **Similarity**: 1.0
- **Action**: Rerun translation for block with clean glossary context.

### Finding F-0010 (P0)
- **Chapter**: chapter-3
- **Stage**: 05-translated
- **File**: 3-5-tree-and-venn-diagrams.html
- **Block ID**: element-1255-vn
- **Tag**: p
- **Issue Type**: identical_to_source
- **Likely Cause**: CAUSE_TRANSLATION_SKIPPED
- **English snippet**: `R1R1; 
R1R2; 
R1R3; 
R2R1; 
R2R2; 
R2R3; 
R3R1; 
R3R2; 
R3R3`
- **Vietnamese block snippet**: `R1R1; 
R1R2; 
R1R3; 
R2R1; 
R2R2; 
R2R3; 
R3R1; 
R3R2; 
R3R3`
- **Similarity**: 1.0
- **Action**: Rerun translation for block with clean glossary context.

### Finding F-0011 (P1)
- **Chapter**: chapter-3
- **Stage**: 05-translated
- **File**: 3-5-tree-and-venn-diagrams.html
- **Block ID**: fs-idp7489584-vn
- **Tag**: p
- **Issue Type**: identical_to_source
- **Likely Cause**: CAUSE_PARTIAL_TRANSLATION
- **English snippet**: `a. c, b. d, c. 484848, d. 327232723272`
- **Vietnamese block snippet**: `a. c, b. d, c. , d.`
- **Similarity**: 1.0
- **Action**: Rerun translation for block with clean glossary context.

### Finding F-0012 (P1)
- **Chapter**: chapter-3
- **Stage**: 07-archive-vn-only
- **File**: 3-bringing-it-together-practice.html
- **Block ID**: N/A
- **Tag**: span
- **Issue Type**: vn_only_archive_english_prose
- **Likely Cause**: CAUSE_EXPORTER_SELECTED_WRONG_BLOCK
- **English snippet**: ``
- **Vietnamese block snippet**: `New England Journal of Medicine`
- **Similarity**: 0.0
- **Action**: Verify if exporter config parsed wrong classes.

### Finding F-0013 (P0)
- **Chapter**: chapter-4
- **Stage**: 07-archive-vn-only
- **File**: 4-7-discrete-distribution-playing-card-experiment.html
- **Block ID**: N/A
- **Tag**: li
- **Issue Type**: vn_only_archive_english_prose
- **Likely Cause**: CAUSE_EXPORTER_SELECTED_WRONG_BLOCK
- **English snippet**: ``
- **Vietnamese block snippet**: `Calculate the following:

μ = ____________
σ = ____________`
- **Similarity**: 0.0
- **Action**: Verify if exporter config parsed wrong classes.

### Finding F-0014 (P0)
- **Chapter**: chapter-4
- **Stage**: 07-archive-vn-only
- **File**: 4-8-discrete-distribution-dice-experiment-using-three-regular-dice.html
- **Block ID**: N/A
- **Tag**: li
- **Issue Type**: vn_only_archive_english_prose
- **Likely Cause**: CAUSE_EXPORTER_SELECTED_WRONG_BLOCK
- **English snippet**: ``
- **Vietnamese block snippet**: `Calculate the following:

μx = _______
σx = _______
μx = _______`
- **Similarity**: 0.0
- **Action**: Verify if exporter config parsed wrong classes.

### Finding F-0015 (P1)
- **Chapter**: chapter-5
- **Stage**: 05-translated
- **File**: 5-3-the-exponential-distribution.html
- **Block ID**: fs-idp114743232-vn
- **Tag**: p
- **Issue Type**: identical_to_source
- **Likely Cause**: CAUSE_TRANSLATION_SKIPPED
- **English snippet**: `1–(1–e^(–0.25*3)) = e^(–0.25*3).`
- **Vietnamese block snippet**: `1–(1–e^(–0.25*3)) = e^(–0.25*3).`
- **Similarity**: 1.0
- **Action**: Rerun translation for block with clean glossary context.

### Finding F-0016 (P1)
- **Chapter**: chapter-6
- **Stage**: 05-translated
- **File**: 6-2-using-the-normal-distribution.html
- **Block ID**: eip-idm169219344-vn
- **Tag**: p
- **Issue Type**: identical_to_source
- **Likely Cause**: CAUSE_TRANSLATION_SKIPPED
- **English snippet**: `a. normalcdf(23,64.7,36.9,13.9) = 0.8186`
- **Vietnamese block snippet**: `a. normalcdf(23,64.7,36.9,13.9) = 0.8186`
- **Similarity**: 1.0
- **Action**: Rerun translation for block with clean glossary context.

### Finding F-0017 (P0)
- **Chapter**: chapter-6
- **Stage**: 05-translated
- **File**: 6-2-using-the-normal-distribution.html
- **Block ID**: eip-idm21130928-vn
- **Tag**: p
- **Issue Type**: identical_to_source
- **Likely Cause**: CAUSE_PARTIAL_TRANSLATION
- **English snippet**: `b. normalcdf(–1099,50.8,36.9,13.9) = 0.8413`
- **Vietnamese block snippet**: `b. normalcdf(–10,50.8,36.9,13.9) = 0.8413`
- **Similarity**: 1.0
- **Action**: Rerun translation for block with clean glossary context.

### Finding F-0018 (P1)
- **Chapter**: chapter-6
- **Stage**: 05-translated
- **File**: 6-2-using-the-normal-distribution.html
- **Block ID**: eip-809-vn
- **Tag**: p
- **Issue Type**: identical_to_source
- **Likely Cause**: CAUSE_TRANSLATION_SKIPPED
- **English snippet**: `a. normalcdf(6,10^99,5.85,0.24) = 0.2660`
- **Vietnamese block snippet**: `a. normalcdf(6,10^99,5.85,0.24) = 0.2660`
- **Similarity**: 1.0
- **Action**: Rerun translation for block with clean glossary context.

### Finding F-0019 (P0)
- **Chapter**: chapter-8
- **Stage**: 07-archive-vn-only
- **File**: 8-5-confidence-interval-place-of-birth.html
- **Block ID**: N/A
- **Tag**: li
- **Issue Type**: vn_only_archive_english_prose
- **Likely Cause**: CAUSE_EXPORTER_SELECTED_WRONG_BLOCK
- **English snippet**: ``
- **Vietnamese block snippet**: `Survey the students in your class, asking them if they were born in this state. Let X = the number that were born in this state.

n = ____________
x =`
- **Similarity**: 0.0
- **Action**: Verify if exporter config parsed wrong classes.

### Finding F-0020 (P0)
- **Chapter**: chapter-9
- **Stage**: 05-translated
- **File**: 9-homework.html
- **Block ID**: id12545176-vn
- **Tag**: p
- **Issue Type**: identical_to_source
- **Likely Cause**: CAUSE_TRANSLATION_SKIPPED
- **English snippet**: `Ai, Akemi, Akiko, Ayumi, Chiaki, Chie, Eiko, Eri, Eriko, Fumiko, Harumi, Hitomi, Hiroko, Hiroko, Hidemi, Hisako, Hinako, Izumi, Izumi, Junko, Junko, K`
- **Vietnamese block snippet**: `Ai, Akemi, Akiko, Ayumi, Chiaki, Chie, Eiko, Eri, Eriko, Fumiko, Harumi, Hitomi, Hiroko, Hiroko, Hidemi, Hisako, Hinako, Izumi, Izumi, Junko, Junko, K`
- **Similarity**: 1.0
- **Action**: Rerun translation for block with clean glossary context.

### Finding F-0021 (P0)
- **Chapter**: chapter-9
- **Stage**: 07-archive-vn-only
- **File**: 9-5-additional-information-and-full-hypothesis-test-examples.html
- **Block ID**: N/A
- **Tag**: li
- **Issue Type**: vn_only_archive_english_prose
- **Likely Cause**: CAUSE_EXPORTER_SELECTED_WRONG_BLOCK
- **English snippet**: ``
- **Vietnamese block snippet**: `State the Question: We need to determine if, at a 0.05 significance level, the average conductivity of the selected glass is greater than one. Our hyp`
- **Similarity**: 0.0
- **Action**: Verify if exporter config parsed wrong classes.

### Finding F-0022 (P1)
- **Chapter**: chapter-10
- **Stage**: 07-archive-vn-only
- **File**: 10-1-two-population-means-with-unknown-standard-deviations.html
- **Block ID**: N/A
- **Tag**: span
- **Issue Type**: vn_only_archive_english_prose
- **Likely Cause**: CAUSE_EXPORTER_SELECTED_WRONG_BLOCK
- **English snippet**: ``
- **Vietnamese block snippet**: `The standard error is:`
- **Similarity**: 0.0
- **Action**: Verify if exporter config parsed wrong classes.

### Finding F-0023 (P1)
- **Chapter**: chapter-10
- **Stage**: 07-archive-vn-only
- **File**: 10-1-two-population-means-with-unknown-standard-deviations.html
- **Block ID**: N/A
- **Tag**: span
- **Issue Type**: vn_only_archive_english_prose
- **Likely Cause**: CAUSE_EXPORTER_SELECTED_WRONG_BLOCK
- **English snippet**: ``
- **Vietnamese block snippet**: `Degrees of freedom`
- **Similarity**: 0.0
- **Action**: Verify if exporter config parsed wrong classes.

### Finding F-0024 (P1)
- **Chapter**: chapter-10
- **Stage**: 07-archive-vn-only
- **File**: 10-2-two-population-means-with-known-standard-deviations.html
- **Block ID**: N/A
- **Tag**: span
- **Issue Type**: vn_only_archive_english_prose
- **Likely Cause**: CAUSE_EXPORTER_SELECTED_WRONG_BLOCK
- **English snippet**: ``
- **Vietnamese block snippet**: `Normal distribution is:`
- **Similarity**: 0.0
- **Action**: Verify if exporter config parsed wrong classes.

### Finding F-0025 (P1)
- **Chapter**: chapter-10
- **Stage**: 07-archive-vn-only
- **File**: 10-2-two-population-means-with-known-standard-deviations.html
- **Block ID**: term-00002
- **Tag**: span
- **Issue Type**: vn_only_archive_english_prose
- **Likely Cause**: CAUSE_EXPORTER_SELECTED_WRONG_BLOCK
- **English snippet**: ``
- **Vietnamese block snippet**: `The standard deviation`
- **Similarity**: 0.0
- **Action**: Verify if exporter config parsed wrong classes.

### Finding F-0026 (P0)
- **Chapter**: chapter-11
- **Stage**: 07-archive-vn-only
- **File**: 11-3-test-of-independence.html
- **Block ID**: N/A
- **Tag**: span
- **Issue Type**: vn_only_archive_english_prose
- **Likely Cause**: CAUSE_EXPORTER_SELECTED_WRONG_BLOCK
- **English snippet**: ``
- **Vietnamese block snippet**: `The table contains expected (E) values (data).`
- **Similarity**: 0.0
- **Action**: Verify if exporter config parsed wrong classes.

### Finding F-0027 (P0)
- **Chapter**: chapter-11
- **Stage**: 07-archive-vn-only
- **File**: 11-7-lab-1-chi-square-goodness-of-fit.html
- **Block ID**: N/A
- **Tag**: li
- **Issue Type**: vn_only_archive_english_prose
- **Likely Cause**: CAUSE_EXPORTER_SELECTED_WRONG_BLOCK
- **English snippet**: ``
- **Vietnamese block snippet**: `Record the values.
     











































Table 
11.23`
- **Similarity**: 0.0
- **Action**: Verify if exporter config parsed wrong classes.

### Finding F-0028 (P0)
- **Chapter**: chapter-11
- **Stage**: 07-archive-vn-only
- **File**: 11-homework.html
- **Block ID**: N/A
- **Tag**: span
- **Issue Type**: vn_only_archive_english_prose
- **Likely Cause**: CAUSE_EXPORTER_SELECTED_WRONG_BLOCK
- **English snippet**: ``
- **Vietnamese block snippet**: `The Chronicle of Higher Education (2/2/2006)`
- **Similarity**: 0.0
- **Action**: Verify if exporter config parsed wrong classes.


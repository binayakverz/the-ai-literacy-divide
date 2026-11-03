# Methodology

## Research design
This study uses a secondary-data comparative quantitative design combined with structured cross-dataset evidence synthesis. FITPED AI Literacy questionnaire microdata provide the primary individual-level empirical analysis. Eurostat, ITU, World Bank WDI, UNESCO UIS, OECD PIAAC, IEA ICILS, Pew Research Center, Stanford AI Index, ILO, and World Bank/Semrush evidence provide independent aggregate, contextual, framework, or selected-sample evidence.

The evidence streams are not respondent-level merged and are not treated as measurements of one common construct.

## Primary dataset and sample
The FITPED dataset contains 1,205 records from 1,146 unique participants. Fifty-nine participant IDs are repeated; these observations correspond to participants observed in both 2022 and 2024 and support a limited matched-subset analysis. The supplied dataset contained no exact duplicate rows and no raw missing cells. The original data were not overwritten during processing.

Dataset: FITPED AI Literacy Questionnaire data, Figshare Version 2. DOI: 10.6084/m9.figshare.29488523.v2.

## Data treatment and scale construction
Zero-coded non-applicable/missing-coded responses were treated as missing for the constructs IM, S, C, and BI. This treatment was not applied to the AI-literacy items, which retain their observed 0–5 response scale.

The primary AI-literacy construct consists of five items, L1–L5. The score is the mean of valid items, with a minimum of 80% valid items required for scale calculation. The original five-item structure was retained. L4 deletion was examined only as a sensitivity statistic and was not used to redefine the primary measure.

Effective analytical sample sizes are determined by the prespecified valid-item rule and may differ from the reporting convention used in the original FITPED data article.

## Statistical analysis
The manuscript reports descriptive statistics, internal-consistency assessment using Cronbach's alpha, group comparisons, Spearman rank correlations, exploratory ordinary least squares regression with cluster-robust standard errors by participant ID, and a paired Wilcoxon signed-rank analysis for the 59 matched participants.

The exploratory regression models AI literacy using year, age, gender, an IT-program indicator, and log(1 + AI-course hours). The matched-subset analysis compares 2022 and 2024 observations for repeated participants.

## Cross-dataset evidence synthesis
External sources are used according to their own unit of analysis, population, construct, and measurement design. They are not pooled with FITPED microdata. Internet access, reported GenAI use, AI awareness, digital literacy, occupational exposure, and performance-based AI capability are treated as distinct indicators rather than interchangeable measures.

## Interpretation boundaries
- Access is not equivalent to AI literacy.
- Perceived AI literacy is not demonstrated AI capability.
- AI use is not equivalent to effective use.
- Education is not itself a direct measure of AI capability.
- Association is not causation.
- Country-level indicators do not establish individual-level relationships.
- The six-stage architecture (Digital Divide → AI Access Divide → AI Literacy Divide → Capability Divide → Effective-Use Divide → Benefit Divide) is conceptual and measurement-oriented; it is not an empirically demonstrated causal pathway.
- No composite Access–Capability–Effective Use–Benefit index was constructed.

## Analysis-code availability
The final manuscript's reproducibility appendix records that no executable analysis-code artifact was present in the supplied materials. Accordingly, this repository documentation does not claim that executable analysis scripts are included or that the full analysis can currently be rerun from code.

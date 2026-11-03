# Reproducibility and Research Audit

## Dataset version
- FITPED AI Literacy Questionnaire data, Figshare Version 2
- DOI: 10.6084/m9.figshare.29488523.v2
- The accompanying questionnaire PDF and Skalka et al. (2025a) data article are identified in the manuscript's reproducibility checklist.

## Cleaning audit reported in the manuscript
- Records: 1,205
- Unique participants: 1,146
- Repeated participant IDs: 59
- Exact duplicate rows: 0
- Raw missing cells: 0
- Zero-coded non-applicable/missing-coded values: treated as missing for IM, S, C, and BI
- Original raw dataset: not overwritten

## Scale construction
- AI literacy = mean of valid L1–L5 items
- Minimum valid-item threshold: 80%
- Original five-item structure retained
- L4 deletion considered only as a sensitivity statistic

## Analysis record
The manuscript identifies the following locked analysis/evidence records:
- FITPED_STEP5_EMPIRICAL_ANALYSIS.xlsx
- STEP5_CROSS_DATASET_EMPIRICAL_EVIDENCE_MATRIX.xlsx

These workbooks are identified as analysis records in the manuscript; they are not included in this documentation package.

## External evidence streams
Eurostat `isoc_ai_iaiu`; ITU DataHub; World Bank WDI `IT.NET.USER.ZS`; UNESCO UIS; OECD PIAAC Cycle 2; IEA ICILS 2023; Pew Research Center; Stanford AI Index 2026; ILO; and World Bank/Semrush GenAI-adoption evidence.

Public-source reconciliation date stated in the manuscript: 2 October 2026. Dataset observation years remain distinct from retrieval/consultation date.

## Non-pooling and non-causal safeguards
- No FITPED respondent-level observations were merged with external datasets.
- No composite Access–Capability–Effective Use–Benefit index was constructed.
- No causal pathway was estimated.
- The conceptual six-stage architecture must not be interpreted as a tested causal sequence.

## Code and data availability statement
The manuscript states that no executable analysis-code artifact was present in the supplied materials. This repository therefore documents the methodology and audit trail but does not represent the analysis as fully computationally reproducible. The CSV files in `tables/` reproduce manuscript tables; they are not respondent-level raw data.

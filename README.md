# FrontiersPDCI

Analysis code for **Voice-based differentiation of Parkinson's disease and cognitive impairment in Bridge2AI-Voice** (Raza, Peng and Sadheesh; Frontiers in Digital Health manuscript 2021657).

## Download the analysis package

[Download the R15 portable code archive](PDCI_analysis_code_R15_portable_20261116.zip?raw=true), then extract it and open the included `PDCI_analysis_code_R15/README.md`.

The archive is the preserved R15 package dated 16 November 2026. Its SHA-256 is:

`732aafeda9421887afb80a61798126412eb840d5611c6b8ed78e8a092bb0ba85`

## Where to start after extracting

| File or folder | Purpose |
|---|---|
| `REPRODUCE_FROM_FEATURES.md` | Data requirements and step-by-step reproduction of Tables 2 and 4 and calibration summaries |
| `ROUND2_ANALYSES.md` | Reviewer-requested matched-model and common-referral-budget analyses |
| `REPRODUCTION_STATUS.json` | Executed checks and their limitations |
| `R15_INDEPENDENT_VERIFICATION.json` | Independent verification of the Round 2 analyses |
| `PORTABLE_CHANGES.md` | Portability changes and execution provenance |
| `reproduce_from_features.py` | Staged reproduction driver |
| `src/` | Scientific analysis modules |
| `figures/` | Figure-generation scripts |
| `results/` | Protocols, reviewer-analysis scripts and aggregate references |
| `requirements.txt` | Recorded software environment |

## Data access and privacy

The analysis requires credentialed access to **Bridge2AI-Voice adult v3.0.0**, dataset DOI **10.13026/k81f-qr68**, through PhysioNet under its access agreement. The dataset is not redistributed here.

This package contains code, protocols, documentation and aggregate verification material, not participant recordings, feature tables, labels, participant-level predictions or fitted payloads. Keep locally generated participant-derived files under the dataset's access controls. Run reproduction in a new analysis workspace, not over the original frozen study runs.

## Reproduction status

The frozen R15 release plus documented runtime path adapters reconstructed nine feature caches and the analytic inputs for 750 participants, completed all 15 original nested fits, and exactly reproduced 24 checked aggregate tables. Independent checks also verified the original Round 2 matched-model and operating-budget analyses.

The portable copy includes the path correction and passed separate compilation and path checks. **It has not undergone a fresh clean installation, a repeated end-to-end run, or cross-platform validation.** The original verification receipts do not claim those additional tests. Consult the package's status and provenance documents before running it.

## Licence and archive notes

This repository is available under the [MIT licence](LICENSE). The controlled-access source dataset and third-party dependencies retain their own terms. **No code DOI has been issued or claimed.** Use this GitHub repository URL for code access.

The ZIP is preserved unchanged for provenance. Some included documents describe the earlier preparation stage and therefore still refer to pending licence/hosting decisions or OSF upload plans. The current repository-level MIT licence and public GitHub availability supersede those historical hosting/licence placeholders; they do not change the analysis or its verification status.

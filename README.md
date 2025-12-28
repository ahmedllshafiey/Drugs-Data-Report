# Pharmaceutical Market Analysis: Drug Characteristics and Prescription Trends

## Author

Ahmed ElShafiey

## Overview

This project contains a LaTeX report analyzing pharmaceutical data obtained from [Kaggle](https://www.kaggle.com/datasets/jithinanievarghese/drugs-related-to-common-treatments). The analysis explores drug classifications, pregnancy safety categories, prescription vs. OTC distribution, and user engagement/activity patterns across various medical conditions.

The report is structured to provide insights into:

- The most represented medical conditions (Pain, Colds & Flu, Acne)
- Prescription and OTC trends
- Analgesic activity and usage patterns
- Pregnancy safety categories across drug types
- Patterns in prescription reliance across medical conditions

## Dataset

The dataset used contains **3,959 drug records** with features including:

- `Activity`: User engagement metric
- `Rx/OTC`: Prescription or over-the-counter classification
- `Pregnancy Category`: Safety ratings (A to X)
- `CSA`: Controlled Substances Act schedule
- `Rating`: User-reported effectiveness (1–10)

## Project Structure

- `Report.tex` – Main LaTeX document containing the full analysis and visualizations.
- `figures/` – Folder containing any charts or images used in the report.

## Key Findings

- Pain medications are the most represented (393 drugs), followed by Colds & Flu (246) and Acne (238).
- Prescription drugs dominate (2,702) versus OTC drugs (1,257).
- OTC analgesics slightly outnumber prescription-only options (236 vs. 157).
- Activity metrics reflect behavioral patterns more than therapeutic potency; Ibuprofen shows unexpectedly high usage.
- Pregnancy safety data is limited: over 50% of painkillers are Category C, ~30% are unassessed (Category N), and Category A drugs are absent.
- High-prevalence conditions like Hypertension and Rheumatoid Arthritis involve more restricted Category D/X drugs, while lower-prevalence conditions rely more on Category B treatments.
- Caution and patient counseling are essential due to gaps in pregnancy safety data.

## Requirements

- LaTeX distribution (TeX Live, MiKTeX, or Overleaf)
- Python 3.x (for `analysis.ipynb`)
- Python packages: `pandas`, `matplotlib`, `seaborn`

## License

This project is released under the MIT License. See [LICENSE](LICENSE) for details.

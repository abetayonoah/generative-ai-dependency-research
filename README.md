# Generative AI Dependency and Perceived Negative Effects on Problem-Solving

**A Cross-Sectional Study of University Students**  
**Researcher:** Abe Tayo Noah | **DataraFlow Cohort 2**

## Overview
This research examines the association between generative AI (GenAI) dependency and students' **perceived negative effects on problem-solving** using a cross-sectional survey of university students in the United States and Indonesia. The outcome is self-reported; it is **not** an objective test of problem-solving performance.

## Research questions
- Is greater GenAI dependency associated with higher reported negative impact on problem-solving?
- Does the association differ between U.S. and Indonesian respondents?
- Are the findings robust to alternative modeling choices and dependency dimensions?

## Data and methods
- **Source:** Pertiwi & Adiningrum (2026), linked below.
- **Original respondents:** 239; **active GenAI users in the analytic sample:** 227 (116 U.S., 111 Indonesia), as reported in the research manuscript.
- **Methods:** questionnaire scoring, reliability analysis, Spearman correlation, adjusted ordinal logistic regression, country interaction, sensitivity analyses, multicollinearity diagnostics, and exploratory factor analysis.

## Findings reported in the manuscript
| Analysis | Reported result |
| --- | --- |
| Adjusted GenAI dependency association | Odds ratio **2.946** |
| 95% confidence interval | **2.065–4.204** |
| Statistical significance | **p < .001** |
| Dependency scale reliability | Cronbach's α **.801** |
| Country interaction | **p = .596** |

These figures are **transcribed from the manuscript and have not been independently re-executed in this packaged release**. An association in cross-sectional self-report data does not establish that GenAI use causes cognitive harm.

## Repository structure
```text
notebooks/genai_dependency_analysis.ipynb  # Analysis notebook
data/README.md                             # Dataset source and access
reports/README.md                          # Where to add final PDF
figures/README.md                          # Where to add generated figures
requirements.txt                           # Python dependencies
.gitignore                                 # Excludes private/local files
```

## Reproduce the analysis
```bash
git clone https://github.com/YOUR-USERNAME/generative-ai-dependency-research.git
cd generative-ai-dependency-research
python3 -m venv .venv
source .venv/bin/activate
python -m pip install -r requirements.txt
jupyter notebook notebooks/genai_dependency_analysis.ipynb
```

Download the original workbook from the cited Zenodo record and save it to `data/When Culture Meets AI - Survey Dataset.xlsx`. Then run the notebook cells in order. The exact dependency versions used in the original analysis were not captured; ranges in `requirements.txt` are a starting point, not a locked reproducible environment.

## Research paper
The final manuscript PDF and publication DOI can be added once publication details are confirmed. **A Zenodo deposit is a public research record, not peer review.**

## Dataset citation
Pertiwi & Adiningrum (2026). *When Culture Meets AI: A Cross-Cultural Study of Generative AI Dependency Among U.S. and Indonesian Business Students*. Zenodo. https://doi.org/10.5281/zenodo.21013786

## Limitations
Cross-sectional design, self-report measures, and nonrandom sampling limit causal and population-wide conclusions. This project uses an existing third-party dataset and does not claim ownership of the underlying survey data.

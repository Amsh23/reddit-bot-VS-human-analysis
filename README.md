# Reddit Dead Internet Theory — Bot Detection Analysis

## Overview
This repository analyzes Reddit comment behavior to evaluate the “Dead Internet Theory” hypothesis. It combines a curated dataset with an exploratory Jupyter notebook and a Looker Studio dashboard snapshot to compare human vs. automated activity signals.

## Repository Contents
- `reddit_dead_internet_analysis.ipynb`: Main analysis notebook with data profiling, cleaning, and behavioral comparisons.
- `reddit_dead_internet_analysis_2026.csv`: Dataset used in the notebook.
- `google-looker-studio-dashboard.jpg`: Static snapshot of the Looker Studio dashboard.
- `google-looker-studio-dashboard.jpg.pdf`: PDF export of the dashboard.
- `docs/`: Additional project documentation.

## Quick Start
### 1) Set up a Python environment
The notebook was authored with common data-science libraries:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

If you want to run the notebook locally, create a virtual environment and install dependencies:

```bash
python -m venv .venv
source .venv/bin/activate
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### 2) Open the notebook
```bash
jupyter notebook reddit_dead_internet_analysis.ipynb
```

> Note: The notebook currently references a local Windows path for the CSV file. Update the CSV path to the repository-relative file (`reddit_dead_internet_analysis_2026.csv`) before executing.

## Dataset Summary
The dataset includes 500 Reddit comment records with behavioral and linguistic features used for bot detection. See the data dictionary in `docs/data-dictionary.md` for details.

## Reports Included in the Notebook
The notebook is organized into five report sections:
1. Dataset understanding & quality
2. Data cleaning & preparation
3. Bot vs. human behavioral analysis
4. Subreddit bot infiltration
5. Automation risk indicators

## Dashboard
A Looker Studio dashboard snapshot is available as a static image and PDF in the repository. See `docs/dashboard.md` for details and the embed link referenced in the notebook.

## Documentation
- `docs/project-overview.md`: Project goals, scope, and methodology.
- `docs/data-dictionary.md`: Field-level dataset documentation.
- `docs/analysis-notes.md`: Key analysis takeaways and open questions.
- `docs/dashboard.md`: Dashboard assets and usage notes.

## License
See the `LICENSE` file for details.

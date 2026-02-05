# Project Overview

## Goal
Assess Reddit comment behavior for evidence of automated activity and identify patterns aligned with the “Dead Internet Theory.” The analysis compares human and bot-labeled accounts using behavioral (timing, activity) and linguistic (sentiment, word length) features.

## Scope
- Exploratory analysis of a 500-row dataset of Reddit comments.
- Descriptive statistics and visualizations to compare bot vs. human behavior.
- Highlighting subreddits with elevated bot ratios.
- Visual context via a Looker Studio dashboard snapshot.

## Methodology (Notebook Flow)
1. **Dataset understanding & quality**: Load CSV, inspect schema, check missing values, summarize distributions.
2. **Data cleaning & preparation**: Remove outliers using IQR-based filtering and percentile trimming.
3. **Bot vs. human behavioral analysis**: Compare response delays, sentiment, and word-length metrics.
4. **Subreddit bot infiltration**: Rank subreddits by bot ratio to identify hotspots.
5. **Automation risk indicators**: Relate account age to modeled bot probability.

## Outputs
- Jupyter notebook with code, charts, and narrative insights.
- Static dashboard image and PDF export.
- This documentation set covering data, analysis, and artifacts.

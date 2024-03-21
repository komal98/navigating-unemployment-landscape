# Layoffs, Economy and Employee Sentiments: A Data-Driven Exploration
<img width="1059" alt="Layoffs Dashboard" src="https://github.com/komal98/navigating-unemployment-landscape/assets/20492468/04993b44-db9d-4c9b-a25e-1adba6ba0ae2">

## Overview
The global economy experiences continuous fluctuations, impacting various facets of society, including employment opportunities and job security. In recent times, the economic downturn has raised concerns about its effects on the job market. Tech layoffs, in particular, have become increasingly common.

## Motivation
Amidst this backdrop, we embarked on an exploration to understand whether economic data could have predicted layoffs across all industries, with a specific focus on the tech sector. Our investigation delves into several critical aspects. We examine the intersection of economic trends, particularly Gross Domestic Product (GDP) and interest rate fluctuations, to discern their impact on the tech industry. Our analysis spans two significant periods: the beginning of COVID-19 in 2020 and the burst of the tech bubble starting in 2022. These external factors significantly influenced workforce dynamics.

## Data Sources 
1. Fred API: Provides economic indicators.
2. layoffs.fyi: Scraped data on layoffs.
3. Kaggle: Publicly available datasets on tech layoffs.

You can find more information on the extracted data under:
```
.
├── data
│   ├── README.md

```   
## Sentiment Analysis
We delve into related Reddit subreddits, such as r/technews, to gauge evolving layoff psychology.

## Directory Structure
```
.
├── README.md
├── code
│   ├── economic-data-analysis.ipynb
│   ├── layoffs-fyi-scraper.ipynb
│   ├── subreddit.ipynb
│   └── tech-layoffs-analysis.ipynb
├── data
│   ├── README.md
│   ├── layoffs.csv
│   ├── layoffs_combined_cleaned.csv
│   └── layoffs_data.csv
├── output
│   ├── LayoffsAnalysis.pptx
│   ├── layoffs_country.png
│   ├── layoffs_industry.png
│   ├── layoffs_industry10.png
│   ├── layoffs_plot.png
│   └── pie-chart.png
└── tableau
    └── LayoffsAnalysis.twbx
```

# Titanic Survival Analysis 

Statistical analysis of the Titanic disaster using Python, exploring which sociodemographic factors determined passenger survival.

## Overview

This project applies **Univariate and Bivariate Descriptive Statistics** to the Titanic dataset to answer a key question: "was survival random, or was it shaped by gender, social class, and family structure?"

The analysis delivers 5 data-driven insights with visualizations and clear interpretations.

## Key Findings

| Factor | Insight |
|--------|---------|
| **Gender** | 74.2% of women survived vs. only 18.9% of men -- maritime evacuation protocol ("women and children first") confirmed statistically |
| **Social Class** | 1st class passengers had the highest survival rate; 3rd class the lowest, wealth determined access to lifeboats |
| **Ticket Fare** | Boxplot reveals extreme wealth variability within 1st class, in contrast to the uniformly low fares of 3rd class |
| **Family Size** | Median of 0 siblings/spouses on board, most passengers traveled alone (immigrants and workers) |
| **Embarkation Port** | Cherbourg (France) passengers had notably higher survival rates, reflecting the high concentration of 1st class boardings there |

## Visualizations

- Bar charts: survival rates by gender
- Bar chart: survival rates by social class
- Boxplot: ticket fare distribution by class (outliers removed)
- Boxplot: siblings/spouses distribution
- Bar chart: survival rates by embarkation port

## Tech Stack

- **Python 3**
- **Pandas** — data manipulation and frequency analysis
- **Matplotlib** — custom bar charts and boxplots
- **Seaborn** — styled statistical visualizations

## How to Run

```bash
# Clone the repository
git clone https://github.com/miguelsantos-dv/titanic-survival-analysis

# Install dependencies
pip install pandas matplotlib seaborn

# Run the notebook
jupyter notebook titanic_survival_analysis.ipynb
```

## Dataset

Classic Titanic dataset loaded directly from Seaborn (`sns.load_dataset("titanic")`) — no external download required. Each record includes survival status, class, gender, age, fare, embarkation port, and family composition.

## Conclusion

Survival on the Titanic was not random. Gender and social class created a clear risk profile: male, 3rd class, solo travelers faced the highest mortality rates. The data mathematically confirms that social dynamics outside the ship governed behavior during the disaster.

---

*Academic project — Statistics and Inferences · PUC-Campinas · 2026*

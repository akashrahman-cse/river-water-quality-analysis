# River Water Quality Analysis

Statistical analysis of oxygen and nitrate concentrations (mg/L) in a river with five sections (headwaters to mouth) across four seasons, 900 measurements in total. Prepared as the data analysis report for my M.Sc. Data Science application.

## Research Questions
1. Do oxygen and nitrate differ significantly between spring and autumn?
2. Do they differ between the five river sections, and which sections differ?

## Methods
- Descriptive statistics and boxplots
- Shapiro–Wilk, Q–Q plots, Levene's test
- Welch's t-test and Mann–Whitney U test
- One-way ANOVA with Tukey's HSD (nitrate), Kruskal–Wallis with Dunn's test (oxygen)
- Holm correction, α = 0.05

## Key Results
- Nitrate is significantly higher in spring than in autumn (+0.87 mg/L, p = 0.001).
- Nitrate rises from 5.35 mg/L (headwaters) to 11.47 mg/L (mouth); all sections differ (p < 0.001).
- Oxygen shows no spring–autumn difference (p = 0.065) and only one significant section difference (A1 vs. A4).

## How to Run
1. `pip install -r requirements.txt`
2. Place `waterquality.csv` in the project folder (the data set is not included).
3. Run all cells in `analysis.ipynb`.

## Author
Md Akash Rahman · akashrahman.cse@gmail.com

# afghanistan-covid-model

Descriptive statistical analysis of reported daily COVID-19 cases and fatalities in Afghanistan using WHO-derived Kaggle data (2020).

## Scope

This project examines reporting patterns, temporal structure, and statistical properties of early pandemic case data under severe data constraints.  
No forecasting or causal inference is attempted.

## Data

Daily COVID-19 case and fatality reports (2020), Kaggle dataset (abdoomoh).

## Methods

- Exploratory data analysis (EDA)
- Temporal visualization and smoothing (7-day moving average)
- Correlation analysis with biologically motivated lag adjustment
- Overdispersion assessment
- Negative binomial GLM diagnostics
- Residual comparison against smoothing baseline

## Key Insight

Under short, noisy, and structurally unstable epidemic time series, simple smoothing-based baselines provide a more reliable descriptive summary than parametric growth models.

## Reference

Zhou et al. (2020). *Clinical course and risk factors for mortality of adult inpatients with COVID-19 in Wuhan, China.*  
The Lancet, 395(10229), 1054–1062.

## License

MIT License. Data subject to Kaggle dataset license.

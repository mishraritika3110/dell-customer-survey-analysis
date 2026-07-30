# dell-customer-survey-analysis
Statistical analysis of Dell customer survey data — price sensitivity, satisfaction, and regression modeling using Python and Excel.

## Overview
Analysis of a 372-respondent Dell customer survey examining price sensitivity, 
customer satisfaction, and repurchase loyalty. Combines Excel (PivotTables, 
crosstabs) for exploratory analysis with Python (regression modeling) for 
statistical testing.
## Note on Data Source
Original raw survey data was not publicly available. This dataset was 
synthetically generated to replicate the structure and distributions of 
a documented Dell customer survey case (n=372), for the purpose of 
practicing the analysis pipeline. Findings should be read as illustrative.

## Key Findings
- ~34% of customers would not purchase at a 10% price increase, regardless of gender or income
- Multiple regression showed Gender (p=0.427) and Income (p=0.470) do NOT 
  significantly predict purchase intent (R²=0.3%)
- Repurchase loyalty remains consistently high (~26-36%) across all income brackets
- Satisfaction levels are stable across age and education groups

## Business Recommendations
1. Hold pricing steady — high price sensitivity across all segments
2. Don't rely on demographic targeting for pricing decisions
3. Invest in retention programs, since loyalty is broadly strong
4. Investigate non-demographic drivers of purchase intent (brand perception, 
   competitor pricing)

## Tools Used
- **Excel**: PivotTables, crosstabs, charts
- **Python**: pandas, statsmodels (OLS regression)

## Files
- `dell_survey_analysis.ipynb` — data generation, encoding, and regression analysis
- `dell_survey_data.xlsx` — survey data used for Excel-based exploratory analysis

## Methodology
Data was synthetically generated to match the distribution patterns of a 
reference survey (372 respondents), since original raw data was not publicly 
available. Analysis pipeline includes descriptive statistics, cross-tabulation, 
and multiple linear regression.

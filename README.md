## Organizational-Behavior-Research
This repository contains the research design, data analysis, and results from a semester-long Organizational Behavior research project examining the factors that influence organizational commitment. The project applied the scientific research method to investigate how workplace attitudes develop and how they can affect employee retention.

## Dataset Preparation
The survey collected responses on 12 dependent variable items and 12 independent variable items.

## Data Cleaning
Reverse-coded items were recoded so higher values consistently represent stronger agreement.
- Manual swap: 1↔5, 2↔4, 3→3

## Reliability Analysis
Cronbach’s Alpha (⍺) calculated for each scale in Google Sheets to verify internal consistency.
- Threshold: ⍺ ≥ 0.70 required for proceeding.
- Inconsistent items were flagged, reviewed, and adjusted iteratively.
- Generated composite scores for each variable (averages of scale items) for regression analysis.


## Descriptive Statistics
Mean (M) and standard deviation (SD) calculated for all variables to assess scale performance and distribution.
- Checked for outliers or anomalies in item responses.

## Correlation Analysis
Imported cleaned dataset into RStudio.
- Generated a correlation matrix to examine relationships among IVs and DV.
- Significance threshold: p < 0.05
		

## Multiple Regression
Conducted regression with Organizational Commitment as DV. Recorded:
- β coefficients for each IV
- p-values (significance)
- Adjusted R² (model fit)
Correlation and regression outputs were analyzed to determine which IVs significantly predict the DV.

## Findings Presentaion
Results interpretated and presented to an open audience.

# Oil Well Location Analysis Project

## Overview
This project analyzes geological data from multiple regions to identify the most profitable location for new oil well development.

## Objective
- Predict oil reserve volumes using machine learning
- Evaluate potential profit for each region
- Assess financial risk using bootstrapping
- Recommend the optimal region based on business constraints

## Tools & Technologies
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Statistical Analysis

## Methodology
- Trained linear regression models for each region
- Split data into training and validation sets (75/25)
- Evaluated model performance using RMSE
- Selected top 200 wells based on predicted reserves
- Calculated profit based on revenue and budget constraints
- Applied bootstrapping (1000 samples) to estimate risk and confidence intervals

## Key Results
- Identified the most profitable region with lowest risk
- Achieved reliable predictions using linear regression
- Determined region meeting risk threshold (<2.5% loss probability)

## Conclusion
Region 1 was selected as the optimal location due to its strong balance of profitability and low risk.

## Business Impact
- Provided data-driven recommendation for optimal well placement
- Balanced profitability with risk constraints
- Demonstrated real-world decision-making using machine learning

## Files
- `oil_well_location_analysis.ipynb` – Full analysis and modeling

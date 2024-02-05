# Insurance Hike by Smoking Habits: Causal Inference Analysis

This project looks at the causal relationship between smoking habits and insurance charges using different causal inference techniques on a health insurance dataset.

## Data

The dataset contains information on age, sex, BMI, number of children, smoking habits (yes/no), geographic region (4 regions) and individual medical charges billed by health insurance. 

## Analysis

The following causal inference techniques are applied:

- Randomized Controlled Trials (RCTs) 
- Instrumental Variables (IV) using BMI as instrument 
- Propensity Score Matching on age and BMI
- Difference-in-Differences (DiD) using region as treatment

For each method, the causal effect of smoking on charges is estimated and visualized. 

## Conclusion

All causal inference techniques consistently show a positive causal relationship between smoking and insurance charges, with estimated effects ranging from $800 to $23,000 increase in average charges. This suggests that smoking leads to significantly higher insurance claims and expenses.

Propensity score matching and RCTs provide lower bound estimates, while IV and DiD provide higher bound estimates of the causal effect.

## Requirements

The analysis uses Python with pandas, matplotlib, seaborn, sklearn, statsmodels, causalnex and other common data science libraries.

## Usage

To reproduce the analysis, simply run the Jupyter notebook in order. The core code for each technique is clearly highlighted.

## References

The health insurance dataset is originally from Kaggle. Methodology follows causal inference literature and tutorials.

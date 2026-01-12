# diabetes-clinical-trial-analysis
This report details the statistical findings of a 24-week clinical trial evaluating a new medication's impact on HbA1c levels in diabetic patients. After rigorous testing, the data confirm that the treatment is highly effective at reducing blood glucose levels and maintains a safety profile comparable to the placebo.

##### Methodology and Data Integrity
The dataset was cleaned to address missing adverse event data, and subject IDs were standardised. HbA1c change was calculated by comparing end-of-trial results (Week 24) against baseline measurements (Week 0). Memory management was optimised by converting relevant variables (Group, Gender, Adverse Events) into appropriate category data types.

##### Key Findings
1. Statistical Significance of HbA1c Reduction
The primary goal of the trial was the reduction of HbA1c levels by week 24. A t-test comparing the treatment and placebo groups revealed a highly significant difference (p < 0.001). With a t-statistic of approximately -12.68, the data indicate that the reduction observed in the treatment group is not due to random chance but is a direct result of the pharmacological intervention.

2. Time Effect and Interaction
The Repeated Measures ANOVA confirmed that the reduction in blood sugar was not an isolated event, but a consistent trend over the 24-week duration. While the placebo group remained relatively stable, the treatment group showed a sustained, linear decline in HbA1c levels, suggesting long-term efficacy rather than a short-term spike in performance.

3. Safety Profile and Adverse Events
A critical component of any clinical trial is the safety of the participants. I used a chi-square test to compare the frequency of adverse events between the two groups. The resulting p-value (p > 0.05) indicates that there is no statistically significant difference in the rate of side effects. This suggests that the medication is well tolerated, and does not pose a significantly higher risk to patients than to the placebo control.

##### Strategic Recommendations
Given the high statistical significance and the clear safety profile, the medication meets the criteria for review by the relevant regulatory bodies. The data support the claim that the drug is a valid tool for glycemic control, and following approval, it can be made available commercially to health providers and patients.

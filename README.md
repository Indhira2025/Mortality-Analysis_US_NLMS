# Modeling of Smoking-Related Mortality: A Big-Data Analysis of the NLMS (National Longitudinal Mortality Study) Tobacco-Use Cohort in the U.S.

## Rationale
Cigarette smoking remains one of the leading preventable causes of death worldwide, driving excess mortality from cardiovascular disease, cancer, and respiratory illnesses. Understanding how smoking duration interacts with demographic, socioeconomic, and lifestyle factors to influence mortality risk is essential for developing targeted public health interventions. Large national cohorts, such as the NLMS PUMS(Public Use Microdata Sample) Tobacco-Use Cohort, provide a unique opportunity to examine these associations using modern analytical tools.

## Objectives 
The primary goal of this project is to characterize and predict mortality risk among smokers while accounting for demographic and socioeconomic characteristics. Key research questions include:
1.	How does time since smoking initiation relate to 5-year mortality risk?
2.	Which demographic or socioeconomic factors (income, education, race, etc.) modify the smoking–mortality association?
3.	Can we build accurate and interpretable models to predict mortality risk among smokers?
4.	What are the most influential factors in mortality prediction?
## Outcomes
By leveraging the NLMS Tobacco Use Cohort, we were able to accurately model and predict mortality risk due to smoking
related behaviors and duration, while accounting for demographic and socioeconomic factors. Our logistic regression analysis,
through adjusted odds ratios, showed that both smoking status and smoking duration had significant impact on the risk of
mortality, even after covariates were accounted for. This analysis provides an interpretable framework for identifying how
smoking behaviors effect mortality risk and the degree to which the selected covariates also impact mortality.
Further, our LightGBM classifier demonstrated strong performance (on cross-validation and test-set data) on predicting
5-year mortality when taking into account the 17 chosen predictors. High recall and AUC values indicate that the model
effectively identifies individuals at elevated mortality risk, even when the positive (deceased) class represents only ~4% of the
population. Although precision is low, as expected in rare-event prediction, the model’s ability to capture the majority of true
deaths makes it suitable for screening and population risk stratification. Overall, LightGBM provides a robust, efficient, and
interpretable framework for mortality prediction in large epidemiologic datasets.
Taken together, our methods and the resulting analyses offer practical utility for public health research and designing targeted
intervention strategies, with the goals of reducing smoking-related mortality, lessening population-wide disease burden, and
improving overall public health.

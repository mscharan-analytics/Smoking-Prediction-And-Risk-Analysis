# Smoking-Prediction-And-Risk-Analysis

## Problem Statement:

Given the approaching annual events, the Great American Smokeout, and Lung Cancer Awareness Month, the concern for public health related to tobacco use and lung cancer has once again come to the spotlight. In addition to raising public awareness, this project also aims to contribute by predicting individuals' smoking habits. This is conducted through the analysis of people’s health indicators and related data. Such identification plays a crucial role in public health and personalized healthcare, helping to encourage healthier lifestyle choices.

## Data Sources:

The dataset was obtained from the Korea National Health Insurance Service and comprises 22 variables and 2 target variables. The dataset can be found , which was originally sourced here.

## Stakeholders and Project Motivation

**Healthcare Providers:**
- Early Intervention: Identify at-risk individuals.
- Tailored Health Advice: Customize advice for better outcomes.

**Policymakers and Public Health:**
- Population-Level Impact: Design interventions to reduce smoking.
- Evidence-Based Decision-Making: Use data for targeted efforts.

**Individuals and Public:**
- Personal Health Awareness: Understand risks for informed choices.
- Community Well-being: Contribute to community health.

**Mental Health Advocates:**
- Holistic Health Promotion: Align with comprehensive health analysis.

**Researchers and Academia:**
- Advancing Knowledge: Contribute to predictive health analysis.

**Insurance Providers:**
- Risk Management: Understand and manage health risks.
- Premium Adjustment: Inform adjustments based on health behaviors.

**Overall Impact:**
- Diverse stakeholders care for health outcomes, community well-being, and advancing public health knowledge.


## Model Performances

<img width="1092" alt="Screenshot 2023-12-29 at 3 24 16 PM" src="https://github.com/mscharan-analytics/Smoking-Prediction-And-Risk-Analysis/assets/140626070/de215c7b-7204-4ec6-917c-2aa21f346f2c">

<img width="883" alt="Screenshot 2023-12-29 at 3 24 37 PM" src="https://github.com/mscharan-analytics/Smoking-Prediction-And-Risk-Analysis/assets/140626070/be7bdaf0-f3e2-4acb-bad9-3a1bb3729d1c">

<img width="1087" alt="Screenshot 2023-12-29 at 3 25 10 PM" src="https://github.com/mscharan-analytics/Smoking-Prediction-And-Risk-Analysis/assets/140626070/665aaf3f-7d43-4672-a6e0-bacd9cd62ae6">

## Conclusions
Best Model: XGBoost emerged as the best-performing model, achieving a balanced accuracy of 83.2%. This model demonstrated strong predictive capabilities in identifying individuals' smoking behaviors.

Cost Analysis: While XGBoost exhibited high accuracy, its associated cost was relatively moderate compared to other models. The average cost of misclassification, considering the consequences of false positives and false negatives, was determined to be 1682.4. This cost factor is a crucial metric for assessing the real-world financial impact of model predictions.

Ensemble Methods: Voting Classification, an ensemble method, also delivered competitive results with a balanced accuracy of 82.5% and an average cost of 1680.8. Ensemble methods leverage the strengths of multiple models to enhance overall predictive performance.

Savings Potential: The project showcased potential annual savings for insurance providers by implementing predictive models. The hypothetical scenario, based on model accuracy of 83%, indicated an annual savings of $10,020,000. This represents a substantial financial benefit achieved through more accurate identification of non-smokers.

Business Implications: The findings underscore the practical implications for insurance companies seeking to optimize premium calculations and risk management. By implementing advanced predictive analytics, businesses can achieve a delicate balance between accuracy and cost-effectiveness, leading to fairer premium adjustments.

Decision-Making Insights: The project provides valuable insights for decision-makers, emphasizing the importance of understanding the trade-offs between model accuracy, interpretability, and financial implications. Decision-makers can leverage these insights to make informed choices aligned with organizational goals and priorities.

In conclusion, the project's quantitative analysis emphasizes the tangible benefits of leveraging predictive analytics in the insurance industry. XGBoost stands out as the top-performing model, striking a balance between accuracy and cost-effectiveness. The potential for substantial annual savings highlights the practical relevance of the project's outcomes for insurance providers.

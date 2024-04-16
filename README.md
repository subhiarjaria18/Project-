# Project_1
Heart Disease Classification 
Project Overview:
The primary objective of this project was to leverage machine learning methodologies for predicting the 10-year risk of coronary heart disease (CHD) among patients, utilizing data sourced from an ongoing cardiovascular study conducted in Framingham, Massachusetts. The dataset comprised information from over 4,000 patients, encompassing 15 attributes representing diverse risk factors for CHD, spanning demographic, behavioral, and medical domains.

Data Preparation:
Extensive data preprocessing was undertaken to ensure data quality and relevance. This involved addressing missing values through various imputation techniques, such as median, mode, and KNN imputation. Outliers were identified and managed using the Interquartile Range (IQR) method, while skewed continuous variables were transformed using techniques like logarithmic and square root transformations to mitigate skewness and enhance model efficacy.

Feature Engineering and Selection:
Feature selection was a critical aspect, involving measures like variance inflation factor to mitigate multicollinearity and the creation of novel features like pulse pressure to encapsulate nuanced relationships within the data. Redundant columns were pruned to streamline the dataset, with ‘age’, ‘sex’, ‘education’, ‘cigs_per_day’, ‘bp_meds’, among others, emerging as pivotal predictors for CHD risk assessment.

Addressing Imbalance:
The imbalanced nature of the dataset was addressed through the adoption of the Synthetic Minority Over-sampling Technique (SMOTE) coupled with Tomek links undersampling, aimed at rebalancing class distribution and enhancing model robustness. Furthermore, standard scaling was applied to ensure uniformity across feature scales.

Model Evaluation and Selection:
Several machine learning models were evaluated based on the primary evaluation metric of recall. Models exhibiting signs of overfitting, characterized by 100% recall, were excluded from consideration. The final selection was based on the models’ performance on recall scores for both training and testing datasets. The Neural Network model, post-tuning, emerged as the optimal choice owing to its superior recall scores.

Results Summary:
The selected models exhibited varying performance metrics, with the tuned Neural Network model showcasing the highest recall score on the testing dataset. This underscores the significance of selecting models that prioritize sensitivity in identifying individuals at risk of CHD, even at the expense of some false positives.

Conclusion:
This project underscores the efficacy of employing machine learning techniques in predicting CHD risk, utilizing real-world data from cardiovascular studies. By adhering to rigorous data preprocessing, feature engineering, and model selection protocols, it was possible to achieve accurate predictions, thereby facilitating informed decision-making in healthcare contexts. This endeavor exemplifies the transformative potential of machine learning in enhancing risk assessment and preventive healthcare interventions.

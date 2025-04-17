# Heart Attacks Record Analysis in Indonesia
This project shows the analysis of the heart attack records in Indonesia. The dataset was downloaded from Kaggle website.

## Table of Contents

- [Introduction](#introduction)
- [Understanding the Dataset](#understanding-the-dataset)
- [Data Cleaning](#data-cleaning)
- [Dashboard and Insights](#dashboard-and-insights)

## Introduction

Health analytics plays a crucial role in the medical field by helping us understand patterns, trends, and causes of diseases more clearly. It has contributed to saving millions of lives through better diagnosis and deeper insights into patient needs.

This dataset includes health records of selected individuals from both rural and urban areas in Indonesia. The variables observed in the study include age, gender, region, income level, hypertension, diabetes, obesity, cholesterol level, waist circumference, smoking habits, alcohol use, physical activity, dietary habits, and whether the person has experienced a heart attack.

The aim of this analysis is to explore how lifestyle choices and environmental factors might be linked to the rate of heart attacks among the sampled individuals.


## Understanding the Dataset

As someone without a background in the medical field, it initially took me some time to understand the meaning and importance of certain variables like cholesterol levels, diastolic and systolic blood pressure, triglycerides, EKG results, and other medical terms. I had to spend some time reading about them online to get a better grasp of what they mean and how they could help me draw insights from the data. Now that I understand the relevance of each variable, the dataset is ready to be cleaned and standardized for analysis.

## Data Cleaning

The dataset was already well-structured and only needed a few refinements. I started by checking for duplicate entries but didn’t find any. I also verified that all the data entries were correctly spelled. To make the data more meaningful, I created a new column for age groups, which is more useful than using individual ages. I also standardized the column headers to make them clearer and easier to understand, especially for someone without a technical background. The images below show both the samples of the original dataset and the refined version.


![Screenshot 2025-04-17 145013](https://github.com/user-attachments/assets/4e2c2c2b-b3a2-4ccf-9920-237d34df2940)

![Screenshot 2025-04-17 145108](https://github.com/user-attachments/assets/0753421e-d004-4d2a-8cb8-768d1787181f)


## Dashboard and Insights

After cleaning and preparing the data, I conducted exploratory data analysis using pivot charts and tables. Several important insights emerged:

Higher Risk in Older Age Groups
The age groups 50–59 and 60–69 recorded the highest number of heart attack cases. This suggests that individuals over 50 are at a significantly higher risk.
Recommendation: Health professionals and relevant organizations should prioritize regular screening and targeted health interventions for people aged 50 and above.

Heart Attack Risk Increases with Age and Lifestyle Factors
The data shows a natural increase in heart attack cases as age increases. However, lifestyle choices like smoking, hypertension, and a history of heart disease were strongly linked to higher risks. Interestingly, the number of active smokers also increased with age.
Recommendation: There should be increased awareness campaigns and smoking cessation programs, especially targeted at older adults. Also, managing blood pressure and providing routine heart health checks for high-risk individuals should be a focus.

Key Risk Profile Identified
The individuals most at risk are those aged 50+, who currently smoke, are hypertensive, or have a history of heart-related conditions. Excessive alcohol consumption was also linked to a slightly increased risk.
Recommendation: Tailored health education and support should be given to individuals who fall into this risk group. Early intervention can significantly reduce heart attack incidence in these cases.

No Significant Link to Certain Lifestyle Factors
Surprisingly, variables such as air pollution, income level, region (rural or urban), and regular physical exercise showed no strong correlation with heart attack occurrence in this dataset.
Recommendation: While these factors may still influence overall health, more focused research may be needed to explore their indirect effects. In the meantime, interventions should concentrate on the proven risk factors.

![Screenshot 2025-04-17 145137](https://github.com/user-attachments/assets/1ce09d9a-d99b-4188-be49-fcecfe3be68e)

### End Note

Please see the excel file for the project in the repository files






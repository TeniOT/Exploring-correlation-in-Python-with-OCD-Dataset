# Understanding Obsessive-Compulsive Disorder (OCD) Trends with Data Analysis

![Causes-of-OCD image resize](https://github.com/TeniOT/Understanding-Obsessive-Compulsive-Disorder-OCD-Trends-A-Data-Analysis/assets/164643376/1a08941d-5635-463c-8e65-9d53e8264732)

Photo by emotionalwellnesclinic.co.uk



## Table of Contents
- [Introduction](#introduction)
- [Dataset Overview](#dataset-overview)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Key Findings](#key-findings)
- [Conclusion](#conclusion)
- [Recommendations](#recommendations)
- [References](#references)



## Introduction
Obsessive-Compulsive Disorder (OCD) affects millions of people worldwide. In this statistical correlation analysis, we explore trends related to OCD using a dataset collected from various sources. The goal is to gain insights into the prevalence, symptoms, and potential risk factors associated with OCD.


### Dataset Overview

- **Source**: The dataset combines survey responses, clinical records, and research studies related to OCD.
 [View Dataset](https://www.kaggle.com/datasets/ohinhaque/ocd-patient-dataset-demographics-and-clinical-data/)
- **Variables**: It includes information on demographics, symptom severity, treatment methods, and comorbidities.
- **Size**: The dataset contains 1500 rows and 17 columns.
- **Tools**: Python [pandas, seaborn, matplotlib] via Jupyter Notebook and PowerBI

----

### Exploratory Data Analysis
1. Demographics:
    - Started by examining the distribution of gender and ethnicity among individuals with OCD.
    - Visualised gender and ethnicity proportions using bar charts.


2. Number of Patients with OCD:
    - Investigate the number of patients diagnosed with OCD per month.
    - Calculate mean severity scores and identify any patterns.


3. Symptom Severity:
    - Explore the number of patients with OCD by Y-BOCS Score (Obsessions) and Y-BOCS Score (Compulsions) by gender.


4. The Most Common Type of OCD
    - Explored the Most common type of OCD diagnosed


5. Treatment Methods:
    - Analyse the number of different treatment approaches (medication or none.
    - Compare remission rates and relapse rates across treatments.

6. Using the Pearson correlation heatmap matrix, there were no correlation found between any of the data parameters, therefore there was no significant factors influencing the dataset.
   
   ![corr resize](https://github.com/TeniOT/Exploring-correlation-in-Python-with-OCD-Dataset/assets/164643376/66ee4722-9220-4750-9cee-c729051b89f0)

---


### Key Findings
![page 1 resize](https://github.com/TeniOT/Understanding-Obsessive-Compulsive-Disorder-OCD-Trends-A-Data-Analysis/assets/164643376/eb633b01-8ef6-4e4c-bf05-3f08d5cd3f37)

I. Demographics:
- Individuals aged **25-34 years** show the highest prevalence of OCD.
- **Females** are slightly more affected than males.
- **Caucasians** show more prevalence for OCD with 26.53%, slightly followed by **_Hispanics_** with 26.13%.
- **Africans** show the lowest number of OCD diagnoses.

II. Number of Patients with OCD:
- In general, the highest number of Diagnosis were recorded in January. 
- Number of patients diagnosis rose significantly in the year 2018 with a slight fall in 2019 and maintained an almost stable state till 2022.

![pg 2 resize](https://github.com/TeniOT/Understanding-Obsessive-Compulsive-Disorder-OCD-Trends-A-Data-Analysis/assets/164643376/4e399aa5-3426-4001-8542-ac1a1dd9479f)


III. Symptom Severity:
- Females had the highest number of Y-BOCS Score (Obsessions) compared to male.
- But, Males have the highest number of Y-BOCS Score (Compulsions) compared to Female.

IV. Most Common Type of OCD
- Most participants report moderate to severe symptoms.
- Harm-related is the most common type of obsession symptom
- Washing is the most common type of compulsion symptom.
- Anxiety and depression seem to frequently co-occur with OCD.
- Addressing these comorbidities is essential for comprehensive treatment.

V. Treatment Insights:
- There is a equal number of patients with NONE medication therapy treatment and patients treated with Benzodiazepines.
- The most prescribed medication is Benzodiazepines.
- Further research is needed to explore the most prescribed Benzodiazepines by name (e.g. brand, generic or proprietary).

---

### Conclusion
- Understanding OCD trends is crucial for improving diagnosis, treatment, and support for affected individuals. OCD seems to be more predominant in the Female population and Caucasians.
- The short decline in diagnosis in the year 2019 and stable till 2022 could be due to operational closures and lockdown from COVID-19.


### Recommendations
- Further research should explore genetic factors, environmental triggers, and personalised interventions for OCD diagnosis
- More research needs to be done to analyse the low count of Africans in OCD diagnosis and if genetics, family or environment play a huge role.


### References
- [Kaggle](https://www.kaggle.com/datasets/ohinhaque/ocd-patient-dataset-demographics-and-clinical-data/)
- To learn more about OCD [Visit NHS.UK](https://www.nhs.uk/mental-health/conditions/obsessive-compulsive-disorder-ocd/overview/)



# Understanding Obsessive-Compulsive Disorder (OCD) Trends: A Data Analysis

![corr resize](https://github.com/TeniOT/Exploring-correlation-in-Python-with-OCD-Dataset/assets/164643376/66ee4722-9220-4750-9cee-c729051b89f0)


## Table of Contents
- [Introduction](#introduction)
- [Dataset Overview](#dataset-overview)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Key Findings](#key-findings)
- [Conclusion](#conclusion)
- [References](#references)

## Introduction
Obsessive-Compulsive Disorder (OCD) affects millions of people worldwide. In this data analysis, we explore trends related to OCD using a dataset collected from various sources. Our goal is to gain insights into the prevalence, symptoms, and potential risk factors associated with OCD.

### Dataset Overview
- **Source**: The dataset combines survey responses, clinical records, and research studies related to OCD.  [View Dataset](https://www.kaggle.com/datasets/ohinhaque/ocd-patient-dataset-demographics-and-clinical-data/)
- **Variables**: It includes information on demographics, symptom severity, treatment methods, and comorbidities.
- **Size**: The dataset contains 1500 rows and 17 columns.
- **Tools**: Python [pandas, seaborn, matplotlib] via Jupyter Notebook


### Exploratory Data Analysis
1. Demographics:
    - We start by examining the distribution of gender and ethnicity among individuals with OCD.
    - Visualised gender and ethnicity proportions using bar charts.


2. Number of Patients with OCD:
    - Investigate the number of patients diagnosed with OCD per month.
    - Calculate mean severity scores and identify any patterns.


3. Symptom Severity:
    - Explore number of patients with OCD by Y-BOCS Score (Obsessions) and Y-BOCS Score (Compulsions) by gender.


4. Most Common Type of OCD
    - Explored the Most common type of OCD diagnosed


5. Treatment Methods:
    - Analyse the number of different treatment approaches (medication or none.
    - Compare remission rates and relapse rates across treatments.



### Key Findings
I. Age and Gender:
- Individuals aged 25-34 show the highest prevalence of OCD.
- Females are slightly more affected than males.

II. Number of Patients with OCD:
- In general, the highest number of Diagnosis were recorded in the month of January 
- Month of January has the highest number of Diagnosis for Female (by age) but Month of August for Male (by age)

III. Symptom Severity:
- Females have the highest number of Y-BOCS Score (Obsessions) compared to Male
- But, Males have the highest number of Y-BOCS Score (Compulsions) compared to Female

IV. Most Common Type of OCD
- Most participants report moderate to severe symptoms.
- Harm-related is most common type of obsession symptom
- Washing is the most common type of compulsion symptom.
- Anxiety and depression seem to frequently co-occur with OCD.
- Addressing these comorbidities is essential for comprehensive treatment.

V. Treatment Insights:
- There is a equal number of patients with no medication therapy treatment and patients treated with Benzodiazepams
- Most prescribed medication is Benzodiazepams.
- Further research is needed to explore the most prescribed Benzodiazepam by name (e.g. brand, generic or proprietary).

### Conclusion
Understanding OCD trends is crucial for improving diagnosis, treatment, and support for affected individuals. Further research should explore genetic factors, environmental triggers, and personalised interventions.


### References
[Kaggle](https://www.kaggle.com/datasets/ohinhaque/ocd-patient-dataset-demographics-and-clinical-data/)



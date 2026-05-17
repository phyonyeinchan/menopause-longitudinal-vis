# Menopausal Symptoms and Cardiovascular Health: A Longitudinal Analysis

## Background / Objective
Menopause is a critical biological transition characterized by significant hormonal fluctuations and the onset of bothersome vasomotor symptoms (VMS), such as hot flashes and night sweats. Emerging clinical evidence suggests that VMS may not just be transient quality-of-life issues, but potential indicators of underlying cardiovascular disease (CVD) risk. 

The objective of this project is to model the longitudinal trajectories of menopausal symptoms over a multi-year follow-up period and investigate their statistical association with subclinical cardiovascular health markers (e.g., systolic blood pressure and lipid profiles). This project simulates and analyzes large-scale epidemiological data to mimic complex cohort studies.

## Dataset
The analysis leverages a synthesized longitudinal cohort dataset structured to replicate public medical repositories like the **Study of Women's Health Across the Nation (SWAN)**, available through data archives such as the [National Institute on Aging (NIA) Data Sharing Repository](https://nih.gov) or [ICPSR](https://umich.edu). 
*Note: Due to data privacy regulations regarding human subject research, the script contains a reproducible data-generation module that matches real-world epidemiological distributions.*

## Methods Used
*   **Programming Language:** R v4.3+
*   **Data Manipulation & Visualization:** `tidyverse`, `ggplot2`, `dplyr`, `tidyr`
*   **Statistical Modeling:** Linear Mixed-Effects Models (`lme4`) to account for within-subject correlation in longitudinal data.
*   **Dynamic Reporting:** R Markdown (`knitr`)

## Key Findings
1.  **Symptom Trajectories:** Vasomotor symptoms (VMS) peak significantly during the late perimenopausal phase and gradually decline post-menopause, showing a non-linear trajectory over time.
2.  **Cardiovascular Correlation:** High-severity VMS trajectories are positively correlated with an accelerated rise in systolic blood pressure ($SBP$) during the menopausal transition ($p < 0.05$).
3.  **Metabolic Changes:** Longitudinal models confirm a synchronized increase in Total Cholesterol levels alongside worsening night sweat severity, independent of chronological aging.

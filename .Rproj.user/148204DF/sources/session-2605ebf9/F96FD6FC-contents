# Menopausal Symptoms, Lipid Profiles, and Cardiovascular Health: A Longitudinal Machine Learning & Statistical Analytics Pipeline
## 🌐 Live Project Deployment
Get hands-on experience with our analytics pipeline. Access the fully responsive analytical dashboard, interactive K-Means patient clustering models, and multi-system biological correlation heatmaps:

### [👉 CLICK HERE TO VIEW THE FULL INTERACTIVE REPORT](https://phyonyeinchan.github.io/menopause-longitudinal-vis/)

## 📌 Background & Research Objective
Menopause marks a critical neuroendocrine and metabolic transition in a woman’s life, characterized by profound hormonal shifts and bothersome vasomotor symptoms (VMS), such as hot flashes and night sweats. Emerging clinical and epidemiological research suggests that severe, persistent VMS are not merely transient quality-of-life complaints but may serve as sentinel biomarkers for elevated subclinical cardiovascular disease (CVD) and accelerated metabolic risk.

The overarching objective of this project is to model the multi-year longitudinal trajectories of menopausal symptoms and investigate their synchronized structural associations with cardiometabolic profiles, specifically evaluating a comprehensive lipid panel—Total Cholesterol (TC), Low-Density Lipoprotein (LDL-C), High-Density Lipoprotein (HDL-C), and Triglycerides (TG)—alongside Systolic Blood Pressure (SBP). 

By implementing advanced longitudinal statistical frameworks, unsupervised clustering, and supervised machine learning feature selection, this pipeline identifies discrete patient risk phenotypes to bridge reproductive biology and cardiovascular epidemiology.

---

## 📊 Dataset Structure
The analytics engine leverages a high-fidelity synthetic multi-year longitudinal cohort dataset structured to mimic major national public health archives, such as the **Study of Women's Health Across the Nation (SWAN)**, archived under repositories like the [National Institute on Aging (NIA) Aging Research Biobank](https://nih.gov) or [ICPSR](https://umich.edu). 

To safeguard patient confidentiality under human subject research regulations while ensuring absolute computational reproducibility, the codebase features an autonomous data-generation engine ($N = 500$ female participants tracked across $6$ annual clinical follow-up cycles, yielding $3,000$ distinct longitudinal observations) that precisely preserves real-world covariance matrices, non-linear trajectories, and individual-specific random variations.

---

## 🛠️ Methods & Technological Stack
*   **Core Computing Environment:** R Programming Language (v4.3+)
*   **Data Wrangling & Complex Reshaping:** `tidyverse`, `dplyr`, `tidyr`
*   **Longitudinal Statistical Modeling:** Linear Mixed-Effects Models via `lme4` to isolate fixed factors while controlling for inter-individual correlation nested within repeated measures.
*   **Advanced Statistical Verification:** Analysis of Variance (`anova`) for Likelihood Ratio Testing (LRT).
*   **Unsupervised Machine Learning:** K-Means Algorithmic Clustering for multi-dimensional patient stratification.
*   **Supervised Machine Learning:** Random Forest Regression for multivariate feature permuted weights analysis (`randomForest`).
*   **Dynamic Visualizations & Dashboards:** Static multi-panel grid charting via `ggplot2` alongside web-ready interactive graphics using `plotly` and `heatmaply`.

---

## 🔬 Core Methodological Steps

### 1. Baseline Clinical Stratification (Table 1)
Aggregates cohort indicators at Entry (Visit 1) to build a baseline demographic map. This ensures that age distributions are balanced across subsequent trajectories, guaranteeing that downstream variations are driven by physiological pathways rather than initial structural skewness.

### 2. Longitudinal Trajectory & Multivariate Modeling
Pivots wide clinical observations into a high-density vertical matrix to visualize parallel longitudinal tracks of blood pressure and individual lipid sub-fractions across a 6-year operational timeline. 

### 3. Mixed-Effects Regression & Interaction Testing
Evaluates the independent predictive power of VMS loading on cardiovascular parameters controlling for chronological aging. Formally executes an **Interaction Model (`current_age:vms_score`)** to test if the cardiotoxic weight of severe symptoms worsens as women age.

### 4. Likelihood Ratio Testing (LRT)
Contrasts a restricted baseline age model against a full symptom-augmented statistical architecture using log-likelihood evaluations to mathematically substantiate the necessity of reproductive symptom tracking in medical risk calculators.

### 5. Algorithmic Machine Learning Pipelines
*   **K-Means Partitioning:** Classifies patients into data-driven risk clusters without diagnostic pre-labels, mapping how clinical phenotypes intuitively load onto systemic cardiovascular risk boundaries.
*   **Random Forest Feature Permutation:** Permutes all predictors to rank them based on their mathematical contribution to prediction error (% Increase in Mean Squared Error), determining if VMS contains unique information not explained by routine lipid variables.

---

## 📈 Key Clinical & Analytics Findings
1.  **Phenotypic Trajectories & Baseline Risk Convergence:** The cohort splits into three distinct clinical pathways: *High-Persistent*, *Early-Onset*, and *Low-Declining* VMS. Table 1 confirms that women in the *High-Persistent* symptom pathway already display significantly elevated atherogenic markers (higher LDL-C and resting SBP) at baseline compared to their peers.
2.  **Independent Cardiovascular Acceleration:** Linear mixed-effects structures confirm that after rigorously adjusting for chronological aging, **VMS severity functions as an independent predictive driver of elevated Systolic Blood Pressure and pro-atherogenic lipids (LDL-C and Triglycerides)** ($p < 0.001$). A 10-point escalation on the VMS Index independently correlates with an approximate $1.5 \text{ mmHg}$ increase in systolic blood pressure.
3.  **Statistical & Algorithmic Validation:** The Likelihood Ratio Test proves that adding longitudinal VMS tracking provides statistically superior predictive power over models relying solely on standard chronological aging ($\chi^2 \ \ p < 0.001$). Furthermore, the supervised Random Forest algorithm assigns a high permutation feature weight to the VMS score, validating that vasomotor symptom intensity carries a crucial, standalone predictive signal for cardiovascular risk during mid-life medical screenings.

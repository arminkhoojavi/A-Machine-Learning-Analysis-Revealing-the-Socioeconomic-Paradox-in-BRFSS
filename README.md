# Predictors of Smoking Cessation in the U.S.: A Machine Learning Analysis

**Project Title:** Predictors of Smoking Cessation in the U.S.: A Machine Learning Analysis Revealing the Socioeconomic Paradox in BRFSS Data (2018-2023)

**Team Memmbers:** Armin KHoojavi, Hamed Hesami, Mahdieh Ebrahimi

**Project Type & Duration:** Team Project (Academic Project), Summer 2025



## **Objective**

This research aimed to provide a deep, multifaceted, and stable understanding of factors influencing successful smoking cessation in adults. Utilizing extensive BRFSS survey data from a six-year period (2018-2023), the goal was to derive data-driven evidence for designing personalized public health interventions.



## **Methodology**

This longitudinal study leveraged a suite of machine learning models for smoking cessation prediction, including:
* **Logistic Regression**
* **LDA**
* **Decision Tree**
* **LightGBM**
* **CatBoost**
* **XGBoost**

Model performance was rigorously evaluated comparing a "full features" strategy against a "VIF-based feature reduction" approach. To enhance prediction accuracy and stability, comprehensive modeling techniques were implemented:
* **Data Pooling**
* **Temporal Ensemble**
* **Stacking Ensemble** (specifically utilized for its superior predictive power)

The influence and directionality of each factor were assessed using **SHAP (SHapley Additive exPlanations) analysis**, also examining their stability over time.



## **Key Contributions**

* **Developed and evaluated** multiple advanced machine learning models, with the **Stacking Ensemble** model achieving superior overall performance:
    * **AUC:** 0.7881
    * **Accuracy:** 0.7446
    * **F1-Score:** 0.7330
* **Identified and validated** remarkably stable key predictors of smoking cessation across the six-year study period. These included:
    * Older age (consistently the strongest factor increasing successful cessation probability).
    * Being married.
    * Higher levels of income and education.
    * Higher BMI and increased weight.
* **Contributed to robust data-driven insights** for public health policy and tobacco control by emphasizing the necessity of personalized, multi-faceted interventions. Insights focused on specific age groups and an integrated approach to supporting mental health, physical health, and socioeconomic factors.



## **Technologies Used**

* **Programming Languages:** Python
* **Machine Learning Libraries:** scikit-learn, LightGBM, CatBoost, XGBoost
* **Interpretability:** SHAP
* **Data Manipulation & Analysis:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn


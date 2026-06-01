# Data Analysis and Machine Learning Portfolio

This portfolio showcases projects in data analysis, SQL, dashboarding, machine learning, model deployment, and model reliability.

My work focuses on applying statistical and machine learning methods to real-world datasets, with an emphasis on reproducible workflows, clear communication, practical evaluation, and interpretable results.

---

## Diabetes Risk Reliability Analysis with PyTorch

Extended a previous scikit-learn diabetes risk prediction pipeline into a PyTorch-based reliability analysis project focused on clinical risk screening under severe class imbalance.

This project compares a Random Forest baseline with a class-weighted PyTorch multilayer perceptron and evaluates the model beyond standard accuracy metrics. The analysis includes threshold tuning, calibration curves, Brier Score, Platt scaling, and Monte Carlo Dropout uncertainty estimation.

This project extends my previous scikit-learn deployment project by shifting the focus from production deployment to model reliability, calibration, and uncertainty analysis.

Key highlights:

* Built a PyTorch MLP for binary diabetes risk prediction using class-weighted `BCEWithLogitsLoss`
* Compared PyTorch performance against a scikit-learn Random Forest baseline
* Evaluated screening-oriented thresholds to prioritize recall
* Found that raw PyTorch probabilities overestimated risk across calibration bins
* Applied Platt scaling, improving Brier Score from 0.1804 to 0.1063 while preserving ROC-AUC
* Used Monte Carlo Dropout to estimate predictive uncertainty and identify less reliable prediction groups

Tools used: Python, PyTorch, scikit-learn, pandas, NumPy, matplotlib

* **GitHub Repository:** [Diabetes Risk Reliability Analysis with PyTorch](https://github.com/jayjay0317/diabetes-risk-reliability-pytorch){:target="_blank" rel="noopener noreferrer"}

---

## Diabetes ML Pipeline and Deployment

Built an end-to-end diabetes risk prediction system using scikit-learn and deployed it as an interactive machine learning application.

This project focused on the full machine learning workflow, including data preprocessing, class imbalance handling, model training, threshold optimization, API development, containerization, and cloud deployment.

Key highlights:

* Built a diabetes risk prediction model using scikit-learn
* Compared machine learning models and selected a Random Forest-based pipeline
* Used threshold tuning to improve recall for preventative screening
* Developed a Flask API for model inference
* Built a Streamlit interface for interactive risk prediction
* Containerized the application using Docker
* Deployed the system using AWS infrastructure

Tools used: Python, scikit-learn, pandas, NumPy, Flask, Streamlit, Docker, AWS

* **GitHub Repository:** [Diabetes ML Pipeline Analysis](https://github.com/jayjay0317/Diabetes-ML-Pipeline-Analysis){:target="_blank" rel="noopener noreferrer"}

---

## Olist E-commerce Analysis

Analyzed the Olist Brazilian e-commerce dataset to uncover key business insights related to sales trends, product performance, regional distribution, operational efficiency, and customer loyalty.

This end-to-end project used PostgreSQL for data extraction and transformation, with Tableau dashboards developed to communicate business findings and strategic recommendations.

Key highlights:

* Analyzed sales trends, delivery performance, product categories, and customer behavior
* Used SQL to extract, transform, and aggregate business data
* Built Tableau dashboards for executive overview, product analysis, and customer insights
* Developed recommendations for growth and operational improvement

Tools used: PostgreSQL, SQL, Tableau

* **GitHub Repository:** [Olist E-commerce Analysis Project Repository](https://github.com/jayjay0317/Olist-E-Commerce-analysis){:target="_blank" rel="noopener noreferrer"}
* **Interactive Dashboard:**

  * [Key Overview](https://public.tableau.com/views/OlistDashboard-KeyOverview/ExecutiveOverview?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link){:target="_blank" rel="noopener noreferrer"}
  * [Product & Market Analysis](https://public.tableau.com/views/OlistDashboard-ProductMarket/ProductMarket?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link){:target="_blank" rel="noopener noreferrer"}
  * [Customer Insights](https://public.tableau.com/views/OlistDashboard-CustomerInsights/CustomerSegmentationValue?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link){:target="_blank" rel="noopener noreferrer"}

---

## Games and Academic Success

Analyzed a dataset containing student demographics, gaming habits, family background, and academic performance to explore factors associated with student grades.

This project used SQL for data cleaning and exploratory analysis, and Tableau for visualization. The analysis compared gaming behavior with academic outcomes while also considering family income and parental education.

Key highlights:

* Cleaned and transformed student survey data using SQL
* Compared academic performance between gamers and non-gamers
* Analyzed relationships between grades, gaming habits, income, and parental education
* Built Tableau visualizations to communicate key patterns

Tools used: SQL, Tableau

* **Project Notebook:** [Games and Academic Success](games_and_academic_success.html){:target="_blank" rel="noopener noreferrer"}
* **Tableau Dashboard:** [Games and Academic Success Dashboard](https://public.tableau.com/app/profile/jaewoo.lee/viz/GamesandAcademicSuccess/Dashboard1?publish=yes){:target="_blank" rel="noopener noreferrer"}

---

## Spotify User Behaviour

Analyzed Spotify user behavior and demographic data to explore listening patterns, subscription preferences, and user engagement.

This project focused on exploratory data analysis using Python, including summary statistics, visualization, and statistical comparison of user behavior patterns.

Key highlights:

* Cleaned and explored Spotify user behavior data
* Analyzed subscription preferences and user engagement patterns
* Created visualizations to identify behavioral differences across user groups
* Practiced Python-based exploratory data analysis and statistical testing

Tools used: Python, NumPy, pandas, matplotlib, seaborn, SciPy

* **Project Notebook:** [Spotify User Behaviour](Spotify_user_behaviour.html){:target="_blank" rel="noopener noreferrer"}

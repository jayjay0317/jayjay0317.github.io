
## CNN Robustness and Generalization under Image Corruption

**Description**

Investigated whether standard geometric data augmentation improves CNN robustness to unseen image corruptions on CIFAR-10.

A baseline CNN and an augmented CNN were trained under identical conditions and evaluated across Gaussian noise, Gaussian blur, and brightness shifts. The experiment showed that random cropping and horizontal flipping preserved clean classification performance but did not improve robustness to the unseen corruptions tested.

**Highlights**

- Trained baseline and augmented CNNs in PyTorch using the same architecture and optimization settings
- Evaluated model performance across multiple severity levels of Gaussian noise, blur, and brightness shifts
- Found that geometric augmentation maintained similar clean accuracy but consistently underperformed the baseline under noise and blur
- Visualized robustness degradation across corruption conditions and documented experimental limitations and future extensions


## Diabetes Risk Reliability Analysis with PyTorch

**Description**

Developed a PyTorch-based diabetes risk prediction project focused on model reliability under severe class imbalance.

Compared a class-weighted neural network with a scikit-learn Random Forest baseline and evaluated the models beyond standard classification metrics through threshold tuning, probability calibration, and uncertainty estimation.

**Highlights**

- Built a multilayer perceptron using class-weighted `BCEWithLogitsLoss` to address severe class imbalance
- Compared PyTorch performance with a Random Forest baseline using consistent train, validation, and test splits
- Applied Platt scaling, improving the Brier Score from 0.1804 to 0.1063 while preserving discrimination performance
- Used Monte Carlo Dropout to estimate predictive uncertainty and examine less reliable prediction groups


## Olist E-commerce Analysis

**Description**

Analyzed more than 100,000 Brazilian e-commerce orders to identify patterns in sales, product performance, delivery efficiency, regional activity, and customer behavior.

Used PostgreSQL for data analysis and Tableau to translate the findings into interactive dashboards and business recommendations.

**Highlights**

- Used joins, CTEs, aggregations, and window functions to calculate business and operational metrics
- Identified an 8.11% delivery delay rate and a 3.00% customer repurchase rate
- Built Tableau dashboards covering executive performance, products and markets, and customer behavior
- Developed recommendations related to customer retention, logistics performance, product strategy, and regional growth


## Diabetes ML Pipeline and Deployment

**Description**

Built an end-to-end machine learning pipeline for diabetes risk prediction, covering model development through deployment.

The project combined scikit-learn modeling with threshold optimization, API development, an interactive user interface, containerization, and cloud deployment.

**Highlights**

- Built and tuned a Random Forest model for diabetes risk prediction using scikit-learn
- Adjusted the classification threshold to prioritize recall for preventive risk screening
- Developed a Flask API and Streamlit interface for interactive model inference
- Containerized the application with Docker and deployed the pipeline using AWS infrastructure


## Games and Academic Success

**Description**

Analyzed student demographics, gaming behavior, family background, and academic performance to explore factors associated with student grades.

Used SQL for data cleaning, transformation, and exploratory analysis, and Tableau to communicate relationships between gaming patterns and academic outcomes.

**Highlights**

- Cleaned and transformed survey data by addressing inconsistent values, duplicates, and formatting issues
- Compared academic performance between gamers and non-gamers and across different levels of gaming activity
- Explored relationships between grades, family income, parental education, and gaming behavior
- Built Tableau visualizations to communicate key patterns and the limitations of the available data


## Spotify User Behaviour

**Description**

Explored Spotify user behavior and demographic data to better understand listening habits, subscription preferences, and engagement patterns.

Used Python for data cleaning, exploratory analysis, visualization, and statistical comparison across user groups.

**Highlights**

- Cleaned and explored user behavior and demographic data using pandas and NumPy
- Analyzed patterns in subscription preferences, listening behavior, and user engagement
- Created visualizations to compare behavioral differences across demographic and user groups
- Applied statistical comparisons to support and interpret exploratory findings

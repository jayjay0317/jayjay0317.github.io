<style>
.wrapper {
  width: 1080px;
}

header {
  width: 240px;
}

section {
  width: 760px;
}

footer {
  width: 240px;
}

@media print, screen and (max-width: 960px) {
  .wrapper {
    width: auto;
  }

  header,
  section,
  footer {
    width: auto;
  }
}

.hero {
  margin-bottom: 32px;
}

.hero h1 {
  margin-bottom: 8px;
}

.hero-subtitle {
  font-size: 1.08rem;
  color: #444;
  line-height: 1.6;
}

.project-grid {
  display: grid;
  gap: 22px;
  margin-top: 24px;
}

.project-card {
  border: 1px solid #e5e7eb;
  border-radius: 14px;
  padding: 22px;
  background: #ffffff;
  box-shadow: 0 3px 10px rgba(0, 0, 0, 0.06);
}

.project-card h2 {
  margin-top: 0;
  margin-bottom: 8px;
}

.project-type {
  font-size: 0.9rem;
  font-weight: 600;
  color: #0366d6;
  margin-bottom: 12px;
}

.project-card p {
  line-height: 1.6;
}

.project-card ul {
  margin-top: 10px;
}

.project-card li {
  margin-bottom: 6px;
}

.tools {
  margin-top: 14px;
  font-size: 0.95rem;
  color: #333;
}

.project-links {
  margin-top: 16px;
}

.project-links a {
  display: inline-block;
  margin: 6px 8px 0 0;
  padding: 8px 12px;
  border-radius: 7px;
  background: #0366d6;
  color: #ffffff;
  text-decoration: none;
  font-size: 0.92rem;
}

.project-links a:hover {
  background: #024f9c;
}

.secondary-link {
  background: #4b5563 !important;
}

.secondary-link:hover {
  background: #374151 !important;
}
</style>

<div class="hero">

# Project Portfolio

<p class="hero-subtitle">
A collection of applied data analysis and machine learning projects using Python, SQL, PyTorch, scikit-learn, Tableau, and deployment tools.
</p>

<p class="hero-subtitle">
These projects focus on reproducible workflows, practical model evaluation, clear communication, and turning real-world datasets into useful insights.
</p>

</div>

## Featured Projects

<div class="project-grid">

<div class="project-card">

<h2>Diabetes Risk Reliability Analysis with PyTorch</h2>

<div class="project-type">Machine Learning · PyTorch · Model Reliability</div>

<p>
Extended a previous scikit-learn diabetes risk prediction pipeline into a PyTorch-based reliability analysis project focused on clinical risk screening under severe class imbalance.
</p>

<p>
This project compares a Random Forest baseline with a class-weighted PyTorch multilayer perceptron and evaluates the model beyond standard accuracy metrics. The analysis includes threshold tuning, calibration curves, Brier Score, Platt scaling, and Monte Carlo Dropout uncertainty estimation.
</p>

<ul>
  <li>Built a PyTorch MLP for binary diabetes risk prediction using class-weighted <code>BCEWithLogitsLoss</code></li>
  <li>Compared PyTorch performance against a scikit-learn Random Forest baseline</li>
  <li>Applied Platt scaling, improving Brier Score from 0.1804 to 0.1063 while preserving ROC-AUC</li>
  <li>Used Monte Carlo Dropout to estimate predictive uncertainty and identify less reliable prediction groups</li>
</ul>

<p class="tools"><strong>Tools:</strong> Python, PyTorch, scikit-learn, pandas, NumPy, matplotlib</p>

<div class="project-links">
  <a href="https://github.com/jayjay0317/diabetes-risk-reliability-pytorch" target="_blank" rel="noopener noreferrer">GitHub Repository</a>
</div>

</div>

<div class="project-card">

<h2>Diabetes ML Pipeline and Deployment</h2>

<div class="project-type">Machine Learning · Deployment · End-to-End Pipeline</div>

<p>
Built an end-to-end diabetes risk prediction system using scikit-learn and deployed it as an interactive machine learning application.
</p>

<p>
This project focused on the full machine learning workflow, including data preprocessing, class imbalance handling, model training, threshold optimization, API development, containerization, and cloud deployment.
</p>

<ul>
  <li>Built a diabetes risk prediction model using scikit-learn</li>
  <li>Used threshold tuning to improve recall for preventative screening</li>
  <li>Developed a Flask API for model inference</li>
  <li>Built a Streamlit interface for interactive risk prediction</li>
  <li>Containerized the application using Docker and deployed it using AWS infrastructure</li>
</ul>

<p class="tools"><strong>Tools:</strong> Python, scikit-learn, pandas, NumPy, Flask, Streamlit, Docker, AWS</p>

<div class="project-links">
  <a href="https://github.com/jayjay0317/Diabetes-ML-Pipeline-Analysis" target="_blank" rel="noopener noreferrer">GitHub Repository</a>
</div>

</div>

<div class="project-card">

<h2>Olist E-commerce Analysis</h2>

<div class="project-type">SQL · Tableau · Business Analytics</div>

<p>
Analyzed the Olist Brazilian e-commerce dataset to uncover key business insights related to sales trends, product performance, regional distribution, operational efficiency, and customer loyalty.
</p>

<p>
This end-to-end project used PostgreSQL for data extraction and transformation, with Tableau dashboards developed to communicate business findings and strategic recommendations.
</p>

<ul>
  <li>Analyzed sales trends, delivery performance, product categories, and customer behavior</li>
  <li>Used SQL to extract, transform, and aggregate business data</li>
  <li>Built Tableau dashboards for executive overview, product analysis, and customer insights</li>
  <li>Developed recommendations for growth and operational improvement</li>
</ul>

<p class="tools"><strong>Tools:</strong> PostgreSQL, SQL, Tableau</p>

<div class="project-links">
  <a href="https://github.com/jayjay0317/Olist-E-Commerce-analysis" target="_blank" rel="noopener noreferrer">GitHub Repository</a>
  <a class="secondary-link" href="https://public.tableau.com/views/OlistDashboard-KeyOverview/ExecutiveOverview?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link" target="_blank" rel="noopener noreferrer">Key Overview</a>
  <a class="secondary-link" href="https://public.tableau.com/views/OlistDashboard-ProductMarket/ProductMarket?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link" target="_blank" rel="noopener noreferrer">Product & Market</a>
  <a class="secondary-link" href="https://public.tableau.com/views/OlistDashboard-CustomerInsights/CustomerSegmentationValue?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link" target="_blank" rel="noopener noreferrer">Customer Insights</a>
</div>

</div>

<div class="project-card">

<h2>Games and Academic Success</h2>

<div class="project-type">SQL · Tableau · Exploratory Analysis</div>

<p>
Analyzed a dataset containing student demographics, gaming habits, family background, and academic performance to explore factors associated with student grades.
</p>

<p>
This project used SQL for data cleaning and exploratory analysis, and Tableau for visualization. The analysis compared gaming behavior with academic outcomes while also considering family income and parental education.
</p>

<ul>
  <li>Cleaned and transformed student survey data using SQL</li>
  <li>Compared academic performance between gamers and non-gamers</li>
  <li>Analyzed relationships between grades, gaming habits, income, and parental education</li>
  <li>Built Tableau visualizations to communicate key patterns</li>
</ul>

<p class="tools"><strong>Tools:</strong> SQL, Tableau</p>

<div class="project-links">
  <a href="games_and_academic_success.html" target="_blank" rel="noopener noreferrer">Project Notebook</a>
  <a class="secondary-link" href="https://public.tableau.com/app/profile/jaewoo.lee/viz/GamesandAcademicSuccess/Dashboard1?publish=yes" target="_blank" rel="noopener noreferrer">Tableau Dashboard</a>
</div>

</div>

<div class="project-card">

<h2>Spotify User Behaviour</h2>

<div class="project-type">Python · Exploratory Data Analysis</div>

<p>
Analyzed Spotify user behavior and demographic data to explore listening patterns, subscription preferences, and user engagement.
</p>

<p>
This project focused on exploratory data analysis using Python, including summary statistics, visualization, and statistical comparison of user behavior patterns.
</p>

<ul>
  <li>Cleaned and explored Spotify user behavior data</li>
  <li>Analyzed subscription preferences and user engagement patterns</li>
  <li>Created visualizations to identify behavioral differences across user groups</li>
  <li>Practiced Python-based exploratory data analysis and statistical testing</li>
</ul>

<p class="tools"><strong>Tools:</strong> Python, NumPy, pandas, matplotlib, seaborn, SciPy</p>

<div class="project-links">
  <a href="Spotify_user_behaviour.html" target="_blank" rel="noopener noreferrer">Project Notebook</a>
</div>

</div>

</div>

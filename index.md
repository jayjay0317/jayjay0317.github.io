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
  font-size: 2rem;
  color: #222;
  margin-bottom: 18px;
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
  margin-bottom: 38px;
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

<h1>Project Portfolio</h1>

<p class="hero-subtitle">
Selected projects in data analysis, machine learning, and statistical modeling using Python, SQL, PyTorch, scikit-learn, and Tableau.
</p>

<p class="hero-subtitle">
My work focuses on practical analysis, model evaluation, reliability, and translating data into clear and useful insights.
</p>

</div>

## Featured Projects

<div class="project-grid">

<div class="project-card">

<h2>CNN Robustness and Generalization under Image Corruption</h2>

<div class="project-type">Deep Learning · PyTorch · Robustness Analysis</div>

<p>
Investigated whether standard geometric data augmentation improves CNN robustness to unseen image corruptions on CIFAR-10.
</p>

<p>
A baseline CNN and an augmented CNN were trained under identical conditions and evaluated under Gaussian noise, blur, and brightness shifts to study how augmentation affects generalization beyond clean test performance.
</p>

<ul>
  <li>Trained baseline and augmented CNNs using PyTorch on CIFAR-10</li>
  <li>Evaluated robustness under Gaussian noise, Gaussian blur, and brightness shifts</li>
  <li>Found that geometric augmentation preserved clean accuracy but did not improve robustness to unseen corruptions</li>
  <li>Compared performance degradation across corruption severities and visualized the results</li>
</ul>

<p class="tools"><strong>Tools:</strong> Python, PyTorch, torchvision, NumPy, pandas, matplotlib, scikit-learn</p>

<div class="project-links">
  <a href="https://github.com/jayjay0317/cnn-robustness-generalization" target="_blank" rel="noopener noreferrer">GitHub Repository</a>
</div>

</div>

<div class="project-card">

<h2>Diabetes Risk Reliability Analysis with PyTorch</h2>

<div class="project-type">Machine Learning · PyTorch · Model Reliability</div>

<p>
Built a PyTorch-based diabetes risk prediction project focused on model reliability under severe class imbalance.
</p>

<p>
Compared a Random Forest baseline with a class-weighted multilayer perceptron and evaluated performance using threshold tuning, calibration, Brier Score, Platt scaling, and Monte Carlo Dropout uncertainty estimation.
</p>

<ul>
  <li>Built a PyTorch MLP using class-weighted <code>BCEWithLogitsLoss</code></li>
  <li>Compared performance against a scikit-learn Random Forest baseline</li>
  <li>Improved Brier Score from 0.1804 to 0.1063 using Platt scaling while preserving ROC-AUC</li>
  <li>Used Monte Carlo Dropout to estimate predictive uncertainty and identify less reliable predictions</li>
</ul>

<p class="tools"><strong>Tools:</strong> Python, PyTorch, scikit-learn, pandas, NumPy, matplotlib</p>

<div class="project-links">
  <a href="https://github.com/jayjay0317/diabetes-risk-reliability-pytorch" target="_blank" rel="noopener noreferrer">GitHub Repository</a>
</div>

</div>

<div class="project-card">

<h2>Olist E-commerce Analysis</h2>

<div class="project-type">SQL · Tableau · Business Analytics</div>

<p>
Analyzed more than 100,000 Brazilian e-commerce orders to evaluate sales trends, product performance, regional distribution, delivery efficiency, and customer behavior.
</p>

<p>
Used PostgreSQL for data extraction and transformation and Tableau to communicate business findings through interactive dashboards.
</p>

<ul>
  <li>Analyzed sales trends, delivery performance, product categories, and customer behavior</li>
  <li>Used joins, CTEs, aggregations, and window functions to calculate business metrics</li>
  <li>Built Tableau dashboards covering executive, product, market, and customer insights</li>
  <li>Developed recommendations related to customer retention, logistics, and growth opportunities</li>
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

<h2>Diabetes ML Pipeline and Deployment</h2>

<div class="project-type">Machine Learning · Deployment · End-to-End Pipeline</div>

<p>
Built an end-to-end diabetes risk prediction system using scikit-learn and deployed it as an interactive machine learning application.
</p>

<p>
The project covered preprocessing, class imbalance handling, model training, threshold optimization, API development, containerization, and cloud deployment.
</p>

<ul>
  <li>Built a diabetes risk prediction model using scikit-learn</li>
  <li>Tuned the classification threshold to prioritize recall for preventative screening</li>
  <li>Developed a Flask API and Streamlit interface for model inference</li>
  <li>Containerized the application with Docker and deployed it using AWS infrastructure</li>
</ul>

<p class="tools"><strong>Tools:</strong> Python, scikit-learn, pandas, NumPy, Flask, Streamlit, Docker, AWS</p>

<div class="project-links">
  <a href="https://github.com/jayjay0317/Diabetes-ML-Pipeline-Analysis" target="_blank" rel="noopener noreferrer">GitHub Repository</a>
</div>

</div>

</div>

## Additional Projects

<div class="project-grid">

<div class="project-card">

<h2>Games and Academic Success</h2>

<div class="project-type">SQL · Tableau · Exploratory Analysis</div>

<p>
Analyzed student demographics, gaming habits, family background, and academic performance to explore factors associated with student grades.
</p>

<p>
Used SQL for data cleaning, preprocessing, and exploratory analysis, and Tableau to visualize relationships between gaming behavior, academic outcomes, and family background factors.
</p>

<ul>
  <li>Cleaned and transformed student survey data using SQL</li>
  <li>Compared academic performance between gamers and non-gamers</li>
  <li>Explored relationships between grades, gaming habits, income, and parental education</li>
  <li>Built Tableau visualizations to communicate key patterns and findings</li>
</ul>

<p class="tools"><strong>Tools:</strong> SQL, PostgreSQL, Tableau</p>

<div class="project-links">
  <a href="games_and_academic_success.html" target="_blank" rel="noopener noreferrer">Full Analysis</a>
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
Used Python for data cleaning, exploratory analysis, visualization, and statistical comparison of behavioral patterns across user groups.
</p>

<ul>
  <li>Cleaned and explored Spotify user behavior data</li>
  <li>Analyzed subscription preferences and engagement patterns across user groups</li>
  <li>Created visualizations to identify differences in user behavior</li>
  <li>Applied statistical comparisons to support exploratory findings</li>
</ul>

<p class="tools"><strong>Tools:</strong> Python, pandas, NumPy, matplotlib, seaborn, SciPy</p>

<div class="project-links">
  <a href="Spotify_user_behaviour.html" target="_blank" rel="noopener noreferrer">Full Analysis</a>
</div>

</div>

</div>

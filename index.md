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
My projects focus on data analysis, statistical modeling, machine learning, and turning results into clear, interpretable insights.
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
A baseline CNN and an augmented CNN were trained under identical conditions and evaluated across Gaussian noise, Gaussian blur, and brightness shifts. The experiment showed that random cropping and horizontal flipping preserved clean classification performance but did not improve robustness to the unseen corruptions tested.
</p>

<ul>
  <li>Trained baseline and augmented CNNs in PyTorch using the same architecture and optimization settings</li>
  <li>Evaluated model performance across multiple severity levels of Gaussian noise, blur, and brightness shifts</li>
  <li>Found that geometric augmentation maintained similar clean accuracy but consistently underperformed the baseline under noise and blur</li>
  <li>Visualized robustness degradation across corruption conditions and documented experimental limitations and future extensions</li>
</ul>

<p class="tools"><strong>Tools:</strong> Python, PyTorch, torchvision, NumPy, Matplotlib</p>

<div class="project-links">
  <a href="https://github.com/jayjay0317/cnn-robustness-generalization" target="_blank" rel="noopener noreferrer">GitHub Repository</a>
</div>

</div>

<div class="project-card">

<h2>Diabetes Risk Reliability Analysis with PyTorch</h2>

<div class="project-type">Machine Learning · PyTorch · Model Reliability</div>

<p>
Extended a previous scikit-learn diabetes risk prediction and deployment project into a PyTorch-based study of model reliability under severe class imbalance.
</p>

<p>
Compared a class-weighted neural network with a scikit-learn Random Forest baseline and evaluated the models beyond standard classification metrics through threshold tuning, probability calibration, and uncertainty estimation.
</p>

<ul>
  <li>Built a multilayer perceptron using class-weighted <code>BCEWithLogitsLoss</code> to address severe class imbalance</li>
  <li>Compared PyTorch performance with a Random Forest baseline using consistent train, validation, and test splits</li>
  <li>Applied Platt scaling, improving the Brier Score from 0.1804 to 0.1063 while preserving discrimination performance</li>
  <li>Used Monte Carlo Dropout to estimate predictive uncertainty and examine less reliable prediction groups</li>
</ul>

<p class="tools"><strong>Tools:</strong> Python, PyTorch, scikit-learn, pandas, NumPy, Matplotlib</p>

<div class="project-links">
  <a href="https://github.com/jayjay0317/diabetes-risk-reliability-pytorch" target="_blank" rel="noopener noreferrer">GitHub Repository</a>
</div>

</div>

<div class="project-card">

<h2>Diabetes ML Pipeline and Deployment</h2>

<div class="project-type">Machine Learning · Deployment · End-to-End Pipeline</div>

<p>
Built an end-to-end machine learning pipeline for diabetes risk prediction, covering model development through deployment.
</p>

<p>
The project combined scikit-learn modeling with threshold optimization, API development, an interactive user interface, containerization, and cloud deployment. It later served as the foundation for the PyTorch-based reliability and uncertainty analysis project above.
</p>

<ul>
  <li>Built and tuned a Random Forest model for diabetes risk prediction using scikit-learn</li>
  <li>Adjusted the classification threshold to prioritize recall for preventive risk screening</li>
  <li>Developed a Flask API and Streamlit interface for interactive model inference</li>
  <li>Containerized the application with Docker and deployed the pipeline using AWS infrastructure</li>
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
Analyzed more than 100,000 Brazilian e-commerce orders to identify patterns in sales, product performance, delivery efficiency, regional activity, and customer behavior.
</p>

<p>
Used PostgreSQL for data analysis and Tableau to translate the findings into interactive dashboards and business recommendations.
</p>

<ul>
  <li>Used joins, CTEs, aggregations, and window functions to calculate business and operational metrics</li>
  <li>Identified an 8.11% delivery delay rate and a 3.00% customer repurchase rate</li>
  <li>Built Tableau dashboards covering executive performance, products and markets, and customer behavior</li>
  <li>Developed recommendations related to customer retention, logistics performance, product strategy, and regional growth</li>
</ul>

<p class="tools"><strong>Tools:</strong> SQL, PostgreSQL, Tableau</p>

<div class="project-links">
  <a href="https://github.com/jayjay0317/Olist-E-Commerce-analysis" target="_blank" rel="noopener noreferrer">GitHub Repository</a>
  <a class="secondary-link" href="https://public.tableau.com/views/OlistDashboard-KeyOverview/ExecutiveOverview?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link" target="_blank" rel="noopener noreferrer">Key Overview</a>
  <a class="secondary-link" href="https://public.tableau.com/views/OlistDashboard-ProductMarket/ProductMarket?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link" target="_blank" rel="noopener noreferrer">Product & Market</a>
  <a class="secondary-link" href="https://public.tableau.com/views/OlistDashboard-CustomerInsights/CustomerSegmentationValue?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link" target="_blank" rel="noopener noreferrer">Customer Insights</a>
</div>

</div>

</div>

## Additional Projects

<div class="project-grid">

<div class="project-card">

<h2>Games and Academic Success</h2>

<div class="project-type">SQL · Tableau · Exploratory Analysis</div>

<p>
Analyzed student demographics, gaming behavior, family background, and academic performance to explore factors associated with student grades.
</p>

<p>
Used SQL for data cleaning, transformation, and exploratory analysis, and Tableau to communicate relationships between gaming patterns and academic outcomes.
</p>

<ul>
  <li>Cleaned and transformed survey data by addressing inconsistent values, duplicates, and formatting issues</li>
  <li>Compared academic performance between gamers and non-gamers and across different levels of gaming activity</li>
  <li>Explored relationships between grades, family income, parental education, and gaming behavior</li>
  <li>Built Tableau visualizations to communicate key patterns and the limitations of the available data</li>
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
Explored Spotify user behavior and demographic data to better understand listening habits, subscription preferences, and engagement patterns.
</p>

<p>
Used Python for data cleaning, exploratory analysis, visualization, and statistical comparison across user groups.
</p>

<ul>
  <li>Cleaned and explored user behavior and demographic data using pandas and NumPy</li>
  <li>Analyzed patterns in subscription preferences, listening behavior, and user engagement</li>
  <li>Created visualizations to compare behavioral differences across demographic and user groups</li>
  <li>Applied statistical comparisons to support and interpret exploratory findings</li>
</ul>

<p class="tools"><strong>Tools:</strong> Python, pandas, NumPy, Matplotlib, seaborn, SciPy</p>

<div class="project-links">
  <a href="Spotify_user_behaviour.html" target="_blank" rel="noopener noreferrer">Full Analysis</a>
</div>

</div>

</div>

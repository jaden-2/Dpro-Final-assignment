<div>
  <h1>Inflation Rate Prediction Project</h1>
<p>This repository contains the code and documentation for an inflation rate prediction project developed as part of an introductory course on Machine Learning Engineering at Dpro.</p>
  
<h3>Project Overview</h3>
<p>Inflation forecasting is a critical task in economics and finance, influencing policy-making, investment decisions, and cost-of-living adjustments. This project aims to build a predictive model that accurately forecasts inflation rates using various machine learning techniques.</p>

<h3>Key Features:</h3>
<ul>
  <li>Data Preprocessing: The project includes steps for cleaning, normalizing, and transforming the data, ensuring it is ready for model training.</li>
  <li>
    <strong>Modeling Approaches:</strong> Different modeling strategies were explored:
    <ul>
      <li><strong>XGBoost:</strong> Initially used but faced limitations in extrapolation.</li>
      <li><strong>Bayesian Regression:</strong> Used for capturing trends effectively.</li>
      <li><strong>Hybrid Model:</strong> Combines Bayesian regression for trend modeling and XGBoost for capturing noise in the data.</li>
    </ul>
  </li>
  <li><strong>Feature Engineering:</strong> Features were engineered based on economic indicators, with a focus on the dollar exchange rate, which showed a strong correlation with inflation-related features.</li>
  <li><strong>Evaluation:</strong> The models were evaluated using R² scores, with the final hybrid model achieving a high accuracy.</li>
</ul>

<h3>Repository Structure</h3>
<ul>
  <li><strong>data/:</strong> Contains the dataset(s) used for training and testing the models.</li>
  <li>I<strong>nflationProject:</strong> Notebook containing inflation prediction model</li>
  <li><strong>README.md:</strong> This file, providing an overview of the project.</li>
  <li><strong>Inflation_Prediction_Presentation v2.pptx:</strong> Presentation slide for inflaiton forecast project</li>
</ul>

<h3>Results</h3>
<p>The final model achieved an R² score of 0.992 during testing, demonstrating strong predictive power for inflation rates. The model effectively combines trend analysis and noise capture, providing accurate forecasts under different economic conditions.</p>

<h3>Future Work</h3>
<p>Potential areas for improvement and expansion include:
<ul>
  <li>Exploring more advanced feature engineering techniques.</li>
  <li>Testing additional machine learning models or deep learning approaches.</li>
  <li>Applying the model to other economic indicators for broader economic forecasting.</li>
</ul>
</p>

<h3>Acknowledgments</h3>
<ul>
  <li><strong>Instructor: </strong> Special thanks to the instructors of the Machine Learning Engineering course at Dpro for their guidance.</li>
  <li><strong>Community: </strong>Grateful for the feedback and suggestions from peers and the online machine learning community.</li>
</ul>
</div>

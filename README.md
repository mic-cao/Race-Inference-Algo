<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Race/BPL Prediction</title>
</head>
<body>
  <h1>Race/BPL Prediction</h1>

  <h2>Overview</h2>
  <p>This project, led by Michael Cao, is part of a broader research effort under the Redlining Lab at the Urban Data Research Lab, Cornell University. The Redlining Lab focuses on using big data and spatial data science to understand historical patterns of urban inequality, particularly through the lens of redlining practices in housing markets. By analyzing large-scale demographic data, the lab aims to inform contemporary housing policies and promote more equitable urban development.</p>

  <h2>Objective</h2>
  <p>The objective of this project is to develop a predictive model that estimates the probabilities of race and foreign/native-born status for loan card records based on data from the 1940 US census. This model serves as a crucial component in the broader research initiative to uncover and analyze patterns of redlining and demographic shifts across different neighborhoods.</p>

  <h2>Methods</h2>
  <p>The prediction algorithm utilizes the Bayesian Improved Surname First-Name Geocoding (BISFG) technique, enhanced with additional refinement steps to improve accuracy. The BISFG algorithm sequentially processes demographic attributes such as first names, last names, and geographic data to infer racial and nativity characteristics. This approach includes iterative checks and relaxation steps to ensure robust predictions even with incomplete or ambiguous data.</p>

  <p>Key steps in the methodology include:</p>
  <ol>
    <li>Initial processing of 1940 census data to create a cleaned dataset suitable for model training and prediction.</li>
    <li>Implementation of the BISFG algorithm with specific modifications tailored to handle diverse demographic scenarios.</li>
    <li>Validation and backtesting of the algorithm using sample census data to assess prediction accuracy through metrics such as confidence intervals and AUC scores.</li>
  </ol>

  <h2>Results</h2>
  <ul>
    <li>Predicted probabilities were generated for 97.80% of the 39,309 loan card records.</li>
    <li>Accuracy results include approximately 80.5% for race prediction across five categories, improving to 83.5% with two categories.</li>
    <li>Nativity prediction achieved an accuracy of approximately 81%.</li>
  </ul>

  <h2>Additional Information</h2>
  <p>More detailed findings and related published research can be explored on the <a href="https://www.urbandataresearchlab.org/">Urban Data Research Lab website</a>. This project's outcomes and methodologies contribute to ongoing efforts in understanding historical and contemporary urban inequalities, influencing evidence-based policy recommendations.</p>
  
  <p>Please note that this paper is pending publication.</p>
</body>
</html>

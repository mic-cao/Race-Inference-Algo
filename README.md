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
  <p>This project, led by Michael Cao, is part of a broader research effort under the Redlining Lab at the Urban Data Research Lab. The lab uses big data and spatial data science to understand urban inequality at the neighborhood level, aiming to inform housing policy and promote equitable cities.</p>

  <h2>Objective</h2>
  <p>To produce predicted probabilities of race and foreign/native-born status for loan card records using data from the 1940 US census.</p>

  <h2>Methods</h2>
  <p>We implemented and refined the Bayesian Improved Surname First-Name Geocoding (BISFG) algorithm, incorporating additional relaxation steps for improved accuracy. Backtesting was performed using accuracy confidence intervals and AUC scores (C-statistics) computed from sample census data.</p>

  <h2>Results</h2>
  <ul>
    <li>Predictions were generated for 97.80% of the 39,309 loan card records.</li>
    <li>Achieved approximately 80.5% accuracy for race prediction with five categories, improving to 83.5% with two categories.</li>
    <li>Achieved approximately 81% accuracy for native/foreign-born prediction.</li>
  </ul>

  <h2>Additional Information</h2>
  <p>More published research can be found on the <a href="https://www.urbandataresearchlab.org/">Urban Data Research Lab website</a>. This paper is pending publication.</p>
</body>
</html>

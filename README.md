<!DOCTYPE html>
<html lang="en">
<head>

  <h1>📊 Sindh & Punjab Vaccine Forecasting</h1>

  <p>This project analyzes and forecasts PCV (Pneumococcal Conjugate Vaccine) distribution trends in the provinces of <strong>Sindh</strong> and <strong>Punjab</strong>, Pakistan. It includes data cleaning, visualization, time series decomposition, and predictive modeling using Facebook Prophet.</p>

  <h2>🔍 Project Objectives</h2>
  <ul>
    <li>Analyze historical vaccine distribution trends from 2021 onward.</li>
    <li>Visualize year-wise and month-wise quantities.</li>
    <li>Apply smoothing techniques to highlight long-term trends.</li>
    <li>Use time series forecasting to predict future vaccine needs.</li>
    <li>Estimate age-wise and region-wise vaccine requirements based on population growth.</li>
  </ul>

  <h2>🧰 Tools & Technologies</h2>
  <ul>
    <li><strong>Languages:</strong> Python 3</li>
    <li><strong>Libraries:</strong> pandas, numpy, matplotlib, seaborn, plotly, Prophet, statsmodels, scikit-learn</li>
    <li><strong>Visualization:</strong> Plotly (interactive), Matplotlib, Seaborn</li>
  </ul>

  <h2>🧪 Methodology</h2>
  <ul>
    <li><strong>Data Preprocessing:</strong> Clean, format, and align Sindh & Punjab datasets.</li>
    <li><strong>Trend Analysis:</strong> Group data, visualize yearly and monthly distribution.</li>
    <li><strong>Seasonal Decomposition:</strong> Decompose time series into trend, seasonality, and residual.</li>
    <li><strong>Feature Engineering:</strong> Add lag features, seasonality indicators, rolling stats.</li>
    <li><strong>Forecasting:</strong> Train Prophet to forecast PCV needs for Dec 2024 – Nov 2025.</li>
    <li><strong>Demographic Scaling:</strong> Estimate age-group-specific vaccine demand using census projections.</li>
  </ul>

  <h2>📈 Results</h2>
  <ul>
    <li>Smoothed trends reveal seasonal distribution patterns.</li>
    <li>Prophet forecast achieves strong accuracy on test data.</li>
    <li>Age-wise distribution planning aids targeted allocation.</li>
    <li>Estimated 2025 PCV requirements computed for Sindh and Punjab.</li>
  </ul>

  <h2>📁 Project Structure</h2>
  <pre><code>
📦pcv-forecasting/
 ┣ 📜sindh&amp;punjab_pcv_prediction.py
 ┣ 📊PCV.xlsx
 ┣ 📈Notebooks/
 ┗ 📄README.md
  </code></pre>

  <h2>📌 Requirements</h2>
  <div class="highlight">
    <p>Install required libraries:</p>
    <pre><code>pip install pandas numpy matplotlib seaborn plotly prophet scikit-learn</code></pre>
  </div>
  
</body>
</html>

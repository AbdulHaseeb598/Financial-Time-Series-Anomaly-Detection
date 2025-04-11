

# README.md

```markdown
# Financial Time-Series Anomaly Detection

## Overview
This project detects anomalies in stock price trends to identify unusual activities or market manipulations using Yahoo Finance data. It focuses on AAPL, calculating indicators (SMA, EMA, RSI, Bollinger Bands), applying Isolation Forest for anomaly detection, and forecasting prices with LSTM. Anomalies are visualized on price trends.

## Features
- **Data**: Yahoo Finance stock data (5 years) for AAPL, MSFT, GOOGL, AMZN, NVDA.
- **Indicators**: SMA, EMA, RSI, Bollinger Bands.
- **Anomaly Detection**: Isolation Forest (59 anomalies in AAPL full dataset, 39 in test set).
- **Forecasting**: LSTM model for AAPL (RMSE: 4.10, MAE: 3.02).
- **Visualization**: Plots of price trends with anomalies and predictions.

## Repository Structure
- `models/`
  - `iso_forest_model.pkl`: Trained Isolation Forest model.
  - `lstm_AAPL_final.keras`: Final LSTM model for AAPL.
  - `lstm_AAPL_checkpoint.keras`: Best checkpointed LSTM model.
- `financial_anomaly_detection.ipynb`: Main notebook with implementation.
- `requirements.txt`: Dependencies.

## Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/AbdulHaseeb598/financial-anomaly-detection.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the notebook:
   - Open `financial_anomaly_detection.ipynb` in Jupyter.
   - Execute cells to preprocess data, detect anomalies, forecast prices, and visualize results.

## Requirements
- Python 3.8+
- Libraries: `pandas`, `numpy`, `scikit-learn`, `tensorflow`, `matplotlib` (see `requirements.txt`)

## Usage
- Run the notebook to analyze AAPL stock data.
- Use saved models for inference on new data:
  - `iso_forest_model.pkl` for anomaly detection.
  - `lstm_AAPL_final.keras` for price forecasting.

## Results
- **Anomaly Detection**: 59 anomalies in AAPL full dataset, 39 in test set.
- **Forecasting**: LSTM achieved RMSE 4.10, MAE 3.02 for AAPL.
- Visualizations show price trends with detected anomalies and predictions.

## License
MIT License
```

---

### Changes Made
- **Heading Structure**:
  - `# Financial Time-Series Anomaly Detection`: Main heading (H1).
  - `## Overview`, `## Features`, etc.: Subheadings (H2) for each section.
- **Rendering**: On GitHub, this will now display as a proper hierarchy with larger text for the main title and smaller text for subheadings, improving readability.
- **Content**: Kept identical to the previous version, just fixed the formatting.

### How It Will Look on GitHub
- **Financial Time-Series Anomaly Detection** (large, bold title)
  - **Overview** (smaller bold subheading)
  - **Features** (smaller bold subheading)
  - And so on...

This should now render correctly with visible headings and subheadings. Add this to your `README.md` file in your repository, and it’ll display as intended! Let me know if you need further tweaks.

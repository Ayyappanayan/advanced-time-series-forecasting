# LSTM vs Prophet for Time Series Forecasting (AAPL Stock)

This project implements and compares two time series forecasting models:

1. **LSTM (Long Short-Term Memory) neural network**
2. **Prophet** (additive time series model)

The dataset consists of **daily closing prices of AAPL** (Apple Inc.) downloaded from Yahoo Finance.  
The goal is to analyze forecasting performance, computational aspects, and interpretability for both models.

## Project Structure

```text
.
├─ main.py              # Main training & evaluation script
├─ config.py            # All hyperparameters and configuration
├─ requirements.txt     # Python dependencies
├─ README.md            # Project overview
├─ report_summary.md    # Detailed analysis and discussion
├─ data/                # Downloaded CSV file
└─ plots/               # Saved forecast plots

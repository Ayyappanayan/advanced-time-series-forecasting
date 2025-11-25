# Advanced Time Series Forecasting with Prophet and LSTM
Advanced Time Series Forecasting project using a Transformer-based deep learning model with Multi-Head Self-Attention. Includes forecasting results, training curves, and attention heatmaps for model interpretability.

This project implements and compares two advanced forecasting methods on a
synthetic time series dataset:

1. **Prophet model** with multiple seasonalities and external regressors.
2. **LSTM neural network** built with TensorFlow/Keras.

Rolling-origin cross-validation is used to evaluate forecasting performance
using RMSE and MAE.

## Project Structure

- `src/`
  - `data_generation.py` – synthetic dataset creation.
  - `prophet_model.py` – Prophet model definition and forecasting.
  - `lstm_model.py` – LSTM model definition and forecasting.
  - `backtesting.py` – rolling-origin cross-validation for both models.
  - `config.py` – configuration and hyperparameters.
  - `main.py` – end-to-end experiment script.
- `reports/`
  - `report_summary.md` – project report (fill in metrics after running).
  - `figures/` – forecast plots.

## Installation

```bash
pip install -r requirements.txt

# 📈 Stock Price Prediction with LSTM (Notebook-First)

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
![Notebook](https://img.shields.io/badge/Made%20with-Jupyter-orange.svg)
![Python](https://img.shields.io/badge/Python-3.9%2B-blue.svg)
![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)

A clean, notebook-first implementation of **stock price forecasting** using **LSTM (Long Short-Term Memory)** for time-series prediction.  
The project is designed to be easy to run, easy to understand, and easy to extend.

> ⚠️ **Disclaimer:** This repository is for educational/research purposes and is **not financial advice**.

---

## ✨ What’s inside

- ✅ End-to-end pipeline in a single Jupyter Notebook:
  - Data loading
  - Cleaning + scaling
  - Sliding-window sequence building
  - LSTM training
  - Evaluation + plots
  - Forecast visualization

---

## 🧠 How it works (high level)

1. **Prepare** historical OHLCV data (or Close-only).
2. **Scale** values (e.g., MinMax scaling) to stabilize training.
3. **Create sequences** using a rolling window:
   - input: last `lookback` timesteps
   - output: next timestep (or next `horizon` steps)
4. **Train LSTM** to learn temporal patterns.
5. **Evaluate** and visualize predicted vs actual series.

---

## 📁 Repository structure (current)


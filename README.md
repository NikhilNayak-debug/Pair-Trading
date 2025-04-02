# Pairs Selection and Trading in Indian Equities

This repository contains our final project for AC 209 at Harvard University (2022–2023), focused on identifying profitable pairs trading opportunities in the Indian equity markets using statistical and machine learning methods.

## 📄 Project Overview

Pairs trading is a market-neutral strategy that exploits the historical relationship between two highly correlated stocks. When their prices diverge beyond a threshold, the strategy involves simultaneously buying the undervalued stock and shorting the overvalued one, expecting their prices to revert to the mean.

In this project, we:
- Investigate state-of-the-art statistical and ML-based approaches for discovering trading pairs
- Benchmark these approaches against a baseline strategy
- Implement and evaluate these strategies using historical data from Indian stock markets (NSE & BSE)

## ✨ Motivation

Pair trading is commonly used to hedge market risk by taking opposing positions in two related securities. Our goal is to use data-driven techniques to uncover these relationships and design profitable trading strategies.

## 🔍 Problem Statement

We explore how machine learning and artificial intelligence can be used to detect statistical arbitrage opportunities using the pair trading framework, focusing specifically on Indian equities.

## 📊 Data

We use daily stock price data from the **NIFTY-100 index** over the past **3 years**. Only companies with complete data for the full duration were considered in our analysis to ensure consistency and comparability.

## 📂 Contents

- `data/`: Cleaned and preprocessed stock price data
- `notebooks/`: Jupyter notebooks for analysis, modeling, and strategy evaluation
- `models/`: Trained models and pair selection outputs
- `report/`: Final report in PDF format
- `README.md`: This file

## ⚠️ Disclaimer

This project is for academic purposes only. It does not constitute financial advice or trading recommendations.

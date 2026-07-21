# 🪙 Bitcoin Historical Data Analysis & Growth Projection

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rohitranjankumar-01/Bitcoin-History-Analysis-ACap-Stone-Project/blob/main/BitcoinDataAnalysis.ipynb)
[![Render in nbviewer](https://img.shields.io/badge/render-nbviewer-orange.svg?style=flat&logo=jupyter)](https://nbviewer.org/github/rohitranjankumar-01/Bitcoin-History-Analysis-ACap-Stone-Project/blob/main/BitcoinDataAnalysis.ipynb)
![Python Version](https://img.shields.io/badge/Python-3.8%2B-3776AB?style=flat&logo=python&logoColor=white)
![Project Status](https://img.shields.io/badge/Status-Completed-success)

> **Semester 1 College Capstone Project** — An in-depth exploratory data analysis (EDA), statistical evaluation, and visual trend projection of Bitcoin's historical market performance.

---

## 📌 Jupyter Notebook Display Notice

If GitHub's native viewer experiences loading delays or fails to display the Jupyter Notebook (`.ipynb`), you can render or execute the notebook instantly using the links below:

* 🌐 **[Render Notebook on nbviewer](https://nbviewer.org/github/rohitranjankumar-01/Bitcoin-History-Analysis-ACap-Stone-Project/blob/main/BitcoinDataAnalysis.ipynb)** *(Recommended for quick high-quality rendering)*
* 🚀 **[Open and Run in Google Colab](https://colab.research.google.com/github/rohitranjankumar-01/Bitcoin-History-Analysis-ACap-Stone-Project/blob/main/BitcoinDataAnalysis.ipynb)** *(Interactive cloud environment)*

---

## 📖 Table of Contents

- [Project Overview](#-project-overview)
- [Key Analysis & Highlights](#-key-analysis--highlights)
- [Dataset Description](#-dataset-description)
- [Repository Structure](#-repository-structure)
- [Installation & How to Run](#-installation--how-to-run)
- [Technologies & Libraries Used](#-technologies--libraries-used)
- [Team Members](#-team-members)

---

## 🔍 Project Overview

Bitcoin, launched in 2009 by Satoshi Nakamoto, has evolved from an experimental digital cash protocol into a major global asset class. This capstone project analyzes historical Bitcoin market data to uncover price patterns, volatility trends, trading volume relationships, and moving average technical indicators.

### Key Objectives
1. **Data Preprocessing & Conversion**: Clean raw dataset, handle currency conversions (USD to INR), format datatypes, and structure metrics chronologically.
2. **Statistical Analysis**: Apply NumPy and Pandas operations to measure mean, median, standard deviation, max/min prices, price ranges, and percentage changes.
3. **Data Visualization**: Generate static plots (histograms, line charts, scatter plots, boxplots, pair plots) to analyze price fluctuations, high/low spread, trading volume, and percentage gains/losses.
4. **Technical Indicators**: Calculate Simple Moving Averages (SMA) to evaluate price trends and market momentum.

---

## 📊 Key Analysis & Highlights

### 1. Data Cleaning & Transformation
- Filtered and converted date strings into `datetime` objects.
- Normalized percentage change fields (`Change %`) into numerical floats.
- Currency conversion from USD to INR using exchange rates.
- Sorted and re-indexed the dataset in chronological order.

### 2. NumPy & Pandas Operations
- Computed overall statistical measures: **Mean**, **Median**, **Standard Deviation**, and **Price Range**.
- Categorized trading sessions by positive vs. negative price movements.
- Queried sessions where Bitcoin exceeded key price thresholds (e.g., $50,000 USD / equivalent INR).
- Extracted subset ranges using `.iloc[]` and `.loc[]`.

### 3. Visualizations & Insights
- **Closing Price Trend**: Visualized historical Bitcoin closing prices over time.
- **High vs. Low Spread**: Analyzed price bounds and intra-session volatility.
- **Trading Volume Dynamics**: Examined the relationship between volume spikes and price surges/drops.
- **Percentage Change Distribution**: Plotted histograms with Kernel Density Estimation (KDE) to observe return distributions.
- **Moving Average Indicator**: Implemented 10-period and multi-period Simple Moving Averages (SMA) to smooth price trends.
- **Pair Plots & Correlation**: Explored cross-variable correlations hue-colored by positive and negative change categories.

---

## 📁 Dataset Description

The dataset `BitcoinHistoricalData.csv` contains historical Bitcoin trading records with the following columns:

| Column Name | Description |
| :--- | :--- |
| `Date` | Timestamp of the trading period |
| `Price` / `Close` | Closing price of Bitcoin |
| `Open` | Opening price at the start of the period |
| `High` | Highest price recorded during the period |
| `Low` | Lowest price recorded during the period |
| `Vol.` / `Volume` | Total trading volume |
| `Change %` | Percentage change in price from the previous session |

---

## 📂 Repository Structure

```
Bitcoin-History-Analysis-ACap-Stone-Project/
├── BitcoinDataAnalysis.ipynb   # Main Jupyter Notebook containing analysis, plots, and insights
├── BitcoinHistoricalData.csv   # Historical Bitcoin dataset
├── .gitignore                  # Git ignore file for Python and Jupyter artifacts
└── README.md                   # Comprehensive project documentation
```

---

## ⚙️ Installation & How to Run

### Prerequisites
Make sure you have Python 3.8+ installed on your system.

### 1. Clone the Repository
```bash
git clone https://github.com/rohitranjankumar-01/Bitcoin-History-Analysis-ACap-Stone-Project.git
cd Bitcoin-History-Analysis-ACap-Stone-Project
```

### 2. Install Dependencies
```bash
pip install numpy pandas matplotlib seaborn mplfinance yfinance jupyter
```

### 3. Launch Jupyter Notebook
```bash
jupyter notebook BitcoinDataAnalysis.ipynb
```

---

## 🛠️ Technologies & Libraries Used

- **Python 3** — Core programming language
- **Pandas** — Data manipulation, cleaning, and tabular analysis
- **NumPy** — High-performance array operations & mathematical calculations
- **Matplotlib** — Data visualization and plotting engine
- **Seaborn** — Statistical graphics and styled visualization (pair plots, KDEs, boxplots)
- **mplfinance** — Financial plotting utilities
- **yfinance** — Yahoo Finance API bindings for market data

---

## 👥 Team Members

This project was developed as a Group Capstone Project for 1st Semester:

* 💻 [rohitranjankumar-01](https://github.com/rohitranjankumar-01)
* 💻 [HAADIN-CTRL](https://github.com/HAADIN-CTRL)
* 💻 [Taranjeet1-coder](https://github.com/Taranjeet1-coder)
* 💻 [Nipun817](https://github.com/Nipun817)
* 💻 [Manuj-Gupta13](https://github.com/Manuj-Gupta13)

---


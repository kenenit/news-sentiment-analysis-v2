# News Sentiment Analysis and Stock Market Prediction

## Project Overview

This project analyzes financial news headlines and stock market data to understand how news sentiment may influence stock price movement. The project combines:

* Exploratory Data Analysis (EDA)
* Natural Language Processing (NLP)
* Sentiment Analysis
* Machine Learning
* Stock Price Analysis

The analysis was performed using Python, Jupyter Notebook, and machine learning libraries such as Scikit-learn and TextBlob.

---

# Objectives

The main objectives of this project are:

1. Analyze financial news headlines
2. Clean and preprocess text data
3. Perform sentiment analysis on news headlines
4. Analyze stock market historical price data
5. Build machine learning models for sentiment classification
6. Compare stock-related sentiment across multiple companies

---

# Dataset Information

## News Dataset

The project uses the analyst ratings dataset containing:

* Headlines
* Publisher information
* Dates
* URLs
* Stock ticker symbols

Main file:

```text
raw_analyst_ratings.csv
```

## Stock Market Datasets

Historical stock price datasets used:

* AAPL.csv
* AMZN.csv
* GOOG.csv
* META.csv
* NVDA.csv

Each stock dataset contains:

* Date
* Open price
* Close price
* High price
* Low price
* Volume

---

# Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* TextBlob
* Git & GitHub

---

# Project Structure

```text
news-sentiment-analysis-v2/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   ├── task1_eda.ipynb
│   ├── task2_sentiment_analysis.ipynb
│   ├── task3_machine_learning.ipynb
│   └── task4_multi_stock_news_analysis.ipynb
│
├── .github/
│   └── workflows/
│       └── unittests.yml
│
├── .vscode/
│   └── settings.json
│
├── requirements.txt
├── README.md
└── .gitignore
```

---

# Tasks Completed

## Task 1 — Exploratory Data Analysis (EDA)

Performed:

* Data loading and inspection
* Checking missing values
* Publication trend analysis
* Publisher analysis
* Data visualization
* Stock price movement exploration

Outputs:

* Tables
* Graphs
* Trend visualizations

---

## Task 2 — Sentiment Analysis

Performed:

* Text cleaning
* Headline preprocessing
* Sentiment scoring using TextBlob
* Sentiment label generation
* Sentiment distribution visualization

Sentiment categories:

* Positive
* Neutral
* Negative

Outputs:

* Sentiment tables
* Bar chart visualization
* Processed CSV dataset

---

## Task 3 — Machine Learning

Performed:

* TF-IDF feature extraction
* Train/test split
* Logistic Regression model training
* Model evaluation
* Confusion matrix visualization

### Initial Model Accuracy

Approximately 45%

### Improved Model Accuracy

Approximately 77%

Evaluation metrics used:

* Accuracy
* Precision
* Recall
* F1-score

---

## Task 4 — Multi-Stock News Analysis

Performed:

* Filtering stock-specific headlines
* Comparing multiple companies
* Multi-stock sentiment analysis
* Data preprocessing for several stock tickers

Companies analyzed:

* Apple (AAPL)
* Amazon (AMZN)
* Google (GOOG)
* Meta (META)
* NVIDIA (NVDA)

---

# Machine Learning Workflow

The machine learning workflow followed these steps:

1. Load processed dataset
2. Clean text headlines
3. Convert text into TF-IDF vectors
4. Split data into training and testing datasets
5. Train Logistic Regression model
6. Evaluate model performance
7. Visualize confusion matrix

---

# Key Findings

* Most financial headlines were neutral.
* Positive headlines were more common than negative headlines.
* TF-IDF significantly improved model performance.
* Logistic Regression produced better classification accuracy than the baseline approach.
* Sentiment analysis can help identify market trends from news headlines.

---

# Installation

## Clone Repository

```bash
git clone https://github.com/kenenit/news-sentiment-analysis-v2.git
```

## Open Project Folder

```bash
cd news-sentiment-analysis-v2
```

## Create Virtual Environment

```bash
python -m venv venv
```

## Activate Virtual Environment

### Windows

```bash
venv\Scripts\activate
```

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

# Running The Project

Start Jupyter Notebook:

```bash
jupyter notebook
```

Open notebooks from the `notebooks` folder and run cells step by step.

---

# Future Improvements

Possible future improvements include:

* Deep learning models
* Real-time news analysis
* More advanced NLP preprocessing
* Better sentiment classification
* Dashboard visualization
* Stock price forecasting

---

# Author

Keneni Teha

---

# License

This project is for educational and research pur

# Financial News Sentiment & Stock Price Correlation

## 📊 Project Overview
This project is part of a series for **Nova Financial Solutions**. The objective is to enhance investment strategies by analyzing the impact of financial news sentiment on stock price movements. We utilize NLP to quantify news headlines and correlate those scores with technical indicators for five major tickers: **AAPL, AMZN, GOOG, META, and NVDA**.

## 🛠️ Technical Stack
- **OS:** Ubuntu (HP ZBook Studio G5)
- **Language:** Python 3.12+
- **Environment:** Linux-based Virtual Environment
- **CI/CD:** GitHub Actions (Automated Environment Verification)
- **Key Libraries:** 
  - `Pandas` (Data manipulation & cleaning)
  - `TA-Lib` (Technical indicator calculations)
  - `Matplotlib/Seaborn` (Data visualization)
  - `Scikit-learn` (Text vectorization)

## 📁 Repository Structure
```text
├── .github/workflows/      # CI/CD pipeline configurations
├── data/                   # Data directory (ignored in git)
├── notebooks/              # Jupyter notebooks for analysis
│   ├── eda.ipynb           # Task 1: Exploratory Data Analysis
│   └── task_2_indicators.ipynb # Task 2: Quantitative Analysis
├── requirements.txt        # Project dependencies
├── .gitignore              # Files to exclude from version control
└── README.md               # Project documentation

```

## 🚀 Completed Work

### Task 1: Exploratory Data Analysis (EDA)

* **Data Normalization:** Developed a robust pipeline to handle inconsistent date formats using `mixed` parsing and UTC normalization.
* **Publisher Analysis:** Identified key news sources and analyzed article distribution across tickers.
* **Headline Analysis:** Performed topic modeling using Bigrams to identify common financial themes (e.g., "Price Target", "Earnings Report").

### Task 2: Quantitative Analysis (In Progress)

* **Indicator Implementation:** Successfully implemented a technical analysis pipeline using **TA-Lib**.
* **Metrics:** Calculated 20-day SMA, 20-day EMA, RSI (14), and MACD.
* **Robustness:** Implemented forward-fill logic to handle market holidays and ensure time-series continuity.

## ⚙️ Setup & Installation

1. **Clone the repository:**
```bash
git clone [https://github.com/mahi7000/news-sentiment-analysis.git](https://github.com/mahi7000/news-sentiment-analysis.git)
cd news-sentiment-analysis

```


2. **Setup Virtual Environment:**
```bash
python3 -m venv venv
source venv/bin/activate
```


3. **Install Dependencies:**
```bash
pip install -r requirements.txt
```

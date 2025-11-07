# fear-greed-trading-analysis

# 🧠 Trader Behavior & Market Sentiment Analysis

## 📄 Overview
This project explores how **market sentiment (Fear and Greed Index)** affects **trader performance** using real trading data.
The analysis combines **Bitcoin market sentiment** with **trader profit/loss data** to identify trends, correlations, and behavioral patterns during different market moods.

## 🎯 Objectives
- Understand how trader performance changes during **Fear** vs **Greed** market phases.
- Analyze whether **sentiment impacts profitability**.
- Provide data-driven insights for improving trading strategies.

## 📂 Dataset
1. **Fear & Greed Index (Sentiment Data)**
   - Columns: `Date`, `Classification` (Fear, Greed, Extreme Fear, Extreme Greed, Neutral)

2. **Trader Historical Data**
   - Columns: `account`, `symbol`, `execution_price`, `size`, `side`, `time`, `closedPnL`, etc.

Both datasets are merged on the `Date` column for joint analysis.

## ⚙️ Steps Performed
1. **Data Cleaning & Preparation**
   - Converted date formats (`yyyy-mm-dd`)
   - Merged sentiment and trader datasets

2. **Exploratory Data Analysis (EDA)**
   - Compared average `closedPnL` across sentiment classes
   - Visualized trading performance trends

3. **Statistical Analysis**
   - Calculated sentiment–PnL correlation
   - Evaluated model performance (accuracy, F1-score)

## 📊 Example Results
| Sentiment | Avg Closed PnL |
|------------|----------------|
| Extreme Fear | 1.89 |
| Fear | 128.28 |
| Neutral | 27.09 |
| Greed | 53.99 |
| Extreme Greed | 205.82 |

## 💡 Key Insights
- Traders **earn more in Extreme Greed** phases, but overall **Greed shows lower average profits** than Fear.
- **Market mood has minimal correlation (-0.03)** with profitability.
- **Fearful markets** may promote more disciplined and strategic trading.

## 🛠️ Tools & Libraries Used
- Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)
- Jupyter Notebook 

## 📁 File Structure
```
├── trading_sentiment_project.ipynb     # Main analysis notebook
├── README.md                           # Project documentation
├── fear_greed_index.csv
```

## 📧 Contact
**Author:** Rohini More  
**Role:** Data Science 
**Email:** morerohini234@gmail.com

# Trader Behavior Insights 

## 👤 Candidate: Ameen  
## 📁 Project: Bitcoin Market Sentiment vs Trader Performance
______________________________________________________________

## 🧠 Objective
This project investigates how Bitcoin market sentiment — measured by the Fear & Greed Index — influences trader behavior and profitability.
Using historical trading data from Hyperliquid and sentiment scores, the goal is to uncover patterns that can guide smarter trading strategies.
___________________________________________________________________________________________________________________________________________

## 📦 Dataset Sources

Historical Data 
https://drive.google.com/file/d/1IAfLZwu6rJzyWKgBToqwSmmVYU6VbjVs/view?usp=sharing

Fear Greed Index link:
https://drive.google.com/file/d/1PgQC0tO8XN-wqkNyghWc_-mnrYv_nhSf/view?usp=sharing
_____________________________________________________________________________________

## 🔍 Key Features Used
From the merged dataset:
- `Size USD`: Trade volume in USD
- `Fee`: Transaction fee
- `Closed PnL`: Profit or loss from trade
- `sentiment_numeric`: Mapped sentiment score (1 to 5)
- `Date`: Trade date aligned with sentiment
- `profitable`: Binary target for modeling (PnL > 0)
_____________________________________________________________________________________

## 📊 Key Findings

From Exploratory Data Analysis
- **Fear sentiment** drives the highest trading volume, while **Extreme Fear** sees the least.
- **Extreme Fear** yields the highest average PnL, suggesting risk-tolerant traders may benefit from volatile conditions.
- The **Fear & Greed Index** fluctuates significantly over time, reflecting dynamic market psychology.
- Scatter plot shows no clear linear relationship between sentiment value and trading volume, indicating complex behavioral drivers.

From Predictive Modeling 
- A Random Forest model was trained to predict trade profitability using sentiment and trade features.
- The model achieved solid accuracy, confirming sentiment plays a meaningful role in trade outcomes.
- Confusion matrix highlights areas for improvement and potential feature expansion.
____________________________________________________________________________________________________________________________________________________

##  Contact
SURAYYA THASNIM AT
surayyathasnim@gmail.com
https://surayya-portfolio-com.netlify.app/


# 📊 Funnel Analysis Project (Python)

## 📌 Overview
This project performs **Funnel Analysis** on user journey data to understand how users move through different stages of an e-commerce or product flow.  
The analysis is implemented using **Python (Pandas, Matplotlib, Plotly, Seaborn,plotly)** inside a Jupyter Notebook.


## 🎯 Problem Statement
The goal of this project is to analyze user behavior across different funnel stages:

- Homepage → Product Page → Cart → Checkout → Purchase





## 🧠 Project Structure 
#### Cleaning and Transform data 

1. Data types
2. Data Consistency Stage
3. Null values
4. Outliers
5. Create new columns (Date , Time , Total Sessions Per User, Purchase Counts Per User,Time Segments)


#### Analysis and Visualization
- Purchase vs Non-Purchase Sessions
  
![Purchase vs Non-Purchase](Charts/PurchasevsNon-PurchaseSessions.png)
- 'Distribution of Purchase Counts Per User
  
- Distribution of Total Session Per User
- Plotly for interactive funnel charts
- GroupBy & aggregation for behavioral insights
- Time-based feature engineering



## 📈 Example Insights

- Highest drop-off usually occurs between **Product Page → Cart**
- Users in **Evening time segment** tend to convert more
- Mobile users may have lower conversion rates than desktop users
- Checkout stage is a critical bottleneck

# 📊 Funnel Analysis Project (Python)

## 📌 Overview
This project performs **Funnel Analysis** on user journey data to understand how users move through different stages of an e-commerce or product flow.  
It helps identify **drop-off points, conversion rates, and user behavior patterns** to improve overall conversion performance.

The analysis is implemented using **Python (Pandas, Matplotlib, Plotly, Seaborn)** inside a Jupyter Notebook.



## 🎯 Problem Statement
The goal of this project is to analyze user behavior across different funnel stages:

- Homepage → Product Page → Cart → Checkout → Purchase

And answer key business questions such as:
- Where do users drop off in the funnel?
- What is the conversion rate at each stage?
- Which segments or behaviors lead to higher purchases?
- How can we improve the overall conversion rate?


## 📊 Key Features

- 🔹 Data cleaning and preprocessing
- 🔹 User journey analysis
- 🔹 Funnel stage definition
- 🔹 Conversion rate calculation
- 🔹 Drop-off analysis
- 🔹 Time segmentation analysis (6 time periods)
- 🔹 Interactive and static visualizations
- 🔹 Device / page type segmentation analysis


## 🧠 Techniques Used

- Pandas for data manipulation
- NumPy for numerical analysis
- Matplotlib & Seaborn for visualization
- Plotly for interactive funnel charts
- GroupBy & aggregation for behavioral insights
- Time-based feature engineering


## ⏰ Time Segmentation (Example Feature)

The project creates a new feature `TimeSegment` from the `Time` column:

- Late Night  
- Early Morning  
- Morning  
- Afternoon  
- Evening  
- Night  

This helps analyze user behavior across different times of the day.


## 📈 Example Insights

- Highest drop-off usually occurs between **Product Page → Cart**
- Users in **Evening time segment** tend to convert more
- Mobile users may have lower conversion rates than desktop users
- Checkout stage is a critical bottleneck

# UK E-Commerce Customer Segmentation  
Capstone Project | Data Analysis & Machine Learning  

## 🎯 Objective
- To analyze customer behavior in UK e-commerce dataset using RFM analysis and clustering.  
- To segment customers into actionable groups (loyal, at risk, lost, etc.) for marketing strategy.  
- **To demonstrate how IBM Granite Models can assist in generating insights and business recommendations from customer segmentation results.**

## 📂 Dataset
Source: [UK E-Commerce Dataset (Kaggle)](https://www.kaggle.com/datasets/carrie1/ecommerce-data)  
- Period: Dec 2010 – Dec 2011  
- 500,000+ transaction rows  
- Columns: InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, Country  

## 🛠️ Methods
1. **Data Cleaning**
   - Handle missing values (CustomerID, Description)
   - Remove duplicates & negative quantities
   - Feature engineering (TotalPrice = Quantity × UnitPrice)

2. **Exploratory Data Analysis (EDA)**
   - Transaction trend over time
   - Top products & countries
   - Average basket size & revenue distribution

3. **RFM Analysis**
   - Recency, Frequency, Monetary scoring
   - Customer segmentation using KMeans clustering

4. **Visualization**
   - Histograms, Boxplots
   - Heatmaps & Customer clusters
   - RFM distribution per segment

5. **AI Support (IBM Granite Models)**
   - Summarize findings from clustering  
   - Generate actionable business insights  
   - Recommend marketing strategies for each segment  

## 📊 Results
- Customers segmented into groups (e.g., Loyal Customers, At-Risk, Lost, Potential).  
- Identified key drivers of customer value.  
- Actionable marketing recommendations powered by **IBM Granite Models**.  

## 🚀 Tools
- Python: Pandas, Matplotlib, Seaborn, Scikit-learn  
- Jupyter / Google Colab  
- AI Insight: **IBM Granite Models**  

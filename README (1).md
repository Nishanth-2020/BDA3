# Intelligent Retail Demand Forecasting and Product Recommendation

## Project Overview
This project develops an intelligent retail analytics system using Python and machine learning. It predicts product demand, discovers frequently purchased product combinations, and recommends products to customers.

## Objectives
- Forecast future product demand.
- Identify frequently purchased product combinations.
- Recommend products based on customer purchase history.
- Evaluate forecasting and recommendation performance.

## Dataset
**Dataset:** UCI Online Retail Dataset

**Source:** https://archive.ics.uci.edu/dataset/352/online-retail

The dataset contains:
- InvoiceNo
- StockCode
- Description
- Quantity
- InvoiceDate
- UnitPrice
- CustomerID
- Country

## Technologies Used
- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- MLxtend
- SciPy

## Algorithms Used

### Demand Forecasting
- Linear Regression
- Random Forest Regressor
- Gradient Boosting Regressor

### Pattern Mining
- FP-Growth
- Association Rule Mining

### Product Recommendation
- Popularity-Based Recommendation
- Item-Based Collaborative Filtering
- User-Based Collaborative Filtering
- Truncated SVD

## Evaluation Metrics
**Demand Forecasting:**
- MAE
- RMSE
- WAPE
- R² Score

**Recommendation:**
- Precision@10
- Recall@10
- HitRate@10
- NDCG@10
- Coverage

## Project Structure
```text
Retail-Demand-Forecasting-and-Recommendation/
│
├── data/
├── notebooks/
├── outputs/
├── requirements.txt
└── README.md
```

## Implementation
The project is implemented using Python in Google Colab.

## Expected Outputs
- Weekly product demand forecasts
- Frequently purchased product combinations
- Customer-based product recommendations
- Model evaluation metrics and visualizations

## Dataset Attribution
Dataset provided by the UCI Machine Learning Repository.

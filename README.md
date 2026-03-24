# olist-customer-churn-analysis
Customer churn prediction using RFM segmentation &amp; Machine Learning on 100k+ real e-commerce orders | Python, Scikit-learn, Pandas

# Customer Churn Prediction — Olist E-Commerce

## Project Overview
Built a customer churn prediction system on 100k+ real Brazilian 
e-commerce orders using RFM segmentation and Machine Learning.

## Dataset
- Source: [Olist Brazilian E-Commerce (Kaggle)](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)
- 100k+ real orders across 4 datasets

## Tools Used
![Python](https://img.shields.io/badge/Python-3.x-blue)
![Pandas](https://img.shields.io/badge/Pandas-grey)
![Scikit--learn](https://img.shields.io/badge/ScikitLearn-orange)
![Seaborn](https://img.shields.io/badge/Seaborn-teal)

## What I Built
- Merged 4 raw datasets into one master dataframe
- Built RFM segmentation → Champions, Loyal, At Risk, Lost
- Trained Logistic Regression & Random Forest churn model
- Generated 4 business insight visualizations

##Results
| Model | Accuracy | AUC |
|---|---|---|
| Logistic Regression | 75% | ~0.83 |
| Random Forest | 75% | ~0.83 |

## Key Findings
- **Overall churn rate:** 57.2%
- **Top churn predictor:** Recency (days since last purchase)
- **Highest churn segment:** Lost customers

## Business Recommendations
1. Re-engage **Lost segment** with discount/coupon campaigns
2. Set automated alerts for customers inactive **30/60/90 days**
3. Protect **Champions** with loyalty rewards & early access
4. Launch **win-back campaigns** for At Risk segment

## Project Files
| File | Description |
|---|---|
| `churn_analysis.ipynb` | Main analysis notebook |
| `rfm_customer_segments.csv` | RFM output table |
| `confusion_matrix.png` | Model evaluation chart |
| `feature_importance.png` | Top churn predictors |
| `rfm_segments.png` | Customer segment distribution |
| `churn_by_segment.png` | Churn rate by segment |

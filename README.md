# Accredian – Fraud Detection Assignment

## Candidate Details
**Name:** Hari Om  
**Role Applied For:** Data Science / Machine Learning Trainee  
**Assignment:** Fraud Detection Case Study  

---

## Project Objective
The objective of this project is to build a machine learning model that can proactively detect fraudulent financial transactions.  
The solution focuses on identifying fraud with high recall while keeping false positives under control and deriving actionable business insights for fraud prevention.

---

## Dataset Information
- Dataset: PaySim simulated financial transaction dataset  
- Total Records: ~6.3 million  
- Target Variable: `isFraud`  
- Problem Type: Binary Classification  
- Key Challenge: Severe class imbalance  

The dataset is widely used in fraud detection research and case studies.

---


---

## Approach Summary
1. Data validation and cleaning  
2. Handling class imbalance  
3. Feature engineering based on transaction behavior  
4. Model training using multiple algorithms  
5. Final model selection using XGBoost  
6. Evaluation using recall, precision, ROC-AUC, and confusion matrix  
7. Business interpretation and fraud prevention recommendations  

---

## Model Used
- Logistic Regression (baseline)
- Random Forest
- **XGBoost (final model)**

XGBoost was selected due to its strong performance on large, imbalanced tabular datasets.

---

## Evaluation Metrics
Since accuracy is misleading for imbalanced data, the following metrics were used:
- Precision
- Recall
- F1-score
- ROC-AUC
- Confusion Matrix

Primary focus was on maximizing fraud recall while maintaining acceptable precision.

---

## Key Insights
- High transaction amounts are strong fraud indicators  
- TRANSFER and CASH_OUT transactions are high-risk  
- Sudden balance drops in origin accounts signal fraud  
- Destination balance inconsistencies are common in fraudulent activity  

These insights align well with real-world fraud patterns.

---

## Fraud Prevention Recommendations
- Real-time transaction risk scoring  
- Dynamic threshold-based monitoring  
- Additional authentication for high-risk transactions  
- Human review for flagged cases  
- Continuous model retraining and monitoring  

---

## How to Run the Notebook
1. Open `Fraud_Detection_Accredian.ipynb`
2. Ensure the dataset is present in the `dataset/` folder
3. Run all cells from top to bottom

---

## Conclusion
This project demonstrates an end-to-end fraud detection pipeline combining data preprocessing, machine learning, and business insights.  
The solution is scalable, interpretable, and suitable for real-world deployment.

---

## Contact
**Hari Om**  

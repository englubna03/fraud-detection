Fraud Detection — Machine Learning Project

##  Overview
End-to-end Machine Learning pipeline for detecting fraudulent transactions on highly imbalanced data (1.21% fraud rate).

##  Objectives
- Build a robust fraud detection model
- Handle severe class imbalance
- Achieve high F1-Score and AUC-ROC

##  Key Insights
1. `amount` is the most important feature (55% importance)
2. Samplers hurt tree-based models
3. `class_weight='balanced'` is effective
4. HistGB outperforms traditional GB by +1.07%

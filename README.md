## DigiCow Adoption Prediction Challenge
# Project Overview

This project aims to predict whether a farmer will adopt a DigiCow-supported agricultural practice within:

7 days

90 days

120 days

after receiving their first training.

Access to agricultural training is only the first step toward improved farm productivity. The real challenge lies in predicting which farmers will turn training into action. Early prediction of adoption enables better follow-ups, targeted support, and improved extension strategies.

This solution builds machine learning models that output probabilities of adoption, optimized using Log Loss and ROC-AUC.

## Objective

For each farmer, predict the probability of adoption within:

TX_07 – Adoption within 7 days

TX_90 – Adoption within 90 days

TX_120 – Adoption within 120 days

The model must use only information available at the time of training.

 ## Evaluation Metrics

The challenge uses a weighted multi-metric evaluation:

Log Loss (75%) – Rewards well-calibrated probability estimates

ROC-AUC (25%) – Measures ranking performance

 ## Final Score:

Final Score = 0.75 × LogLoss + 0.25 × ROC-AUC

Because Log Loss has a higher weight, probability calibration is critical.


Exploratory Data Analysis (EDA)

During E

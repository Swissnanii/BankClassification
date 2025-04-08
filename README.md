# Classification Project: Bank Classification

## What is the objective of this project?
The goal of this project is to determin whether the customer will subscribe to a term deposit or not.

## Where is the data from?
The dataset in this project is from the UCI repository repository link [UCI]https://archive.ics.uci.edu/dataset/222/bank+marketing. The dataset, collected through phone calls, contains important information about individuals who either
subscribed to a term deposit or declined the offer.

## Model Performance
- AUC Score: 0.91% 
- Precision: Macro Avg: 0.76% 
            Weighted Avg: 0.89%
- Recall: Macro Avg: 0.75%
         Weighted Avg: 0.89%
- f1-score: Macro Avg: 0.76%
           Weighted Avg: 0.89%

## Feature Importance
The Most Important Features are:
1. **Duration**
  - The longer the call, the more likely the were to subscribe 
2. **Contact**
  - Customers are likely to trust calls from cell phones than landlines 
3. **Month**
 - Due to vacations,bonuses/tax returns
 - End of quarter/year pressure 

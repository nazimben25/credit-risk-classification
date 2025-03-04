# Using a supervised machine learning model,
# create a classification model that focuses on predicting and categorizing credit risk

### credit-risk-classification

1) content 
the purpose is to  use various techniques to train and evaluate a model based on loan risk. 
A logistic regression  will be performed
A dataset of historical lending activity will be used from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

2) Dependencies
        import numpy as np
        import pandas as pd
        from pathlib import Path
        from sklearn.metrics import confusion_matrix, classification_report

        from sklearn.model_selection import train_test_split
        from sklearn.linear_model import LogisticRegression


3) directory organization
- jupiter notebook (credit_risk_classification_mywork.ipynb) to run and execute the code
- lending_data CSV data file
- directory Starter_code : contains the original input

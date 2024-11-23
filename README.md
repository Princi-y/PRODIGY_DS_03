This project predicts whether a customer will subscribe to a product using a Decision Tree Classifier. The dataset is from the Bank Marketing Dataset available on https://archive.ics.uci.edu/dataset/222/bank+marketing.

Dataset Description
Features: age, job, marital, education, default, balance, housing, loan, contact, day, month, duration, campaign, pdays, previous, poutcome
Target: y (yes/no - subscription status)
Workflow
1. Preprocessing:
Handled missing values and encoded categorical data.
Split the data into training (70%) and testing (30%).
2. Model Training:
Used a Decision Tree Classifier with gini criterion and max_depth=4.
3. Evaluation:
Accuracy: 89.88%
Class Imbalance: The model performs better on the majority class (no) than the minority class (yes).

Results
Metric  	No Class  	Yes Class
Precision	  0.91	      0.65
Recall	    0.98	      0.29
F1-Score	  0.94	      0.40

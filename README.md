### This is a repo for course homework and project for INSFCI0510: Python for Data Analysis and Machine Learning

The course project was conducted using the same dataset as CEE project on flight delay prediction. The outcome was not ideal, which indicates low quality of dataset

### Project Workflows
1. transfer regression problem into classification problem
2. adress missing values, fliter redundancy columns and encode categorical ones
3. Due to dataset after encoding has too many features, anomaly detection (isolation forest), importance analysis (truncated SVD)
4. conduct more elaborate analysis using random forest and hyperparameter tuning, with best accuracy of 0.647 and outcome of the highest component explains most of the target variable
5. filter top3 and continue ML task (although makes little sense but due to time limit, using another dataset was not feasible)
6. Algorithms like LR, DT, GD, SVM were experimented with SVM achieved highest accuracy of 59%

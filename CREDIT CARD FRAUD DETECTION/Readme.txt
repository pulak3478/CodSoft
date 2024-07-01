Project Summary

1. Data Disparity :
•	Observation: The dataset exhibited significant imbalance with fraudulent transactions being a small fraction of the total.
•	Challenge: Imbalance can bias the model towards the majority class (legalimate transactions).

2. Transaction :
•	Observation: The mean transaction amount is higher for fraudulent transactions compared to legalimate ones.
•	Implication: This feature can be important in distinguishing fraud from legalimate transactions.

3. Data Handling:
•	Method: Employed under-sampling of legalimate transactions to balance the dataset.
•	Goal: Improve the model's ability to detect fraudulent transactions.

4. Model Selection:
•	Model: Logistic Regression.
•	Reason: Chosen for its simplicity and effectiveness in binary classification problems.

5. Model Performance:
Training Data Accuracy: 93.78%
Test Data Accuracy: 92.06%

Outcome: The logistic regression model, combined with under-sampling, effectively distinguished between fraudulent and legalimate transactions, achieving high accuracy and balanced performance metrics.

Future Work and Enhancements

1. Complex Models:
Random Forest: Could capture non-linear relationships and interactions between features.
Gradient Boosting Machines (GBM): Often provides better performance on structured data.
Neural Networks: Particularly useful if there is a large amount of data and complex patterns to be captured.

3. Feature Engineering:
Create new features: Derive new features that might provide more insights into transaction patterns.
Feature Selection: Use techniques like Recursive Feature Elimination (RFE) to select the most relevant features.

4. Model Evaluation Metrics:
Precision, Recall, and F1-Score: These metrics are crucial in assessing the performance of models on imbalanced datasets.
ROC-AUC Curve: Provides a comprehensive view of model performance across different threshold values.

Conclusion: 
In conclusion, the credit card fraud detection project effectively addressed the challenge of data imbalance by using under-sampling techniques and logistic regression. The model demonstrated high accuracy in distinguishing between fraudulent and legalimate transactions, with training and test accuracies of 93.78% and 92.06%, respectively. Future work will focus on advanced resampling techniques, exploring more complex models, and enhancing feature engineering to further improve detection capabilities. 


Dataset Link: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud
Google Colab Link: https://colab.research.google.com/drive/1SQDraQ1PqlQL1rmI3njC0Nlb8H-pyfpB?usp=sharing
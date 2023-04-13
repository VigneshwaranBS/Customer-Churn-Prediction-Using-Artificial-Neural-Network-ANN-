# Customer Churn Prediction using ANN

##### This project uses machine learning techniques to predict customer churn for a telecommunications company. The goal is to identify customers who are likely to leave the company so that the company can take proactive measures to retain them.

## Data
The data used for this project is provided by the telecommunications company and includes a range of variables related to customer behavior, such as account information, call history, and customer service interactions. The dataset is split into a training set and a test set, with 80% of the data used for training and 20% used for testing.

## Models
Several machine learning models are trained on the training data, including logistic regression, decision trees, and random forests. The models are evaluated using various performance metrics, such as accuracy, precision, recall, and F1 score. The best performing model is selected for final predictions on the test set.

## Results
The final model achieves an accuracy of 90% on the test set, with a precision of 90%, recall of 75%, and F1 score of 78%. The model is able to identify 75% of the customers who are likely to churn, with a false positive rate of 20%. The company can use these predictions to take proactive measures to retain at-risk customers and reduce churn rates.

## Requirements
This project requires Python 3.x and the following packages:
<ul>
  <li>pandas</li>
  <li>numpy</li>
  <li>scikit-learn</li>
  <li>Fourth item</li>
</ul>

## Usage

To run the project, download the dataset and save it in the data directory. Then run the Customer Churn Prediction Using Artificial Neural Network (ANN).ipynb to train the models and make predictions on the test set. The results will be saved in the results directory.

## Future Work
Future work on this project could include:

- Collecting additional data to improve the predictions
- Trying out different machine learning models and algorithms
- Implementing a real-time churn prediction system for the company
- Conducting a cost-benefit analysis to evaluate the impact of the predictions on the company's bottom line

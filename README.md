#Customer Churn Prediction using ANN
This project aims to predict customer churn using Artificial Neural Networks (ANN). Customer churn is a significant problem for businesses, and predicting it accurately can help them take timely actions to retain their customers. We have used a dataset of telecom customers and trained an ANN model to predict which customers are likely to churn. The model achieved an accuracy of 85% on the test set. In addition to the model, we have also included the dataset, pre-processing code, and evaluation metrics for transparency and reproducibility.

#Dataset
The dataset used in this project is the Customer Churn dataset from Kaggle. It contains information about Bank customers such as their Credit Score, Estimated Salary, Geography Region etc. as well as whether they churned or not. The dataset has 10000 rows and 14 columns.

#Pre-processing
The dataset was pre-processed before training the ANN model. The pre-processing steps included:

Handling missing values
Encoding categorical variables
Scaling numerical variables

#Training
The ANN model was trained using Keras with TensorFlow backend. The model architecture consisted of two hidden layers with 11 and 11 neurons, respectively, and a binary output layer. The model was trained for 100 epochs.

#Evaluation
The trained model was evaluated on a test set, and it achieved an accuracy of 85%. We have included the whole work in the customer-churn-prediction-ANN.ipynb notebook.

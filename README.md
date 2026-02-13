📌 Overview

This project predicts customer churn using an Artificial Neural Network (ANN).
The goal is to identify customers who are likely to leave a service based on historical data.
Churn prediction helps businesses:
Improve customer retention
Reduce revenue loss
Design targeted marketing strategies

📊 Dataset

The project uses the Churn_Modelling.csv dataset containing customer information such as:
Credit Score
Geography
Gender
Age
Tenure
Balance
Number of Products
Has Credit Card
Is Active Member
Estimated Salary
Target Variable:
Exited → 1 (Churned), 0 (Retained)

⚙️ Tech Stack
Python 3.10
TensorFlow / Keras
Pandas
NumPy
Scikit-learn
Streamlit (for deployment)

🧠 Model Architecture
The ANN model includes:
Input Layer
Hidden Layers (Dense layers with ReLU activation)
Output Layer (Sigmoid activation for binary classification)
Loss Function:
Binary Crossentropy
Optimizer:
Adam
Evaluation Metric:
Accuracy

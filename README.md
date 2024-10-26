CodSoft Team,

I wanted to take a moment to express my sincere gratitude for the remote internship experience in machine learning. Working independently on each project provided a unique opportunity to develop my technical skills and gain hands-on exposure to real-world applications. The guidance and support I received were invaluable in helping me navigate challenges and deepen my understanding.

Thank you for this opportunity, which has greatly contributed to my growth. I look forward to applying what I've learned in future projects.

Dwaipayan Dasgupta

# Codsoft2
Intership Project

Fraudulent Credit Card Transaction Detection
This project aims to build a machine learning model to detect fraudulent credit card transactions using various classification algorithms, including Logistic Regression, Decision Trees, and Random Forests. The model is designed to classify transactions as fraudulent or legitimate based on transactional and customer data.

Introduction
This project addresses the critical task of identifying fraudulent credit card transactions. With the rise of online transactions, detecting fraudulent activity in real-time is essential to protect customers and minimize losses.

Dataset
The dataset (fraudtest1.csv) contains transaction details, customer information, and labels indicating whether a transaction is fraudulent. Essential preprocessing steps include handling missing data, feature engineering (e.g., time extraction), and one-hot encoding of categorical variables.

Features
Standard Scaling: Standardizes the feature set for improved performance of machine learning algorithms.
SMOTE: Used to balance the dataset by oversampling the minority class, improving the model’s ability to detect fraud.
One-Hot Encoding: Converts categorical features into a format suitable for model training.
Model
The project includes three algorithms:

Logistic Regression: A straightforward linear classifier with a one-vs-rest scheme.
Decision Tree: A non-linear classifier that makes hierarchical decisions to determine class labels.
Random Forest: An ensemble of decision trees that reduces overfitting and improves classification accuracy.
Model Evaluation
The model's performance is assessed using accuracy, precision, recall, F1-score, and ROC-AUC metrics, along with visualizations of the confusion matrix and ROC curve.

Results
The models' performances are displayed through various metrics and visualizations.

Sample Confusion Matrix:

![image](https://github.com/user-attachments/assets/50f1434c-5871-4784-a534-f24cf897ce94)

Sample ROC Curve:

![image](https://github.com/user-attachments/assets/886359bf-7715-4d30-8cee-4f963fcb53e6)

Contributing
Contributions are welcome. Please feel free to submit a Pull Request.

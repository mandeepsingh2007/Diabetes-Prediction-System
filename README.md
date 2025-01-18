**🩺 Diabetes Prediction ML System**

**📖 Overview**

This project implements a machine learning predictive system that determines whether a person is diabetic or non-diabetic based on health diagnostic data.

The system leverages the Support Vector Machine (SVM) classifier with a linear kernel, ensuring high accuracy for binary classification.

**🛠️ Technologies Used**

Programming Language: Python

Libraries:

pandas for data manipulation

numpy for numerical operations

scikit-learn for machine learning and preprocessing

Dataset: Pima Indians Diabetes Dataset

**🧪 Model Workflow**

**Data Loading**

Load the diabetes dataset and split it into features (X) and target labels (Y).

**Data Preprocessing**

Standardize the data using StandardScaler to ensure uniform scaling of features.

**Data Splitting**

Split the data into training (80%) and testing (20%) sets using stratified sampling to maintain class balance.

**Model Training**

Train the SVM classifier with a linear kernel on the training dataset.

**Model Evaluation**

Calculate accuracy on both training and testing datasets.

**Prediction**

The model predicts whether the input health data corresponds to a diabetic or non-diabetic individual.

**🧪 Results**

Training Accuracy: 78.5%

Testing Accuracy: 77.4%

**📜 Future Enhancements**

Implement additional algorithms such as Random Forest, Gradient Boosting, etc., for performance comparison.

Add visualizations to explore the dataset and understand feature importance using matplotlib or seaborn.

Deploy the system as an interactive web application using Flask, Streamlit, or Dash.

**🤝 Contributing**

Feel free to fork this repository and create a pull request to contribute.

Suggestions for improvement and new features are highly encouraged! 😊

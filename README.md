#  Student Career Prediction using AIML

# Project Overview
This project predicts the most suitable career path for students based on their skills using a Deep Learning model. It analyzes multiple intelligence features such as linguistic, logical, interpersonal, and more to recommend a job profession.

# Technologies Used
* Python 
* TensorFlow / Keras 
* Pandas & NumPy 
* Scikit-learn 
* Matplotlib 

# Dataset
* The dataset is loaded from an Excel file (`Dataset Project 404.xlsx`)
* It contains student skill scores and corresponding job professions

# Features Used
* Linguistic
* Musical
* Bodily
* Logical - Mathematical
* Spatial-Visualization
* Interpersonal
* Intrapersonal
* Naturalist

# Target Variable
* **Job Profession** (Career prediction output)

# Project Workflow
1. Data Loading using Pandas
2. Data Preprocessing (cleaning, handling missing values)
3. Label Encoding & One-Hot Encoding
4. Train-Test Split
5. Feature Scaling using StandardScaler
6. Model Building using Neural Network
7. Model Training
8. Model Evaluation (Accuracy, Precision, Recall, F1-score)
9. Visualization (Accuracy & Loss Graphs)
10. Career Prediction for New Students

# Model Architecture
* Input Layer
* Dense Layer (128 neurons, ReLU)
* Dropout Layer (0.3)
* Dense Layer (64 neurons, ReLU)
* Dropout Layer (0.2)
* Output Layer (Softmax)
  
# Evaluation Metrics
* Accuracy
* Precision
* Recall
* F1-Score
* Classification Report

# Results
* The model achieves good accuracy in predicting career paths
* Performance is evaluated using both metrics and graphs

# Sample Prediction
Example input:
[15, 8, 12, 18, 16, 14, 17, 10]
Output:
Recommended Career Path: <Predicted Job>

# Key Concepts
* Machine Learning
* Deep Learning
* Neural Networks
* Data Preprocessing
* Model Evaluation

# Future Improvements
* Add more features for better accuracy
* Use advanced models (CNN, RNN)
* Deploy as a web application

# Author
Lakshmi Priya

# Conclusion
This project demonstrates how Artificial Intelligence can help students choose suitable career paths based on their abilities.

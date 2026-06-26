# 🧠 Customer Satisfaction (CSAT) Prediction using Deep Learning (ANN)

## 📌 Project Overview

Customer satisfaction is one of the most important indicators of service quality in the e-commerce industry. Understanding customer experiences enables organizations to improve operational efficiency, enhance customer retention, and make informed business decisions.

This project develops a **Deep Learning Artificial Neural Network (ANN)** to predict Customer Satisfaction (CSAT) scores based on customer service interactions from an e-commerce platform. The project follows a complete end-to-end machine learning workflow, including data preprocessing, feature engineering, model development, evaluation, and interpretation.

---

# 🎯 Problem Statement

The objective of this project is to predict customer satisfaction scores (CSAT) using historical customer interaction data.

Instead of relying only on customer surveys, the developed ANN model predicts customer satisfaction based on various service-related attributes, allowing businesses to identify factors influencing customer experience and improve service quality proactively.

---

# 📂 Dataset Information

The dataset contains approximately **85,900 customer service records** collected over one month from an e-commerce platform.

### Dataset Features

- Unique ID
- Customer Support Channel
- Category
- Sub-category
- Customer Remarks
- Order Information
- Issue Reported Time
- Response Time
- Customer City
- Product Category
- Item Price
- Connected Handling Time
- Agent Details
- Tenure Bucket
- Agent Shift
- CSAT Score (Target Variable)

---

# 🎯 Project Objectives

- Clean and preprocess customer interaction data.
- Handle missing values and inconsistent records.
- Engineer meaningful features for prediction.
- Build an Artificial Neural Network (ANN) model.
- Optimize model training using callbacks.
- Evaluate model performance using multiple metrics.
- Interpret model predictions using feature importance.
- Save the trained model for future deployment.

---

# 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- TensorFlow / Keras
- Joblib

---

# 📊 Project Workflow

1. Import Libraries
2. Load Dataset
3. Exploratory Data Analysis (EDA)
4. Data Cleaning
5. Missing Value Treatment
6. Feature Engineering
7. Feature Encoding
8. Feature Scaling
9. Train-Test Split
10. Artificial Neural Network Development
11. Model Training
12. Model Evaluation
13. Model Interpretability
14. Business Insights
15. Model Saving

---

# 🧠 Feature Engineering

Several new features were created to improve prediction performance, including:

- Response Time (Minutes)
- Issue Hour
- Survey Month
- Survey Day
- Weekend Indicator
- Price Category
- Handling Time Category

---

# 🤖 ANN Architecture

The final neural network consists of:

- Input Layer
- Dense Layer (128 neurons, ReLU)
- Batch Normalization
- Dropout Layer (30%)
- Dense Layer (64 neurons, ReLU)
- Batch Normalization
- Dropout Layer (20%)
- Dense Layer (32 neurons, ReLU)
- Output Layer (5 neurons, Softmax)

### Training Configuration

- Optimizer: Adam
- Loss Function: Categorical Crossentropy
- Metric: Accuracy
- Early Stopping
- Reduce Learning Rate on Plateau
- Model Checkpoint

---

# 📈 Model Performance

### Test Accuracy

**36.05%**

### Evaluation Metrics

The ANN model was evaluated using:

- Accuracy
- Loss
- Classification Report
- Confusion Matrix
- Training & Validation Curves
- Permutation Feature Importance

Although the dataset is highly imbalanced, the model successfully learned meaningful customer satisfaction patterns and provided valuable business insights.

---

# 🔍 Key Insights

Permutation Feature Importance identified the following as the most influential features:

1. Customer City
2. Category
3. Product Category
4. Price Category
5. Item Price
6. Sub-category
7. Weekend
8. Issue Hour
9. Support Channel
10. Response Time

These findings highlight the importance of customer demographics, issue type, and product characteristics in influencing customer satisfaction.

---

# 📁 Project Structure

```
Customer-Satisfaction-Prediction/
│
├── Customer_Satisfaction_ANN.ipynb
├── best_ann_model.keras
├── scaler.pkl
├── target_encoder.pkl
├── dataset.csv
├── README.md
└── requirements.txt
```

---

# 🚀 How to Run

### Clone the Repository

```bash
git clone https://github.com/yourusername/customer-satisfaction-ann.git
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```
Customer_Satisfaction_ANN.ipynb
```

Run all cells sequentially.

---

# 💼 Business Value

This project demonstrates how deep learning can support customer service teams by:

- Predicting customer satisfaction
- Identifying key drivers of customer experience
- Supporting service quality improvements
- Assisting data-driven decision making
- Enabling future real-time prediction systems

---

# 🔮 Future Improvements

- Improve class balance using advanced resampling techniques.
- Apply hyperparameter optimization.
- Use embedding layers for categorical variables.
- Incorporate customer remarks using Natural Language Processing (NLP).
- Compare ANN with advanced boosting algorithms.
- Deploy the model using Streamlit or Flask for real-time predictions.

---

# 👨‍💻 Author

**Yashman Singh**

Master's in Computer Science (Data Science & AI)

Interested in Machine Learning, Data Science, Business Intelligence, and Deep Learning.

---

## ⭐ If you found this project helpful, consider giving the repository a star!

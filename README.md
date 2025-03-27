# Fraud Detection Project

## **Overview**
This project is a **fraud detection system** built using **Machine Learning** techniques. The model is designed to classify transactions as either **fraudulent** or **legitimate**, helping organizations minimize financial risks and enhance security in financial transactions.

## **Features**
### **Data Preprocessing**
- Handling missing values.
- Removing duplicate transactions.
- Normalizing and standardizing features.

### **Feature Engineering**
- Selecting the most important features for classification.
- Creating new features for better model performance.

### **Exploratory Data Analysis (EDA)**
- Visualizing transaction distributions.
- Identifying fraudulent transaction patterns.

### **Machine Learning Model Implementation**
- **Logistic Regression**: A simple yet effective classification algorithm used for fraud detection.

### **Performance Evaluation**
- Measuring **Accuracy, Precision, Recall, F1-score, and AUC-ROC score**.
- Avoiding overfitting and bias in model predictions.

## **Technologies Used**
- **Python** *(Primary programming language)*
- **Pandas & NumPy** *(Data manipulation and analysis)*
- **Matplotlib & Seaborn** *(Data visualization)*
- **Scikit-Learn** *(Machine learning model training and evaluation)*
- **Jupyter Notebook** *(For interactive development and visualization)*

## **How to Run the Project**
### **Step 1: Clone the repository**
```bash
git clone <repository_url>
```

### **Step 2: Navigate to the project directory**
```bash
cd fraud-detection
```

### **Step 3: Install dependencies**
```bash
pip install -r requirements.txt
```

### **Step 4: Run the Jupyter Notebook**
```bash
jupyter notebook FraudDetection_final.ipynb
```

Follow the instructions in the notebook to execute the fraud detection pipeline step by step.

## **Dataset Information**
- The dataset contains transaction records with features such as **transaction amount, time, location, sender details, and receiver details**.
- The target variable indicates whether a transaction is **fraudulent (1)** or **legitimate (0)**.
- The dataset underwent **cleaning, normalization, and balancing techniques** to enhance model performance.

## **Results**
### **Model Performance Metrics**
- **Accuracy**: Measures overall correctness.
- **Precision**: Ensures fewer false positives.
- **Recall**: Captures as many fraudulent transactions as possible.
- **F1-score**: A balance between precision and recall.
- **AUC-ROC Score**: Measures model discrimination ability.

## **Challenges Faced**
### **Imbalanced Dataset**
- Addressed using **SMOTE (Synthetic Minority Over-sampling Technique)** to balance classes.

### **Feature Selection**
- Used **feature importance and correlation analysis** to remove irrelevant features.

### **Overfitting**
- Controlled using **cross-validation and regularization techniques**.

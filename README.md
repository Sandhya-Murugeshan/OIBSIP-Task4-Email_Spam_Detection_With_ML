# OIBSIP-Task4-Email_Spam_Detection_With_ML

# 📧 Email Spam Detection using Machine Learning

## Project Overview
Spam emails are unwanted messages sent in bulk, often containing advertisements, scams, or phishing links. This project builds a Machine Learning model that automatically classifies emails as **Spam** or **Not Spam (Ham)** based on their content.

---

## Objective
The main objective of this project is to:
- Analyze email text data
- Convert text into numerical features
- Train a machine learning model
- Classify emails accurately into spam or ham

---

## Technologies Used
- Python 
- Pandas
- NumPy
- Scikit-learn

---

##  Dataset
The dataset consists of:
- `Category` → Label (spam / ham)
- `Message` → Email text content

---

## Project Workflow

### 1. Data Preprocessing
- Loaded the dataset using Pandas
- Selected only required columns
- Converted labels:
  - Spam → 1
  - Ham → 0

### 2. Feature Extraction
- Used **TF-IDF Vectorization** to convert text data into numerical form

### 3. Model Training
- Applied **Multinomial Naive Bayes** algorithm
- Split the dataset into training and testing sets

### 4. Evaluation
- Evaluated the model using:
  - Accuracy Score
  - Classification Report

---

## 📊 Results
- Achieved high accuracy (~95% – 98%)
- The model performs well on unseen email data

---

## Sample Prediction

```python
sample_email = ["Congratulations! You have won a free prize. Click now!"]
Output:
Spam Email 🚫

 
## Conclusion

This project demonstrates how Machine Learning can be effectively used to detect spam emails. By applying text preprocessing and TF-IDF vectorization, the model is able to understand patterns in email content and classify them accurately. The approach is simple, efficient, and can be extended for real-world email filtering systems.

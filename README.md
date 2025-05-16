# ML-model

## 🎧 Audiobook Customer Purchase Prediction
This project uses machine learning to predict whether an existing customer of an Audiobook app will make another purchase within the next 6 months, based on their past engagement over a 2-year period.

## 📌 Project Objective
The goal is to help the Audiobook company:

Identify returning customers using historical data.

Reduce advertising costs by avoiding spend on low-probability customers.

Enhance customer targeting and retention strategies.

This is a binary classification problem (Buy Again: 1, Won't Buy Again: 0).

## 🧠 Technologies Used
Python 3

TensorFlow / Keras – for building the deep learning model

NumPy & Pandas – for data processing

Scikit-learn – for data preprocessing and train-test splitting

## 📊 Dataset Overview
The dataset (Audiobooks_data.csv) contains anonymized customer behavior data with the following features:

Feature	Description
Book length overall	Total minutes of audiobooks purchased
Book length avg	Average length per purchase
Price paid overall	Total money spent
Price paid avg	Average price per purchase
Review	Boolean (1 if review was left)
Review out of 10	Rating left by the customer (if reviewed)
Total minutes listened	Total engagement time
Completion	Average completion ratio (0–1)
Support requests	Number of customer support interactions
Last visited minus purchase date	Days since last visit relative to last purchase

The Target column indicates whether a customer made another purchase in the 6-month prediction window.

## ✅ Results
Model is trained on balanced data (equal number of 0s and 1s) to prevent bias. Accuracy on the test set is typically around 85%–90% (depending on parameters and data split).

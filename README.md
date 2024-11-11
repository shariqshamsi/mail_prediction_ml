# Mail_Prediction_Ml
This repository contains a machine learning model for predicting email categories, such as spam detection. The model uses a logistic regression classifier and TF-IDF vectorization to analyze text data, providing accurate predictions for given email.

# Project Overview
The goal of this project is to train a machine learning model that can predict categories for email text data. By using a TF-IDF (Term Frequency-Inverse Document Frequency) vectorizer, we transform text data into numerical features, which allows the model to better understand and classify emails. The logistic regression model is used due to its simplicity and effectiveness in binary classification tasks.

# Technologies and Libraries
The following libraries were used to develop this project:

 - **NumPy**: For handling arrays and performing efficient numerical computations.
 - **Pandas**: For data manipulation and preprocessing.
 - **Scikit-Learn:**
   - **TfidfVectorizer**: To convert email text into numerical features.
   - **train_test_split**: For splitting data into training and testing sets.
   - **LogisticRegression**: The main algorithm used for classification.
   - **accuracy_score:** To measure the accuracy of the model on test data.

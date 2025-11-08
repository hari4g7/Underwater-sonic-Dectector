**Project Overview:**

Underwater environments are difficult to observe directly because visibility is often low. Sonar signals help detect objects such as rocks, submarines, mines, and underwater structures. In this project, Logistic Regression, a supervised machine learning algorithm, is used to classify sonar signals into two categories: Rock or Mine/Object.

The model learns patterns from sonar frequency data and predicts the nature of the object from new sonar readings.

**Objective:**

1.To analyze underwater sonar signal data.

2.To classify signals into Rock or Mine.

3.To apply Logistic Regression for binary classification.

4.To evaluate model performance and accuracy.

**Dataset:**

This project uses the Sonar Dataset which contains:

**->** 300 sonar signal features (numerical frequency energy values)

**->** Label: R = Rock, M = Mine

**Methodology:**

1.Data Loading & Exploration

2.Data Preprocessing

3.Converted categorical labels into numeric form

4.Standardized feature values

5.Train-Test Split

6.Model Training using Logistic Regression

7.Model Evaluation (Accuracy)

**Tools & Technologies:**

1.Python Programming

2.Pandas / NumPy for Data handling

3.Scikit-Learn for Logistic Regression model

4.Matplotlib / Seaborn for Data Visualization

**Results:**

**->** The trained model successfully classifies sonar readings with good accuracy.

**->** It helps identify whether the detected object underwater is a rock or a mine.

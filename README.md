## Emotion Recognition using EEG Brainwave Data

---

### Project Overview

---

In this project, I aim to predict human emotions using EEG brainwave data. EEG (Electroencephalography) is a technique used to record electrical activity in the brain. The dataset I'm using contains EEG readings from individuals experiencing different emotions, and my goal is to build a machine learning model that can accurately predict the emotion based on these readings.

 ---

### Dataset
The dataset I'm using is available on Kaggle and contains EEG brainwave data along with the associated emotion for each data point. The emotions are categorized into three classes: POSITIVE, NEUTRAL, and NEGATIVE. The EEG data is represented as various features derived from the EEG signals, such as mean and FFT (Fast Fourier Transform) values.

### Approach
I start by preprocessing the data, which involves cleaning, normalization, and splitting the data into a training set and a test set. I then train a Random Forest model on the training data and evaluate its performance on the test data. I also explore other models like Logistic Regression and Gradient Boosting, and perform hyperparameter tuning and cross-validation to improve the performance of my models.

Throughout the project, I also visualize the data and the results to gain a better understanding of the relationships between the features and the target variable. This includes creating a correlation heatmap, a feature importance plot, and a confusion matrix.

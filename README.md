# EEP_596_Project2
## Deep Learning-Based ECG Heartbeat Classification for Arrhythmia Detection

### Project Overview:
This repository contains Project 2 for the course EE P 596: Advanced Introduction to Machine Learning. The project, instructed by Prof. Karthik Mohan, was completed by students Naif A Ganadily and Sarah Selim, with assistance from TA Ayush Singh and Grader Fatwir SM.

This project employs deep learning techniques to accurately classify distinct heartbeat types from electrocardiogram (ECG) data, with the primary aim of assisting in arrhythmia diagnosis. The models built in this project were tested and ranked high in the Kaggle competition "Arrhythmia heartbeat classification Win23."

### Data Source and Preprocessing:
The ECG data is derived from the MIT-BIH database and preprocessed using a tailored "preprocessor" function that isolates specific heartbeat types and consolidates the data into a single dataframe.

### Data Visualization:
Various data visualization techniques, such as scatter plots and histograms, are utilized to understand patterns and correlations in the data, guiding the feature extraction process.

### Handling Class Imbalance and Feature Extraction:
After cleaning and normalizing the data, class imbalance is assessed and addressed using random under-sampling and data augmentation methods, such as SMOTE (Synthetic Minority Over-sampling Technique). Feature extraction is performed to reduce dimensionality and retain only significant features for model training.

### Machine Learning Models and Evaluation:
Logistic regression and random forest models are trained and evaluated using metrics such as accuracy, precision, recall, and F1 score. The models are optimized using hyperparameter tuning, cross-validation, and feature selection methods.

### Convolutional Neural Network (CNN) Model:
A CNN model is built with multiple convolutional and dense layers, using the Keras library in TensorFlow. The model is optimized through techniques like dropout layers and batch normalization. The performance is evaluated using the same metrics as the machine learning models.

### Performance Metrics and Visualization:
The project encompasses functions for computing and visualizing confusion matrices, ROC curves, and false positive and false negative results for Class R. These visualizations provide valuable insights into the model's performance and help identify areas for improvement.

### Kaggle Competition Participation:
This project participated in the Kaggle competition "Arrhythmia heartbeat classification Win23," and the team, Rhythm Detectives, achieved a score of 0.61917. Link: https://www.kaggle.com/competitions/arrhythmia-heartbeat-classification-win23/leaderboard

### Conclusion:
In summary, this project showcases the promising potential of deep learning in the precise classification of heartbeats and arrhythmia diagnosis, and serves as a valuable learning resource for future research in the field of ECG-based arrhythmia detection.

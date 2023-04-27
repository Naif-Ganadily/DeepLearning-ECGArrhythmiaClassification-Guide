# EEP_596_Project2
# Deep Learning-Based ECG Heartbeat Classification for Arrhythmia Detection


This project employs deep learning techniques to accurately classify distinct heartbeat types from electrocardiogram (ECG) data, with the primary aim of assisting in arrhythmia diagnosis. The project focuses on the identification of normal heartbeats (N) and various abnormal heartbeats (R, A, L, V). The workflow encompasses several stages, such as data preprocessing, visualization, addressing class imbalance, feature extraction, and model training and evaluation.

The ECG data is derived from the MIT-BIH database and preprocessed using a tailored "preprocessor" function that isolates specific heartbeat types and consolidates the data into a single dataframe. Subsequently, the data is visualized, cleaned, and non-numeric values are replaced with NaNs, which are then substituted with 0s. The dataset undergoes normalization and class imbalance assessment, which is tackled through random under-sampling and data augmentation methods.

Two machine learning models, logistic regression and random forest, are trained and evaluated on the processed data. Moreover, a convolutional neural network (CNN) model is constructed using the Keras library in TensorFlow, featuring multiple convolutional and dense layers, and assessed on the same dataset.

The project encompasses functions for computing and visualizing false positive and false negative results for Class R, offering valuable insights into the model's performance. In summary, this project showcases the promising potential of deep learning in the precise classification of heartbeats and arrhythmia diagnosis.

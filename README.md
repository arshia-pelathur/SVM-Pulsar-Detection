# SVM-Pulsar-Detection

### Project Overview
This project aims to classify pulsar candidates collected during the High Time Resolution Universe Survey (HTRU2), using Support Vector Machine (SVM) models. Pulsars are a rare type of Neutron star that produce radio emission detectable here on Earth. They are of great scientific interest as probes of space-time, the interstellar medium, and states of matter.

### Dataset
The dataset used in this project is the HTRU2 dataset, which can be accessed here. It contains 17,898 total examples with 1,639 positive examples and 16,259 negative examples. Each example has eight continuous features and a class label that indicates whether a pulsar is present (1) or not (0).

### Features
The dataset includes the following eight continuous variables:

1. Mean of the integrated profile.
2. Standard deviation of the integrated profile.
3. Excess kurtosis of the integrated profile.
4. Skewness of the integrated profile.
5. Mean of the DM-SNR curve.
6. Standard deviation of the DM-SNR curve.
7. Excess kurtosis of the DM-SNR curve.
8. Skewness of the DM-SNR curve.

### Points Covered
The Analysis done are as below:

1. Feature Analysis
2. Missing Values
3. Outlier Analysis
4. Target Feature Distribution
5. Handling Imbalanced Classes - SMOTE
6. Model Building and Evaluation
7. Model Comparision

### Conclusion
This repository contains a machine learning project that utilizes Support Vector Machines (SVM) to classify pulsar candidates from the HTRU2 dataset. The project explores different SVM kernels including linear, polynomial, sigmoid and RBF to determine the most effective approach for identifying these rare neutron stars based on radio emissions. Through rigorous hyperparameter tuning, including adjustments to regularization and kernel parameters, this analysis aims to optimize classification accuracy and provide insights into the predictive capabilities of SVM in astrophysical data.


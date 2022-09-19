# ML-collusion-fraud-classification
By /pernillekober & /EkaterinaBatueva

Comparison of neural network against different ML algorithms for fraud detection - specifically applied to detect collusion in publid procurement of vaccines. It was concluded that the best classification model for predicting collusion appeared to be a Gradient boosting model based on merged data, having 99.6% recall and 20% precision. The weighted neural network is expected to work better on a larger dataset with more variation.

The best neural network - among nn apllied with upsampling and weighting techniques - is benchmarked against Random Forest, Gradient Boosting (XGBoost) and SVM. To handle the issue of class imbalance upsampling techniques were used and performance compared with recall, precision and F1. 

Libraries applied: Keras, sklearn, imblearn, scipy, seaborn, matplotlib, numpy

#collusiondetection, #frauddetection, #binaryclassification, #classimbalance #costsensitivelearning

# ML-collusion-fraud-classification
By /pernillekober & /EkaterinaBatueva

**Libraries:** Keras, sklearn, imblearn, scipy, seaborn, matplotlib, numpy. \
**Techniques:** ML (SVM, RF, XGB), neural networks, up/down-sampling, cost-sensitive learning.

Comparison of neural network against different ML algorithms for fraud detection - specifically applied to detect collusion in public procurement of vaccines (prior to auction). It was concluded that the best classification model for predicting collusion appeared to be a Gradient boosting model based on merged data, having 99.6% recall and 20% precision. The number of approved applicants, number of rejected applicants, number of applications that somehow “show up in the submission within one hour2 and the amount required as security for application. This study also indicated that models could be applied on vaccine procurements auctions regardless of vaccine type and data could be merged across pathology type to increase data set. 

The best neural network - among nn apllied with upsampling and weighting techniques - is benchmarked against Random Forest, Gradient Boosting (XGBoost) and SVM. To handle the issue of class imbalance, upsampling techniques were used and performance compared with recall, precision and F1. The approach should be applied again on a larger data set and possible improvements may include investigation of deep over-sampling framework that outperforms other NN frameworks for imbalanced data as well as does not show clear trade-off between recall and precision as introduced by Ando and Huang (2017).

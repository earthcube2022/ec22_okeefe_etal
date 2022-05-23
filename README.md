**[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/earthcube2022/ec22_okeefe_etal/HEAD?filepath=PO_02_Handling_Highly_Imbalanced_Data_in_Machine_Learning_Applications.ipynb)**

# Handling Highly Imbalanced Data in Machine Learning Applications
## Abstract
Machine learning techniques can be applied across various industries to make accurate predictions of future data points based on observed patterns. However, in cases where there are vast imbalances to training data, algorithms may default to the majority classes when predicting future data points and thus cause inaccuracy in predictions. This may be especially undesirable when predicting rare but dangerous activities such as solar proton events (SPE) that could damage sensitive electronics and affect the general ecosystem on Earth. Traditional methods to remedy class imbalance involve manipulation of the training data to create even splits between classes, but synthetically balanced data may be unrepresentative of the original data. There are, however, additional techniques that can be used without the risk of using sampled data that is unrepresentative of the original data.

In this work, we develop a database and analyze the application of various class-imbalance treatment techniques (oversampling, undersampling, class weight assignment) to build balanced classifiers for the prediction of whether the solar flare results in an SPE event, with the goal of developing an unbiased solution. Our data set consists of the soft X-ray properties of the solar flares detected by GOES satellite from 2001 to 2020, namely the peak values of the flux in 0.05-0.4 nm and 0.1-0.8 nm channels and related temperature and emission measure peak values derived with TEBBS algorithm. We utilize the balanced accuracy score and other assessment metrics (such as TSS and HSS) for the evaluation of the machine learning prediction. We find that vastly imbalanced data may be analyzed without the risks involved with oversampling or undersampling and accurate, unbiased classifications may be produced.

# Credit_Risk_Analysis

## Project Overview
The purpose of this project is to use different supervised machine learning models on a credit card dataset from LendingClub to predict credit risk. The machine models used for this project are the Random Over Sampler, Random Under Sampler, SMOTE, SMOTEENN, Random Forest, and ADA Boost.

## Project Results

### RandomOverSampler
- The accuracy score for the Random Over Sampler model was 64%.

![](Resources/oversample_acc.png)

![](Resources/oversample_class.png)

### SMOTE
- The accuracy score for the SMOTE model was 66%.

![](Resources/smote_acc.png)

![](Resources/smote_class.png)

### RandomUnderSampler
- The accuracy score for the Random Under Sampler model was 60%.

![](Resources/undersample_acc.png)

![](Resources/undersample_class.png)

### SMOTEENN
- The accuracy score for the SMOTEENN model was 65%.

![](Resources/smoteenn_acc.png)

![](Resources/smoteenn_class.png)

### RandomForestClassifier
- The accuracy score for the Random Forest model was 68%.

![](Resources/forest_acc.png)

![](Resources/forest_class.png)

### AdaBoostClassifier
- The accuracy score for the ADA Boost model was 69%.

![](Resources/boost_acc.png)

![](Resources/boost_class.png)

## Project Summary
- All six machine learning models returned an accuracy range between approximately 60 and 69%. While the improvements were modest and incremental between the different models, the ADA Boost model had the highest accuracy and therefore the most recommended for this dataset. 

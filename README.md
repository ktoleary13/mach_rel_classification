# mach_rel_classification
Machine learning classification model for relationship status based on Machiavellianism and other personality markers. 

This uses data from OpenPsychometrics on Machiavellianism. A machine learning pipeline was developed to build a classification model 
for predicting marital status outcomes. The final model selected was XGBoost, which was implemented with a stratified kfolds on 26,000 data points.
The results showed ~85% balanced accuracy score, which is well above the baseline for this metric. 

The packages used: 
Python version is 3.9.7 | packaged by conda-forge | (default, Sep 2 2021, 17:58:46)
numpy version 1.21.1
matplotlib version 3.4.2 
sklearn version 0.24.2 
pandas version 1.3.1 
xgboost version 1.3.3 
shap version 0.39.0 
seaborn version 0.11.2
opendatasets version 0.1.20
joypy version 0.2.5

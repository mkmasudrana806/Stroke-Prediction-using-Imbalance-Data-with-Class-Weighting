# Stroke-Prediction-using-Imbalance-Data-with-Class-Weighting
An explainable ensemble framework (CWSE) for stroke risk prediction using imbalanced EHR data without synthetic oversampling. Includes SHAP-based clinical interpretability and comparative performance analysis.

- Imbalance learn: Where we train model on raw imbalance dataset with class-weighted stacking ensemble learning.
- Under-sampling: Where we train all models again with undersampling data.
- Oversampling: Where we train model 2 steps. 1st: We oversampling train data and keep test data intact. 2nd: We oversampling both train and test data.

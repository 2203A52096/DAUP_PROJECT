# DAUP_CSV : DATA SET PROTEIN
--> Data set taken from kaggle from https://www.kaggle.com/datasets/gallo33henrique/bioinformatics-protein-dataset-simulated 

## Project Workflow

* *Data reading is performed to load the dataset.*

* *Data exploration is conducted to understand the structure and contents of the data.*

* *Data visualization is done using scatter plots, histograms, and box plots to identify patterns and distributions.*

* *Target and features are selected for model training.*

* *Data preprocessing is applied to clean and prepare the data.*

* *SVM , LGBMClassifier and Random forest are trained on the preprocessed data.*

* *Classification report and confusion matrix are printed to evaluate the initial model performance.*

* *Classes with very few data points are fixed, and outliers are removed to improve data quality.*

* *In Classes with very few data points duplicate rows are addded i.e., oversampling is done.*

* *SMOTE (Synthetic Minority Over-sampling Technique) is applied to handle class imbalance.*

* *The new data is preprocessed again, and the same models are retrained.*

* *Updated classification report and confusion matrix are printed after retraining.*

*  *Skewness and kurtosis values are printed.*

*  *Statistical tests are done.*

After removing outliers and applying SMOTE, the retrained models show an increase in accuracy, F1 score, precision, recall, and support.


# DAUP_IMAGE : DATA SET FASHION
--> From kaggle different datasets are takena nd this dataset is made. Some classes in the dataset are taken from https://www.kaggle.com/datasets/abeerelmorshedy/fashion-clothes and some from https://www.kaggle.com/datasets/ryanbadai/clothes-dataset 

## Project Workflow

# DAUP_AUDIO : DATA SET INDIAN LANGUAGES
--> Data set taken from kaggle from https://www.kaggle.com/datasets/hmsolanki/indian-languages-audio-dataset and size is reduced.

## Project Workflow


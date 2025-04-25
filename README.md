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

Random forest model works best.

# DAUP_IMAGE : DATA SET FASHION
--> From kaggle different datasets are taken and this dataset is made. Some classes in the dataset are taken from https://www.kaggle.com/datasets/abeerelmorshedy/fashion-clothes and some from https://www.kaggle.com/datasets/ryanbadai/clothes-dataset 

## Project Workflow

* *Data collection and data loading is done.*

* *Data is explored with image patha nd class labels.*

* *Data visualization is done in both grey scale and rgb class wise.*

* *data is preprocessed*

* *CNN, mobileNet, EfficeientNet model are trained with 10 epoches each.*

* *Classification report and confusion matrix are plotted.*

* *Statistical tests are done.*

  EfficeientNetB0 is the best model

# DAUP_AUDIO : DATA SET INDIAN LANGUAGES
--> Data set taken from kaggle from https://www.kaggle.com/datasets/hmsolanki/indian-languages-audio-dataset and size is reduced.

## Project Workflow

* *Data collection and data loading is done*
  
* *Audio features are extracted, including:*
  * *MFCCs (Mel Frequency Cepstral Coefficients)*
  * *Chroma features*
  * *Mel-spectrogram*
  * *Zero-Crossing Rate*

* *Duration distribution of audio files is analyzed to understand variability in clip lengths.*

* Waveform, spectogram and MFCC od a sample audio is plotted.*

* *Feature extration is done Of 13 Mfcc mean values.*

* *MFCCs are flattened into 2D vectors for use with traditional machine learning models like Random Forest.*

* *3D MFCC arrays are prepared for deep learning models like LSTM in the format: (samples, time_steps, features).*

* *Data Preprocessing is done.*

* *Model are trained.*

* Classification report and confusion matrix for each model is plotted.*

* *Statitical test are done.*
  
Considering for audio dataset lstm model is the best model.

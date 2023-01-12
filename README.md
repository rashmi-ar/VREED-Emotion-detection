# Emotion dataset VREED
## About dataset
* Analysing emotions using **VREED** dataset. 
* VREED is a publicly available dataset on Kaggle. Download the dataset using this link - [Kaggle](https://www.kaggle.com/datasets/lumaatabbaa/vr-eyes-emotions-dataset-vreed "Kaggle-VREEDdataset") .
* We are using feature extracted eye tracking data, ecg data and gsr data.

## About files
* Each modality is analyzed seperately (GSR, EYE, ECG).
* GSR+ECG+EYE.ipynb contains analysis of multimodal data.
* Visualization.ipynb contains visualization of videos used to collect vreed dataset.

## Results
* Multimodal approach worked better than individual modalities.

GSR+ECG+EYE | Quad_Cat | Arousal | Valence
----------- | -------- | ------- | -------
Accuracy    |   70%    |   90%   |   74%

* Machine learning models like LGBM, LDA, Random Forest, Gradient Boosting Classifier gave better results.



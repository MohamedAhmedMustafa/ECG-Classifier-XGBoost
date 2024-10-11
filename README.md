# ECG-hearbeat

This app first classifies ECG signals using a pre-trained model to determine if the signal is abnormal then provides further classification ( 1 - 2 -3 - 4 ).

The model contains two XGBoost models:
- one to classifiy if it is normal or not
- second to classifiy which type of abnormality it is

The Dataset is taken from kaggle: shayanfazeli/heartbeat

The application is deployed on Streamlit.

App deployment link: https://ecg-classifier-xgboost-pmf6vwgfqjnhan4kwxhqd6.streamlit.app/

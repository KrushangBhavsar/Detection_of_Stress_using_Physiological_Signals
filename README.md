
# Detection_of_Stress_using_Physiological_Signals
This work aims to detect depression using physiological signals such as ECG (Elecrocardiography), EEG(Electroencephalographgy), GSR (Galvanic Skin Response), HRV (Heart Rate Variability). We used classifier to classify stress into 3-class classification. In addition to that, filtering and analysis techniques will be employed to improve algorithm efficiency.

## Project Background
In the current Anthropocene era many people are suffering from stress due to our current lifestyle. Long-term stress that isn’t managed properly might cause major health issues. It is a very dangerous and can lead to some major problems like cardiovascular disease, depression, suicidal activities and many. Early identification of mental stress can help to avoid number of serious health problems.

## Dependency
- Python = 3.6.8
- os
- matplotlib = 3.3.4
- Pickel = 0.7.5
- Numpy = 1.19.5
- Scipy = 1.5.4
- Pandas = 0.23.5
- Scikit-learn = 0.22.2

## Dataset
WESAD dataset will be most relevant. in which a multi-modal data set was collected for stress classifications and assessed by multiple algorithms based on physiological data. The data was gathered in a laboratory setting. For collecting this data, they had chosen 15 people and recorded the physiological data such as threeaxis acceleration, electrocardiogram, blood volume pulse, body temperature, respiration, electromyogram and electrodermal activity by putting wearable devices – RespiBAN Professional and Empatica E4 on the chest and on the wrist respectively. RespiBAN provides sensor data of EDA(Electro Dermal Activity), ECG(Electrocardiography), EMG(Electromyography), RESP(Respiratory), ACC(Three-axis Acceleration). All this signals are sampled at 700 Hz.The Empatica E4 device provides sensor data of blood volume pulse (BVP, 64 Hz), electrodermal activity (EDA, 4 Hz), body temperature (4 Hz), and three-axis acceleration (32 Hz).[1]

## Project Flow
![flow](https://user-images.githubusercontent.com/88844422/129942954-fe224812-124b-4e94-ac78-a10bb004f0a9.PNG)

## Instruction to Implement
1.	Download [WESAD Dataset](https://archive.ics.uci.edu/ml/datasets/WESAD+%28Wearable+Stress+and+Affect+Detection%29)
2.	Now open Jyupter Notebook and Run below Files sequentially.
3.	cvxEDA.ipynb
4.	data_collection_cleaning.ipynb 
5.	sub_info_parser.ipynb
6	  feature_classification.ipynb
7.	model_stress.ipynb 
##### Note:Change "Path to Dataset" to the path where you stored the dataset in code.

## Reference
[1] P. Schmidt, A. Reiss, R. Duerichen, C. Marberger and K. Van Laerhoven, "Introducing WESAD, a Multimodal Dataset for Wearable Stress and Affect Detection", Proceedings of the 20th ACM International Conference on Multimodal Interaction, 2018. Available: 10.1145/3242969.3242985.

[2] A. Greco, G. Valenza, A. Lanata, E. Scilingo and L. Citi, "cvxEDA: a Convex Optimization Approach to Electrodermal Activity Processing", IEEE Transactions on Biomedical Engineering, pp. 1-1, 2016. Available: https://github.com/lciti/cvxEDA.

## Resource
- https://github.com/arsen-movsesyan/springboard_WESAD
- https://github.com/lciti/cvxEDA.
- https://github.com/MITMediaLabAffectiveComputing/eda-explorer/blob/master/AccelerometerFeatureExtractionScript.py

## Contact
:e-mail: - kbhavsar@lakeheadu.ca

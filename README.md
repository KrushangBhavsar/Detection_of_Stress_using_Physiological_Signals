
# Detection_of_Stress_using_Phyiological_Signals
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
WESAD dataset will be most relevant. in which a multi-modal data set was collected for stress classifications and assessed by multiple algorithms based on physiological data. The data was gathered in a laboratory setting. For collecting this data, they had chosen 15 people and recorded the physiological data such as threeaxis acceleration, electrocardiogram, blood volume pulse, body temperature, respiration, electromyogram and electrodermal activity by putting wearable devices – RespiBAN Professional and Empatica E4 on the chest and on the wrist respectively.

## Project Flow
![flow](https://user-images.githubusercontent.com/88844422/129225318-60f5cd98-6d5d-49a8-a5f9-4b2d415e1650.PNG)


## Instruction to Implement
1.	Download WESAD Dataset
2.	Provide proper path name 
3.	Run Data Wrangling.py for Data collection and Cleaning
4.	Run Readme Parser.py
5.	Run feature extraction.py for extracting the feature and classification
6.	Validate the Data and Implement



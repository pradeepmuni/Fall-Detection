Falls among the elderly is an important health issue. Fall detection and movement tracking are therefore instrumental in addressing this issue. This paper responds to the challenge of classifying different movements as a part of a system designed to fulfill the need for a wearable device to collect data for fall and near-fall analysis. Four different fall trajectories (forward, backward, left and right), three normal activities (standing, walking and lying down) and near-fall situations are identified and detected.

Falls are a serious public health problem and possibly life threatening for people in fall risk groups. We develop an automated fall detection system with wearable motion sensor units fitted to the subjects’ body at six different positions. Each unit comprises three tri-axial devices (accelerometer, gyroscope, and magnetometer/compass). Fourteen volunteers perform a standardized set of movements including 20 voluntary falls and 16 activities of daily living (ADLs), resulting in a large dataset with 2520 trials. To reduce the computational complexity of training and testing the classifiers, we focus on the raw data for each sensor in a 4 s time window around the point of peak total acceleration of the waist sensor, and then perform feature extraction and reduction.


Acknowlegement:

Özdemir, Ahmet Turan, and Billur Barshan. “Detecting Falls with Wearable Sensors Using Machine Learning Techniques.” Sensors (Basel, Switzerland) 14.6 (2014): 10691–10708. PMC. Web. 23 Apr. 2017

Reference:https://www.kaggle.com/pitasr/falldata

General information about the dataset, what the columns contain, and what the codes in the ACTIVITY column mean:

Fall detection data set of Chinese hospitals of old age patients.

Columns

ACTIVITY: activity classification
TIME: monitoring time
SL: sugar level
EEG: EEG monitoring rate
BP: Blood pressure
HR: Heart beat rate
CIRCLUATION: Blood circulation
ACTIVITY

0- Standing
1- Walking
2- Sitting
3- Falling
4- Cramps
5- Running

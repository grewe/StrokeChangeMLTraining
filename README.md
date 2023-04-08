# StrokeChangeMLTraining

StrokeChange is a proof-of-concept system that uses computer vision and machine learning to monitor stroke patients in-situ towards the goal of monitoring patient progress and changes. This innovative system can detect changes in a patient's facial expressions, which may indicate changes in their condition, such as the onset of new symptoms or the worsening of existing ones.   Various approaches including detection, classification and regression to solve this problem are implemented and compared.  A dataset was curated for training and testing of StrokeChange.   This work used a modified version of the dataset originally found at Facial_Droop_and_Facial_Paralysis_image, https://www.kaggle.com/datasets/kaitavmehta/facial-droop-and-facial-paralysis-image



This is the repository for the python Tensorflow based Colabs for training the 3 implementations of StrokeChange:  Detection Only,  Region Detect to Classification and Region Detect to Regression

![image](https://user-images.githubusercontent.com/11790686/230692220-c84efe7a-1915-4198-b462-b62febb06c4f.png)




### Directories

#### GeneralColabs
base colabs/notebooks used to train detectors, classifiers and regression models used in StrokeChange
ALSO see other directories for specific directories for spefic colabs used in actual training that are based off of these
general colabs

#### ColabsForProcessingData 
contains colabs/notebooks for processing data to prepare it for training

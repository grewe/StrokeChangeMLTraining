## This directory contains the base Colabs generated for detection, classification and regression training


### StrokeChange (object detection lite)
= colab to use Tensorflow Model Maker to train an EfficientDet D0 - LITE model (for mobile deployment) to DETECT eye and mouth regions AND severity: normalEye, strokeEyeWeak,strokeEyeMid,strokeEyeSevere, normalMouth,strokeMouthWeak,strokeMouthMid,strokeMouthSevere. Data used is located at drive folder https://drive.google.com/drive/folders/1dQkZb838D2vW4xHDHMKuiEPLnMg-gh2i?usp=share_link


### Image_REGRESSION (regression)
= colab to use Tensorflow to train an EfficientNet B0 to PERFORM REGRESSION on  Eye regions (sub-images) into range of 0.0 to 9.0 on regression severity value.  Note: part of the colab is to convert and save the Tensorflow lite model for use in deployment. Data used is located at drive folder https://drive.google.com/drive/u/0/folders/1HpfcaBs5UtV-aeFgRqNhvMmGkwyo8lPC


### Image_Classifier_with_Standard_TensorFlow (classifier)
= colab to use Tensorflow to train an EfficientNet B0 -  model  to PERFORM CLASSIFICATION on  Eye regions (sub-images) into classes: normalEye, strokeEyeWeak,strokeEyeMid,strokeEyeSevere. Note: part of the colab is to convert and save the Tensorflow lite model for use in deployment.    Data used is located at drive folder https://drive.google.com/drive/u/0/folders/12wiKdxR5jwhq5L9Mq0IVJD44YW1LuS3x


### Eye_Severity_ClassificationModelMaker (classifier lite)
= colab to use Tensorflow to train an EfficientNet B0 - LITE model (for mobile deployment) to PERFORM CLASSIFICATION on  Eye regions (sub-images) into classes: normalEye, strokeEyeWeak,strokeEyeMid,strokeEyeSevere.    Data used is located at drive folder https://drive.google.com/drive/u/0/folders/12wiKdxR5jwhq5L9Mq0IVJD44YW1LuS3x

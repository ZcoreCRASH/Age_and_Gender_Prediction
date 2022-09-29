# Age and Gender Prediction - Image Classification - CNN

The objective of the project is to detect gender and age using facial images. Convolutional Neural Network is used to classify the images. There are 2 output types namely, gender(M or F) and age.


## Dataset Information

The dataset chosen from kaggle, i.e. the UTKFace dataset is a large-scale face dataset with long age span (range from 0 to 116 years old). The dataset consists of over 23,000 face images with annotations of age, gender, and also ethnicity. I have ignored the ethnicitiy part of the image as it is out of the scope of the project. The images cover large variation in pose, facial expression, illumination, occlusion, resolution, etc. and they had to be standardized.


**Download link:** https://www.kaggle.com/datasets/jangedoo/utkface-new

**Environment:** Kaggle

## Libraries

- pandas
- numpy
- matplotlib
- seaborn
- os
- random
- keras
- tensorflow

## Neural Network

- Convolutional Neural Network
  
**Gender Accuracy:** 90%
**Age MAE:**  6.5 years
# Racist
Racist repository is to supplement the paper "Race bias of deep learning models in predicting criminals: Role of facial elements". This repository provides code used for experiments in the paper.

# Overview of our Experiments
<img src="https://user-images.githubusercontent.com/63252403/105454857-f1cd2c00-5cc5-11eb-93db-830c11eaf7a8.jpg"  width="1000" height="350">


- How it works
1. data_preprocessing file works for preprocessing stage. 
2. In train_test_split, we divide data into train, test set.
3. change_facial_features file transform facial elements for both black to white and white to black.
4. baseline_CNN, Facenet, VGGface train 3 models with preprocessed data. Also, test stage was processed in 3 files.


# Examples
Following are some results of facial elements changed.


- From black to white

<img src="https://user-images.githubusercontent.com/63252403/105443168-67c59900-5cae-11eb-9d33-80d6ff2f5ad3.jpg"  width="300" height="120">

- From white to black

<img src="https://user-images.githubusercontent.com/63252403/105443189-72802e00-5cae-11eb-893f-50dec9663b99.jpg"  width="300" height="120">



# Requirements
These are the requirements for changing facial elements
- opencv
- dlib
- PIL
- skin detection (https://github.com/cirbuk/skin-detection)

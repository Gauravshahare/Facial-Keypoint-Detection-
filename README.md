# Facial-Keypoint-Detection-
Solution to kaggle competition (https://www.kaggle.com/c/facial-keypoints-detection ) using Python 3 and Pytorch Library 

### Data Description

Data includes  1 * 98 * 98 images and there are 30 target lables we need to predict

![github_facial](https://user-images.githubusercontent.com/51395380/59057075-328ced00-88b7-11e9-8dc2-5b573d2d3fcd.PNG)

### Model Architecture

1) Multilayer perceptron model

    96 * 96 ==> 128 ==> 64 ==> 30
    
2) CNN Model
  1 * 96 * 96  ==> 16 * 96 * 96 ==> 16 * 48 * 48 ===> 32 * 48 * 48 ===>32 * 24 * 2 4 ===>64 *  12 * 12   ==>64 * 12 * 12 ===>1024 ===>30



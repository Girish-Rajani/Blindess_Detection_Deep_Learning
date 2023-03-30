# Blindess_Detection_Deep_Learning


Tasks:

Data Preprocessing:
1. Split the training folder into sub folders (class 0 - class 4) based on the class labels in train.csv
2. Split the training data into validation and training set 
To Do: 
3. The dimensions of the images range from 474 x 358 pixels to 3388 x 2588 pixels. To make all images equal in size, we resize the images  
4. Perform data augmentation to get the number of samples in each to be equally distributed (perform 90, 180, and 270 degree rotations on class 1, 3, and 4)

Models:
Need an optimizer along with appropriate loss function (Adams optimizer & categorical cross-entropy loss)
#1. Logistic Regression
2. Custom CNN's 
3. Transfer Learning:
3a. VGG16
3b. ResNet
3c. ImageNet
4. ET Classifier (Extra Trees Classifier - Ensemble Learning) from decision trees - Implemented in https://arxiv.org/ftp/arxiv/papers/2006/2006.07475.pdf


# Blindness_Detection_Deep_Learning


The goal of this project is to use algorithms in Machine Learning and Deep Learning, such as Convolutional Neural Networks to extract features from retina images to automate this process. This will be done by performing multi-class image classification using the APTOS 2019 Blindness Detection dataset. Machine learning models allow us to speed up the process of detecting DR early and make this service available to those who may not have access to the infrastructure.

Various models were made such as a custom CNN model, VGG-16 model, ResNet50 model, and an InceptionV3 model. After training and evaluating all models (with and without data augmentation), the test data was labelled using each model.

- The Blindness Detection.ipynb contains the code used to preprocess the retina images, perform train/val split, build and evaluate the various CNN models, and lastly label the testing dataset.

- The Blindness Detection Presentation.pptx contains the presentation which illustrates the process throughout this project

- The CS 584 Intermediate Project.pdf document is a prelinimary project report that explains in more detail what the project is about and the different approaches that would be implemented

- The test_labelled.csv is the final outcome of this project. It contains the predicted labels for each test sample using each of the eight models trained 

# shot_classifier

This repository focuses on implementing the research paper that explores the application of Convolutional Neural Networks (CNNs) in categorizing cricket batting shots, leveraging transfer learning techniques. By utilizing the Shot-Net dataset consisting of 4586 images, it aimed to classify four distinct batting strokes. Through rigorous experimentation, we identified the InceptionV3 network as the most effective model architecture, achieving an impressive 98.84% accuracy on the validation dataset.

# Inceptionv3

![image](https://github.com/Nelson-code/shot_classifier/assets/62516702/27b952e1-442d-4c87-916a-88842db7996b)

Inception V3 is a deep convolutional neural network (CNN) architecture developed by Google.Introduced as part of the Inception family of models, Inception V3 incorporates several innovative features, including inception modules that utilize various filter sizes within the same layer to capture diverse patterns and features at multiple scales. 

# Dataset

The dataset was extracted from Kaggle: https://www.kaggle.com/datasets/aneesh10/cricket-shot-dataset

It consists of 4586 image samples categorized into four distinct cricket batting shots. Additionally, the dataset includes augmented images, incorporating transformations such as flipping, rotation, scaling, shearing, and translation, enhancing its diversity and robustness. So it is suggested not to employ any additional augumentation on the given images.

Samples: 

![image](https://github.com/Nelson-code/shot_classifier/assets/62516702/4eab3604-1a43-44ec-83b2-a4debc349499)

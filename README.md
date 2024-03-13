# Quality Classification of Germinated Oil Palm Seeds based on CNN Models

This report outlines the process for classifying germinated oil palm seeds using two Convolutional Neural
Network (CNN) models and the dataset obtained from Applied Agricultural Resources (AAR) which was divided
into three batches. Our first model consists of five trainable layers, while the second model utilizes ResNet-50 for
transfer learning with all fully-connected layers unfrozen.We performed experiments to find the optimal combination of
hyperparameters, resulting in our model achieving an accuracy of 95.76% on batch 1 images. Our model outperformed
the transfer learning model, which achieved an accuracy of 86.78% on batch 1 images. However, both models exhibited
a significant bias towards training with batch 1 images. When tested on batch 2 and batch 3 images, both models showed
lower performance. To address this weakness, we augmented batch 1 images with images from batches 2 and 3 during
training. This improved the models’ accuracy in classifying the seeds in batches 2 and 3 during transfer learning.

This is a group project for COMP3029 at The University of Nottingham*

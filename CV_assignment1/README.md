# CV_assignment1

This repository contains my submissions for Assignment 1 of the Computer Vision course (CSE344/ CSE544/ ECE344/ ECE544) for the year 2024. The assignment involves theoretical questions and practical implementation of image classification and segmentation models.

Q2: q2_2021389_HW1.ipynb: 

Objective:
The task was to build and evaluate image classification models using a structured approach, from basic CNN architectures to sophisticated pre-trained models.

Contributions:
Building CNNs: Developed a convolutional neural network from scratch, tailored with specific layer configurations and activation functions, to classify images from the Russian Wildlife Dataset.
Model Training and Evaluation: Implemented training routines using cross-entropy loss and Adam optimizer, tracked via Weights & Biases, and analyzed model performance based on standard metrics like accuracy and F1-Score.
Fine-tuning Pre-trained Models: Leveraged a ResNet-18 model pre-trained on ImageNet, fine-tuned it for the same classification task, and analyzed the feature spaces using tSNE plots.
Data Augmentation: Applied several augmentation techniques to enhance model robustness and analyzed their effects on model performance.

Q3: q3_2021389_HW1.ipynb: 

Objective:
This part focused on applying deep learning models to the task of image segmentation, specifically using datasets designed to challenge model performance across varied and complex urban scenes.

Contributions:
Segmentation Model Implementation: Utilized a pre-trained DeepLabv3Plus model on the Indian Driving Dataset, adjusting the framework to fit the specific needs of the dataset.
Performance Evaluation: Conducted detailed performance evaluations of the segmentation model, calculating metrics like IoU, precision, and recall, and visualized these metrics to assess model effectiveness.
Visual Analysis: Provided visual comparisons of predicted and ground truth masks, identifying and discussing potential reasons for model failures.
Comparative Analysis: Extended the segmentation task to cross-dataset evaluation, comparing performance on Cityscapes and Indian Driving Datasets, and deriving insights from differences in model behavior across these datasets.

# CV_assignment1

This subdirectory contains my submissions for Assignment 1 of the Computer Vision course (CSE344/ CSE544/ ECE344/ ECE544) for the year 2024. The assignment involves theoretical questions and practical implementation of image classification and segmentation models.

Q1: q1_2021389_HW1.py

Objective:
This part focused on foundational theoretical concepts in computer vision and deep learning, covering loss functions, regularization, probability distributions, and numerical stability.

Contributions:

Loss Function Analysis: Compared Mean Squared Error (MSE) with Binary Cross-Entropy (BCE) for binary classification, deriving why BCE is better suited for such tasks.

BCE Loss Derivations: Computed the BCE formula, calculated example losses for given predictions, and extended to dataset-level averaged loss.

Regularization Insights: Derived the gradient descent update rule with L2 regularization and discussed its effect on weight magnitudes compared to models trained without regularization.

Softmax & Stability: Explained the properties of the softmax function, derived key gradients for classification tasks, and discussed numerical stability issues (log-sum-exp trick).

KL Divvergence and Cross-entropy: Derived the relation between KL Divergence and Cross-Entropy, based on the deep learning textbook by Ian Goodfellow.

Q2: q2_2021389_HW1.ipynb

Objective:
The task was to build and evaluate image classification models using a structured approach, from basic CNN architectures to sophisticated pre-trained models.

Contributions:

Building CNNs: Developed a convolutional neural network from scratch with custom layer configurations and activations to classify images from the Russian Wildlife Dataset.

Model Training & Evaluation: Implemented training routines with cross-entropy loss and Adam optimizer, tracked via Weights & Biases, and evaluated with metrics like accuracy and F1-score.

Fine-tuning Pre-trained Models: Leveraged a ResNet-18 pre-trained on ImageNet, fine-tuned it for the classification task, and analyzed feature spaces using t-SNE.

Data Augmentation: Applied multiple augmentation techniques to enhance robustness and compared their effects on performance.

Q3: q3_2021389_HW1.ipynb

Objective:
This part focused on image segmentation, applying deep learning models to urban scene datasets.

Contributions:

Segmentation Model Implementation: Used a pre-trained DeepLabv3Plus model on the Indian Driving Dataset, adapting it for dataset-specific requirements.

Performance Evaluation: Computed metrics including IoU, precision, and recall, and visualized results to assess model effectiveness.

Visual Analysis: Compared predicted and ground truth masks, analyzing failure cases.

Comparative Analysis: Performed cross-dataset evaluation (Cityscapes vs Indian Driving Dataset) and discussed differences in model behavior.

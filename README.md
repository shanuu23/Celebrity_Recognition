# Celebrity_Recognition

This project focuses on the classification of celebrities using machine learning models. The objective is to identify and recognize celebrities from images based on facial features.

# ML models Performance

Models Tested and Their Performance
Several traditional machine learning models were evaluated for this task:

Support Vector Machine (SVM): 62% accuracy

Logistic Regression: 61% accuracy

Random Forest: 30% accuracy

While SVM and Logistic Regression showed moderate performance, Random Forest underperformed significantly on this dataset, likely due to the high-dimensional nature of facial image data.

# DL model Performance

This project uses ResNet18, a deep convolutional neural network pretrained on ImageNet, as the backbone for the celebrity classification task. By fine-tuning the model on a curated dataset of cropped celebrity faces and applying appropriate preprocessing (including ImageNet-standard normalization), the model achieved a validation accuracy of 94%. The training process incorporated techniques such as early stopping and train/validation/test splitting to ensure generalization and robust performance on unseen data.


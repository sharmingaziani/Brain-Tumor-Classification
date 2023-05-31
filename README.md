# Brain-Tumor-Classification

[Link to data set](https://www.kaggle.com/datasets/sartajbhuvaji/brain-tumor-classification-mri?resource=download) found on kaggle.

## Key Features:
- Data augmentation: The project utilizes the Keras ImageDataGenerator to perform data augmentation
- Model architecture: The ResNet50 model is used as the backbone, with a Global Average Pooling layer and a Dense layer for classification.
- Training and evaluation: The model is compiled with the Adam optimizer and categorical cross-entropy loss. Training and evaluation are performed using the train and test data generators.
- Classification results: The project provides accuracy and loss metrics, as well as a summary of the model's architecture.

## Requirements:
- Python
- TensorFlow
- Keras
- Google Colab (for GPU acceleration)

This project serves as a starting point for building an image classification system for brain tumor images. It can be extended and modified for other medical image analysis tasks or different datasets. The code is provided as a Jupyter Notebook for easy execution and experimentation.




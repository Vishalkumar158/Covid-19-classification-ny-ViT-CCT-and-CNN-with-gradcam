# Covid-19-classification with ViT,CCT and CNN architeture with gradcam
This repository contains code and resources for detecting COVID-19 in chest X-ray images using three different models: [Vision Transformer (ViT)](https://paperswithcode.com/method/vision-transformer), [Convolutional Neural Network (CNN)](https://www.ibm.com/topics/convolutional-neural-networks), and [Convolutional Contrastive Transformer (CCT)](https://keras.io/examples/vision/cct/). The project aims to compare the performance of these models in COVID-19 detection and provide insights into their strengths and weaknesses.

## Dataset
The dataset used for training and evaluation consists of chest X-ray images of patients with COVID-19 and healthy individuals. The dataset is publicly available and is properly cited in the code. It is important to ensure that you have the necessary permissions and comply with the terms of use when using the dataset.

## Models
### 1. Vision Transformer (ViT)
The ViT model is a state-of-the-art image classification model based on the transformer architecture. It has shown remarkable performance in various computer vision tasks, including image classification. The ViT model is implemented using the TensorFlow library and achieve maximum accuracy of 84%.

### 2. Convolutional Neural Network (CNN)
The CNN model is a classic deep learning architecture widely used for image classification tasks. It consists of multiple convolutional layers, followed by pooling and fully connected layers. The CNN model in this project is implemented using the Keras framework and achieve maximum accuracy of 95%.

### 3. Convolutional Contrastive Transformer (CCT)
The CCT model is a recent advancement in computer vision that combines the transformer and contrastive learning techniques. It is designed to handle challenging image recognition tasks by leveraging both spatial and context information. The CCT model is implemented using Tensorflow and achieve maximum accuracy of 77%.

## Acknowledgments
The dataset used in this project is sourced from [SARS-COV-2 Ct-Scan Dataset](https://www.kaggle.com/datasets/plameneduardo/sarscov2-ctscan-dataset), [COVID-19_Radiography_Dataset](https://www.kaggle.com/datasets/tawsifurrahman/covid19-radiography-database). Please refer to their documentation for citation and usage guidelines.

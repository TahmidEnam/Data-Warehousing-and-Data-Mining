# Data-Warehousing-and-Data-Mining
MSC Course Final Project

# Project Title: Mosquito Species and Larvae Classification Using a Modified Deep Learning Framework with XAI

Submitted by-
Name: Tahmid Enam Shrestha
ID No: 25-93790-2

## Project Overview
This project involves applying Convolutional Neural Networks (CNN) to classify mosquito larvae and species. The model aims to assist in identifying mosquito species and larvae, which is important for controlling and preventing diseases caused by mosquitoes, such as malaria and dengue fever. The model leverages a modified CNN architecture for efficient and accurate classification.

## Abstract
Mosquito-borne infections, including Malaria, Dengue, and Zika virus, are substantial public health challenges worldwide. Early detection of mosquito species and larvae is essential for effective disease control and prevention. However, manual classification is labor-intensive and prone to error. Even though deep learning has advanced, existing automated classification models have suffered from poor performance, limited testing across diverse databases, and limited interpretability at high computational cost. This study presents a modified explainable deep learning model named modified MobileNet V2 with an Explainable Artificial Intelligence (XAI) approach, such as GradCam++, to enhance transparency in decision-making. The model is trained on two datasets: Dataset A, containing images of mosquito species (Culex, Anopheles, Aedes), and Dataset B, focused on mosquito larval images. Data augmentation, such as resizing, rotation, and normalization techniques, is used to improve model generalization. The proposed model is integrated with XAI methods to achieve high classification accuracy and transparency. The effectiveness of the model is evaluated by standard metrics of accuracy, precision, recall and F1-score as compared to other existing state-of-the-art methods. The proposed model achieved test accuracies of 99.56% on Dataset A and 82.95% on Dataset B. The proposed model seeks to increase the sensitivity and specificity of mosquito classification by providing transparent, interpretable insights to support better public health surveillance and to implement more efficient mosquito control measures.

## Methodology
The methodology consists of several stages:
1. **Data Collection and Preprocessing**: The dataset includes images of mosquito larvae and species. The images are preprocessed to normalize the data, resize images, and augment the dataset for better model generalization.

3. **Model Architecture**: A CNN architecture is defined and modified to best suit the classification problem. This model is trained on the preprocessed dataset to learn to differentiate between different species and larvae stages.
4. **Training**: The CNN model is trained using a training script, where we optimize the model with the Adam optimizer and monitor its performance using accuracy, precision, recall, and F1-score.
5. **Evaluation**: The model's performance is evaluated using a test set and visualized through confusion matrices and classification reports.

## Dataset
The dataset used for training and evaluation includes:
- **Mosquito Species Images**: A collection of images representing various species of mosquitoes.
- Dataset A Link: https://www.kaggle.com/datasets/masud1901/mosquito-dataset-for-classification-cnn
  
- **Mosquito Larvae Images**: Images of mosquito larvae at different developmental stages.
- Dataset B Link: https://www.kaggle.com/datasets/cyberthorn/mosquitolarvae-7400-classification

The dataset was preprocessed using image transformations such as resizing, normalization, and augmentation to enhance the model's ability to generalize.


## Installation

### Prerequisites
To run this project, you need to have Python 3.x installed on your system. The following Python libraries are required:

- `torch`
- `torchvision`
- `PIL`
- `matplotlib`
- `numpy`
- `seaborn`
- `sklearn`
- `timm`
- `scipy`

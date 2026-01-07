# Data-Warehousing-and-Data-Mining
MSC Course Final Project
# Modified CNN for Mosquito Larva and Species Classification

## Project Overview
This project involves applying Convolutional Neural Networks (CNN) to classify mosquito larvae and species. The model aims to assist in identifying mosquito species and larvae, which is important for controlling and preventing diseases caused by mosquitoes, such as malaria and dengue fever. The model leverages a modified CNN architecture for efficient and accurate classification.

## Methodology
The methodology consists of several stages:
1. **Data Collection and Preprocessing**: The dataset includes images of mosquito larvae and species. The images are preprocessed to normalize the data, resize images, and augment the dataset for better model generalization.
2. **Model Architecture**: A CNN architecture is defined and modified to best suit the classification problem. This model is trained on the preprocessed dataset to learn to differentiate between different species and larvae stages.
3. **Training**: The CNN model is trained using a training script, where we optimize the model with the Adam optimizer and monitor its performance using accuracy, precision, recall, and F1-score.
4. **Evaluation**: The model's performance is evaluated using a test set and visualized through confusion matrices and classification reports.

## Dataset
The dataset used for training and evaluation includes:
- **Mosquito Species Images**: A collection of images representing various species of mosquitoes.
- **Mosquito Larvae Images**: Images of mosquito larvae at different developmental stages.

The dataset was preprocessed using image transformations such as resizing, normalization, and augmentation to enhance the model's ability to generalize.

> **Note**: If the dataset is too large to be included directly in the repository, please provide a link to where it can be accessed or downloaded.

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

### Steps to Set Up
1. Clone this repository:
   ```bash
   git clone https://github.com/your_username/modified-cnn-mosquito.git

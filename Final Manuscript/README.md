# Mosquito Species and Larvae Classification Using a Modified Deep Learning Framework with XAI

## Project Overview
This project involves developing a modified deep learning model to classify mosquito species and larvae. By utilizing MobileNetV2 architecture with added Explainable AI (XAI) methods, specifically Grad-CAM++, this model achieves high classification accuracy and transparency. The project aims to improve mosquito classification accuracy and interpretability, which is crucial for effective mosquito control and public health surveillance.

## Key Contributions
- **Development of an Explainable Model**: A modified MobileNetV2 architecture integrated with Explainable AI techniques, such as Grad-CAM++, to ensure the interpretability of model predictions.
- **Evaluation Across Multiple Datasets**: The model is tested on two distinct datasets—one for mosquito species (Culex, Anopheles, Aedes) and one for mosquito larvae, providing a broader classification capability.
- **Performance Metrics**: The model is evaluated using standard metrics including accuracy, precision, recall, and F1-score, and compared to other state-of-the-art methods.

## Methodology
The model's backbone architecture is **MobileNetV2**, a lightweight deep learning model optimized for mobile and embedded systems. For classification, a custom fully connected classifier is used after extracting features with MobileNetV2. The model is trained using image data augmentation techniques such as resizing, rotation, Gaussian blur, and color jitter to improve its generalization capability.

The **Grad-CAM++** technique is used to visualize and interpret the areas of images that contribute most to classification decisions, providing transparency in the model's predictions.

### Datasets:
- **Dataset A (Mosquito Species)**: Contains 3000 images of mosquito species (Culex, Anopheles, Aedes).
- **Dataset B (Mosquito Larvae)**: Contains 7463 images of mosquito larvae from four categories (AB, AG, AN, CQ).

### Performance:
- **Dataset A (Mosquito Species)**: Test accuracy of 99.56%
- **Dataset B (Mosquito Larvae)**: Test accuracy of 82.95%

## Results
The model achieves remarkable performance:
- **Dataset A** (Mosquito Species): Training accuracy of 99.67%, testing accuracy of 99.56%
- **Dataset B** (Mosquito Larvae): Training accuracy of 83.16%, testing accuracy of 82.95%

The **Grad-CAM++** visualizations (available in the repository) show how the model focuses on important features, such as the wings and body segments, for species and larvae classification.

## Installation

### Prerequisites
To run this project, Python 3.x is required along with the following dependencies:
- `torch`
- `torchvision`
- `PIL`
- `matplotlib`
- `numpy`
- `seaborn`
- `sklearn`
- `timm`

Install the necessary libraries using:
```bash
pip install -r requirements.txt


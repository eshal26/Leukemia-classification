# Leukemia Classification using Deep Learning Models

This repository contains Python code for leukemia classification using various deep learning models. Leukemia classification is a critical task in medical image analysis, and deep learning models have shown promising results in automating this process.

## Table of Contents

- [Introduction](#introduction)
- [Models Implemented](#models-implemented)
- [Dataset](#dataset)
- [Results](#results)
- [Contributing](#contributing)


## Introduction

Leukemia is a type of cancer that affects the blood and bone marrow. Early and accurate classification of leukemia cells from microscopic images is crucial for effective treatment planning and patient management. This repository explores different deep learning models to automate the classification process, leveraging their ability to learn discriminative features from image data.

## Models Implemented

The following deep learning models have been implemented and evaluated for leukemia classification:

- **AlexNet**: A pioneering deep convolutional neural network architecture.
- **ResNet**: Known for its depth and use of residual connections, facilitating training of very deep networks.
- **GoogleNet (Inception)**: Notable for its inception modules that allow for efficient use of computational resources.
- **VGG**: Characterized by its uniform architecture with very small (3x3) convolution filters.

## Dataset
This dataset is divided into two classes benign and malignant. The malignant class consists of 3 categories early, pre, pro.

 https://www.kaggle.com/datasets/mehradaria/leukemia

## Results

| Model      | Test Loss | Test Accuracy | Test Precision | Test Recall | Test F1-score | Confusion Matrix         |
|------------|------------|---------------|----------------|-------------|---------------|--------------------------|
| **AlexNet**  | 0.0888     | 0.9786        | 0.9794         | 0.9786      | 0.9788        | `[[ 49   2] [  5 271]]`  |
| **GoogLeNet**| 0.0984     | 0.9725        | 0.9721         | 0.9725      | 0.9721        | `[[ 45   6] [  3 273]]`  |
| **ResNet50** | 0.0234     | 0.9908        | 0.9909         | 0.9908      | 0.9907        | `[[ 48   3] [  0 276]]`  |
| **VGG16**    | 0.0008     | 1.0000        | 1.0000         | 1.0000      | 1.0000        | `[[ 51   0] [  0 276]]`  |
| **VGG19**    | 0.0034     | 1.0000        | 1.0000         | 1.0000      | 1.0000        | `[[ 51   0] [  0 276]]`  |

## ROC and PR Curve
![image](https://github.com/eshal26/Leukemia-classification/assets/124394813/f5bfb9c2-c68a-45b5-83b8-592c9252b218)

## Conclusion

- **VGG16 and VGG19** performed the best overall, with perfect accuracy, precision, recall, and F1-scores, as well as no misclassifications.
- **ResNet50** also performed very well but with a slight edge to VGG models.
- **AlexNet and GoogLeNet** performed decently but with more errors compared to the other models.

Given these metrics, VGG16 and VGG19 are the top performers, with ResNet50 as a strong contender.


## Contributing
Contributions to improve the repository, add new models, or enhance documentation are welcome. 


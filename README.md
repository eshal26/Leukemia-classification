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

We evaluated four different deep learning models: AlexNet, ResNet-50, GoogLeNet, and VGG16 on our dataset. The performance metrics for each model are as follows:

### Test Metrics

| Model     | Accuracy | Precision | Recall  | F1-score |
|-----------|----------|-----------|---------|----------|
| **AlexNet**   | 0.9847   | 0.9892    | 0.9928  | 0.9910   |
| **ResNet-50** | 0.9939   | 0.9941    | 0.9939  | 0.9939   |
| **GoogLeNet** | 0.9817   | 0.9927    | 0.9855  | 0.9891   |
| **VGG16**     | 0.9969   | 0.9982    | 0.9902  | 0.9941   |

## Conclusion

Based on the test metrics, VGG16 performed the best with the highest accuracy and precision. ResNet-50 also showed excellent performance, closely following VGG16. AlexNet and GoogLeNet, while still performing well, lagged behind the other two models in some metrics.

For further details, refer to the code and data in this repository.


## Contributing
Contributions to improve the repository, add new models, or enhance documentation are welcome. 


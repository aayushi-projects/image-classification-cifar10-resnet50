# CIFAR-10 Object Recognition using ResNet50
Dataset link: https://www.kaggle.com/datasets/tanlikesmath/the-oxfordiiit-pet-dataset

This project focuses on building an image classification model using the CIFAR-10 dataset and the ResNet50 architecture. The CIFAR-10 dataset contains 60,000 32×32 color images in 10 different classes, with 6,000 images per class.

Since ResNet50 is designed for larger images (typically 224×224), all images in the dataset are resized accordingly before being passed to the model. I used transfer learning, loading a pre-trained ResNet50 model (trained on ImageNet) and then fine-tuned it for CIFAR-10 classification.

## Model Architecture
(i) Base Model: ResNet50 (pre-trained on ImageNet)

(ii) Input Size: 224 × 224 × 3 (resized from 32 × 32)

(iii) Training Strategy:

Feature extraction using the convolutional base

Global Average Pooling

Fully connected Dense layers for classification (10 output classes)

## Libraries & Tools Used
(i) Python 3.x

(ii) TensorFlow / Keras

(iii) NumPy, Matplotlib

## Evaluation
(i) The model was evaluated using accuracy on both training and test data.

(ii) Results may vary slightly depending on training epochs, learning rate, and data augmentation techniques.

(iii) ResNet50 gave a significant improvement over traditional CNNs on this task.


# CIFAR-10 Object Recognition using ResNet50
This project focuses on building an image classification model using the CIFAR-10 dataset and the ResNet50 architecture. The CIFAR-10 dataset contains 60,000 32×32 color images in 10 different classes, with 6,000 images per class.

Since ResNet50 is designed for larger images (typically 224×224), all images in the dataset are resized accordingly before being passed to the model. I used transfer learning, loading a pre-trained ResNet50 model (trained on ImageNet) and then fine-tuned it for CIFAR-10 classification.

This project was inspired by the section at 4:20:18 in the video "Deep Learning Full Course – Learn Deep Learning in 6 Hours" on YouTube.


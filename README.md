# U-Net for image segmentation

This repository contains an implementation of the U-Net architecture for image segmentation from scratch using PyTorch. U-Net is a convolutional neural network architecture for fast and precise segmentation of images, especially in the field of biomedical image analysis. The implementation is based on the original U-Net paper [1] with the dataset used for training and testing from Kaggle [2].

![image](https://user-images.githubusercontent.com/78913240/231573416-5d0007e0-6edf-4d39-8d75-39bd9366e9d1.png)
![image](https://user-images.githubusercontent.com/78913240/231573472-242d2465-cf72-4dbc-9a72-00d2b1d7c650.png)

## Requirements
- Python 3.6+
- PyTorch 1.7.0+
- torchvision 0.8.1+
- numpy 1.19.2+
- matplotlib 3.3.2+
- tqdm 4.50.2+
- scikit-learn 0.23.2+
- pillow 8.0.1+

## Results
The model achieved an F1 score of more than 0.9 on the test set.

## References
[1] Olaf Ronneberger, Philipp Fischer, and Thomas Brox. "U-Net: Convolutional Networks for Biomedical Image Segmentation." 2015.
[2] Fetal Head UltraSound Dataset For Image Segment, Kaggle. [Link](https://www.kaggle.com/datasets/ankit8467/fetal-head-ultrasound-dataset-for-image-segment)

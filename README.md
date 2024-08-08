# Fetal Head Segmentation in Ultrasound Images via Deep Learning and Classical Methods

## Overview

This project is a part of the Digital Image Processing Graduate Course at the Electrical Engineering Department of Sharif University of Technology. The primary objective is to segment the fetal head in ultrasound images using deep learning models, specifically U-Net and VGG-16, and compare these methods with classical segmentation techniques.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Methods](#methods)
  - [U-Net Architecture](#u-net-architecture)
  - [VGG-16 Architecture](#vgg-16-architecture)
  - [Classical Methods](#classical-methods)
- [Results](#results)
- [Conclusion](#conclusion)
- [Files](#files)
- [References](#references)

## Introduction

Fetal head segmentation in ultrasound images is a critical task for estimating biometric measurements in prenatal care. This project aims to leverage deep learning models to achieve accurate segmentation results and compare the performance with traditional image processing techniques.

## Dataset

The HC18 dataset is used in this project. It contains annotated ultrasound images of fetal heads, which serve as ground truth for training and evaluation.

## Methods

### U-Net Architecture

The U-Net model is a convolutional neural network designed for biomedical image segmentation. It consists of an encoder-decoder structure with skip connections, which helps in preserving spatial information during the upsampling process.

![U-Net Architecture](u-net-architecture.png)

### VGG-16 Architecture


![VGG-16 Architecture](vgg16.png)

### Classical Methods

Classical image processing techniques, including thresholding, edge detection, and morphological operations, are implemented to provide a baseline for comparison with deep learning approaches.

## Results

The performance of the segmentation models is evaluated using metrics such as Dice coefficient, Intersection over Union (IoU), and pixel accuracy. The results are compared to highlight the strengths and weaknesses of each method.

## Conclusion

This project demonstrates the effectiveness of deep learning models, particularly U-Net and VGG-16, in segmenting fetal heads in ultrasound images. The comparison with classical methods provides insight into the advancements brought by deep learning in medical image processing.

## Files

- `ProjectReport-98107077-SajjadHashembeiki.pdf`: Detailed project report.
- `Segmentation_Based_vs_Regression_Based_Biomarker_Estimation_A_Case.pdf`: Related paper discussing segmentation-based and regression-based biomarker estimation.
- `u-net-architecture.png`: Image of the U-Net architecture used in the project.
- `vgg16.png`: Image of the VGG-16 architecture used in the project.

## References

- Ronneberger, O., Fischer, P., & Brox, T. (2015). U-Net: Convolutional Networks for Biomedical Image Segmentation. arXiv preprint arXiv:1505.04597.

For more details, please refer to the provided project report and related paper.

---

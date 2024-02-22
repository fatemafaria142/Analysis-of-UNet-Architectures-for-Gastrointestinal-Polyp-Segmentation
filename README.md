# GastroSegNet: A Comparative Study of UNet Variants for Accurate Gastrointestinal Polyp Segmentation

This project focuses on comparing different variants of the UNet architecture for segmenting gastrointestinal polyps. The project utilizes the [Kvasir-SEG dataset](https://huggingface.co/datasets/kowndinya23/Kvasir-SEG).

## Overview

Gastrointestinal polyps pose a significant health risk, and accurate segmentation plays a vital role in their diagnosis. This repository compares the performance of two main UNet variants, namely Unet++ and Attention UNet, with different backends.

### UNet Variants Utilized

1. **Unet++:**
    - Backends Used:
        - DenseNet121
        - DenseNet169
        - DenseNet201

2. **Attention UNet:**
    - Backends Used:
        - DenseNet121
        - VGG19

## Results

### Evaluation of Segmentation Result

The evaluation metrics for the segmentation results obtained from the experiments conducted on the Kvasir-SEG dataset are as follows:

1. **Mean Intersection over Union (IoU):**
   - This metric measures the ratio of the intersection to the union of the predicted and ground truth masks.

2. **Mean Dice Coefficient:** 
   - The Dice coefficient calculates the similarity between two samples and is used here to assess the segmentation accuracy.

3. **Mean Pixel Accuracy:** 
   - Pixel accuracy indicates the percentage of correctly predicted pixels compared to the total number of pixels.

4. **Mean Modified Hausdorff Distance:** 
   - Modified Hausdorff distance evaluates the dissimilarity between two point sets and is applied here to quantify segmentation performance.

5. **Mean Surface Dice Overlap:** 
   - Surface Dice overlap measures the agreement between predicted and ground truth surfaces, providing insight into the quality of surface segmentation.

These metrics collectively assess various aspects of the segmentation quality and accuracy, providing a comprehensive evaluation of the UNet variants' performance on the Kvasir-SEG dataset.

### Usage

1. Obtain the Kvasir-SEG dataset from [here](https://huggingface.co/datasets/kowndinya23/Kvasir-SEG).




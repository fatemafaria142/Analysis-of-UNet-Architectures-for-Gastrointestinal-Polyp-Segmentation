# Comparative Analysis of Variants of UNet Architectures for Gastrointestinal Polyp Segmentation

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

- **Mean Intersection over Union (IoU):** `mean_IoU`
- **Mean Dice Coefficient:** `mean_dice_coefficient`
- **Mean Pixel Accuracy:** `mean_pixel_accuracy`
- **Mean Modified Hausdorff Distance:** `mean_modified_hausdorff_distance`
- **Mean Surface Dice Overlap:** `mean_surface_dice_overlap`

### Usage

1. Obtain the Kvasir-SEG dataset from [here](https://huggingface.co/datasets/kowndinya23/Kvasir-SEG).




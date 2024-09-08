## Project Overview

This repository contains the code I contributed to the larger project. The documentation file provides a detailed plan and step-by-step code execution of the entire project.

### Repository Structure

The code in this repository is divided into two primary files:

1. **Jupyter Notebook**:
    - This file contains the code for training and testing the **DeepLabV3 ResNet101** model.
    - The code is a modified version of the [DeepLabV3+ ResNet101 for segmentation](https://www.kaggle.com/code/balraj98/deeplabv3-resnet101-for-segmentation-pytorch#Training-DeepLabV3+-with-Pretrained-ResNet101-Encoder) from Kaggle.
    - Major modifications and customizations have been made to suit the project's specific requirements.

2. **Original Python Script**:
    - This file contains my 100% original code.
    - It takes the segmented image from the model and:
        - **Calculates the area** and
        - **Generates a WKT polygon** from the centroid coordinates of the segmented image.
    - The code automatically saves the calculated areas and polygon coordinates in a **GeoJSON** file.

### Key Highlights
- **DeepLabV3+**: A state-of-the-art image segmentation model was used with the **ResNet101** encoder, pre-trained on ImageNet, and fine-tuned for this project.
- **GeoJSON Automation**: My code efficiently handles post-segmentation image analysis by converting image regions into polygons and saving them in GeoJSON format, making them ready for further geospatial analysis.




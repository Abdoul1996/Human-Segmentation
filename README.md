# Human-Segmentation

# General Architecture of ML 


## 1. Business Understanding

### Business Problem
We need to extract humans from images using computer vision. The dataset contains input images and their corresponding segmentation masks, where each mask highlights the human regions in the image.

### Objective
Build an application that can predict a human mask from an input image.

### Proposed Solution
There are two main strategies to build the segmentation model:
1. Build a model from scratch
2. Use transfer learning with pre-trained segmentation architectures

### Key Takeaways from This Project
1. In-depth understanding of image segmentation
2. Deep dive into U-Net architecture
3. Custom data preprocessing and loading using PyTorch
4. Deploying the model via a Flask web application
5. Dockerizing the application for portability
6. Storing Docker images using Amazon Elastic Container Registry (ECR)
7. Using GitHub Actions for CI/CD deployment
8. Deploying the application on an AWS EC2 instance

## 2. Data Understanding: 

Images: This is the original image you feed into the model.
Ground-Thruth(label): The ground truth is what we know the correct result should be.
mask: per-pixel label: It's like labeled image (segmentation map) 

Dataset Link: https://www.kaggle.com/code/nikhil1e9/image-segmentation-with-pytorch





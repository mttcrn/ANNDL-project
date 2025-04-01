# Kaggle challenges - Artificial Neural Networks and Deep Learning
This repository contains projects developed for the Artificial Neural Networks and Deep Learning course at Politecnico di Milano during the academic year 2024-2025.

The repository is organized into two main challenges:

## Challenge 1: Image Classification
- Objective: Classify images of red blood cells into different categories based on their morphology.
- Approach: Implemented **transfer learning** with **DenseNet161**, **fine-tuning** the model to optimize classification accuracy.
- Challenges: Dealing with **class imbalance**, enhancing feature extraction, and optimizing generalization.
- Results: Achieved a high classification accuracy using data augmentation, **SMOTE** for dataset balancing, and fine-tuning selected layers.

## Challenge 2: Image Segmentation
- Objective: Classify Mars surface images into distinct terrain categories.
- Approach: Implemented **U-Net** with custom architectural modifications (SE blocks, **attention mechanisms**).
- Challenges: No pre-trained models allowed, requiring training from scratch.
- Results: Achieved competitive segmentation accuracy, optimizing performance through **data augmentation** and **loss function tuning**.

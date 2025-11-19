# Predicting Cardiovascular Disease Risk Using Spark-Based Classification
This project explores the use of distributed deep learning with Apache Spark to classify flower images using Convolutional Neural Networks (CNNs). Image classification is a core task in computer vision, and CNNs are well-suited for learning hierarchical features directly from raw image data. By integrating Spark into this workflow, the project demonstrates how distributed computing can accelerate large-scale image preprocessing and model training across multiple virtual machines

I am using the publicly available Kaggle Dataset [Flowers Recognition]([url](https://www.kaggle.com/datasets/alxmamaev/flowers-recognition?select=flowers)), which contains thousands of images across five categories: daisy, dandelion, rose, sunflower, and tulip. The project highlights the integration of Spark with deep learning libraries to handle big image data efficiently, while also serving as a stepping stone toward my final project on pneumonia detection from X-ray images.

# Overview
I think that flower classification is a good starter problem for computer vision. By applying Spark-based distributed preprocessing and PyTorch CNN training, this project shows how scalable infrastructure can reduce training time and improve reproducibility. Running Spark across one master node and one worker node demonstrates the benefits of parallel computation for image-heavy tasks.

Ultimately, the goal is to show how Spark-based CNNs can be applied to real-world image classification problems, while preparing the foundation for more complex medical imaging tasks.

# Key Features
## Data Preprocessing
### preprocess.py script
- Extracts image file paths and labels from the Flowers Recognition dataset.
- Creates a Spark DataFrame with shuffled samples.
- Splits into train/test CSVs for fine-tuning.

## Model Approaches
### train_cnn.py script
- Uses a simple CNN with two convolutional layers and fully connected classifier.
- Trains on resized and normalized images (128x128).
- Evaluates accuracy on a held-out test set.
- Saves trained model as flower_cnn.pth.

# Results

# Distributed Cluster Setup
To handle the dataset’s scale, the project was deployed on two virtual machines (VMs):
- 1 Master Node and 1 Worker Node

# Dataset
I found a dataset on Kaggle with 4242 images of flowers. It contains 5 classes of flowers including: daisy, dandelion, rose, sunflower, and tulip

Source: [Flower Recognition]([url](https://www.kaggle.com/datasets/alxmamaev/flowers-recognition?select=flowers))

Reference: Kaggle. (2021). Flower Recognition Dataset [Dataset]. Retrieved from https://www.kaggle.com/datasets/alxmamaev/flowers-recognition?select=flowers. 

# Methods Summary
## Preprocessing

## Modeling

# How to Run Project
## Prereqs
- Python 3.x
- Apache Spark installed on all VMs
- PySpark, NumPy, Pandas

# Team Members
- Olivia Gette

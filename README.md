Food Image Classification Project using Deep Learning

This project was developed as part of a student assignment for my deep learning module from 2022. The goal was to build an image classification model capable of recognizing 10 different types of food. Wow, I used to be horrible at writing reports.

Overview

 The dataset used consists of 101,000 images (from Kaggle), covering 101 food categories. Each student was assigned a subset of 10 food types to classify using two distinct approaches:

    A custom CNN model built from scratch with Conv2D and Dense layers.

    A transfer learning model leveraging pre-trained architectures.

The goal was to follow the universal machine learning workflow—data preprocessing, model training, hyperparameter tuning, and evaluation—to determine the best-performing model for the task.
Dataset & Preprocessing
Data Source

    The dataset was downloaded from Kaggle (link if available).

    Contains 101,000 images across 101 food categories.

    A 20.txt file specified the 10 food types assigned for this project.

Preprocessing Steps

    Directory Setup:

        Images were extracted into a local folder.

        Three directories were created:

            train/ (7,500 images per class)

            validation/ (2,000 images per class)

            test/ (500 images per class).

    Data Loading:

        Used a provided Jupyter notebook (Image_Preprocessing.ipynb) to:

            Read the 20.txt file to identify the 10 target food classes.

            Split images into train/validation/test sets by filename ranges.

        Images were copied into their respective directories for model training.

    Model Input Pipeline:

        Data loaded into the model notebook using base_dir paths.

        Augmentation (if applied) would be noted here (e.g., resizing, normalization).

Model Development

(Note: Expand this section based on your full report!)

    Custom CNN: Built with Conv2D, pooling, and Dense layers.

    Pre-trained Model: Fine-tuned a model like VGG16 or ResNet.

    Evaluation: Tested on held-out images and external downloads.

Hardware & Tools

    GPU: NVIDIA GeForce GTX 1060 (6GB)

    CPU: Intel Core i3-8100 @ 3.60GHz

    Software: Jupyter Notebook, TensorFlow/Keras.


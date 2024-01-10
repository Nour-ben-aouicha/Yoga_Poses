# 🧘‍♀️ Yoga Pose Prediction Project 🧘‍♂️

## Project Overview
In this project, we leveraged the Yoga Poses dataset from Kaggle to develop and compare two distinct models, evaluating their effectiveness in predicting Yoga poses.

## Data Preparation
For data preparation, we loaded and resized images, organized datasets into DataFrames, and implemented PyTorch's `transforms` for data augmentation. These steps aimed to create a well-structured dataset, crucial for training robust Yoga pose prediction models.

## Models and Methods Used
Two models were employed for training:
1. **Model 1: Convolutional Neural Network (CNN)**
   - Architecture: Conv2D layers, Batch Normalization, MaxPooling2D, Dense layers with ReLU activation, Dropout, and Softmax output.
   - Training: Compiled with Adam optimizer, categorical crossentropy loss, and trained for 10 epochs.

2. **Model 2: EfficientNetB0**
   - Architecture: Utilized EfficientNetB0 architecture with GlobalAveragePooling2D and Dense output layer.
   - Training: Compiled with Adam optimizer, categorical crossentropy loss, and trained for 15 epochs.

## Results and Artifacts
At the project's conclusion, you will find detailed results of the prediction task, along with essential artifacts such as model architecture weights and summaries.

## Dataset Link
Here is the link to access the Yoga Poses dataset: [Yoga Poses Dataset](https://www.kaggle.com/datasets/niharika41298/yoga-poses-dataset)

Feel free to explore the project, dive into the results, and examine the provided model insights! 🧘‍♂️✨

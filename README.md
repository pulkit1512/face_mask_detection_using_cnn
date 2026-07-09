# Face Mask Detection using VGG16 and Transfer Learning

This project is a binary image classification system that detects whether a person is wearing a face mask or not. It was built with **VGG16**, **transfer learning**, and **OpenCV** for image preprocessing.

## Project Overview

The model classifies input images into two categories:

- `with_mask`
- `without_mask`

The dataset is organized into train, validation, and test folders, and the trained model is saved as `mask_model.keras`.

## Model Used

The core model is **VGG16**, a popular convolutional neural network that was originally trained on ImageNet.

Instead of training a deep network from scratch, this project uses **transfer learning**:

1. Load the pretrained VGG16 backbone.
2. Reuse the learned visual features from earlier layers.
3. Freeze the base layers so they do not change during initial training.
4. Add a custom classification head for mask detection.
5. Train the final layers on the face mask dataset.

This approach gives better results with less training time and fewer images than building a model from zero.

## Role of OpenCV

**OpenCV** is used for image handling and preprocessing. In this project it helps with:

- Reading images from disk
- Resizing images to `224 x 224`
- Preparing image data before it is passed to the model

## Why This Project Matters

Face mask detection is useful in situations where quick public-health screening is needed. In a future pandemic or similar outbreak, such a system could help:

- Monitor mask compliance in public places
- Support hospitals, clinics, airports, schools, and offices
- Reduce manual checking effort
- Enable faster automated screening at entrances

## Workflow

1. Load images from the organized dataset
2. Preprocess images with OpenCV
3. Feed images into the VGG16-based transfer learning model
4. Predict whether the person is wearing a mask
5. Save and evaluate the trained model

## Files in the Project

- `ai.ipynb` - notebook used for training and experimentation
- `mask_model.keras` - saved trained model
- `organized_dataset/` - train, validation, and test data
- `model_evaluation_results/` - evaluation metrics

## Future Improvements

- Real-time webcam-based detection
- Face detection before classification
- Better performance on crowded scenes
- Deployment in a web or mobile application
# face_mask_detection_using_cnn

# AI Image Classifier

An end to end AI powered image classification web application that identifies objects in images using a pretrained deep learning model and displays the top predictions with confidence scores.

This project demonstrates how to deploy a computer vision model into an interactive application using Streamlit, without training a model from scratch.

## What does this project do?

This project allows users to:

- Upload an image in JPG or PNG format
- Analyze the image using artificial intelligence
- View the top three predicted objects in the image
- See confidence scores for each prediction


## How does this project work?

### Step by step flow

- The user uploads an image through the Streamlit interface
- The image is resized and preprocessed to match model requirements
- A pretrained MobileNetV2 deep learning model performs inference
- The model outputs probabilities for object classes
- The top three predictions are decoded into readable labels
- Results are displayed along with confidence percentages

This project uses transfer learning, meaning the model is already trained on a large dataset and is only used for prediction.

## Technologies used

- Python
- Streamlit for building the web application
- TensorFlow and Keras for model loading and inference
- MobileNetV2 pretrained convolutional neural network
- OpenCV for image resizing and preprocessing
- NumPy for numerical operations
- Pillow (PIL) for image handling

## Model details

- Model name: MobileNetV2
- Training dataset: ImageNet
- Number of classes: 1,000
- Input size: 224 x 224
- Output: Top three predictions with confidence scores

MobileNetV2 is optimized for speed and efficiency, making it suitable for real time applications.

## How to use the application

- Launch the Streamlit app
- Upload an image
- Click on Classify Image
- View predicted labels and confidence scores

## Why this project matters

This project demonstrates:

- Practical application of deep learning models
- Image preprocessing and inference pipelines
- Deployment of machine learning models into user facing applications
- End to end AI project implementation

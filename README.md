
# Emotion Detection Using CNN and FER-2013 Dataset

## Overview
This project implements emotion detection using convolutional neural networks (CNN) on the FER-2013 dataset. The main focus is to classify facial expressions into seven emotion categories, improving model robustness and addressing class imbalance issues.

## Dataset
**FER-2013**: The FER-2013 dataset consists of 35,887 grayscale images of 48x48 pixels, each labeled with one of seven emotion categories:
- Angry
- Disgust
- Fear
- Happy
- Sad
- Surprise
- Neutral

## Technologies Used
- **Python**
- **TensorFlow**
- **Keras**
- **ResNet50v2**
- **VGG16**
- **OpenCV**
- **Gradio**

## Key Features
- **Class Imbalance Handling**: Addressed class imbalance in the FER-2013 dataset using image augmentation and class weights, ensuring better model performance across underrepresented emotions.
- **Model Architectures**: Custom CNN models were designed and iterated upon, including advanced architectures like VGG16 and ResNet50v2, to optimize accuracy.
- **Emotion Classification**: Achieved 66% overall accuracy on emotion classification with the final model based on ResNet50v2. Results were detailed with precision, recall, and F1-scores across seven emotion labels.

## Results
- **Accuracy**: 66% overall accuracy
- **Evaluation Metrics**: Precision, recall, and F1-scores were computed for each of the seven emotion categories to assess the model’s performance.


# Hand Gesture Recognition Model

## Introduction

This project demonstrates the development of a hand gesture recognition model that accurately identifies and classifies different hand gestures from image data. The model enables intuitive human-computer interaction and gesture-based control systems.

## Dataset

The dataset used for this project is the LeapGestRecog dataset from Kaggle, which consists of images of different hand gestures. The dataset is stored in a zip file (`archive.zip`) on Google Drive and is extracted during execution.

## Requirements

- Python 3.x
- NumPy
- Pandas
- OpenCV
- Keras
- TensorFlow
- Matplotlib
- Seaborn
- Scikit-learn


## Data Preparation

The dataset is extracted from the zip file and preprocessed to resize and normalize the images. A DataFrame is created to store image paths and their corresponding labels. The dataset is then split into training and testing sets.


## Model Training

The model is built using Keras with TensorFlow as the backend. It consists of convolutional layers for feature extraction and dense layers for classification. The model is trained using the training set, and data augmentation is applied to improve generalization.


## Evaluation and Testing

The model's performance is evaluated on the test set, and the accuracy is reported. Additionally, a function is provided to classify random images from the test set and display the predicted gestures.


## Results

The model achieves a certain level of accuracy on the test set, demonstrating its ability to classify hand gestures accurately. The results can be visualized by randomly classifying images from the test set.


## Conclusion

This project successfully demonstrates the development and training of a hand gesture recognition model using convolutional neural networks. The model can classify various hand gestures, making it suitable for applications in human-computer interaction and gesture-based control systems.

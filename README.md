# CNN Image Classification Project

This repository contains the CNN Image Classification Project created using Google Colab.

## Project Goal
The goal of this project is to classify images from the CIFAR-10 dataset using a Convolutional Neural Network (CNN).

## Steps Taken
1. **Import Libraries:**
   - Installed and imported necessary libraries such as TensorFlow and Keras.

2. **Load and Preprocess Data:**
   - Loaded CIFAR-10 dataset.
   - Preprocessed the data by normalizing pixel values.

3. **Build CNN Model:**
   - Constructed a CNN model using Keras with layers including Conv2D, MaxPooling2D, Flatten, Dense, and Dropout.

4. **Compile Model:**
   - Compiled the model with an Adam optimizer and sparse categorical cross-entropy loss function.

5. **Train Model:**
   - Trained the model on the training dataset for 20 epochs.
   - Plotted training and validation accuracy and loss.

6. **Evaluate Model:**
   - Evaluated the model's performance on the test dataset.
   - Visualized the results with accuracy and loss plots.

## Results
The model achieved an accuracy of X% on the test dataset with a loss of Y.

## Conclusion
This project demonstrates the use of CNNs for image classification tasks. The model shows satisfactory performance and can be further improved with hyperparameter tuning and additional data augmentation techniques.

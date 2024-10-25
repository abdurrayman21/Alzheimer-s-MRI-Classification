# Alzheimer-s-MRI-Classification
A deep learning project for classifying Alzheimer’s stages using MRI scans, implementing a Convolutional Neural Network (CNN) for multi-class classification
# Features
Image Preprocessing: Rescaling and normalization of MRI images.
CNN Architecture: Multiple convolutional layers with dropout for robust feature extraction.
Callbacks: EarlyStopping and ModelCheckpoint to optimize training and avoid overfitting.
# Setup
Install Dependencies: pip install -r requirements.txt
Imports: Ensure essential libraries like tensorflow and keras are installed.
# Data
The dataset consists of MRI scans categorized by Alzheimer’s stages.
Data Loading and Exploration sections in the code provide insights and initial visualizations.
# Model Overview
The CNN model includes:

Convolutional layers with ReLU activation.
MaxPooling and Dropout layers to enhance feature extraction and reduce overfitting.
Dense layers for final classification across four Alzheimer’s categories.
# Training
To train the model: model.fit(train_data, epochs=50, validation_data=val_data, callbacks=[early_stopping, model_checkpoint])
# Evaluation
Evaluate the model on the test set: model.evaluate(test_data)
# Results
The final model accuracy and loss are tracked, with checkpoints saved for optimal performance.
# License
This project is licensed under the MIT License.

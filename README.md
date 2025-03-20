# Deep_Learning_Assignments
This repository contains a deep learning assignment utilizing PyTorch, TensorFlow, and Keras. The notebook demonstrates practical applications of machine learning techniques in audio processing, feature extraction, and model training.

📌 Overview
Uses pandas for data handling.
Utilizes librosa for MFCC (Mel-Frequency Cepstral Coefficients) feature extraction from audio files.
Applies scikit-learn for data preprocessing, model training, and evaluation.
Implements a Gradient Boosting Classifier for animal sound classification (Bird, Cat, Dog).

📂 Dataset
The dataset consists of .wav audio files categorized into three classes:
Bird
Cat
Dog
MFCC features are extracted from the audio signals to serve as input for training.

⚙️ Model & Training
The dataset is preprocessed using StandardScaler for normalization.
Gradient Boosting Classifier (with 100 estimators) is trained using 5-fold cross-validation.
The model is evaluated on both training and test sets using accuracy, precision, recall, F1-score, and confusion matrix.

📊 Results
Cross-Validation Accuracy: Achieved a mean accuracy of ~77%
Test Accuracy: ~84%
Confusion Matrix & Classification Report included in the notebook.

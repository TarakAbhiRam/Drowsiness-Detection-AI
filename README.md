Real-Time Multi-Person Monitoring System
Technologies: Python, CNN, Haar Cascades, OpenCV

Overview
This project implements an AI-powered monitoring system that detects multiple individuals in images and videos, classifies their drowsiness state, and predicts the ages of sleeping subjects. The system integrates deep learning, computer vision, and real-time processing for accurate and efficient performance.

Features:

✅ Parallel Model Development:

Trained a CNN from scratch on the UTK dataset to predict age using regression.
Implemented Haar Cascades for real-time face detection.

✅ Post-Processing Enhancements:

Applied a running median filter to improve age prediction accuracy and stability.


✅ System Integration:

Combined CNN age predictions with face detection to enable multi-person monitoring.
Provided real-time input previews for instant visual feedback.



Usage:

Install Dependencies Manually:
Ensure you have the required libraries installed:


pip install torch torchvision torchaudio opencv-python numpy matplotlib


Run the Monitoring System:

Open and execute main.ipynb to:
*Capture frames from an image or video stream.
*Detect faces using Haar Cascades.
*Predict age using the pre-trained CNN model (.pth file).
*Classify drowsiness state.
*Apply running median filtering for stable age predictions.
*Display real-time monitoring results with input previews.
*Retrain the Age Prediction Model (Optional, if needed):

Run age_predictor_cnn.ipynb to train a new CNN model on the UTK dataset.
Save the trained model as a .pth file for later use.
Applications:

Driver Monitoring: Detects drowsy drivers for road safety.
Security & Surveillance: Identifies individuals and monitors activity.
Healthcare & Elderly Care: Monitors sleep patterns for well-being.


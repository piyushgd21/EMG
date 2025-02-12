An Electromyography system for Sitting and Walking Postures

Project Description: This project presents an Electromyography (EMG)-based system designed for the classification of sitting and walking postures. The system is a foundational model for lower limb prosthesis, leveraging machine learning techniques to recognize human postures with high accuracy.

Key Features:
Data Collection: EMG signals are acquired using a 4-channel Clarity Medical EMG machine, capturing muscle activity from the rectus femoris (RF), biceps femoris (BF), vastus medialis (VM), and semitendinosus (ST).
Signal Processing: Raw EMG data undergoes bandpass filtering (10-200 Hz) and notch filtering (49-51 Hz) to remove noise and enhance signal quality.
Feature Extraction: A combination of time-domain (RMS, MAV, ZC), frequency-domain (mean power, peak frequency), and time-frequency features is used to create a comprehensive feature set.
Classification Models: Machine learning models, including Decision Tree, SVM, KNN, and Random Forest, are trained on the extracted features.
High Accuracy: The Random Forest classifier achieved an accuracy of 99.19%, demonstrating the system’s effectiveness in posture classification.


Workflow Overview:
EMG Data Acquisition: Recording muscle activity from subjects performing sitting and walking movements.
Preprocessing: Noise removal using filters to enhance signal clarity.
Feature Extraction: Extracting meaningful features from time, frequency, and time-frequency domains.
Classification: Training and evaluating machine learning models for accurate posture recognition.

Deployment & Future Applications: This system can be integrated into rehabilitation devices, prosthetics, and assistive robotics.

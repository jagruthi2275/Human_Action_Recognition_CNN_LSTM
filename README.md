# Human Action Recognition using CNN-LSTM

## Project Overview
This project performs Human Action Recognition using Deep Learning techniques.  
A CNN-LSTM architecture is used to classify human activities from video sequences.

The model extracts spatial features using MobileNetV2 (CNN) and temporal features using LSTM.

---

## Dataset
Dataset Used: UCF101 Subset

Classes Used:
- CricketShot
- PlayingCello
- PlayingGuitar
- Punch
- ShavingBeard

---

## Technologies Used
- Python
- TensorFlow / Keras
- OpenCV
- NumPy
- Scikit-learn
- Google Colab

---

## Deep Learning Architecture

Video Input  
↓  
Frame Extraction  
↓  
MobileNetV2 (CNN Feature Extraction)  
↓  
LSTM (Temporal Learning)  
↓  
Softmax Classification  

---

## Features
- Video preprocessing
- Frame extraction
- CNN-LSTM architecture
- Transfer Learning using MobileNetV2
- Classification Report
- Confusion Matrix
- Action Prediction System

---

## Model Performance

- Test Accuracy: 90%
- F1 Score: 0.90

---

## Results

### Prediction Example
Model successfully predicted:
- ShavingBeard
- Confidence Score: 0.78

---

## Future Improvements
- Real-time webcam action recognition
- YOLO integration
- Pose estimation
- Transformer-based architectures
- Larger dataset training

---
## Accuracy Graph

![Accuracy](images/accuracy%20graph%20HAR.png)

## Loss Graph

![Loss](images/loss%20graph%20HAR.png)

## Confusion Matrix

![Confusion Matrix](images/confusion%20matrix.png)

## Prediction Output

![Prediction](images/predicted%20output.png)
## Author
Jagruthi Reddy

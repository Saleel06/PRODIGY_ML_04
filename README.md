Hand Gesture Recognition Model - Task 4
Overview
This project is part of Task 4 of my internship at Prodigy Infotech. The aim is to develop a Hand Gesture Recognition Model using the LeapGestRecog dataset, enabling intuitive human-computer interaction and gesture-based control systems.

Project Details
Dataset: LeapGestRecog from Kaggle
Goal: Classify different hand gestures to facilitate gesture-based controls and interactions.
Model: Custom architecture designed to classify hand gestures effectively.
Table of Contents
Installation
Usage
Model Architecture
Results
Contributors
License
Installation
Clone the repository:
bash
Copy code
git clone https://github.com/YourUsername/PRODIGY_Task4_HandGestureRecognition.git
Navigate to the project directory:
bash
Copy code
cd PRODIGY_Task4_HandGestureRecognition
Install the required packages:
bash
Copy code
pip install -r requirements.txt
Usage
Train the Model:
To train the model on your system, run:
bash
Copy code
python train_model.py
Evaluate the Model:
To evaluate the model’s performance, run:
bash
Copy code
python evaluate_model.py
Real-time Prediction:
Connect a webcam and use the model for real-time gesture prediction:
bash
Copy code
python real_time_prediction.py
Model Architecture
The model consists of:

Input Layer: Grayscale images of size 32x32 pixels.
Hidden Layers: A series of layers designed to extract and learn features of hand gestures.
Output Layer: 10 classes corresponding to different hand gestures.
Results
The model achieved an accuracy of X% on the validation set, effectively classifying gestures such as:

Class 0: Gesture '00'
Class 1: Gesture '01'
...
Class 9: Gesture '09'
Contributors
Saleel, Machine Learning Intern at Prodigy Infotech
License
This project is licensed under the MIT License - see the LICENSE file for details.

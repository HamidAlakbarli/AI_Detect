#AIDetect: Predicting Behavioral Indicators of Crime
Overview
AIDetect is an advanced AI system designed to predict behavioral indicators of crime using a Human Action Recognition Model. This project focuses on automatically detecting criminal behaviors to enhance security measures and ensure prompt responses.

Project Structure
Input
CNN Layer: The Convolutional Neural Network (CNN) layer is utilized for feature extraction from the input video frames. This layer processes the spatial information in the frames.
Model
LSTM Model: The Long Short-Term Memory (LSTM) network is employed for time-series analysis, capturing temporal dependencies and ensuring accurate detection of criminal activities over time.
Dense Layer: Following the LSTM, the dense layer helps in consolidating the learned features and making final predictions.
Output
Adjustable Assessment Model: This component allows for the customization and fine-tuning of the detection parameters to suit specific security requirements.
Automatic Alarming: The system triggers alarms automatically upon detecting potential criminal behaviors, ensuring immediate attention and response.
Dataset
The project utilizes the UCF50 dataset, which comprises 50 action categories. This diverse dataset aids in training the model to recognize a wide range of human actions, enhancing its capability to detect suspicious activities.

Advantages
Better Use of Up/Down Frames: The model efficiently processes both upward and downward frames, ensuring comprehensive analysis of the input video.
LSTM for Time Series Analysis: The LSTM model excels in time series analysis, enabling the AI to achieve high accuracy in detecting criminal behaviors by understanding the sequence of actions.

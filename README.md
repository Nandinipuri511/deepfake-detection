Deepfake Video Detection using Deep Learning

ResNeXt + LSTM based Approach

Overview

With the rapid rise of AI-generated media, detecting manipulated (deepfake) videos has become a critical challenge.
This project focuses on detecting deepfake videos using deep learning, leveraging a combination of CNN-based spatial feature extraction and temporal sequence modeling.

The system uses a pretrained ResNeXt network to extract frame-level features from videos and an LSTM network to capture temporal inconsistencies across frames. The final model classifies videos as real or fake.

🚀 Key Highlights

🎯 Deepfake detection using transfer learning

🧠 Feature extraction via ResNeXt CNN

⏱️ Temporal modeling using LSTM

🎥 Video-level classification

🌐 Web-based interface built with Django

🐳 Fully Dockerized for easy deployment

💻 Works on CUDA and non-CUDA systems

🏗️ Project Structure
Deepfake_detection_using_deep_learning
│
├── Django_Application
│   ├── Web interface for video upload & prediction
│   └── Backend integration with trained model
│
├── Model_Creation
│   ├── Data preprocessing
│   ├── Feature extraction (ResNeXt)
│   └── Sequence modeling & training (LSTM)
│
└── Documentation
    └── Project reports, diagrams, and explanations

    System Architecture

Input Video

Frame Extraction

Feature Extraction using ResNeXt

Temporal Learning via LSTM

Binary Classification (Real / Fake)

Result Display via Django Web App

Experimental Results
Model File	Videos	Frames per Video	Accuracy (%)
model_84_acc_10_frames	6000	10	84.21
model_87_acc_20_frames	6000	20	87.79
model_89_acc_40_frames	6000	40	89.34
model_90_acc_60_frames	6000	60	90.59
model_91_acc_80_frames	6000	80	91.49
model_93_acc_100_frames	6000	100	93.58

Tech Stack

Python

PyTorch

ResNeXt (Pretrained CNN)

LSTM

Django

Docker

OpenCV

NumPy

🧪 Features Implemented

✔️ Dockerized application

✔️ Support for systems without NVIDIA CUDA

✔️ End-to-end deepfake detection pipeline

✔️ Web-based video upload and prediction

🔮 Future Enhancements

We actively welcome improvements and contributions. Possible extensions include:

☁️ Deployment on free cloud platforms

🔗 Public REST API for deepfake detection

📦 Batch processing of entire videos

⚡ Performance and inference speed optimization

📈 Model explainability & visualization tools

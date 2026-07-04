# 🏃 ActiVision AI – Real-Time Human Activity Recognition Using Deep Learning

A Flask-based computer vision application that recognizes human activities in real time using a laptop camera. The system uses MediaPipe to extract human body landmarks and a trained deep learning model to classify activities through an interactive web interface.

The project demonstrates an end-to-end AI workflow including pose estimation, feature extraction, deep learning model training, and real-time inference.

---

# 🚀 Tech Stack

[![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![Flask](https://img.shields.io/badge/Flask-000000?logo=flask&logoColor=white)](https://flask.palletsprojects.com/)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?logo=tensorflow&logoColor=white)](https://www.tensorflow.org/)
[![Keras](https://img.shields.io/badge/Keras-D00000?logo=keras&logoColor=white)](https://keras.io/)
[![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?logo=opencv&logoColor=white)](https://opencv.org/)
[![MediaPipe](https://img.shields.io/badge/MediaPipe-4285F4?logo=google&logoColor=white)](https://developers.google.com/mediapipe)
[![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?logo=scikitlearn&logoColor=white)](https://scikit-learn.org/)
[![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white)](https://numpy.org/)
[![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

---

# 🏗 Workflow & Activity Recognition Pipeline

```bash
🎥 Live Camera Input
          ↓
🦴 MediaPipe Pose Detection
          ↓
📍 Body Landmark Extraction
          ↓
🧹 Feature Processing
          ↓
🧠 Trained Deep Learning Model
          ↓
📊 Activity Prediction
          ↓
🌐 Flask Web Application
          ↓
✅ Real-Time Result Display
```

---

# ✨ Core Features

- Real-time human activity recognition using webcam
- Human pose estimation with MediaPipe
- Body landmark feature extraction
- Deep learning-based activity classification
- Flask-powered interactive web application
- Real-time inference from live video
- Modular pipeline for data collection, training, and prediction

---

# 🧪 Deep Learning Models

| Model | Purpose |
|--------|---------|
| CNN | Spatial feature learning |
| RNN | Sequential activity modeling |
| LSTM | Temporal sequence learning |
| GRU | Efficient sequence learning |
| CNN-LSTM | Combined spatial and temporal learning |

### ✅ Final Prediction Pipeline

The trained deep learning model processes MediaPipe pose landmarks extracted from live camera frames and predicts the corresponding human activity in real time through the Flask application.

---

# ⚙️ Development Workflow

## 📌 Data & Model Development
- Pose landmark extraction using MediaPipe
- Data preprocessing and feature engineering
- Deep learning model training and evaluation
- Model export (`model.h5`) with activity labels (`labels.npy`)

## 📌 Web Application Integration
- Flask backend integration
- Live webcam input processing
- Real-time activity prediction
- Interactive browser interface

---

# 📂 Repository Structure

```text
HUMAN_ACTIVITY_FINAL/
│
├── app.py
├── data_collection.py
├── data_training.py
├── inference.py
├── model.h5
├── labels.npy
├── requirements.txt
│
├── templates/
│   ├── home.html
│   └── login.html
│
├── static/
│   ├── bg.jpg
│   └── styles/
│
├── Snapshots/
│
└── README.md
```

---

# ▶️ Running the Application

```bash
python app.py
```

Then open your browser:

```text
http://127.0.0.1:5000/
```

---

# 📸 Project Snapshots

| Screenshot | Description |
|------------|-------------|
| ![Login Page](Snapshots/Snap-1.png) | User login interface |
| ![Home Page](Snapshots/Snap-2.png) | Main application dashboard |
| ![Prediction Output](Snapshots/Snap-3.png) | Real-time activity recognition |

---

# 🧠 Skills Demonstrated

- Deep Learning implementation
- Computer Vision with OpenCV
- Human Pose Estimation using MediaPipe
- Feature extraction and preprocessing
- Flask web application development
- Real-time AI inference systems
- End-to-end machine learning workflow

---

# 🔮 Future Improvements

- Support additional human activities
- Improve accuracy using larger datasets
- Explore Transformer-based architectures
- Optimize for edge devices
- Deploy on cloud platforms
- Add activity history and analytics dashboard

---

# 🏁 Project Note

> This project was developed as a final-year academic project to demonstrate the practical implementation of deep learning, computer vision, human pose estimation, and real-time human activity recognition through a Flask-based web application.

---

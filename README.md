# 🎵 Music Recommendation System Based on Emotion Detection

This project uses real-time facial emotion detection to recommend music that matches the user's current emotional state. It leverages deep learning and computer vision to analyze facial expressions and plays suitable music accordingly.

---

## 🚀 Features

- 🎥 Real-time webcam-based face detection
- 😄 Emotion classification using a pre-trained deep learning model
- 🎶 Music recommendation engine based on detected emotions
- 📦 Easy-to-run Jupyter Notebook interface

---

## 🧠 Technologies Used

- **Python**
- **OpenCV** – For face detection
- **TensorFlow / Keras** – For loading and using the pre-trained emotion detection model
- **Transfer Learning** – Used to train the emotion classification model
- **Haar Cascade Classifier** – For real-time face detection

---

## 📁 Project Files
- ├── emotion detection.ipynb # Jupyter notebook with the full system
- ├── My_model.h5 # Trained deep learning model for emotion classification
- ├── haarcascade_frontalface_default.xml # Haar Cascade XML for face detection
- └── README.md # Project documentation


---

## 📷 Supported Emotions

- Happy 😊  
- Sad 😢  
- Angry 😡  
- Neutral 😐  
- Surprise 😲  
- Fear 😨  
- Disgust 🤢

---

## 🛠️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/music-recommendation-system.git
   cd music-recommendation-system

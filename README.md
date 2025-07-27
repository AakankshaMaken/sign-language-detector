# 🤟 Sign Language Detection using Deep Learning and OpenCV

A real-time sign language recognition system using MediaPipe for hand tracking, LSTM neural networks for temporal sequence classification, and OpenCV for video stream handling.

---

## 📹 Demo
https://drive.google.com/file/d/19iaxnNY1D5eIaSQV-lnUYkN90lugIfE2/view?usp=drive_link 


---

## 🧠 Model Overview

- **Input**: Live webcam feed with hand gestures
- **Preprocessing**: Hand landmark extraction using MediaPipe
- **Model**: LSTM Neural Network
- **Output**: Predicted letter or digit (A-Z, 1-9)

---

## 🛠️ Tech Stack

- Python 3.8+
- OpenCV
- MediaPipe
- TensorFlow / Keras
- NumPy
- Scikit-learn

---

## 📁 Project Structure

```
sign-language-detector/
├── README.md
├── requirements.txt
├── .gitignore
├── src/
│   ├── app.py               # Real-time sign language detection
│   ├── collectdata.py       # Collects raw hand gesture images
│   ├── data.py              # Extracts MediaPipe keypoints to .npy files
│   ├── trainmodel.py        # LSTM model training script
│   └── function.py          # Utility functions (MediaPipe, landmarks, etc.)
├── model/
│   ├── model.h5             # Trained model weights
│   └── model.json           # Model architecture
├── demo/
│   └── demo.gif             # Demo of the working app
```




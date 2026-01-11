# 🎭 Facial Expression Analyzer

**Real-Time Facial Emotion Detection using Computer Vision & Deep Learning**

[![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python)](https://www.python.org/)
[![OpenCV](https://img.shields.io/badge/OpenCV-Computer%20Vision-orange?style=for-the-badge&logo=opencv)](https://opencv.org/)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-Deep%20Learning-red?style=for-the-badge&logo=tensorflow)](https://www.tensorflow.org/)

---

## ✨ Project Overview

The **Facial Expression Analyzer** detects human emotions in **real-time** using a **Convolutional Neural Network (CNN)** and **OpenCV**.  
It can process live webcam feed, images, or videos to classify emotions and display them visually.

🎯 **Use Cases:**  
- AI chatbots & virtual assistants  
- Classroom engagement analysis  
- Marketing & UX research  


---
---

## 🎥 Demo – Watch It in Action

Click the thumbnail below to watch the **live demo** of the Facial Expression Analyzer on YouTube:

[![Watch Demo](https://img.youtube.com/vi/01bKFDHlSxc/0.jpg)](https://youtube.com/shorts/01bKFDHlSxc?si=IG3j6nAyJBrc48bL)

> 🎬 This is a YouTube Short showing real‑time emotion detection using your model!

---

## 🧩 Model Details

- **Model Type:** Convolutional Neural Network (CNN)  
- **Input Image Size:** 64 × 64 pixels (grayscale)  
- **Output:** Probability of each emotion  
  - 😄 Happy  
  - 😢 Sad  
  - 😠 Angry  
  - 😲 Surprised  
  - 😐 Neutral  
  - 😮 Fear  
  - 😏 Disgust  

---

## 🗂 Folder Structure

Facial_Expression_Analyzer-main/  
│  
├── model/                               # Trained CNN model files  
├── haarcascade_frontalface_default.xml  # Pre-trained Haar Cascade for face detection  
├── main.py                              # Main script for detection  
├── test_webcam.py                       # Test webcam feed  
├── Facial_Expression_Analyzer_Project.txt  # Project documentation/notes  
├── README.md                             # This file  
└── .gitattributes                        # Git attributes file  

---


## 🎬 Usage

Run on Webcam:  
python main.py  

Test Webcam:  
python test_webcam.py  

Run on Image or Video:  
python main.py --image path_to_image.jpg  
python main.py --video path_to_video.mp4  

---

## 🧠 How It Works

1. **Capture Frame:** OpenCV captures frames from webcam or video.  
2. **Detect Face:** Haar Cascade detects faces.  
3. **Preprocess:** Convert face to grayscale and resize to 64×64 pixels.  
4. **Predict Emotion:** CNN outputs probabilities for each emotion.  
5. **Display Result:** Draw bounding box & show predicted emotion label.  

![Workflow Animation](https://media.giphy.com/media/l3vR85PnGsBwu1PFK/giphy.gif)

---

## 🎨 Features

- ✅ Real-time webcam emotion detection  
- ✅ Image & video support  
- ✅ Lightweight CNN for fast predictions  
- ✅ Visual feedback with bounding boxes & emotion labels  
- ✅ Open-source & customizable  
- ✅ Professional project structure & documentation  

---

## 🤝 Contributing

1. Fork the repository  
2. Create a branch: git checkout -b feature-name  
3. Commit your changes: git commit -m 'Add feature'  
4. Push to branch: git push origin feature-name  
5. Open a Pull Request  

---



 

---

**Made with ❤️, OpenCV & TensorFlow**  

![Emoji Animation](https://media.giphy.com/media/3o7aD2saalBwwftBIY/giphy.gif)

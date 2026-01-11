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

![Facial Expression Animation](https://media.giphy.com/media/3o6ZsXkJlVhMP3zjS8/giphy.gif)

---
---

## 🎥 Live Demo

Check out the **live demo** of Facial Expression Analyzer in action!  

[![Watch Demo](https://img.youtube.com/vi/YOUR_VIDEO_ID/0.jpg)](https://youtube.com/shorts/01bKFDHlSxc?si=IG3j6nAyJBrc48bL)  

> Click the thumbnail to watch the demo on YouTube or Instagram Reel.


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

## 🚀 Installation

1. Clone the repository:  
git clone https://github.com/yourusername/Facial_Expression_Analyzer.git  
cd Facial_Expression_Analyzer-main  

2. Create and activate a virtual environment:  
python -m venv venv  
# Windows: venv\Scripts\activate  
# Linux/Mac: source venv/bin/activate  

3. Install dependencies:  
pip install -r requirements.txt  

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

## 📜 License

MIT License © 2026 [Your Name]  

---

## 🔗 Connect

- [LinkedIn](https://www.linkedin.com/in/yourprofile)  
- [GitHub](https://github.com/yourusername)  
- [Portfolio](https://yourportfolio.com)  

---

**Made with ❤️, OpenCV & TensorFlow**  

![Emoji Animation](https://media.giphy.com/media/3o7aD2saalBwwftBIY/giphy.gif)

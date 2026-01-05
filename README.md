# 😷 Face Mask Detection Using Image Processing & Deep Learning

A real-time **Face Mask Detection System** built using **Deep Learning and Computer Vision** to identify whether a person is wearing a mask or not through images and live webcam feed.  
The system leverages **MobileNetV2**, **OpenCV**, and **TensorFlow** for fast, accurate, and lightweight detection.

---

## 📌 Project Overview

During the COVID-19 pandemic, enforcing mask compliance in public places became critical.  
This project provides an **automated, low-cost, real-time solution** to detect whether individuals are wearing face masks using cameras.

### Key Highlights
- Real-time face detection using OpenCV DNN  
- Mask / No-Mask classification with confidence score  
- Supports live webcam feed  
- Audio alerts for mask violations  
- Detects multiple faces simultaneously  
- Lightweight CNN using MobileNetV2 (Transfer Learning)

---

## 🧠 Tech Stack & Skills

![Python](https://img.shields.io/badge/Python-Programming-blue)
![Deep%20Learning](https://img.shields.io/badge/Deep%20Learning-CNN%20Models-red)
![TensorFlow](https://img.shields.io/badge/TensorFlow-Model%20Training-orange)
![Keras](https://img.shields.io/badge/Keras-Neural%20Networks-brightgreen)
![OpenCV](https://img.shields.io/badge/OpenCV-Computer%20Vision-purple)
![MobileNetV2](https://img.shields.io/badge/MobileNetV2-Transfer%20Learning-success)
![Image%20Processing](https://img.shields.io/badge/Image%20Processing-Face%20Detection-yellow)
![Real--Time%20Detection](https://img.shields.io/badge/Real--Time%20Detection-Webcam%20Inference-critical)
![Computer%20Vision](https://img.shields.io/badge/Computer%20Vision-Video%20Analytics-informational)
![Model%20Evaluation](https://img.shields.io/badge/Model%20Evaluation-Accuracy%20%26%20Loss-lightgrey)
![Audio%20Alerts](https://img.shields.io/badge/Audio%20Alerts-Violation%20Notification-blueviolet)
![Transfer%20Learning](https://img.shields.io/badge/Transfer%20Learning-Pretrained%20CNNs-green)

---

## 🗂 Project Structure
```
📁 Face-Mask-Detection
│
├── code_for_testing.py              # Real-time mask detection using webcam
├── source_code_for_training.py      # Model training using MobileNetV2
│
├── data sets/                       # Mask / No-Mask image dataset
├── Outputs/                         # Result images & plots
├── Voice files/                     # Audio alerts (mask / no mask)
│
├── Project Publication paper.pdf    # Full academic project documentation
├── README.md                        # Project documentation
├── requirement.txt                  # Python dependencies

```

---

## 🧪 Dataset

- ~4000 curated images  
- Classes:
  - `with_mask`
  - `without_mask`
- Sources:
  - MAFA
  - RMFD
  - CelebA
  - Internet images (manually cleaned)

Balanced dataset to improve model accuracy and robustness.

---

## 🏗 Model Architecture

- **Base Model:** MobileNetV2 (ImageNet pretrained)
- **Head Layers:**
  - Average Pooling
  - Dense (ReLU)
  - Dropout (0.5)
  - Softmax (2 classes)
- **Loss:** Binary Crossentropy  
- **Optimizer:** Adam  
- **Epochs:** 20  
- **Batch Size:** 32  

---


## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository
git clone https://github.com/your-username/face-mask-detection.git  
cd face-mask-detection

### 2️⃣ Install Dependencies
pip install -r requirement.txt

### 📚 Required Libraries
- numpy  
- opencv-python  
- tensorflow  
- keras  
- imutils  
- matplotlib  
- playsound  


## 🚀 Training the Model

Run the training script:

python source_code_for_training.py

This process will:

- Train a CNN-based deep learning model  
- Save the trained model as mask_detector.model  
- Generate training accuracy and loss plots  


## 🎥 Real-Time Mask Detection (Webcam)

Run the testing script:

python code_for_testing.py

Live Features:

- 🟩 Green box → Mask detected  
- 🟥 Red box → No mask detected  
- Confidence score displayed  
- Audio alert triggered  
- Press q to exit  


## 📊 Results

- Accuracy: ~97%  
- Real-time detection with minimal latency  
- Works for:
  - Single face  
  - Multiple faces  
  - Improper mask usage  


## 🏁 Conclusion

This project demonstrates a practical, efficient, and deployable AI-based face mask detection system using deep learning and image processing.

Potential Applications:

- CCTV surveillance systems  
- Airports  
- Shopping malls  
- Offices  
- Public environments  


## 🔮 Future Enhancements

- Better detection of improperly worn masks  
- Integrate thermal screening  
- Deploy on Raspberry Pi / Edge devices  
- Add face recognition & access control  
- Develop a web or mobile interface  


## 👨‍💻 Author

Sri Harsha Chinthala  
Bachelor of Technology – Electronics & Communication Engineering  
AI | Machine Learning | Computer Vision


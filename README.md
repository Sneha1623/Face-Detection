# 👁️ Face Detection System using Haarcascade Classifier

## 📌 Project Overview

This project is a **real-time face detection system** developed using **Python** in the **Spyder IDE**. It uses the **Haarcascade Classifier** for detecting human faces and an **IP Webcam** for capturing live video feed.

The system processes video frames and identifies faces instantly with bounding boxes.

---

## 🚀 Features

* Real-time face detection
* Uses IP Webcam for live streaming
* Lightweight and fast detection using Haarcascade
* Easy to run and understand
* Works on basic system configurations

---

## 🛠️ Technologies Used

* Python
* OpenCV
* Haarcascade Classifier
* Spyder IDE
* IP Webcam (Android App)

---

## 📂 Project Structure

```
clean_data/                # Processed data (if used)
config/                    # Configuration files
collect_data.py            # Script to collect face data
consolidated.py            # Main detection script
deploy.py                  # Deployment script
haarcascade_frontalface_default.xml  # Pre-trained classifier
```

---

## ⚙️ How It Works

1. The IP Webcam streams video from a mobile device.
2. Python script captures frames using OpenCV.
3. Haarcascade classifier detects faces in each frame.
4. Detected faces are highlighted with rectangles.

---

## ▶️ Installation & Setup

### 1. Install Dependencies

```bash
pip install opencv-python
```

### 2. Run IP Webcam

* Install IP Webcam app on your phone
* Start server and copy the IP address

### 3. Run the Project

```bash
python consolidated.py
```

---

## 📸 Output

* Detects and highlights faces in real-time video stream

---

## 📈 Future Improvements

* Add face recognition
* Improve accuracy using deep learning
* Store detected faces
* Add GUI interface

---

## 🙌 Acknowledgment

This project uses OpenCV’s pre-trained Haarcascade model for face detection.

---

## 📬 Contact

**Sneha Sudha Behera**
📧 [snehasudha97777@gmail.com](mailto:snehasudha97777@gmail.com)
* Add **LinkedIn-ready project description**
* Help you **upload this README properly on GitHub** 🚀

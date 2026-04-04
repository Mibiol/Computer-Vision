# Computer-Vision
Collection of simple computer vision experiments using Python, OpenCV, and NumPy.
# 🧠 Face Detection & Recognition using OpenCV

This project demonstrates **face detection and face recognition** using classical computer vision techniques in **Python with OpenCV**. It includes implementations for face detection in images, face detection in videos, and face recognition using a custom dataset.

---

## 📌 Features
- 📷 Detect faces in uploaded images  
- 🎥 Detect faces in video frames  
- 🧑‍🤝‍🧑 Train a face recognition model using a dataset  
- 🏷️ Identify known faces with labels  
- 💾 Save trained model and label mappings  

---

## 🛠️ Technologies Used
- Python  
- OpenCV (`cv2`)  
- NumPy  
- Matplotlib  
- Google Colab  

---

## 📂 Project Structure

---

## 🚀 How It Works

### 1️⃣ Face Detection (Image)
Upload an image, convert it to grayscale, use Haar Cascade classifier, and detect faces with bounding boxes.  
**Output:** Image with detected faces highlighted  

### 2️⃣ Face Detection (Video)
Upload a video file (`.mp4`, `.avi`), process frames using OpenCV, detect faces in each frame, and display results.  
**Output:** Frames showing detected faces  

### 3️⃣ Face Recognition System

**Step 1: Load Dataset**  
Reads images from dataset folders, converts to grayscale, and resizes to 200×200.  

**Step 2: Train Model**  
Uses **LBPH (Local Binary Patterns Histogram)** algorithm, assigns labels, and trains the model.  

**Step 3: Save Model**  
- `face_recognizer.yml` → trained model  
- `label_map.txt` → label mapping  

**Step 4: Recognition**  
Detect faces, predict identity, and display name with confidence.  
**Output:** Recognized faces with labels  

---

## 📦 Installation
```bash
pip install opencv-python-headless matplotlib numpy

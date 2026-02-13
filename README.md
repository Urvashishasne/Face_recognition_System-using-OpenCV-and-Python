# Face Recognition System using OpenCV and Python

A real-time face recognition system built using Python and OpenCV.  
It captures faces through a webcam, trains a model using the LBPH (Local Binary Patterns Histograms) algorithm, and recognizes faces in live video streams. The system is designed to be easy to set up and extend for multiple users. 
---

## 🚀 Features

✅ Face dataset creation  
✅ Haar Cascade face detection  
✅ LBPH face recognition  
✅ Real-time identification  
✅ Confidence score display  
✅ Model persistence (trainer.yml)

---

## 🧠 How It Works

### Step 1: Create Dataset
- Capture images using webcam
- Detect faces
- Save cropped grayscale images
- Store in `dataset/`

### Step 2: Train Model
- Load images from dataset
- Extract labels from filenames
- Train using LBPH algorithm
- Save trained model in `trainer/`

### Step 3: Recognize Faces
- Detect faces in real time
- Predict ID using trained model
- Display name and confidence percentage

---

## 🛠 Technologies Used

- Python
- OpenCV
- NumPy
- PIL
- Haar Cascade
- LBPH Algorithm

---

## 📂 Project Structure
Face_Recognition_System/
│
├── dataset/
├── trainer/
│ └── trainer.yml
├── capture_faces.py
├── train_model.py
└── recognize_faces.py

---

## 🔮 Future Improvements

- Attendance system using MySQL
- Timestamp logging
- Deep learning-based recognition (CNN)
- Web deployment

# Face Recognition Project - VBK

This project demonstrates **face detection and recognition** using Python. It can detect faces in images, recognize known individuals, annotate them, and display results.  

The notebook is fully compatible with **Google Colab**, so anyone can run it without installing Python locally.

---

## 🔹 Features
- Detect faces in images using `face_recognition` and `OpenCV`
- Recognize known individuals from reference images
- Annotate images with bounding boxes and labels
- Save annotated images automatically
- Works on Colab or locally

---

## 📂 Repository Structure
FaceRecognition-VBK/
│
├── FaceRecognition.ipynb ← Main notebook
├── IMAGES/ ← Sample/reference images
└── README.md

---

## 🚀 How to Run

### Option 1: Run on Google Colab (Recommended)
Click the badge below to open the notebook in Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/balaram-krishna/FaceRecognition-VBK/blob/main/FaceRecognition.ipynb)

**Steps:**
1. Click the badge to open the notebook in Colab.
2. Run **all cells** (`Runtime → Run All`).
3. Upload your images when prompted.
4. See annotated images automatically displayed in the notebook output.

> ✅ **Note:** Images in the `IMAGES/` folder are automatically displayed in Colab, so you don’t have to manually upload if they are already in the repo.

---

### Option 2: Run Locally
1. Install Python 3.12+  
2. Install dependencies:

```bash
pip install face_recognition opencv-python matplotlib
Open FaceRecognition.ipynb in Jupyter Notebook or VS Code.

Run all cells.

Upload your reference images if prompted. Annotated images will appear as output.

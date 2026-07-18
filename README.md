# Face Detection using OpenCV

A simple Computer Vision project that detects human faces in images using **OpenCV** and the **Haar Cascade Classifier**. The application identifies faces in an input image and highlights them with bounding boxes.

## 📌 Overview

This project demonstrates the fundamentals of face detection using classical computer vision techniques. It reads an image, detects faces using the Haar Cascade algorithm, and displays the detected faces with rectangles.

## 🚀 Features

- Detects one or multiple faces in an image
- Uses Haar Cascade Classifier for face detection
- Draws bounding boxes around detected faces
- Simple and lightweight implementation

## 🛠️ Tech Stack

- Python
- OpenCV
- NumPy

## 📂 Project Structure

```text
Face-Detection/
│── images/
│   ├── input.jpg
│── haarcascade_frontalface_default.xml
│── face_detection.py
│── requirements.txt
│── README.md
```

## ⚙️ Installation

1. Clone the repository

```bash
git clone https://github.com/your-username/Face-Detection.git
```

2. Navigate to the project directory

```bash
cd Face-Detection
```

3. Install the required dependencies

```bash
pip install -r requirements.txt
```

4. Run the project

```bash
python face_detection.py
```

## 🔍 How It Works

1. Load the input image.
2. Convert the image to grayscale.
3. Load the Haar Cascade Classifier.
4. Detect faces in the image.
5. Draw bounding boxes around detected faces.
6. Display or save the output image.

## 📈 Results

- Successfully detects faces in static images.
- Highlights detected faces with rectangular bounding boxes.
- Provides a simple introduction to computer vision and image processing.

## 📚 Learning Outcomes

- Image preprocessing using OpenCV
- Face detection using Haar Cascade
- Working with image processing techniques
- Understanding basic computer vision workflows

## 🔮 Future Improvements

- Real-time face detection using a webcam
- Face recognition for identity verification
- Eye and smile detection
- Deep learning-based face detection using DNN or MTCNN

## 👩‍💻 Author

**Adina Isran**

B.Tech Computer Science (AI & ML)

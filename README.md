# Face Detection and Recognition

This project implements a face detection and recognition system using machine learning techniques. It uses the **Haar Cascade Classifier** for face detection and the **Local Binary Patterns Histograms (LBPH)** algorithm for face recognition.

## Features

- Detect human faces in real-time using OpenCV's Haar Cascade.
- Train a custom face recognition model using LBPH.
- Recognize and identify faces from a live video stream or dataset.

## Technologies Used

- Python
- OpenCV
- Haar Cascade Classifier
- LBPH (Local Binary Patterns Histograms)

## Project Structure

Face-Detection-and-Recognition/
│
├── face_dataset.py # Captures and stores face images
├── training.py # Trains the LBPH model using stored images
├── face_recognition.py # Detects and recognizes faces in real-time
├── haarcascade_frontalface_default.xml # Haarcascade classifier file
├── dataset/ # Stores captured face images
├── trainer/ # Stores the trained model
└── README.md

## Setup Instructions

1. **Clone the Repository**
   git clone https://github.com/Srinidhi2507/Face-Detection-and-Recognition.git
   cd Face-Detection-and-Recognition
2. Install Dependencies
Make sure you have Python 3 installed. Then install OpenCV:
   pip install opencv-python
3. Download Haar Cascade File
Ensure that haarcascade_frontalface_default.xml is present in the directory. You can also download it from OpenCV GitHub.
4. How to Use
Step 1: Create Face Dataset
Run the script to capture face images:
   python face_dataset.py
Step 2: Train the Recognizer
Train the model using the captured face dataset:
   python training.py
Step 3: Run Face Recognition
Start the face recognition system:
   python face_recognition.py

## Notes
- Make sure your webcam is connected and accessible.
- Captured images are stored in the dataset/ folder.
- Trained model is saved in the trainer/ directory as trainer.yml.

## License
This project is open-source and available under the MIT License.





# CodeAlpha-ImageRecognition 🎥🔍

Welcome to the **CodeAlpha-ImageRecognition** repository! This project uses **TensorFlow** and **OpenCV** to implement **image classification** and **face detection**. The model utilizes **MobileNetV2** for image classification and **Haar Cascade** for detecting faces in images. 💖

## Project Overview 🚀

This project demonstrates how to classify objects in images using **MobileNetV2**, and detect faces using OpenCV's pre-trained Haar Cascade classifier. It's a simple, yet powerful example of combining two widely-used techniques in the field of computer vision. 😎

### Features 🌟
- **Image Classification**: Classifies images into categories using the MobileNetV2 model, which is pre-trained on ImageNet data.
- **Face Detection**: Detects human faces in images using OpenCV's Haar Cascade Classifier and highlights them with bounding boxes.

## Getting Started 💻

### Prerequisites 📦
You need to install Python and some dependencies before running the code.

1. Install **Python 3.8** or later if you haven't already.
2. Create a **virtual environment** (optional, but recommended):
```bash
   python -m venv venv
 ```

3. Activate the virtual environment:
For Windows:
```bash
venv\Scripts\activate
```
For Mac/Linux:
```bash
source venv/bin/activate
```
Install the necessary Python libraries:
```bash
pip install tensorflow opencv-python numpy matplotlib
```
Running the Project 🏃‍♀️
Steps to Run
Clone the repository to your local machine:
```bash

git clone https://github.com/Malita15/CodeAlpha-ImageRecognition.git

cd CodeAlpha-ImageRecognition
```
Download a test image and place it in the project directory.
Run the Python script to classify the image and detect faces:
```bash
python image_recognition.py
```

### Folder Structure 📁
```bash
CodeAlpha-ImageRecognition/
│
├── venv/                      # Virtual Environment folder
├── image_recognition.py        # Python script for face detection and classification
├── .gitignore                  # Git ignore file
├── README.md                   # This README file
└── test_image.jpg              # Test image (replace with your own images)
```
### License 📄
```bash
This project is licensed under the MIT License - see the LICENSE file for details.
```

### Acknowledgments 🎉

TensorFlow: For providing the pre-trained models like MobileNetV2.

OpenCV: For offering the Haar Cascade Classifier for face detection.

ImageNet: For providing a large dataset to train models like MobileNetV2.




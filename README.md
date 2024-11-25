# Face Detection in Java Using OpenCV

A Java application for face detection utilizing the OpenCV library. This project demonstrates how to integrate OpenCV with Java to detect faces in real-time using static images. It's an excellent starting point for understanding computer vision and image processing concepts.

## Introduction

This project leverages OpenCV's robust face detection capabilities via Haar Cascades and DNN (Deep Neural Network)-based models to detect human faces in images streams. The application can be expanded for other facial analysis tasks such as emotion detection or facial recognition.

## Features

- Real-time face detection using a webcam.
- Face detection in static images.
- Uses OpenCV's pre-trained Haar Cascade classifier.
- Modular and extendable codebase for further applications.

## Prerequisites

- **Java Development Kit (JDK)** 8 or higher.
- **Apache Maven** or any other build tool for Java.
- **OpenCV Library** version 4.x or later.
- An IDE like IntelliJ IDEA, Eclipse, or NetBeans.
  
## Usage

1. **Run the Application**:
   - Open the project in your IDE.
   - Compile and run the main Java file (e.g., `FaceDetection.java`).
2. **Input Sources**:
   - For real-time detection, ensure your webcam is connected.
   - For static images, provide the image file path when prompted.
3. **View Results**:
   - Detected faces will be highlighted with bounding boxes in the video stream or images.

#### `FaceDetection.java`
The main class for initializing OpenCV and running face detection. Key functionalities include:
- Loading the Haar Cascade XML file.
- Capturing video feed or reading static images.
- Detecting faces using the `CascadeClassifier` class.
- Drawing rectangles around detected faces.

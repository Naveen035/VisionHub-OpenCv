# VisionHub 🚀

Welcome to **VisionHub** – a powerful computer vision application built with **OpenCV** and **Streamlit**. The project demonstrates real-time detection of **faces**, **eyes**, and **cars** using pre-trained **Haar Cascade Classifiers**. With a user-friendly interface powered by **Streamlit**, VisionHub makes it easy to upload images, process live video streams, and interact with the results in real time.

---

## 🎯 Project Overview

**VisionHub** combines various computer vision techniques to create a seamless experience where users can:

- **Detect Faces in Images** 📸
- **Detect Eyes in Images** 👁️
- **Detect Faces in Live Video** 🎥
- **Detect Eyes in Live Video** 👀
- **Detect Cars in Videos** 🚗

Each functionality leverages **Haar Cascade Classifiers**, a fast and reliable object detection method for tasks like facial recognition, eye detection, and vehicle detection. Whether it's analyzing still images or processing live video from a webcam or uploaded video files, VisionHub has you covered.

---

## 🔧 Key Features

- **Face Detection with Image**: Upload an image to detect and highlight faces.
- **Eye Detection with Image**: Upload an image to identify and highlight eyes.
- **Real-time Face Detection**: Activate your webcam to detect faces in live video.
- **Real-time Eye Detection**: Use your webcam to detect eyes in live video feeds.
- **Car Detection with Video**: Upload a video to detect and highlight cars.

Each feature is easily accessible through the **Streamlit** interface, making it simple to interact with the app in an intuitive way.

---

## 📦 Packages Used

To run **VisionHub**, you'll need to install the following packages:

- `opencv-python` 🎥 - The OpenCV library for computer vision.
- `numpy` ➗ - Essential for numerical operations and image processing.
- `streamlit` 🌐 - For building interactive web apps.
- `pillow` 🖼️ - For additional image processing capabilities.

To install the required packages, you can use:

## 📥 Haar Cascade Files

To enable face, eye, and car detection, the project relies on Haar Cascade XML files. You can find the necessary files on GitHub:

- [Download the Haar Cascade files from OpenCV GitHub](https://github.com/opencv/opencv/tree/master/data/haarcascades)

Please make sure to place the Haar Cascade files in the corresponding directories for the project to work as intended.


## 🎓 What You Will Gain from This Project

By working on VisionHub, you'll gain practical experience and knowledge in several important domains of Computer Vision and Web Development:

### 📸 Face Detection with Image
- Learn to use Haar Cascade Classifiers to detect and highlight faces in static images.
- Understand the process of converting images to grayscale and applying detection algorithms to identify features in photos.

### 👁️ Eye Detection with Image
- Implement eye detection using pre-trained models, enabling you to identify eyes in images.
- Explore the use of bounding boxes to highlight detected features.

### 🎥 Real-time Face Detection with Webcam
- Master real-time object detection in video streams using your webcam.
- Learn how to detect and track faces in live video, useful in applications like video surveillance or interactive systems.

### 👀 Real-time Eye Detection with Webcam
- Extend real-time detection to eyes and other facial features in a live video stream.
- Understand the challenges and techniques behind live video processing.

### 🚗 Car Detection with Video
- Implement car detection using Haar Cascade Classifiers for vehicle recognition in video files.
- Explore practical applications in video surveillance, smart city projects, and automated vehicle monitoring.

### 💻 Interactive Web Interface with Streamlit
- Create an intuitive and user-friendly interface with Streamlit to interact with computer vision models.
- Learn how to deploy a Python app as a web application for easy access and interaction.

## 💡 Contributing

We welcome contributions! If you have suggestions for improvements or new features, feel free to fork the repository and create a pull request. If you encounter any issues or bugs, open an issue, and I'll be happy to help.

## 📢 Acknowledgements

- **OpenCV**: For providing the pre-trained Haar Cascade Classifiers.
- **Streamlit**: For making it easy to create interactive web apps.
- **Python Community**: For their continuous support in the development of useful libraries and frameworks.

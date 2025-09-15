# Deep Learning for your Face Detection in Rpi

The following project ussed ur phone as live video footage and detects humans using Haar Cascade classifier

## 📽️ Demo Video

👉 *[[Demo video link here](https://www.youtube.com/watch?v=NVE-flz3cJY)]*

---

## 📌 Project Overview

This project implements a real-time face detection system on a Raspberry Pi, leveraging live video footage streamed from a mobile phone camera. The phone acts as an IP camera using the IP Webcam app, and the video stream is processed on the Raspberry Pi.

A Haar Cascade classifier is used as the detection model to identify human faces in the video frames. This approach enables a low-cost, portable, and efficient face detection system without requiring an external webcam.
---

## ⚙️ Features

- 📱 Live video streaming from mobile phone to Raspberry Pi via IP Webcam
- 👤 Real-time face detection using Haar Cascade classifier
- 💻 Lightweight model suitable for Raspberry Pi’s limited resources

---

## 🧰 Technologies & Libraries

- **Python 3**
- **OpenCV** (for image processing and face detection)
- **IP Webcam App** (for turning mobile into an IP camera)

---

## 🛠️ Hardware Components

| Component                    | Quantity |
|-----------------------------|----------|
| Raspberry Pi                | 1        |
| Android Mobile              | 1        |



---

## 🧪 Working Principle

1. The mobile phone camera streams live video over Wi-Fi using the IP Webcam app.
2. The Raspberry Pi connects to the IP camera stream using the provided URL.
3. Each frame of the video stream is captured and processed using OpenCV.
4. The Haar Cascade classifier scans the frames to detect human faces.
5. Detected faces are highlighted with bounding boxes, displayed on the Pi’s screen

---

## 👨‍💻 Authors

Developed by:

- **Anshul Dewangan**
- **Pratyaksh Lodhi**
- **Aaron David Don**
- **Joshua Benchamin**

---

## 📝 License

This project is open-source and available under the [MIT License](LICENSE).

---


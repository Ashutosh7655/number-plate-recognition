# 🚗 Number Plate Recognition and Speed Measurement (Ongoing)

A real-time system for detecting vehicle number plates and measuring vehicle speed using computer vision and deep learning.

## 📌 Features

- **Vehicle Detection** using YOLO (You Only Look Once) for high-accuracy object localization.
- **Number Plate Localization** via OpenCV for image preprocessing and plate isolation.
- **Text Extraction (OCR)** using EasyOCR or Tesseract to read license plate characters.
- **Speed Measurement** by calculating displacement across video frames over time.
- **Real-Time Processing** optimized for surveillance and enforcement use cases.

## 🛠 Tech Stack

- **Programming Language**: Python  
- **Frameworks & Libraries**:  
  - YOLOv5 (via Ultralytics) – Object Detection  
  - OpenCV – Image Processing & Tracking  
  - EasyOCR / Tesseract – Optical Character Recognition  
  - TensorFlow – Model integration and training support

## 📷 Workflow

1. **Capture** video stream or use recorded footage.
2. **Detect** vehicles and number plates using YOLO.
3. **Crop & Process** plates using OpenCV filters.
4. **Read** alphanumeric data via OCR.
5. **Track** vehicle across frames and calculate speed using frame difference & distance covered.

## 🚧 Project Status

🛠 Currently in development:  
- Improving OCR accuracy on blurry or angled plates  
- Refining speed estimation with camera calibration  
- Testing with different lighting and vehicle scenarios

## 📁 Future Enhancements

- GUI Dashboard for live monitoring  
- Database integration for storing plate numbers and timestamps  
- Integration with traffic violation alert systems

## 👨‍💻 Contributors

- Ashutosh Mishra – Lead Developer

---

> This project is being developed for research and educational purposes. Not intended for commercial deployment (yet).

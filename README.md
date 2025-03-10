# Fire Detection using YOLOv7

## 📌 Introduction

This project utilizes **YOLOv7** to detect **fire, smoke, and flames** in images and videos. YOLO (You Only Look Once) is a state-of-the-art deep learning model that enables real-time object detection with high accuracy and efficiency.

## 📌 Motivation

Fire incidents are a major threat in Vietnam and worldwide, causing significant damage and loss. Traditional fire detection systems often rely on **smoke detectors** or **infrared sensors**, which may have limitations in detecting fires in open areas or early-stage fires. This project aims to leverage **computer vision** and **deep learning** to enhance fire detection capabilities.

## 📌 Features

✅ **Real-time fire and smoke detection** using YOLOv7  
✅ **Works with images and videos** for practical use cases  
✅ **Optimized model with improved training techniques**  
✅ **Handles environmental variations** to minimize false detections

## 📌 Dataset

The dataset consists of:

- **Images and videos** containing fire and smoke in different scenarios
- **Annotated labels** for supervised learning

### 🔹 Challenges in Fire Detection

1. **Identifying unique fire features** (shape, color, texture)
2. **Environmental factors** such as lighting, smoke density, and reflections
3. **Minimizing false positives** (e.g., mistaking red lights or sunlight for fire)

## 📌 Model Performance

The trained YOLOv7 model is evaluated based on:

- **Detection accuracy** on test images and videos
- **Comparison with different YOLO versions** to analyze improvements

## 📌 Installation

```bash
# Clone this repository
git clone https://github.com/yourusername/yolov7-fire-detection.git
cd yolov7-fire-detection

# Install dependencies
pip install -r requirements.txt
```

## 📌 Usage

### 🔹 Detect fire in an image

```bash
python detect.py --source path/to/image.jpg --weights yolov7.pt --conf 0.5
```

### 🔹 Detect fire in a video

```bash
python detect.py --source path/to/video.mp4 --weights yolov7.pt --conf 0.5
```

## 📌 Contributors

- **Trần Thế Bảo**
- **Đỗ Hoàng Hải**
- **Trần Đức Thịnh**
- **Hoàng Thế Cường**

![experimental video]()

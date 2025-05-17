# 🧠 YOLOv8 Object Detection Projects

This repository contains two object detection projects :
- **Empty Shelf Detection**: Detecting empty shelf spaces in grocery stores.
- **Pet Classifier**: Detecting and classifying pets (e.g., cats, dogs) from images.

## 📁 Repository Contents

### 1. 🛒 `EmptyShelfDetection.ipynb`

A project that leverages YOLOv8 to detect **empty shelf spaces** in retail environments, useful for store compliance and inventory monitoring.

#### 🔧 Key Features:
- Uses pre-trained YOLOv8 model for shelf image analysis.
- Detects empty areas on shelves from uploaded images.
- Visualizes bounding boxes around empty regions for visual clarity.

#### 📌 Use Cases:
- Retail stock monitoring
- Shelf space management
- Automated restocking alerts

---

### 2. 🐶 `PetClassifier.ipynb`

An object detection application to classify and localize **pets** such as cats and dogs in input images using YOLOv8.

#### 🔧 Key Features:
- Runs inference using YOLOv8 on pet images.
- Draws bounding boxes with labels and confidence scores.
- Useful for animal classification or pet detection tasks.

#### 📌 Use Cases:
- Pet monitoring systems
- Animal species classification
- Wildlife or vet applications

---

## 🚀 How to Use

1. Clone this repository or open the notebooks in Google Colab.
2. Make sure to install dependencies:
   ```bash
   !pip install ultralytics

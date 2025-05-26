# car-object-detection

# 🚗 Car Detection Using YOLOv5u (Ultralytics)

A simple, lightweight pipeline to detect cars using YOLOv5u on Google Colab. This repo contains code for training, evaluating, and testing YOLO models on a custom dataset.

---

## 📌 Features

- 🔍 Real-time object detection (car detection)
- 🧠 Finetuned YOLOv5u on custom dataset
- ☁️ Runs fully on Google Colab (no local setup needed)
- 📊 Easy evaluation and result visualization

---

## 🧪 Demo

![Demo GIF or Screenshot](link-to-image-or-gif-if-any)

---

## 📁 Directory Structure

```bash
.
├── data/
│   └── car.yaml           # Dataset configuration
├── images/
│   ├── training_images/   # Training images
│   └── testing_images/    # Test images
├── labels/
│   ├── training_images/   # YOLO-format .txt labels
│   └── testing_images/    # YOLO-format .txt labels (optional)
├── runs/
│   └── car_detect/        # Output model weights and logs
└── car_detection.ipynb    # Google Colab Notebook

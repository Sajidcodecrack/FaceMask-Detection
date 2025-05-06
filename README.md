# 🧪😷 Chemical Equipment & Face Mask Recognition (YOLOv8 | 91% Accuracy)

Ensuring safety and compliance in laboratories, industrial zones, and healthcare settings is vital. This AI-powered system leverages **YOLOv8**, a cutting-edge object detection model, to detect chemical equipment and ensure **face mask compliance** in real-time.

---

## 🔍 Project Overview

This solution identifies:
- ✅ **Chemical Equipment**: Detects safety gear, lab tools, hazardous containers, and chemical instruments.
- ✅ **Face Mask Compliance**: Detects presence and correct usage of face masks in real-world environments.

---

## 🚀 Key Features

- ✔ **High Accuracy (91%+)**  
  Achieved using data augmentation, class balancing, and transfer learning on a curated dataset.

- ✔ **Real-Time Detection**  
  Fast, low-latency inference using **OpenCV** and **YOLOv8** for instant results.

- ✔ **Edge AI & IoT Ready**  
  Compatible with **Raspberry Pi**, **Jetson Nano**, and cloud-based systems.

- ✔ **Smart Alerts & Reports**  
  Non-compliance triggers alerts and logs with timestamped reports.

- ✔ **Scalable & Customizable**  
  Easily adaptable to industries such as manufacturing, research labs, hospitals, and chemical plants.

---

## 🎯 Why This Solution?

- 🔹 **YOLOv8 Optimized**  
  Fine-tuned model for industrial-grade performance.

- 🔹 **Field-Tested System**  
  Successfully deployed in a microprocessor-based vision system with **91%+ detection accuracy**.

- 🔹 **Lightweight & Fast**  
  Optimized for both **edge** and **cloud** deployments.

- 🔹 **Easy Integration**  
  REST API and plug-in ready for **security systems**, **dashboards**, and **monitoring tools**.

---

## 🛠️ Tech Stack

- **YOLOv8 (Ultralytics)**
- **Python**
- **OpenCV**
- **PyTorch**
- **Raspberry Pi / Jetson Nano**
- **Flask / FastAPI (for API Integration)**

---

## 📁 Directory Structure

```bash
chemical-mask-detection/
│
├── dataset/                   # Annotated images in YOLO format
├── models/                    # Trained YOLOv8 weights
├── scripts/
│   ├── detect.py              # Real-time detection script
│   ├── train.py               # YOLOv8 training script
│   └── utils.py               # Helper functions
├── app/
│   ├── api.py                 # Flask or FastAPI backend
│   └── alerts.py              # Notification system
├── requirements.txt
├── README.md
└── yolov8_config.yaml         # YOLOv8 training configuration

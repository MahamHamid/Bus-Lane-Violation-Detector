# Bus Lane Violation Detector using MobileNetV2

## Overview

This project presents a deep learning solution for detecting unauthorized vehicles in dedicated bus lanes using transfer learning with MobileNetV2.

The model classifies road images into two categories:

- ✅ Bus Lane Compliant
- 🚫 Bus Lane Violation

The complete pipeline includes:

- Dataset preparation
- Image preprocessing
- Transfer learning
- Model training
- Performance evaluation
- TensorFlow Lite model export for mobile deployment

---

## Features

- Transfer Learning using MobileNetV2
- Binary image classification
- Data augmentation
- Early stopping
- Model checkpointing
- Performance visualization
- Confusion matrix
- TensorFlow Lite conversion
- Mobile deployment ready

---

## Technologies Used

- Python
- TensorFlow / Keras
- MobileNetV2
- NumPy
- Pandas
- OpenCV
- Matplotlib
- Scikit-learn
- TensorFlow Lite
- Google Colab

---

## Dataset

This project uses the Vehicle Detection Image Set from Kaggle.

The notebook automatically downloads the dataset using the Kaggle API.

> **Note:** Configure your Kaggle API credentials before running the notebook.

---

## Project Workflow

```
Dataset
      │
      ▼
Image Preprocessing
      │
      ▼
Train / Validation Split
      │
      ▼
Transfer Learning (MobileNetV2)
      │
      ▼
Model Training
      │
      ▼
Evaluation
      │
      ▼
TensorFlow Lite Conversion
      │
      ▼
Mobile Deployment
```

---

## Results

The project evaluates the model using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- Training & Validation Curves

(Add your screenshots here.)

---

## Repository Structure

```
Bus-Lane-Violation-Detector/
│
├── README.md
├── requirements.txt
├── Bus_Lane_Violation_Detector_MobileNetV2.ipynb
├── screenshots/
└── images/
```

---

## Installation

Clone the repository

```bash
git clone https://github.com/yourusername/Bus-Lane-Violation-Detector.git
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

## Running the Project

Open

```
Bus_Lane_Violation_Detector_MobileNetV2.ipynb
```

Run all notebook cells sequentially.

---

## Future Improvements

- Real-time object detection
- YOLO-based vehicle localization
- Lane detection integration
- Multi-class vehicle classification
- Live CCTV inference
- Web application deployment

---

## License

This project is released under the MIT License.

---

## Author

**Maham Hamid**

Computational Finance Graduate

PGD Data Science & AI

GitHub: https://github.com/yourusername

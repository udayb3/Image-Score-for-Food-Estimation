# Image Score for Food Estimation

This repository contains notebooks and code of the project in the Digital Image Processing course for analyzing food images with two primary focuses:

- **Blur Estimation**: Detecting image quality issues using perceptual blur metrics.
- **Marker Detection**: Training a CNN to identify presence of visual markers in food images.

---

## Directory Structure
```
Image-Score-for-Food-Estimation
├── blur-estimation
│   └── blurDetection.ipynb
├── marker-detection
│   ├── dataset_creation.ipynb
│   └── marker_detection_final.ipynb
├── README.md
└── requirements.txt
```

## Project Overview

### Blur Estimation
- Here, We estimated the blur using an approximate version of the CPBD (Cumulative Probability of Blur Detection) method.
- Blur degrades visibility of food items, impairing recognition and counting.

### Marker Detection
- For this task, We first created a synthetic dataset and then used it for training a CNN attached with feed-forward network which classifies the images into 2 classes:
  - 0: Images without marker.
  - 1: Images with colored markers under varying lighting conditions.

## Installation & Setup

Clone the repository:

```bash
git clone https://github.com/udayb3/Image-Score-for-Food-Estimation.git
cd Image-Score-for-Food-Estimation
```
Install dependencies:
```bash
  pip install -r requirements.txt
```

## License

This project is intended for academic and non-commercial use.

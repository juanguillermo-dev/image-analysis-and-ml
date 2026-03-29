# Image Analysis and Machine Learning

A collection of Jupyter notebooks covering image processing fundamentals and deep learning applied to computer vision, developed across two semesters of an Image Analysis course.

## Overview

The work is split into two parts. The first part (Talleres 1–5) covers classical image processing techniques. The second part (Talleres 6–9 and the final project) applies deep learning models — including transfer learning and custom CNNs — to real-world image classification and object detection tasks.

## Tech Stack

| | |
|---|---|
| Language | Python 3 |
| Notebooks | Jupyter |
| Deep Learning | TensorFlow / Keras, PyTorch (YOLOv8) |
| Computer Vision | OpenCV, NumPy, Matplotlib |
| Models | ResNet50, VGG, custom CNN, YOLOv8 |

## Project Structure

```
image-analysis-and-ml/
├── Talleres/                       # Part 1 — Classical image processing
│   ├── Taller 1/                   # Basic operations, arithmetic, quantization
│   ├── Taller 2/                   # Filtering and transformations
│   ├── Taller 3/                   # Frequency domain analysis
│   ├── Taller 4/                   # Morphological operations
│   └── Taller 5/                   # Segmentation and synthesis
├── Talleres P2/                    # Part 2 — Deep learning
│   ├── Taller 6/                   # Binary image classification (Alien vs Predator)
│   ├── Taller 7/                   # Sign language recognition (ASL dataset)
│   ├── Taller 8/                   # Multi-class classification (Drone vs Bird)
│   └── Taller 9/                   # COVID-19 X-ray classification
└── Proyecto/                       # Final project — Object detection with YOLOv8
    └── proyecto_final/
        └── runs/detect/train/      # Training results & metrics
```

## Highlights

### Classical Processing (Part 1)
- Arithmetic operations, histogram equalization, and quantization
- Linear and non-linear spatial filters
- Fourier transforms and frequency-domain filtering
- Morphological operations (erosion, dilation, opening, closing)
- Image segmentation techniques and synthesis

### Deep Learning (Part 2)

| Taller | Task | Approach |
|--------|------|----------|
| 6 | Binary classification | Custom CNN (Alien vs Predator) |
| 7 | Sign language recognition | Transfer learning on ASL dataset |
| 8 | Drone vs Bird detection | ResNet50, VGG, custom CNN |
| 9 | Medical image classification | COVID-19 X-ray detection |

### Final Project — YOLOv8 Object Detection
Fine-tuned a YOLOv8 model for a custom object detection task. Training results, metrics (precision, recall, mAP), and configuration are stored in `runs/detect/train/`.

## Notes

- Trained model files (`.h5`, `.keras`, `.pt`) are excluded from this repository due to their size
- Image datasets are not included — sources are noted in each notebook
- Each notebook is self-contained with its own data loading, training, and evaluation cells

## Course

Image Analysis — Universidad de los Andes
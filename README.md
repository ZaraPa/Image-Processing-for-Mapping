# 🦜 Animal Figure Detection in Complex Backgrounds
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/<your-username>/<repo-name>/blob/main/BirdsProject.ipynb)
![Python](https://img.shields.io/badge/Python-3.9-blue)
![PyTorch](https://img.shields.io/badge/PyTorch-Instance%20Segmentation-red)
![Colab](https://img.shields.io/badge/Run%20on-Google%20Colab-yellow)

---

### 🎯 Overview
This project explores **instance segmentation with Mask R-CNN** to detect and segment animals (specifically parrots) in visually complex environments — such as cages, branches, and rope structures.  
It demonstrates **transfer learning**, **data augmentation**, and **fine-tuning** on a small custom dataset.

The work was done as part of the *Image Processing for Mapping Purposes (0148555)* final project, extending state-of-the-art deep learning methods for real-world image segmentation.

---

### 🧠 Key Features
- **Instance segmentation** using Mask R-CNN (ResNet-50 backbone)
- **Transfer learning** from COCO pre-trained weights
- **Custom Birds dataset** with JSON annotations
- **Data augmentation** (random flips, scaling)
- **Evaluation** with Intersection-over-Union (IoU) and visual results
- **Visualization utilities** for masks, bounding boxes, and overlays

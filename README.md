# Residual Dense Network (RDN) for Image Super-Resolution

This project implements a **Residual Dense Network (RDN)** for enhancing low-resolution  to high-resolution images using deep learning.

---

## Project Overview

Super-resolution is the process of reconstructing high-quality images from low-resolution inputs.  
In this project, we use **RDN**, a deep convolutional neural network that combines:

- Residual learning
- Dense connections
- Feature fusion

to achieve better image reconstruction compared to traditional models like SRCNN.

---

## Model Architecture

The RDN consists of:

- Residual Dense Blocks (RDBs)
- Local feature fusion
- Global feature fusion
- PixelShuffle upsampling

### Key idea:
Instead of learning directly from input images, RDN learns **residual features + dense feature extraction**, which improves fine detail recovery.

---

## Dataset

- Medical CT scan images (kidney stones)
- Grayscale images (TIFF format)
- Resolution:
  - Low-resolution: 64×64
  - High-resolution: 128×128

---

## Requirements


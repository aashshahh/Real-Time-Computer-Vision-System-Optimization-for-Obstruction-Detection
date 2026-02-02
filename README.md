# Real-Time Computer Vision System Optimization for Obstruction Detection

## Overview
This project focuses on optimizing and benchmarking convolutional neural network (CNN) architectures for **road obstruction detection** under clear and obstructed conditions. The work evaluates baseline performance, robustness under visual noise, and the impact of automated data augmentation strategies, with an emphasis on real-time applicability.

The project was completed as part of a graduate-level Computer Vision / Machine Learning course and reflects an end-to-end experimental ML workflow.

---

## Problem Statement
Reliable road obstruction detection is critical for autonomous driving and intelligent transportation systems. Visual obstructions, motion blur, and environmental noise can significantly degrade model performance.

This project investigates:
- How different CNN architectures perform under obstruction
- Whether automated augmentation (RandAugment) improves robustness
- Trade-offs between accuracy and model complexity for real-time use

---

## Models Evaluated
The following architectures were implemented, trained, and evaluated:

- **ResNet18**
- **ResNet50**
- **MobileNetV2**
- **EfficientNetB0**

Each model was evaluated under:
- Clear conditions  
- Obstructed conditions  
- Augmented training regimes  

---

## Key Experiments
- Baseline CNN training and evaluation  
- Clear vs obstructed performance comparison  
- RandAugment-based data augmentation experiments  
- Cross-model performance visualization and analysis  

---

## Tech Stack
- **Python**
- **PyTorch**
- **Torchvision**
- **OpenCV**
- **NumPy / Pandas**
- **Matplotlib**
- **Jupyter Notebook**

---

## Repository Structure
- `notebooks/`
  - `baselines/` – Baseline training notebooks
  - `augmentation/` – RandAugment experiment notebooks
  - `analysis/` – Comparison/plots notebook(s)
  - `demo/` – Demo notebook(s)
- `results/`
  - `figures/` – Output plots and result images
  - `videos/` – Demo videos (if included)

## How to Run
1. Create an environment and install dependencies:
   ```bash
   pip install -r requirements.txt

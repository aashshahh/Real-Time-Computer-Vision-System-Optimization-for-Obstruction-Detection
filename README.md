# Real-Time Computer Vision System Optimization for Obstruction Detection

## Overview
This repository contains experiments comparing multiple CNN architectures for road obstruction detection under clear vs obstructed conditions. It includes baseline training runs, augmentation experiments (RandAugment), analysis notebooks, and result visualizations.

## Models Evaluated
- ResNet18
- ResNet50
- MobileNetV2
- EfficientNetB0

## Experiments Included
- Baseline model training and evaluation
- Clear vs obstructed comparison
- RandAugment variants
- Result visualization and demo notebook(s)

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

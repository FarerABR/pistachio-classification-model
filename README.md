# Pistachio Classification Model

This repository contains experiments and saved artifacts for pistachio image classification using multiple deep learning approaches.

## What is in this repository

- **Notebook-based training workflows** for different model families:
  - `pistachio_v2.ipynb` (baseline CNN workflow)
  - `custom-vit.ipynb` and `small-ViT/small-ViT.ipynb` (Vision Transformer variants)
  - `Swin/Swin.ipynb` (Swin Transformer)
  - `BiT/BiT.ipynb` and `BiT/torch-bit.ipynb` (BiT in Keras and PyTorch)
- **Saved model artifacts** in `.keras` and `.pth` formats (for example under `models/BiT/` and `BiT/`).

## Project focus

The project compares different computer vision architectures for classifying pistachio images and preserves both experimentation notebooks and trained model outputs.

## Repository layout

- `BiT/` - BiT model notebooks and related exported models
- `Swin/` - Swin Transformer notebook
- `small-ViT/` - compact ViT notebook
- `models/` - trained model files
- root notebooks (`pistachio_v2.ipynb`, `custom-vit.ipynb`) - additional experiments

## Notes

- Notebooks reference a local dataset directory (for example `pistachio-edited`) that is not included in this repository.
- This repository is primarily for experimentation and model artifacts rather than a packaged Python library.

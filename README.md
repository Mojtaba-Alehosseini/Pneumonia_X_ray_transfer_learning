# Pneumonia Detection from Chest X-Rays (Transfer Learning)

Deep-learning image classification that detects pneumonia from chest X-ray images using transfer learning with several pretrained CNN backbones.

## Approach

- Binary classification: NORMAL vs. PNEUMONIA chest X-rays
- Transfer learning with multiple architectures compared: `VGG`, `ResNet`, and `NASNet`
- Image preprocessing and augmentation to improve generalization on limited medical data

## What's inside

- Notebook(s) implementing the data pipeline, transfer-learning models, training, and evaluation

## Dataset

Chest X-ray (pneumonia) image dataset, organised into NORMAL and PNEUMONIA classes. The images are not included in this repository; see the public Kaggle 'Chest X-Ray Images (Pneumonia)' dataset.

## Note

Built as a learning project on medical-image classification; it is a research/education exercise and not a clinical tool.

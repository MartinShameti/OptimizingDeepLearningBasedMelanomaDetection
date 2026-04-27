# OptimizingDeepLearningBasedMelanomaDetection

This repository contains the source code, experiments, and results for an improved deep learning framework for melanoma detection using dermoscopic images.

The study extends previous work by applying a structured optimization pipeline across multiple experiments (E00–E06), followed by external testing on Albanian clinical images and localized model training.

# Project Objective

The main goal of this research is to improve melanoma classification performance, model robustness, and experimental reliability using evidence-based deep learning techniques.

The work focuses on:
- Hyperparameter optimization
- Class imbalance handling
- Data augmentation
- Fine-tuning depth analysis
- CNN architecture comparison
- Threshold optimization
- External validation on Albanian images
- Localized Albanian-only training/testing
- CPU performance benchmarking

# Dataset

## Primary Dataset
**ISIC 2020 Challenge Dataset**
Used for training and evaluation of experiments E00–E06.

Dataset source:
https://challenge.isic-archive.com/

## External Dataset

A local Albanian dermoscopic image dataset was used for:

- External testing of the best model
- Localized train/test experiments

Due to privacy restrictions, Albanian images are not publicly included.

# Repository Structure

```text
Melanoma_Optimization_Study/
│
├── E00_hyperparameter_tuning.ipynb
├── E01_resnet50_baseline.ipynb
├── E02_class_imbalance.ipynb
├── E03_augmentation_overfitting.ipynb
├── E04_finetuning_depth.ipynb
├── E05_architecture_comparison.ipynb
├── E06_threshold_optimization.ipynb
│
├── Albanian_external_testing.ipynb
├── Albanian_local_training.ipynb
├── Core_Performance_Test.ipynb
│
├── requirements.txt
├── README.md
└── results/

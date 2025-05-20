# Sequence Learning for Transliteration 

## Overview
This code base is for part-A of the assignment(graded portion). This project implements and compares various sequence-to-sequence models (RNN, GRU, LSTM) with and without attention mechanisms for transliteration tasks. The implementation includes model training, hyperparameter sweeps, visualization tools, and prediction analysis.

## Report Links
[![W&B Report](https://img.shields.io/badge/Weights_&_Biases-Report_Link-blue)](https://wandb.ai/mm21b010-indian-institute-of-technology-madras/dakshina-transliteration/reports/Assignment-3-Exploring-Sequence-learning-problems-in-deep-learning-and-the-attention-mechanism--VmlldzoxMjg2NzY0MQ)

## Key Components

### 1. Main Notebook (`explain.ipynb`)
Contains all implementation code with detailed comments:
- **Model Architectures**:
  - Basic RNN/GRU/LSTM implementations
  - Attention mechanism implementation
- **Training Pipeline**:
  - Data preprocessing
  - Training loops
  - Model validation
- **Analysis Tools**:
  - Hyperparameter sweeps using W&B
  - Attention heatmap visualizations
  - Interactive prediction explorers

### 2. Best Models
Saved PyTorch state dicts for optimal configurations:
- Trained on full dataset
- Selected based on validation metrics
- Includes both baseline and attention variants

### 3. Prediction Files
Test set outputs for all models:
- **Without Attention**:
  - Raw predictions
  - Accuracy metrics
- **With Attention**:
  - Predictions with attention weights
  - Comparative metrics

## Usage Instructions

### Running the Code
```bash
jupyter notebook explain.ipynb

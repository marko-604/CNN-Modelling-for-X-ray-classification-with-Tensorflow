# CNN-Modelling-for-X-ray-classification-with-Tensorflow

This repository contains a deep learning model using **ResNet50** to classify colorectal cancer images. The model is trained on a structured dataset with **data augmentation** and **feature extraction**.
---
## Features
- **ResNet50 Backbone**: Pre-trained model for feature extraction.
- **t-SNE Visualization**: Reduces CNN feature embeddings for visualization.
- **GPU Optimization**: Configured TensorFlow for GPU acceleration.
- **Dataset Augmentation**: Improves generalization with rotation, zoom, flips, etc.
- **Small Dataset Mode**: Quickly test model behaviour with a smaller dataset.
---

## Installation

### Prerequisites

Ensure you have Python 3.8+ installed. Then install dependencies using:

```bash
pip install -r requirements.txt

## Running the Model

To train the CNN, run:

python train.py

# Music Genre Classification 🎶

This project classifies music genres using deep learning.

## 🚀 Setup

```bash
pip install -r requirements.txt
```

## 🛠️ Steps
1. Download and extract dataset from Dropbox.
2. Open and run `notebooks/genre_classification.ipynb` to train the model.



## 🧠 Model Overview

- Preprocessing:
  - Audio trimmed and converted into Mel Spectrograms
  - Spectrograms resized for CNN input

- Model:
  - Convolutional Neural Network (CNN) with batch normalization and dropout
  - Trained using categorical cross-entropy
  - Optimized with Adam optimizer

- Evaluation:
  - Accuracy and loss visualizations
  - Confusion matrix
  - Sample prediction visualizations



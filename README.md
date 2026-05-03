# Fashion Image Classifier

A deep learning image classifier built with TensorFlow and Keras that identifies clothing categories from real-world fashion images using a multi-layer CNN architecture.

## Overview

This project trains a Convolutional Neural Network (CNN) to classify fashion images into 5 clothing categories: hoodies, hoodies-female, longsleeve, shirt, and sweatshirt. The model is trained on the [Zalando Store Crawl dataset](https://www.kaggle.com/datasets/dqmonn/zalando-store-crawl) from Kaggle.

## Model Architecture

- 5 Convolutional layers with ReLU activation and Max Pooling
- Dropout regularization to reduce overfitting
- Fully connected Dense layers
- Adam optimizer with Sparse Categorical Crossentropy loss

## Technologies Used

- Python
- TensorFlow / Keras
- OpenCV
- NumPy
- Matplotlib
- scikit-learn
- Pillow

## Getting Started

### Prerequisites

Install the required dependencies:

```bash
pip install -r requirements.txt
```

### Dataset

The dataset is downloaded automatically from Kaggle inside the notebook. You'll need a Kaggle API key (`kaggle.json`) to run it.

### Running the Project

Open the notebook in Google Colab or Jupyter and run all cells:

```bash
jupyter notebook notebook.ipynb
```

## Results

The model classifies clothing images across 5 categories with predictions visualized using Matplotlib.

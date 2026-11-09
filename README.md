# 🐱🐶 Pet Face Classification using CNN

A deep learning project that uses a Convolutional Neural Network (CNN) built with TensorFlow and Keras to classify pet images into two categories: cats and dogs.

## 📌 Overview

This project explores image classification using deep learning. It implements a CNN that learns visual features from images and performs binary classification.

The project covers dataset loading, image preprocessing, CNN architecture development, model training, and visualization of training and validation accuracy.

## ✨ Features

- Image dataset loading using TensorFlow.
- 80:20 training and validation split.
- Image resizing to 150 × 150 pixels.
- Pixel normalization (0–1).
- Custom CNN architecture using Keras.
- Binary classification using a sigmoid output layer.
- Training and validation accuracy visualization.

## 🛠️ Technologies Used

- Python
- TensorFlow
- Keras
- Matplotlib

## 🧠 Model Architecture

The CNN consists of:

1. Convolutional layer (32 filters, 3 × 3 kernel)
2. Max Pooling layer
3. Convolutional layer (64 filters, 3 × 3 kernel)
4. Max Pooling layer
5. Flatten layer
6. Dense layer (128 neurons, ReLU activation)
7. Output layer (1 neuron, Sigmoid activation)

**Model configuration:**
- Optimizer: Adam
- Loss Function: Binary Crossentropy
- Metric: Accuracy
- Training Epochs: 5
- Batch Size: 32

## 📂 Dataset Structure

The dataset should be organized into two class folders:

```text
dataset/
├── cat/
│   ├── image1.jpg
│   ├── image2.jpg
│   └── ...
│
└── dog/
    ├── image1.jpg
    ├── image2.jpg
    └── ...
```

The dataset is loaded using TensorFlow's `image_dataset_from_directory()` utility.

**Note:** The dataset is not included in this repository.

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/mansimransehgal/pet-face-classification-cnn.git
```

### 2. Navigate to the project directory

```bash
cd pet-face-classification-cnn
```

### 3. Install dependencies

```bash
pip install tensorflow matplotlib
```

### 4. Prepare the dataset

Place your cat and dog image folders inside the `dataset/` directory.

### 5. Run the project

```bash
python Project2-PetFaceClassification-CNN.py
```

**Note:** Update the dataset path in the Python script to match your local dataset location before running.

## 📊 Training Visualization

The project plots training and validation accuracy across five epochs to observe model learning and validation performance.

## 📚 Learning Outcomes

- Understanding Convolutional Neural Networks.
- Image preprocessing and normalization.
- Binary image classification.
- Building and training models using TensorFlow and Keras.
- Understanding training and validation accuracy.

## 🔮 Future Improvements

- Improve model accuracy through hyperparameter tuning.
- Experiment with data augmentation.
- Add model evaluation using precision, recall and F1-score.
- Save and load trained models.
- Implement predictions on unseen images.
- Explore deployment through a web application.

## 👩‍💻 Author

**Mansimran Sehgal**

B.E. Computer Science Engineering  
Specialization: Artificial Intelligence & Machine Learning

- GitHub: [@mansimransehgal](https://github.com/mansimransehgal)
- LinkedIn: [Mansimran Sehgal](https://www.linkedin.com/in/mansimran-sehgal/)

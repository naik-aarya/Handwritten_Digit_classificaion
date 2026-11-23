# Handwritten Digit Classification Using CNN

## 1. Project Overview

This project focuses on recognizing and classifying handwritten digits (0–9) using a Convolutional Neural Network (CNN), a Deep Learning algorithm.

The CNN model learns patterns and features from handwritten digit images and predicts the corresponding numerical digit.

The objective is to develop an image classification model that can accurately recognize handwritten digits.

## 2. Problem Statement

Handwritten digit recognition is an important application of computer vision and deep learning.

Different individuals write digits in different styles, shapes, and sizes, making automatic recognition challenging.

This project uses a Convolutional Neural Network (CNN) to automatically extract image features and classify handwritten digits into one of ten classes (0–9).

## 3. Objectives

- Load and understand the handwritten digit dataset.
- Perform image preprocessing and normalization.
- Visualize handwritten digit images.
- Build a Convolutional Neural Network (CNN).
- Train the CNN model on handwritten digit images.
- Evaluate model performance.
- Predict handwritten digits from input images.

## 4. Dataset Description

The project uses the MNIST handwritten digit dataset.

**Dataset Information:**

- Training Images: 60,000
- Testing Images: 10,000
- Image Dimensions: 28 × 28 pixels
- Color Format: Grayscale
- Number of Classes: 10 (digits 0–9)

Each image represents a handwritten digit, and its corresponding label identifies the actual digit.

## 5. Technologies and Libraries Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- TensorFlow
- Keras
- Scikit-learn

## 6. Deep Learning Algorithm

### Convolutional Neural Network (CNN)

CNN is a Deep Learning architecture commonly used for image classification and computer vision tasks.

It automatically extracts important visual features from images using convolution and pooling operations.

**CNN Architecture Components:**

- Input Layer: Accepts 28 × 28 grayscale images.
- Convolutional Layer: Extracts important image features.
- ReLU Activation: Introduces non-linearity.
- Max Pooling Layer: Reduces spatial dimensions.
- Flatten Layer: Converts feature maps into a one-dimensional vector.
- Dense Layer: Learns classification patterns.
- Output Layer: Predicts one of the ten digit classes.

## 7. Project Workflow

1. Dataset Loading
2. Data Exploration
3. Image Visualization
4. Image Preprocessing
5. Image Normalization
6. CNN Model Architecture Development
7. Model Compilation
8. Model Training
9. Model Evaluation
10. Handwritten Digit Prediction

## 8. Model Evaluation

The CNN model can be evaluated using:

- Accuracy
- Loss
- Confusion Matrix
- Classification Report

These evaluation metrics help measure the model's performance in classifying handwritten digits.

## 9. Applications

- Automatic cheque processing.
- Postal code recognition.
- Bank document digit recognition.
- Automated form processing.
- Number recognition in digital documents.
- Optical Character Recognition (OCR) systems.

## 10. Project Structure

```text
Handwritten-Digit-Classification-Using-CNN/
│
├── README.md
├── requirements.txt
├── main.py
└── images/
    ├── sample_digits.png
    ├── accuracy_plot.png
    └── loss_plot.png
```

## 11. Installation and Execution

### Step 1: Clone the repository

```bash
git clone https://github.com/naik-aarya/Handwritten-Digit-Classification-Using-CNN.git
```

### Step 2: Navigate to the project directory

```bash
cd Handwritten-Digit-Classification-Using-CNN
```

### Step 3: Install dependencies

```bash
pip install -r requirements.txt
```

### Step 4: Run the Python file

```bash
python main.py
```

## 12. Conclusion

This project demonstrates the application of Convolutional Neural Networks (CNN) for handwritten digit recognition.

The model learns important visual features from handwritten digit images and classifies them into ten numerical categories (0–9).

This project provides practical experience in Deep Learning, image preprocessing, CNN architecture development, and image classification.

---

**Author:** Aarya Naik

**GitHub:** https://github.com/naik-aarya

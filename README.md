# Tree_Species_Identification
# 🌳 Tree Species Classification using CNN

This project uses a Convolutional Neural Network (CNN) to classify tree species from leaf or tree images. It is trained on a dataset with 31 different species and built using TensorFlow and Keras in Google Colab.

---

## 📌 Problem Statement

Accurately identifying tree species from images is challenging due to:
- High inter-species visual similarity,
- Varying angles, lighting conditions, and backgrounds,
- The requirement for expert human knowledge in traditional methods.

This project aims to automate the classification process using deep learning and computer vision.

---

## 🎯 Project Goal

To build a deep learning model that classifies tree species from images with good accuracy, using a CNN trained on a labeled dataset of 31 classes.

---

## 🧠 Learning Objectives

- Understand how CNNs work for image classification tasks.
- Implement data preprocessing and augmentation.
- Train and evaluate deep learning models using TensorFlow.
- Visualize model performance over training epochs.

---

## 🛠️ Tools & Technologies

- Python 🐍
- Google Colab 💻
- TensorFlow & Keras 🤖
- Matplotlib 📊
- Google Drive (for dataset storage) 📁

---

## 🗃️ Dataset

- **Source**: [Custom Google Drive Folder]
- **Structure**: 31 folders, one for each tree species.
- **Images**: RGB, resized to 224x224 for training.

---

## 🏗️ Methodology

1. Data loaded using `ImageDataGenerator` with augmentation.
2. CNN model built with multiple `Conv2D` and `MaxPooling2D` layers.
3. Model compiled using Adam optimizer and categorical cross-entropy loss.
4. Trained over 10 epochs with validation split.
5. Accuracy and loss visualized using Matplotlib.

---

## 📈 Model Performance

- **Training Accuracy**: Up to ~25%
- **Validation Accuracy**: Up to ~29%
- Result is promising for 31-class classification on a small dataset.

---

## 📸 Sample Output

![Accuracy Plot](path-to-saved-accuracy-plot.png)

---

## 🗂️ File Structure


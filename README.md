# 🍎 Deep Learning-Based Fruit Image Classification

### *Teaching machines to see, classify, and understand visual patterns.*

---

## 🚀 Overview

This project explores **image classification using deep learning**, comparing how different architectures perform on visual data.

Two models were implemented:

* A **Multi-Layer Perceptron (MLP)**
* A **Convolutional Neural Network (CNN)**

> The goal: understand how model architecture impacts performance when dealing with images.

---

## 🎯 Objective

* Classify fruit images into multiple categories
* Compare **MLP vs CNN performance**
* Analyze how well each model captures visual features

---

## 🧬 Approach

### 🔹 1. Data Preprocessing

* Image normalization
* Resizing and formatting
* Efficient input pipeline using TensorFlow

---

### 🔹 2. Model Architectures

#### 🧠 MLP (Baseline Model)

* Fully connected layers
* Treats images as flattened vectors
* Limited ability to capture spatial relationships

---

#### 🧠 CNN (Advanced Model)

* Convolutional + pooling layers
* Learns **spatial hierarchies and patterns**
* Better suited for image data

---

### 🔹 3. Training & Evaluation

* Trained both models on the same dataset
* Evaluated using:

  * Accuracy
  * Loss curves
  * Confusion matrix

---

## 📊 Results & Insights

* CNN significantly outperformed MLP
* MLP struggled due to lack of spatial awareness
* CNN effectively captured:

  * edges
  * textures
  * shapes

> 📌 Key Insight:
> **Architecture matters more than complexity when dealing with image data.**

---

## ⚙️ Tech Stack

* 🐍 Python
* 🔥 TensorFlow / Keras
* 📊 NumPy, Matplotlib
* 🧠 Deep Learning (MLP, CNN)

---

## 🧠 Why this matters

Images aren’t just numbers — they contain **spatial structure**.

This project demonstrates how:

* Traditional neural networks fall short
* CNNs leverage spatial patterns to achieve better accuracy

---

## 🚀 Future Improvements

* Use **transfer learning (ResNet, VGG)**
* Apply **data augmentation**
* Deploy as a **real-time image classifier**

---

## ✨ Takeaway

This project highlights the importance of choosing the **right architecture for the right problem**, and how CNNs revolutionize image-based tasks by learning spatial features effectively.

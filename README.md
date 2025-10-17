<!-- 🖼️ Banner -->
![Cat vs Dog Classifier Banner](assets/banner.png)

# 🐱🐶 Cat vs Dog Image Classifier using CNN

A deep learning project built with **TensorFlow** and **Keras**, designed to classify images of **cats** and **dogs** with high accuracy.  
Developed and trained entirely in **Google Colab**.

---

## 📦 Dataset

The dataset used is the **“Cats vs Dogs Filtered”** dataset, available via TensorFlow’s public datasets.

- **Training Data:** 2000 images (1000 Cats, 1000 Dogs)  
- **Validation Data:** 1000 images (500 Cats, 500 Dogs)  
- **Test Data:** 50 unseen images (mixed cats and dogs)

Dataset is automatically downloaded and extracted using Python code.

---

## 🧠 Model Architecture

| Layer Type        | Details |
|--------------------|---------|
| **Conv2D** + ReLU | Feature extraction |
| **MaxPooling2D**  | Dimensionality reduction |
| **Conv2D** + ReLU | Deeper feature extraction |
| **MaxPooling2D**  | Reduce spatial size |
| **Flatten**        | Convert 2D → 1D |
| **Dense (512)** + ReLU | Fully connected layer |
| **Dense (1)** + Sigmoid | Output layer (Binary classification) |

The model uses **Binary Crossentropy** as loss and **Adam Optimizer** for training.

---

## ⚙️ Training Setup

- **Batch Size:** 32  
- **Epochs:** 20  
- **Image Size:** 150×150 pixels  
- **Augmentation:** Rescale, Rotation, Zoom, Horizontal Flip  

Training and validation were monitored over epochs for accuracy and loss trends.

---

## 📈 Visualizations

### 🔹 Training vs Validation Accuracy
![Training Accuracy](assets/training_accuracy.png)

### 🔹 Training vs Validation Loss
![Training Loss](assets/training_loss.png)

### 🔹 Confusion Matrix
![Confusion Matrix](assets/confusion_matrix.png)

---

## 🏆 Results Summary

| Metric | Description | Result |
|--------|--------------|--------|
| **Training Accuracy** | Model accuracy on training data | 96% |
| **Validation Accuracy** | Accuracy on unseen validation data | 93% |
| **Validation Loss** | Error rate | 0.21 |
| **F1 Score** | Balance between precision & recall | 0.92 |

---

## 📊 Results Visualization Gallery
<div align="center">

| Accuracy | Loss | Confusion Matrix |
|-----------|------|------------------|
| ![Accuracy](assets/training_accuracy.png) | ![Loss](assets/training_loss.png) | ![Confusion](assets/confusion_matrix.png) |

</div>

---

## 🚀 How to Run

1. Open the project in **Google Colab**.  
2. Run each cell sequentially.  
3. Model will automatically:
   - Download dataset  
   - Train CNN  
   - Evaluate model  
   - Display visualizations  

> 💡 You don’t need to run this on GitHub — it’s designed for **Colab execution only**.

---

## 👩‍💻 Author

**Javeria Munir**  
🔗 [GitHub Profile](https://github.com/javeriamunir-dev)

---

## 🖼️ Folder Structure

---

## ⭐ Support

If you like this project, consider giving it a **⭐ Star** on [GitHub](https://github.com/javeriamunir-dev/Cat-and-Dog-Image-Classifier)!

---

> 📌 *This project demonstrates end-to-end image classification using Convolutional Neural Networks (CNNs) — from dataset preprocessing to visualization and evaluation.*

---


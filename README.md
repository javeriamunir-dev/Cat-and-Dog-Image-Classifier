<!-- 🖼️ Banner Section -->
![Cat vs Dog Classifier Banner](assets/banner.png)

# 🐱🐶 Cat vs Dog Image Classifier using Convolutional Neural Network (CNN)

A **Deep Learning project** built in **Python (TensorFlow + Keras)** to classify images of **cats** and **dogs**.  
This notebook demonstrates the complete **machine learning pipeline** — from data preprocessing to CNN training, evaluation, and visualization — all inside **Google Colab**.

---

## 🚀 Project Highlights

| Feature | Description |
|----------|--------------|
| 🧠 **Model Type** | Convolutional Neural Network (CNN) |
| 📂 **Dataset** | TensorFlow Cats vs Dogs Filtered Dataset |
| 📊 **Visualization** | Accuracy, Loss, Confusion Matrix |
| 🧮 **Evaluation Metrics** | Accuracy, Loss, F1 Score |
| ☁️ **Platform** | Google Colab (Cloud-based) |
| 🎯 **Goal** | Classify cat 🐱 vs dog 🐶 images accurately |

---

## 📘 Overview

This project shows how **Convolutional Neural Networks** can automatically learn visual patterns from images to distinguish between two classes — cats and dogs.  
It includes data loading, preprocessing, model training, evaluation, and performance visualization.

---

## 🐾 Dataset Information

- **Dataset:** [Cats vs Dogs Filtered Dataset](https://storage.googleapis.com/mledu-datasets/cats_and_dogs_filtered.zip)  
- **Provided By:** TensorFlow  
- **Classes:** 2 → `cats` and `dogs`  
- **Images:** ~3,000 total  

The dataset is automatically downloaded and extracted in Colab into these folders:


---

## 🧠 Model Details

The **CNN (Convolutional Neural Network)** model is designed to identify important image features such as edges, shapes, and colors to differentiate between cats and dogs.

### Model Architecture
- 3 × Convolution + MaxPooling layers  
- 1 × Flatten layer  
- 1 × Dense layer (512 units, ReLU)  
- 1 × Output layer (Sigmoid activation)

**Loss Function:** Binary Crossentropy  
**Optimizer:** Adam  
**Metrics:** Accuracy  

---

## 🧮 Model Training and Validation

- **Epochs:** 20  
- **Batch Size:** 32  
- **Training Set:** ~2000 images  
- **Validation Set:** ~1000 images  

The model learns to generalize by minimizing the loss and maximizing accuracy over multiple epochs.

---

## 📈 Visualizations

### 🔹 Training vs Validation Accuracy
Shows model accuracy improvement over epochs.

![Training Accuracy](assets/training_accuracy.png)

---

### 🔹 Training vs Validation Loss
Displays loss reduction and convergence over time.

![Training Loss](assets/training_loss.png)

---

### 🔹 Confusion Matrix
Represents correct and incorrect predictions for each class.

![Confusion Matrix](assets/confusion_matrix.png)

---

## 🏆 Results Summary

| Metric | Description | Result |
|--------|--------------|--------|
| **Training Accuracy** | Accuracy on training data | 96% |
| **Validation Accuracy** | Accuracy on unseen validation data | 93% |
| **Validation Loss** | Error rate | 0.21 |
| **F1 Score** | Balance between precision & recall | 0.92 |

✅ The model achieved **over 93% validation accuracy**, effectively distinguishing between cat and dog images.

---

## 🧩 Key Learnings

- CNNs automatically learn image features without manual extraction.  
- Proper **data preprocessing** improves performance significantly.  
- Comparing **training vs validation curves** helps detect overfitting.  
- **Confusion matrix** gives insight into classification accuracy.  

---

## 🔮 Future Enhancements

- Use **Transfer Learning** (e.g., VGG16, ResNet50) for better accuracy.  
- Apply **Data Augmentation** to increase dataset diversity.  
- Add **Grad-CAM** visualization for interpretability.  
- Create a **Streamlit web app** for real-time image predictions.  

---

## 👩‍💻 Author

**Javeria Munir**  
💼 GitHub: [@javeriamunir-dev](https://github.com/javeriamunir-dev)  
📧 Email: javeriamunirbwn@email.com  

> 🧠 *Developed entirely on Google Colab*  
> ☁️ *A Deep Learning project for Computer Vision and Image Classification.*

---

⭐ *If you found this project interesting, please give it a star on GitHub!* ⭐


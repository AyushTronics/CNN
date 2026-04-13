# 📘 CNN Lab Assignment (Task 1–5)

## 📌 Overview
This project covers fundamental concepts of Convolutional Neural Networks (CNNs) using popular datasets like MNIST and CIFAR-10.  
It includes dataset exploration, visualization, CNN model building, training, evaluation, and interpretability using Grad-CAM.

---

## 📂 Datasets Used

### 1. MNIST Dataset
- Grayscale images of handwritten digits (0–9)
- Image size: 28 × 28
- Training samples: 60,000
- Test samples: 10,000

### 2. CIFAR-10 Dataset
- Colored images of 10 classes:
  airplane, automobile, bird, cat, deer, dog, frog, horse, ship, truck
- Image size: 32 × 32 × 3
- Training samples: 50,000
- Test samples: 10,000

---

# 🧪 Task 1: Dataset Exploration

### ✔️ Objectives
- Load datasets
- Analyze shapes, data types, and pixel ranges
- Study class distribution

### 🔍 Observations
- MNIST shape: (60000, 28, 28)
- CIFAR-10 shape: (50000, 32, 32, 3)
- Data type: uint8
- Pixel range: 0–255
- MNIST dataset is balanced (~6000 samples per class)

---

# 🖼️ Task 2: Data Visualization

### ✔️ Objectives
- Visualize random samples from datasets

### 🔍 Observations
- MNIST images are grayscale and simple
- CIFAR-10 images are complex and colored
- Visualization helps understand patterns and variability

---

# 🧠 Task 3: CNN Model Building & Training

### ✔️ Objectives
- Build CNN model using Conv2D, MaxPooling, Dense layers
- Train model on dataset

### ⚙️ Model Features
- Convolution layers for feature extraction
- Pooling layers for dimensionality reduction
- Fully connected layers for classification

### 🔍 Observations
- CNN performs well on MNIST (high accuracy)
- CIFAR-10 is more challenging due to complexity

---

# 📊 Task 4: Model Evaluation & Analysis

### ✔️ Objectives
- Evaluate model performance
- Generate confusion matrix
- Analyze predictions

### 🔍 Observations
- MNIST accuracy is high due to simple patterns
- CIFAR-10 shows some misclassifications
- Confusion matrix helps identify weak classes

---

# Task 5: Grad-CAM Visualization

### ✔️ Objectives
- Understand model decisions
- Highlight important regions in images

### 🔍 Observations
- Grad-CAM shows which parts of image influence prediction
- Helps in model interpretability
- Useful for debugging and trust in AI models

---

# 🛠️ Technologies Used
- Python  
- TensorFlow / Keras  
- NumPy  
- Matplotlib  

---

# ▶️ How to Run

1. Open the notebook in Google Colab / Jupyter  
2. Run all cells sequentially  
3. Datasets will download automatically  
4. Outputs (graphs, images, Grad-CAM) will be displayed  

---

# 📊 Outputs
- Dataset statistics  
- Sample visualizations  
- Model accuracy & loss graphs  
- Confusion matrix  
- Grad-CAM heatmaps  

---

# 🚀 Overall Conclusion

- CNNs are highly effective for image classification tasks  
- MNIST is easier and gives very high accuracy due to simple grayscale patterns  
- CIFAR-10 is more complex and requires deeper models for better performance  
- Visualization techniques like Grad-CAM improve model interpretability  
- Understanding data before training is crucial for better model design  

This assignment builds a strong foundation in:
- Computer Vision  
- Deep Learning  
- CNN architectures  
- Model evaluation & explainability  

---

# 📌 Future Improvements
- Use deeper architectures (ResNet, VGG)
- Apply data augmentation
- Tune hyperparameters
- Improve CIFAR-10 accuracy

---


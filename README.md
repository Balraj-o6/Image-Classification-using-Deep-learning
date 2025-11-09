# 🧠 Image Classification Using Deep Learning (CIFAR-10 Dataset)

This project demonstrates an end-to-end implementation of an **image classification model** using **Convolutional Neural Networks (CNNs)** trained on the **CIFAR-10 dataset**, along with a **Flask web interface** for real-time predictions.

---

## 🚀 Project Overview

The goal of this project is to build and deploy an AI model capable of classifying images of common objects such as **airplanes, cars, birds, cats, dogs, ships**, and more.  
It combines **deep learning (TensorFlow/Keras)** and **web development (Flask)** to create an interactive user interface for testing the model.

---

## 🧩 Features

- 📊 Trains a Convolutional Neural Network (CNN) from scratch using the CIFAR-10 dataset  
- 🧠 Achieves ~70% accuracy after training and optimization  
- 🌐 Web interface using Flask for easy user interaction  
- 🖼️ Upload any image to get its predicted class  
- 🧮 Visualizes accuracy and loss during training  

---

## 🧠 Dataset: CIFAR-10

- **Total Images:** 60,000  
- **Classes:** 10 (airplane, automobile, bird, cat, deer, dog, frog, horse, ship, truck)  
- **Image Size:** 32x32 pixels  
- **Train/Test Split:** 50,000 / 10,000  

---

## 🏗️ Project Architecture

1. **Data Loading & Preprocessing**
   - Normalized pixel values between 0 and 1  
   - One-hot encoded labels  
2. **Model Construction**
   - Built a CNN with 3 convolutional blocks  
   - Used ReLU activations and MaxPooling layers  
3. **Model Training**
   - Optimizer: Adam  
   - Loss: Sparse Categorical Crossentropy  
   - Epochs: 10  
4. **Model Evaluation**
   - Tested model accuracy and validation loss  
5. **Deployment**
   - Integrated the model into a Flask/Streamlit web app  

---

## 🧰 Tech Stack

| Component | Technology Used |
|------------|----------------|
| Programming Language | Python |
| Deep Learning Framework | TensorFlow, Keras |
| Web Framework | Flask |
| Dataset | CIFAR-10 |
| Environment | Google Colab / Jupyter |
| Visualization | Matplotlib, Seaborn |

---



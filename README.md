# MNIST Digit Classifier

A simple deep learning project using **TensorFlow/Keras** to classify handwritten digits (0–9) from the popular **MNIST dataset**.  

---

## 📊 Dataset
- **MNIST** contains 70,000 grayscale images of handwritten digits.  
  - 60,000 training images  
  - 10,000 test images  
- Each image is **28×28 pixels** (flattened to 784 features).  

---

## 🏗️ Model Architecture
The model is a **fully connected neural network** with the following layers:

- `Flatten` layer (28×28 → 784)  
- `Dense` layer with 128 neurons, ReLU activation  
- `Dense` layer with 50 neurons, ReLU activation  
- `Dense` output layer with 10 neurons, Softmax activation  

---
## MODEL ACCURACY 
97%

## ⚙️ Requirements
Install dependencies with:

```bash
pip install tensorflow numpy matplotlib seaborn scikit-learn

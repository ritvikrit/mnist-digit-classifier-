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
The model achieved ~97% accuracy on the MNIST test dataset.

Below is the confusion matrix showing how well the model performed across all digit classes (0–9):

<img width="1058" height="607" alt="image" src="https://github.com/user-attachments/assets/38c75f7e-a465-47ce-9221-6911a24b72bd" />


## ⚙️ Requirements
Install dependencies with:

```bash
pip install tensorflow numpy matplotlib seaborn scikit-learn

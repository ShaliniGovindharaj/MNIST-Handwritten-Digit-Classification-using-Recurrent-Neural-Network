# MNIST Handwritten Digit Classification Using RNN

##  Project Overview

This project implements a **Recurrent Neural Network (RNN)** to classify handwritten digits from the **MNIST dataset**. Instead of using a CNN, each image is treated as a **sequence**, allowing the RNN to learn patterns row‑by‑row.

The complete implementation is available in a Jupyter Notebook.

---

## Objectives

* Understand digit classification using RNNs
* Learn how images can be treated as sequences
* Build and train an RNN model using TensorFlow/Keras
* Evaluate model performance on test data

---

##  Key Concepts Covered

* Loading the MNIST dataset
* Image preprocessing and normalization
* Reshaping images into sequential format
* Building an RNN model
* Training and evaluating the network
* Visualizing accuracy and loss

---

##  Dataset Description

The **MNIST dataset** consists of grayscale handwritten digit images:

* **60,000** training images
* **10,000** test images
* Image size: **28 × 28 pixels**
* Digit classes: **0 to 9**

---

##  Model Architecture

Each 28×28 image is reshaped into a sequence of **28 time steps**, with **28 pixel values per step**.

The RNN model includes:

* **Input Sequence Layer** – pixel rows as sequences
* **Recurrent Layer** (SimpleRNN / LSTM / GRU)
* **Dense Output Layer** – softmax activation for digit prediction

This approach allows the RNN to learn spatial relationships along image rows.

---

##  Training & Evaluation

* **Optimizer:** Adam
* **Loss Function:** Categorical Crossentropy
* **Metric:** Accuracy

Steps include training on the training set and evaluating accuracy on the test set. Training curves are plotted for performance analysis.

---

##  Results

* Training and validation accuracy trends
* Final test accuracy
* Optional visualization of predictions vs actual labels

These results show how effectively an RNN can classify handwritten digits.

---

##  Dependencies

Install required libraries using:

```bash
pip install tensorflow numpy matplotlib jupyter
```

---

##  References

* MNIST Dataset
* Recurrent Neural Networks (RNN)
* TensorFlow & Keras Documentation

---



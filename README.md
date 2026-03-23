# Deep Learning Case Studies and Labs 🧠

This repository contains various Deep Learning case studies and lab experiments, covering fundamental concepts to practical applications using Python, NumPy, and TensorFlow/Keras.

## 📁 Repository Structure

### 🔬 Labs
Introductory notebooks focusing on the basics of Deep Learning environments and tensor operations.
- `DLE_LAB_1.ipynb`: Introduction to TensorFlow, basic tensor operations, and data types.
- `DLE_LAB_2.ipynb` & `DLE_LAB_3.ipynb`: Further explorations and exercises in Deep Learning fundamentals and environment setups.

### 📚 Case Studies

#### Case Study 1: MNIST Digit Classification
- **File:** `Case Study 1/MNIST_CASE_STUDY .ipynb`
- **Description:** A from-scratch implementation of a Feed-Forward Neural Network to classify handwritten digits from the MNIST dataset.
- **Highlights:**
  - Implemented using core `numpy` (no deep learning frameworks used for building the network layer).
  - Custom implementations of Activation functions (ReLU, Softmax), Forward Propagation, Cross-Entropy Loss, and Backpropagation.

#### Case Study 2: Image Classification on CIFAR-10
- **File:** `Case Study 2/CNN_based_Image_Classification_on_CIFAR_10.ipynb`
- **Description:** Building a Convolutional Neural Network (CNN) to classify images across 10 classes using the CIFAR-10 dataset.
- **Highlights:**
  - Implemented using `TensorFlow` and `Keras`.
  - Includes robust Data Augmentation using `ImageDataGenerator` (rotation, shifts, flips, zooms).
  - Visualization of accuracy and loss metrics across epochs.

#### Case Study 3: Binary Image Classification (Cats vs. Dogs)
- **File:** `Case Study 3/code.ipynb`
- **Description:** A deeper Convolutional Neural Network built with Data Augmentation to classify images into two categories.
- **Highlights:**
  - Designed a multi-block CNN architecture with Dropout layers to prevent overfitting.
  - Implements `EarlyStopping` callback for efficient training and best weight restoration.
  - Validation tracking and comprehensive graphical performance evaluation.

## 🛠️ Technologies Used
- **Python** 🐍
- **NumPy** (for mathematical operations and building neural layers from scratch)
- **TensorFlow & Keras** (for building, training, and augmenting complex models)
- **Matplotlib** (for plotting loss, accuracy metrics, and visual demonstrations)
- **Scikit-learn** (for dataset loading, splitting, and encoding)

## 🚀 Getting Started
1. Ensure you have Python installed.
2. Install the required dependencies:
   ```bash
   pip install numpy tensorflow matplotlib scikit-learn
   ```
3. Launch Jupyter Notebook or Jupyter Lab to interact with and run the `.ipynb` files!

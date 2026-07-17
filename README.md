# 👕 Fashion MNIST Image Classification using Convolutional Neural Network (CNN)

A Deep Learning project that uses a **Convolutional Neural Network (CNN)** built with **TensorFlow/Keras** to classify grayscale images of clothing items from the **Fashion MNIST** dataset. The model learns to recognize different categories of apparel with high accuracy.

---

# 📌 Project Overview

Fashion MNIST is a popular benchmark dataset that replaces the original MNIST handwritten digits with images of fashion products. This project demonstrates how CNNs can effectively extract image features and perform accurate image classification.

The project includes:

* Loading the Fashion MNIST dataset
* Data preprocessing and normalization
* Visualizing sample images
* Building a CNN model
* Training and validating the model
* Evaluating model performance
* Making predictions on unseen images

---

# 📂 Project Structure

```
CNN-Fashion-MNIST/
│
├── main.ipynb          # Complete project notebook
├── README.md           # Project documentation
```

---

# 📊 Dataset

**Dataset:** Fashion MNIST

The dataset contains **70,000 grayscale images** of fashion products.

* **Training Images:** 60,000
* **Test Images:** 10,000
* **Image Size:** 28 × 28 pixels
* **Number of Classes:** 10

### Classes

| Label | Category      |
| ----: | ------------- |
|     0 | T-shirt / Top |
|     1 | Trouser       |
|     2 | Pullover      |
|     3 | Dress         |
|     4 | Coat          |
|     5 | Sandal        |
|     6 | Shirt         |
|     7 | Sneaker       |
|     8 | Bag           |
|     9 | Ankle Boot    |

Dataset can be loaded directly using TensorFlow:

```python
from tensorflow.keras.datasets import fashion_mnist
```

---

# 🛠️ Technologies Used

* Python
* TensorFlow
* Keras
* NumPy
* Matplotlib
* Jupyter Notebook

---

# 🧠 CNN Architecture

The model consists of:

* Convolutional Layers
* ReLU Activation
* Max Pooling Layers
* Flatten Layer
* Fully Connected (Dense) Layers
* Softmax Output Layer

Architecture Flow:

```
Input Image (28×28×1)

↓

Conv2D + ReLU

↓

MaxPooling2D

↓

Conv2D + ReLU

↓

MaxPooling2D

↓

Flatten

↓

Dense + ReLU

↓

Dropout

↓

Dense (10) + Softmax
```

---

# 🚀 How to Run

### Clone the repository

```bash
git clone https://github.com/Harshal-bhaisare/CNN-MNIST.git
```

### Navigate to the project folder

```bash
cd CNN-MNIST
```

### Install dependencies

```bash
pip install tensorflow numpy matplotlib jupyter
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

Open **main.ipynb** and run all cells.

---

# 📈 Model Performance

The CNN model achieves high classification accuracy on the Fashion MNIST test dataset.

Typical performance:

* **Training Accuracy:** ~92–95%
* **Test Accuracy:** ~90–93%

> *Results may vary depending on the model architecture and training parameters.*

---

# 📊 Features

* Image preprocessing and normalization
* Fashion MNIST visualization
* CNN model implementation
* Model training and validation
* Performance evaluation
* Prediction on test images
* Visualization of predicted labels

---

# 📚 Concepts Covered

* Deep Learning
* Convolutional Neural Networks (CNN)
* Computer Vision
* Image Classification
* Feature Extraction
* Pooling
* Softmax Classification
* Model Evaluation

---

# 🎯 Learning Outcomes

Through this project, I learned:

* How CNNs process image data
* Building image classification models using TensorFlow/Keras
* Training and evaluating deep learning models
* Visualizing datasets and predictions
* Improving image classification performance using convolutional layers

---

# 👨‍💻 Author

**Harshal Bhaisare**

Aspiring Machine Learning & Deep Learning Engineer

* GitHub: https://github.com/Harshal-bhaisare

---

# ⭐ Support

If you found this project useful, consider giving the repository a **⭐ Star**. It helps others discover the project and supports my learning journey in Machine Learning and Deep Learning.

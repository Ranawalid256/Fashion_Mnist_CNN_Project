# 🧵 Fashion-MNIST CNN Classification

This repository contains a complete implementation of a Convolutional Neural Network (CNN) applied to the Fashion-MNIST dataset using two deep learning frameworks:

PyTorch

Keras (TensorFlow)


The project compares the training process, evaluation results, and learning behavior between the two libraries.


---

# 📌 Overview

Builds a CNN for image classification

Implements two versions: PyTorch and Keras

Includes training, validation, evaluation, and accuracy/loss visualization

Code is optimized for Google Colab and supports GPU

Clean, commented, and easy to understand for students and beginners



---

# 📂 Project Structure

│
├── Keras_vs_pytorch.ipynb     # PyTorch implementation and Keras implementation
└── README.md


---

#🧪 Dataset: Fashion-MNIST

Fashion-MNIST contains 70,000 grayscale images (28×28) of clothing items across 10 categories:

T-shirt/top

Trouser

Pullover

Dress

Coat

Sandal

Shirt

Sneaker

Bag

Ankle boot



---

#🚀 How to Use

1. Install Dependencies

pip install torch torchvision torchaudio tensorflow matplotlib numpy

2. Open the Notebook

Upload the .ipynb file to Google Colab or Jupyter Notebook.

3. Run All Cells

The model will train, evaluate, and display accuracy & loss graphs automatically.


---

#📊 Results

Both models achieve:

Strong classification accuracy

Stable convergence

Clear visualization for:

Training Loss

Validation Loss

Training Accuracy

Validation Accuracy



The graphs help analyze overfitting and performance differences between PyTorch & Keras.


---

#🧠 Model Architectures

PyTorch Model

Conv2D → ReLU

MaxPooling

Conv2D → ReLU

MaxPooling

Fully Connected (128)

Dropout

Output layer (10 classes)


Keras Model

Equivalent model using Sequential()

Same preprocessing/normalization

Direct visualization through history



---

👩‍💻 Author

Rana Walid
3rd-year Intelligent Systems Student
Alexandria National University
AI • Deep Learning • Quantum Computing Enthusiast


---

⭐ Acknowledgements

Fashion-MNIST by Zalando Research

PyTorch, TensorFlow, and Keras teams for their frameworks

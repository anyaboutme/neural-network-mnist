# neural-network-mnist
# 🧠 Neural Networks Project  
## Handwritten Digit Recognition using MLP (MNIST) - PyTorch

---

# 📌 Problem Description
This project implements a Neural Network (Multilayer Perceptron - MLP) to classify handwritten digits from the MNIST dataset (0–9).  
The goal is to compare different activation functions and hidden layer sizes to improve performance.

---

# 📊 Dataset
The dataset used is MNIST, a standard dataset for handwritten digit recognition.

- 60,000 training images
- 10,000 testing images
- Each image is 28x28 grayscale

### Dataset Link:
http://yann.lecun.com/exdb/mnist/

or PyTorch built-in dataset:
https://pytorch.org/vision/stable/datasets.html

---

# ⚙️ Model Architecture
The model is a Multilayer Perceptron (MLP):

- Input Layer (28x28 flattened)
- One Hidden Layer (128 or 256 neurons)
- Activation Function (ReLU / Tanh / Sigmoid)
- Dropout (0.2)
- Output Layer (10 classes)

---

# 🚀 Experiments Conducted
Two experiments were performed:

### Experiment 1
- Activation: ReLU
- Hidden Neurons: 128
- Learning Rate: 0.001

### Experiment 2
- Activation: Tanh
- Hidden Neurons: 256
- Learning Rate: 0.001

---

# 📊 Results Comparison

| Experiment | Hidden Neurons | Test Accuracy | Test Loss |
|------------|---------------|---------------|-----------|
| ReLU Model | 128 | 97.63% | 0.0781 |
| Tanh Model | 256 | 97.12% | 0.0866 |

---

# 📈 Visualizations
The following graphs are included:
- Training vs Validation Loss
- Training vs Validation Accuracy

---

# 🧪 Evaluation Metrics
- Accuracy
- Loss

---

# 🛠️ How to Run the Project

## 1. Install requirements
```bash
pip install torch torchvision matplotlib numpy pandas

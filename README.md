# Historical CNN vs Modern CNN on MNIST

This project compares a historical LeCun-style convolutional neural network with a modern Keras CNN architecture using the MNIST handwritten digit dataset. The goal is to understand how early CNN designs differ from contemporary approaches in terms of accuracy, training behavior, and architectural complexity.

---

## 📂 Project Contents

| File | Description |
|------|-------------|
| `lecun_vs_collet_cnn.ipynb` | Main notebook containing both CNN implementations, training, evaluation, and comparison |
| `README.md` | Project documentation and overview |

---

## 🧠 Overview

This project implements and evaluates two CNN architectures:

### **1. LeCun-style CNN (Historical)**
- Inspired by LeNet-5 (1989)
- Uses `tanh` activations  
- Average pooling  
- Shallow architecture  
- Trained with SGD + momentum  

### **2. Modern Keras CNN**
- Uses ReLU activations  
- Max pooling  
- Dropout regularization  
- Adam optimizer  
- Deeper dense layers  

The notebook trains both models on MNIST and compares:

- Training accuracy  
- Validation accuracy  
- Loss curves  
- Final test accuracy  
- Training time  

---

## 📊 Dataset

**MNIST Handwritten Digits**

- 60,000 training images  
- 10,000 test images  
- 28×28 grayscale  
- Normalized to `[0, 1]`  
- Reshaped to `(28, 28, 1)` for CNN input  

---

## 🚀 Running the Notebook

### 1. Clone the repository
```bash
git clone https://github.com/1994Simba/historical-cnn-mnist.git
# Historical CNN vs Modern CNN on MNIST

This project compares a historical LeCun-style convolutional neural network with a modern Keras CNN architecture using the MNIST handwritten digit dataset. The goal is to understand how early CNN designs differ from contemporary approaches in terms of accuracy, training behavior, and architectural complexity.

---

## 📂 Project Contents

| File | Description |
|------|-------------|
| `lecun_vs_collet_cnn.ipynb` | Main notebook containing both CNN implementations, training, evaluation, and comparison |
| `README.md` | Project documentation and overview |

---

## 🧠 Overview

This project implements and evaluates two CNN architectures:

### **1. LeCun-style CNN (Historical)**
- Inspired by LeNet-5 (1989)
- Uses `tanh` activations  
- Average pooling  
- Shallow architecture  
- Trained with SGD + momentum  

### **2. Modern Keras CNN**
- Uses ReLU activations  
- Max pooling  
- Dropout regularization  
- Adam optimizer  
- Deeper dense layers  

The notebook trains both models on MNIST and compares:

- Training accuracy  
- Validation accuracy  
- Loss curves  
- Final test accuracy  
- Training time  

---

## 📊 Dataset

**MNIST Handwritten Digits**

- 60,000 training images  
- 10,000 test images  
- 28×28 grayscale  
- Normalized to `[0, 1]`  
- Reshaped to `(28, 28, 1)` for CNN input  

---

## 🚀 Running the Notebook

### 1. Clone the repository
```bash
git clone https://github.com/1994Simba/historical-cnn-mnist.git
cd historical-cnn-mnist
```

### 2. Install dependencies
```bash
pip install tensorflow numpy matplotlib jupyter
```

### 3. Launch Jupyter Notebook
```bash
jupyter notebook
```

Open `lecun_vs_collet_cnn.ipynb` and run all cells.

---

## 📈 Results Summary

Typical outcomes:

- Modern CNN achieves slightly higher accuracy (~99.1–99.3%)
- LeCun-style CNN performs strongly but slightly lower (~98.7–99.0%)
- Modern CNN trains faster due to ReLU + Adam

The notebook includes:

- Accuracy curves  
- Loss curves  
- Side‑by‑side comparison table  

---

## 📚 References

- LeCun, Y. et al. (1989). *Backpropagation Applied to Handwritten Zip Code Recognition.*  
- Collet, F. (2021). *Deep Learning with Python.*  
- MNIST dataset: http://yann.lecun.com/exdb/mnist/

---

## 📄 License

MIT License

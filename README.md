# 🧠 MNIST Handwritten Digit Classification

<div align="center">

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Deep Learning](https://img.shields.io/badge/Deep%20Learning-Neural%20Network-purple.svg)
![ML](https://img.shields.io/badge/Machine%20Learning-Classification-green.svg)
![License](https://img.shields.io/badge/License-MIT-blue.svg)

**Handwritten digit classification using the MNIST dataset**

</div>

---

## 📌 Project Overview

This project implements a **machine learning model** to classify handwritten digits (0–9) using the **MNIST dataset**.  
MNIST is a standard benchmark dataset widely used to evaluate classification algorithms in machine learning and deep learning.

The project demonstrates the **end-to-end ML workflow**, from data loading and preprocessing to model training and evaluation.

---

## 🎯 Problem Statement

Given a grayscale image of a handwritten digit (28×28 pixels), predict the correct digit (0–9).

---

## 📊 Dataset

- **Dataset Name:** MNIST Handwritten Digits
- **Total Samples:** 70,000
  - Training: 60,000
  - Testing: 10,000
- **Classes:** 10 (digits 0–9)
- **Image Size:** 28 × 28 pixels

---

## 🛠️ Tech Stack

- Python 3.8+
- NumPy
- Pandas
- Matplotlib
- Scikit-Learn
- TensorFlow / Keras *(if used)*
- Jupyter Notebook

---

## 🔄 Machine Learning Workflow

1. Load MNIST dataset
2. Data preprocessing and normalization
3. Flatten image data
4. Train classification model
5. Evaluate accuracy on test data
6. Predict unseen handwritten digits

---

## 🚀 How to Run

```bash
git clone https://github.com/Ashwinder0186/mnist-digit-classification.git
cd mnist-digit-classification
pip install -r requirements.txt
jupyter notebook mnist.ipynb
```

---

## 📁 Project Structure

```
mnist-digit-classification/
│
├── mnist.ipynb
├── README.md
└── requirements.txt
```

---

## 📈 Model Performance

- **Accuracy:** ~97% – 99% (depending on model)
- Strong performance due to clean and well-labeled dataset
- Suitable for demonstrating classification fundamentals

---

## 🔮 Future Enhancements

- Convolutional Neural Network (CNN)
- Hyperparameter tuning
- Model comparison
- Web app deployment using Flask/FastAPI

---

## 📝 License

MIT License

---

## 👨‍💻 Author

**Ashwinder Singh**  
MS in Computer Science, University of Texas at Arlington  
GitHub: https://github.com/Ashwinder0186

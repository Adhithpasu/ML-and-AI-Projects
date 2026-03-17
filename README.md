# 🤖 ML & AI Projects

> A curated collection of machine learning and artificial intelligence projects spanning deep learning, computer vision, regression modeling, and sequence prediction — built to learn, experiment, and contribute to the broader ML community.

[![Python](https://img.shields.io/badge/Python-3.8%2B-3776AB?logo=python&logoColor=white)](https://python.org)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-FF6F00?logo=tensorflow&logoColor=white)](https://tensorflow.org)
[![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white)](https://pytorch.org)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter&logoColor=white)](https://jupyter.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-22C55E.svg)](LICENSE)

---

## 👤 About

Hi, I'm **Adhithya Pasumarthi** — a Python programmer and researcher specializing in AI, machine learning, full-stack web development, and algorithms. This repository is a hands-on portfolio of ML projects I've built to deepen my understanding of the field and to serve as a practical resource for others getting into AI.

The projects here are directly connected to my peer-reviewed research published in the **Journal of Computer Science and Technology Studies (JCSTS)**, which systematically compares Vision Transformers (ViTs) and Convolutional Neural Networks (CNNs) for image recognition tasks. The code in this repository — especially the Digit Recognition project — represents the practical foundation that motivates and supports that research.

📄 **Published Research:**
> **Comparing Vision Transformers and Convolutional Neural Networks: A Systematic Analysis**
> *Chandrasekar Adhithya Harsha Pasumarthi*
> Journal of Computer Science and Technology Studies, Vol. 8(2), pp. 19–26, 2026
> DOI: [10.32996/jcsts.2026.8.2.3](https://doi.org/10.32996/jcsts.2026.8.2.3)
> **[Read the Full Paper →](https://al-kindipublisher.com/index.php/jcsts/article/view/11991)**

🔗 **LinkedIn:** [chandrasekar-adhithya-pasumarthi](https://www.linkedin.com/in/chandrasekar-adhithya-pasumarthi-0320a329b)

---

## 📁 Projects

### 🔢 Digit Recognition
**[`/DigitRecognition`](./DigitRecognition)**

A Convolutional Neural Network (CNN) trained on the MNIST dataset to classify handwritten digits (0–9) with high accuracy.

- **Model:** CNN with convolutional, pooling, and fully connected layers
- **Dataset:** MNIST — 70,000 grayscale 28×28 images
- **Accuracy:** ~99%+
- **Tech:** Python, TensorFlow/Keras, NumPy, Matplotlib

> 🔬 **Research Connection:** This project is the CNN side of the central comparison in my published paper, *Comparing Vision Transformers and Convolutional Neural Networks: A Systematic Analysis*. The paper argues that CNNs excel at learning local spatial features through convolutional filters and inductive biases like translation invariance — properties that make them powerful on structured, grid-like data such as handwritten digits. This project is a working demonstration of exactly that: a CNN trained end-to-end on raw pixel data, learning hierarchical features from edges to curves to complete digit shapes without any manual feature engineering. It serves as the concrete, reproducible baseline against which the ViT architectures in the paper are compared.

---

### 🔁 LSTM with PyTorch & Lightning
**[`/LSTM Pytorch and Lightning`](./LSTM%20Pytorch%20and%20Lightning)**

Long Short-Term Memory (LSTM) models for sequence modeling and time-series prediction, implemented in both native PyTorch and PyTorch Lightning for clean, scalable training loops.

- Temporal dependency modeling with gated recurrent units
- PyTorch Lightning for structured, reproducible training
- **Tech:** Python, PyTorch, PyTorch Lightning, NumPy, Matplotlib

> 🔬 **Research Connection:** The paper's comparison of CNNs and Vision Transformers is fundamentally about *how different architectures handle context and dependencies* — CNNs use local receptive fields while ViTs use global self-attention. LSTMs address the same challenge in the time domain: modeling long-range dependencies in sequential data. Understanding LSTMs and attention mechanisms provides the conceptual grounding for understanding *why* Transformers are now being applied to vision tasks, which is the core question the paper investigates.

---

### 📐 Nonlinear Regression
**[`/NonLinearReg`](./NonLinearReg)**

Exploration of nonlinear regression for modeling complex, curved relationships that linear models cannot capture.

- Polynomial and kernel-based regression techniques
- Comparison of fit quality, residuals, and generalization
- **Tech:** Python, scikit-learn, PyTorch, NumPy, Matplotlib

> 🔬 **Research Connection:** The paper's systematic analysis is built on the idea that different model families have different inductive biases — CNNs assume local structure, ViTs assume global relationships. Nonlinear regression makes the same point at a smaller scale: the choice of model family fundamentally shapes what patterns can be learned. This project provides the mathematical intuition behind that argument.

---

### 🏠 Predicting House Prices
**[`/PredictingHousePrices`](./PredictingHousePrices)**

A supervised regression model that predicts house prices from structured features like size, location, and number of rooms.

- Feature engineering, exploratory data analysis, model evaluation (RMSE, R²)
- **Tech:** Python, pandas, scikit-learn, Matplotlib, seaborn

---

### 🧠 Predicting Student Stress Levels
**[`/PredictingStudentStressLevels`](./PredictingStudentStressLevels)**

A classification model that predicts student stress levels based on academic and behavioral features.

- Multi-class classification with model interpretability analysis
- **Tech:** Python, pandas, scikit-learn, seaborn

---

### 📊 Logistic Regression
**[`/LogisticReg`](./LogisticReg)**

From-scratch and library-based implementations of logistic regression for binary classification problems.

- Gradient descent, sigmoid activation, decision boundary visualization
- **Tech:** Python, NumPy, scikit-learn, Matplotlib

---

### 📈 Univariate & Multivariable Linear Regression
**[`/UniVariateLinear`](./UniVariateLinear) · [`/MultiVariableLinearReg`](./MultiVariableLinearReg)**

Foundational regression models covering single and multi-feature prediction tasks.

- Cost function minimization, gradient descent, vectorized implementations
- **Tech:** Python, NumPy, Matplotlib, scikit-learn

---

### 🧰 Library Fundamentals
**[`/Introduction to Numpy`](./Introduction%20to%20Numpy) · [`/Introduction to Pandas`](./Introduction%20to%20Pandas) · [`/Introduction to Pytorch`](./Introduction%20to%20Pytorch) · [`/Matplotlib and Seaborn`](./Matplotlib%20and%20Seaborn)**

Reference notebooks covering the core ML/data science libraries every practitioner needs.

- NumPy arrays, broadcasting, linear algebra operations
- Pandas DataFrames, data wrangling, and aggregation
- PyTorch tensors, autograd, and neural network basics
- Matplotlib and Seaborn visualization techniques
- **Tech:** Python, NumPy, Pandas, PyTorch, Matplotlib, Seaborn

---

## 📚 Published Research

### Comparing Vision Transformers and Convolutional Neural Networks: A Systematic Analysis

**Journal of Computer Science and Technology Studies (JCSTS)**
*Al-Kindi Centre for Research and Development, London, UK*
*Volume 8, Issue 2 · Pages 19–26 · Published January 28, 2026*
*Licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)*

**[📄 Read the Full Paper →](https://al-kindipublisher.com/index.php/jcsts/article/view/11991)**

This paper presents a systematic analysis of two dominant paradigms in computer vision: Convolutional Neural Networks (CNNs) and Vision Transformers (ViTs). Key contributions include:

- A structured comparison of CNN inductive biases (locality, translation invariance) vs. ViT global self-attention mechanisms
- Empirical evaluation of both architectures across benchmark image classification tasks
- Analysis of data efficiency, scalability, and generalization tradeoffs between the two approaches
- Practical guidance on when to use CNNs vs. ViTs depending on dataset size and task complexity

#### 🗺️ How the Projects Connect to the Research

| Project | Connection to the Paper |
|---|---|
| **Digit Recognition** | The CNN baseline — a hands-on implementation of the convolutional architecture at the heart of the paper's comparison. Demonstrates local feature learning, translation invariance, and the inductive biases the paper analyzes. |
| **LSTM Pytorch & Lightning** | Provides the conceptual bridge to Transformers — attention and sequential context modeling in LSTMs mirror the self-attention mechanism that makes ViTs work, grounding the paper's architecture comparison. |
| **Nonlinear Regression** | Illustrates the broader principle underlying the paper: that model architecture shapes what can be learned. Different inductive biases → different capabilities. |
| **Logistic / Linear Regression** | Classical baselines that contextualize the paper's performance benchmarks and frame the leap from traditional ML to deep learning architectures. |
| **Predicting House Prices / Student Stress** | Applied ML on real-world structured data, showing the full landscape of ML the paper situates CNN and ViT comparisons within. |

> **The research in one sentence:** CNNs and Vision Transformers are two different answers to the same question — *how should a model learn to see?* CNNs look locally and build up, ViTs look globally from the start. The Digit Recognition project shows the CNN answer working in practice; the paper asks which answer wins, and when.

---

## 📖 Citation

If you reference this work or the associated research paper, please cite:

```bibtex
@article{pasumarthi2026vit,
  title   = {Comparing Vision Transformers and Convolutional Neural Networks: A Systematic Analysis},
  author  = {Chandrasekar Adhithya Harsha Pasumarthi},
  journal = {Journal of Computer Science and Technology Studies},
  volume  = {8},
  number  = {2},
  pages   = {19--26},
  year    = {2026},
  doi     = {10.32996/jcsts.2026.8.2.3}
}
```

---

## 🛠️ Tech Stack

| Category | Tools |
|---|---|
| **Languages** | Python 3.8+ |
| **Deep Learning** | TensorFlow, Keras, PyTorch, PyTorch Lightning |
| **Classical ML** | scikit-learn |
| **Data & Visualization** | NumPy, pandas, Matplotlib, Seaborn |
| **Computer Vision** | OpenCV, PIL |
| **Environment** | Google Colab, VS Code, Jupyter Notebook |

---

## 🚀 Getting Started

### Prerequisites
```bash
Python 3.8+
pip or conda
```

### Clone & Install
```bash
git clone https://github.com/Adhithpasu/ML-and-AI-Projects.git
cd ML-and-AI-Projects
pip install -r requirements.txt
```

### Run Any Project
Open the relevant folder in **VS Code** or **Google Colab** and launch the `.ipynb` notebook. Each project is fully self-contained.

```bash
# Example: Digit Recognition
cd DigitRecognition
jupyter notebook
```

---

## 📂 Repository Structure

```
ML-and-AI-Projects/
│
├── DigitRecognition/               # ⭐ CNN classifier — core research paper implementation
├── LSTM Pytorch and Lightning/     # LSTM sequence models (PyTorch + Lightning)
├── NonLinearReg/                   # Nonlinear regression experiments
├── LogisticReg/                    # Logistic regression from scratch & via sklearn
├── MultiVariableLinearReg/         # Multivariable linear regression
├── UniVariateLinear/               # Univariate linear regression
├── PredictingHousePrices/          # House price prediction
├── PredictingStudentStressLevels/  # Student stress level classification
├── Introduction to Numpy/          # NumPy reference notebook
├── Introduction to Pandas/         # Pandas reference notebook
├── Introduction to Pytorch/        # PyTorch fundamentals notebook
├── Matplotlib and Seaborn/         # Data visualization reference
│
└── README.md
```

---

## 🤝 Contributing

Found a bug or want to extend a project? Contributions are welcome!

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/your-idea`
3. Commit your changes: `git commit -m "Add your feature"`
4. Push and open a Pull Request

---

## 📬 Contact

**Adhithya Pasumarthi**

- 🐙 GitHub: [@Adhithpasu](https://github.com/Adhithpasu)
- 💼 LinkedIn: [chandrasekar-adhithya-pasumarthi](https://www.linkedin.com/in/chandrasekar-adhithya-pasumarthi-0320a329b)
- 📄 Research: [JCSTS — Vol. 8(2), 2026](https://al-kindipublisher.com/index.php/jcsts/article/view/11991)

---

## 📜 License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

---

<div align="center">
  <sub>Built with curiosity, gradient descent, and a lot of Colab runtime reconnects. ⚡</sub>
</div>

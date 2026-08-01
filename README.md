# Machine Learning from Scratch

A collection of machine learning algorithms and data preprocessing techniques implemented from scratch using Python and NumPy.

This repository brings together several independent projects developed to understand the mathematical foundations, internal mechanics, and practical applications of machine learning algorithms without relying on pre-built machine learning models.

## Projects

### 1. ML Preprocessing from Scratch

Repository: [from-scratch-ml-preprocessing](https://github.com/Fidan6557/from-scratch-ml-preprocessing)

From-scratch implementations of core machine learning preprocessing techniques with leakage-safe case studies on the Titanic and California Housing datasets.

Main topics:

- Missing value handling
- Feature scaling
- Categorical encoding
- Data preprocessing workflows
- Leakage-safe train and test processing
- Titanic classification case study
- California Housing regression case study
- Automated testing with Pytest

### 2. Supervised Learning from Scratch

Repository: [supervised-learning-from-scratch](https://github.com/Fidan6557/supervised-learning-from-scratch)

From-scratch implementations of fundamental supervised learning algorithms with automated tests and reproducible experiments.

Main topics:

- Linear Regression
- Regularization
- Logistic Regression
- Naive Bayes
- Bag-of-Words text features
- Classification and regression
- Model evaluation
- Reproducible experiments
- Automated testing

### 3. K-Nearest Neighbors from Scratch

Repository: [knn-from-scratch-titanic](https://github.com/Fidan6557/knn-from-scratch-titanic)

A from-scratch implementation of the K-Nearest Neighbors algorithm applied to Titanic survival prediction.

Main topics:

- Distance calculation
- Nearest-neighbor search
- KNN classification
- Data preprocessing
- Titanic survival prediction
- Model evaluation

## Technologies

- Python
- NumPy
- Scikit-learn
- Jupyter Notebook
- Pytest
- Git
- GitHub

## Repository Structure

```text
machine-learning-from-scratch/
├── from-scratch-ml-preprocessing/
├── knn-from-scratch-titanic/
├── supervised-learning/
├── .gitmodules
└── README.md
```

Each project is maintained as an independent GitHub repository and included in this collection as a Git submodule.

## Clone the Repository

To clone the main repository together with all submodules, run:

```bash
git clone --recurse-submodules https://github.com/Fidan6557/machine-learning-from-scratch.git
```

To enter the repository:

```bash
cd machine-learning-from-scratch
```

If the main repository has already been cloned without its submodules, run:

```bash
git submodule update --init --recursive
```

## Project Goals

The main goals of this collection are to:

- Understand the mathematical logic behind machine learning algorithms
- Implement preprocessing and learning algorithms from scratch
- Practice clean and modular Python development
- Build reproducible machine learning experiments
- Validate implementations using automated tests
- Apply algorithms to real-world datasets

## Author

**Fidan Baghirova**

AI and Machine Learning student interested in machine learning, deep learning, computer vision, and practical artificial intelligence applications.

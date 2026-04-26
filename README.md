# CIFAR-10 Image Classification with PyTorch

**Project 2** from the [Udacity PyTorch Nanodegree](https://www.udacity.com/course/deep-learning-pytorch--ud188)

A convolutional neural network built from scratch to classify images from the **CIFAR-10** dataset (10 classes: airplane, automobile, bird, cat, deer, dog, frog, horse, ship, truck).

## 🎯 Project Goal
Build and train a deep learning model capable of accurately classifying small color images. The final model achieved strong performance through careful architecture design, data augmentation, and training optimizations.

## 🛠️ Technologies Used
- **PyTorch**
- Python 3
- Matplotlib / Seaborn (visualizations)
- Jupyter Notebook

## Key Features & Techniques
- Custom CNN architecture
- Data augmentation (random flips, crops, normalization)
- Training with GPU support
- Learning rate scheduling
- Early stopping
- Comprehensive evaluation (accuracy, confusion matrix, sample predictions)
- Helper utilities for training loops and visualization

## 📊 Results
- **Final Test Accuracy**: in the mid 60s
`

## 📁 Project Structure
U_py_nano_project_2/
├── CIFAR10_Final.ipynb          ← Main notebook
├── CIFAR10_Final.html           ← Exported HTML version
├── helper.py                    ← Training & utility functions
├── workouts/                    ← Experimentation notebooks
├── URL reference list.txt
└── README.md

## 🚀 How to Run
```bash
git clone https://github.com/rolly9992/U_py_nano_project_2.git
cd U_py_nano_project_2

# Recommended: use the HTML version for quick viewing
open CIFAR10_Final.html
Or open CIFAR10_Final.ipynb in Jupyter Notebook / JupyterLab / VS Code.
📝 What I Learned

Importance of data augmentation for small image datasets
How to design effective CNN architectures
Proper training loop management and regularization techniques
Debugging and improving model performance iteratively

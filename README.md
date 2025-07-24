# Fashion MNIST Classifier with TensorFlow

This project uses a Convolutional Neural Network (CNN) built with TensorFlow and Keras to classify clothing images from the [Fashion MNIST dataset](https://github.com/zalandoresearch/fashion-mnist). The model can recognize 10 different categories, including shirts, sneakers, bags, and more.

---

## Dataset

The Fashion MNIST dataset consists of 28x28 grayscale images belonging to the following 10 classes:


- **Training samples:** 60,000  
- **Test samples:** 10,000

---

## Model Overview

The model is a simple CNN with dropout and trained using data augmentation.  
Final accuracy achieved on test set: **91%**

### Sample prediction:
![Prediction Sample](plots/predictions.png)

---

## Performance Metrics

- Accuracy: **91%**
- Loss: optimized with `Adam` and early stopping
- Includes confusion matrix, best/worst predictions, and class-wise F1-score

![Confusion Matrix](plots/confusion_matrix.png)

---

## Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib / Seaborn
- Scikit-learn

---

## How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your_username/fashion-mnist-classifier.git
   cd fashion-mnist-classifier

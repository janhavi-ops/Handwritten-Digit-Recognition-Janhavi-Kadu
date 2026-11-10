# Handwritten Digit Recognition Using Neural Networks

## 1. Project Overview
This project focuses on recognizing handwritten digits (0–9) using an Artificial Neural Network (ANN). The model is trained using the MNIST handwritten digit dataset.

## 2. Objective
To develop a neural network model that can identify handwritten digits from grayscale images with good accuracy.

## 3. Dataset
- Dataset: MNIST
- Training images: 60,000
- Testing images: 10,000
- Image size: 28 × 28 pixels
- Number of classes: 10 (digits 0–9)

The dataset was loaded directly using TensorFlow/Keras.

## 4. Technologies Used
- Python
- Google Colab
- TensorFlow and Keras
- NumPy
- Matplotlib
- Scikit-learn

## 5. Methodology
1. Load the MNIST dataset.
2. Visualize sample handwritten digits.
3. Normalize pixel values between 0 and 1.
4. Build an Artificial Neural Network.
5. Train the model using training images.
6. Evaluate the model using test images.
7. Generate accuracy graphs and a confusion matrix.
8. Test the model with sample handwritten digits.

## 6. Model Architecture
- Flatten layer
- Dense layer with 128 neurons and ReLU activation
- Dropout layer (0.2)
- Output layer with 10 neurons and Softmax activation

Optimizer: Adam  
Loss Function: Sparse Categorical Crossentropy  
Training Epochs: 5

## 7. Results
The model achieved approximately **97% test accuracy**.

The project also includes accuracy and loss graphs, a classification report, a confusion matrix, and sample digit predictions.

## 8. Project Files
- `Handwritten_Digit_Recognition_MNIST.ipynb` – Complete project notebook.
- `mnist_digit_model.keras` – Trained neural network model.
- `screenshots/` – Screenshots of project execution and results.

## 9. Conclusion
The project successfully demonstrates how neural networks can recognize handwritten digits using the MNIST dataset. The trained model achieved approximately 97% accuracy on test data.

## 10. How to Run
1. Open the notebook using Google Colab.
2. Run the cells sequentially.
3. The dataset will be loaded automatically through TensorFlow/Keras.
4. Train and evaluate the model to view the results.

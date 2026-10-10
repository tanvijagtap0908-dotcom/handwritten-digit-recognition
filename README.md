# Handwritten Digit Recognition Using Artificial Neural Networks

## Project Overview

This project uses an Artificial Neural Network (ANN) to recognize handwritten digits from 0 to 9. It is built using TensorFlow and Keras and trained on the MNIST dataset of handwritten digit images.

The model processes grayscale images, learns patterns from training data, and predicts the digit represented by each image.

## Objectives

- Understand image data preprocessing.
- Build and train an Artificial Neural Network.
- Apply normalization to pixel values.
- Predict handwritten digits using a trained model.
- Evaluate model performance on unseen test data.

## Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab / Jupyter Notebook

## Dataset

The project uses the MNIST handwritten digit dataset, which contains 60,000 training images and 10,000 test images. Each image is a 28 × 28 grayscale image representing a digit from 0 to 9.

The dataset is loaded using `keras.datasets.mnist.load_data()`.

## Model Architecture

The ANN consists of the following layers:

1. Input layer: accepts 28 × 28 images.
2. Flatten layer: converts each image into a 784-element vector.
3. Dense layer: 128 neurons with ReLU activation.
4. Output layer: 10 neurons with Softmax activation.

## Model Training

- Optimizer: Adam
- Loss function: Sparse Categorical Crossentropy
- Epochs: 10
- Validation split: 20% of the training data

## Results

**Test Accuracy: 97.65%**

The model's predictions are evaluated against the actual test labels using Scikit-learn's accuracy score.

## How to Run

1. Open the notebook in Google Colab or Jupyter Notebook.
2. Install the dependencies listed in `requirements.txt`, if needed.
3. Run the notebook cells in order.
4. Allow Keras to download the MNIST dataset.
5. Review the training results and test predictions.

## Future Improvements

- Add a Convolutional Neural Network (CNN).
- Display multiple correct and incorrect predictions.
- Plot training and validation accuracy and loss.
- Build a web interface where users can draw a digit and receive a prediction.

## Conclusion

This project demonstrates a complete introductory deep learning workflow, from loading and preprocessing image data to training an ANN and evaluating its predictions.

This project was developed for educational and portfolio purposes.

## Project Screenshots
<img width="960" height="473" alt="Screenshot 2026-10-10 141236" src="https://github.com/user-attachments/assets/bd03d0a4-e6fb-4624-97c6-d31bd2a81c3e" />

<img width="960" height="476" alt="Screenshot 2026-10-10 141334" src="https://github.com/user-attachments/assets/31dc2731-8a93-4274-92bc-4b1d0b611315" />


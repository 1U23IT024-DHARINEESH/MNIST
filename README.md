# MNIST
# MNIST Handwritten Digit Classification

This project uses Artificial Neural Networks (ANN) and Deep Learning to recognize handwritten digits from 0 to 9 using the MNIST dataset.

## Business Objective

Handwritten digit recognition helps automate number identification in documents, forms, postal codes, and other digital applications.

The main objective is to train neural networks to accurately classify handwritten digit images.

## Dataset Features

The MNIST dataset includes:

- Total Training Images: 60,000
- Total Testing Images: 10,000
- Image Size: 28 × 28 pixels
- Number of Classes: 10 (Digits 0–9)
- Image Type: Grayscale

## Data Preprocessing

The project includes:

- Loading the MNIST dataset.
- Splitting training and validation data.
- Normalizing pixel values between 0 and 1.
- Reshaping images into 784 features.
- One-hot encoding target labels.
- Stratified train-validation splitting.

The data is divided into:

- Training Data: 50,000 images
- Validation Data: 10,000 images
- Testing Data: 10,000 images

## Deep Learning Models

13 neural network configurations are experimented with:

1. Softmax Output Model
2. Single Hidden Layer Model
3. Multiple Hidden Layer Models
4. Different Neuron Configurations
5. Sigmoid Activation
6. Tanh Activation
7. ReLU Activation

The experiments compare different epochs, batch sizes, hidden layers, and activation functions.

## Evaluation Metrics

The models are evaluated using:

- Training Accuracy
- Validation Accuracy
- Training Loss
- Validation Loss
- Training Time

## Final Result

The best validation accuracy is achieved by Model 13:

- Validation Accuracy: `97.55%`
- Training Accuracy: `100%`
- Validation Loss: `0.131`

Model 10 also provides a good balance with `97.46%` validation accuracy and `0.087` validation loss.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- TensorFlow
- Keras
- Scikit-learn
- Jupyter Notebook

## Conclusion

This project demonstrates handwritten digit classification using Artificial Neural Networks. Different neural network architectures and training configurations are compared to identify their effect on model performance.


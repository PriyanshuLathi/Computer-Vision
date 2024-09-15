# Hand-Written Digits Recognition Using Simple Neural Network

## Overview

This Jupyter Notebook demonstrates the implementation of a simple neural network for recognizing hand-written digits using the MNIST dataset. Hand-written digit recognition is a classic problem in machine learning and deep learning, and this notebook uses a basic feedforward neural network built with TensorFlow to classify images of digits.

## Aim

The notebook covers the following objectives:

- **Data Loading and Preprocessing:** Prepare the MNIST dataset for training and testing the neural network.
- **Model Design:** Build a simple neural network using TensorFlow to classify hand-written digits.
- **Training and Evaluation:** Train the neural network on the MNIST dataset and evaluate its performance on unseen test data.
- **Accuracy Visualization:** Plot and analyze the accuracy and loss of the model during training.

## Dataset Description

The MNIST dataset is a large database of 70,000 images of handwritten digits (0-9), each image being 28x28 pixels in grayscale. It is widely used for training various image processing systems and is a benchmark dataset in the field of machine learning and computer vision.

- **Training Set:** 60,000 images.
- **Test Set:** 10,000 images.
- **Image Dimensions:** 28x28 pixels, grayscale.
- **Labels:** Each image is associated with a digit label (0-9).

The dataset is provided by TensorFlow and can be easily loaded using the `tensorflow.keras.datasets` module.

## Practical Implementation

The notebook includes the following steps:

1. **Dataset Loading:** Load the MNIST dataset of hand-written digits.
2. **Data Preprocessing:** Normalize the data for better model performance.
3. **Model Construction:** Build a simple feedforward neural network using TensorFlow.
4. **Training the Model:** Train the model on the training data using backpropagation and gradient descent.
5. **Model Evaluation:** Test the model on the test data and compute accuracy.
6. **Result Visualization:** Plot the training loss and accuracy for better insight into the model's performance.

## Requirements

- **Python Version:** 3.x
- **Libraries:**
    - NumPy
    - TensorFlow
    - Matplotlib
    - MNIST Dataset (available via TensorFlow)

## Usage

To run this notebook:

1. **Clone the repository:**
    ```bash
    git clone https://github.com/PriyanshuLathi/Computer-Vision.git
    ```

2. **Install the required libraries:**
    ```bash
    pip install numpy tensorflow matplotlib
    ```

3. **Open the notebook in Jupyter.**

4. **Run each cell** to train the neural network and visualize the results.

## Conclusion

This experiment demonstrated the implementation of a basic neural network for recognizing hand-written digits from the MNIST dataset using TensorFlow. We covered:

- Loading and preprocessing the dataset.
- Constructing and training a simple neural network.
- Evaluating the network's performance on unseen data.
- Visualizing the accuracy and loss over the training period.

This notebook serves as an introductory guide to building neural networks for image classification tasks, such as digit recognition.

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/PriyanshuLathi/Computer-Vision/blob/main/LICENSE) file for details.

## Contact

For questions or feedback:

- LinkedIn: [Priyanshu Lathi](https://www.linkedin.com/in/priyanshu-lathi)
- GitHub: [Priyanshu Lathi](https://github.com/PriyanshuLathi)

## Authors

- Priyanshu Lathi
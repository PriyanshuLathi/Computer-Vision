# Hand-Written Digits Classification Using Convolutional Neural Networks (CNN)

## Overview

This Jupyter Notebook demonstrates the implementation of a Convolutional Neural Network (CNN) to classify hand-written digits from the MNIST dataset. CNNs are particularly effective for image classification tasks, making them ideal for this problem. The notebook uses TensorFlow to build and train the CNN for hand-written digit classification.

## Aim

The notebook covers the following key objectives:

- **Data Loading and Preprocessing:** Loading and preparing the MNIST dataset for training and testing.
- **CNN Model Design:** Building a Convolutional Neural Network using TensorFlow/Keras for digit classification.
- **Model Training and Evaluation:** Training the CNN on the MNIST dataset and evaluating its accuracy on unseen test data.
- **Result Visualization:** Analyzing model performance by plotting the training accuracy and loss.

## Dataset Description

The MNIST dataset consists of a collection of 70,000 grayscale images of hand-written digits (0-9). Each image is 28x28 pixels, and it is commonly used as a benchmark in image classification tasks.

- **Training Set:** 60,000 images.
- **Test Set:** 10,000 images.
- **Image Size:** 28x28 pixels.
- **Labels:** Digits ranging from 0 to 9.

The dataset can be loaded using the `tensorflow.keras.datasets` module, making it easy to integrate into TensorFlow workflows.

## Practical Implementation

The notebook includes the following steps:

1. **Dataset Loading:** Download and load the MNIST dataset.
2. **Data Preprocessing:** Normalize the pixel values and reshape the images as required by the CNN input.
3. **Model Design:** Construct a CNN with convolutional layers, max-pooling layers, and dense layers.
4. **Model Compilation:** Compile the model using an optimizer and appropriate loss function.
5. **Training the Model:** Train the model using backpropagation and evaluate its performance on the test set.
6. **Result Analysis:** Plot the training and validation loss/accuracy to assess the model's learning behavior.

## Requirements

- **Python Version:** 3.x
- **Libraries:**
    - NumPy
    - Matplotlib
    - TensorFlow
    - Keras (provided by TensorFlow)

## Usage

To run the notebook:

1. **Clone the repository:**
    ```bash
    git clone https://github.com/PriyanshuLathi/Computer-Vision.git
    ```

2. **Install the required libraries:**
    ```bash
    pip install numpy matplotlib tensorflow 
    ```

3. **Open the notebook in Jupyter.**

4. **Run the cells** to train the CNN and visualize the model performance.

## Conclusion

This notebook presents a simple but effective approach to classifying hand-written digits using a CNN. The steps covered include:

- Loading and preprocessing the MNIST dataset.
- Building a CNN for digit classification.
- Training the model and evaluating its performance.
- Visualizing the training and validation metrics.

This serves as an excellent introduction to using CNNs for image classification tasks.

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/PriyanshuLathi/Computer-Vision/blob/main/LICENSE) file for details.

## Contact

For any questions or feedback:

- LinkedIn: [Priyanshu Lathi](https://www.linkedin.com/in/priyanshu-lathi)
- GitHub: [Priyanshu Lathi](https://github.com/PriyanshuLathi)

## Authors

- Priyanshu Lathi

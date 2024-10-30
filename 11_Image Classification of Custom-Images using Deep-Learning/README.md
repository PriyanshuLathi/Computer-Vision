# Image Classification of Custom-Images using Deep-Learning (CNN)

## Overview
This Jupyter Notebook demonstrates the implementation of a Convolutional Neural Network (CNN) to classify custom images. CNNs are highly effective for image classification tasks, making them ideal for this problem. The notebook utilizes TensorFlow and Keras to build, train, and evaluate the CNN.

## Aim
The key objectives of this notebook are as follows:

- **Data Loading and Preprocessing:** Load and prepare the image dataset for training and testing.
- **CNN Model Design:** Build a Convolutional Neural Network using TensorFlow and Keras to classify the images.
- **Model Training and Evaluation:** Train the CNN on the dataset and evaluate its accuracy on unseen test data.
- **Result Visualization:** Analyze the model's performance by plotting the training accuracy and loss over time.

## Dataset Description
The dataset contains images of cats and dogs organized into separate folders for training and testing.

- For CAT_DOGS:
    - **Training Set:** 
        - Location: `/CATS_DOGS/train/`
        - Subfolders: `CAT/` for cat images, `DOG/` for dog images.
    - **Testing Set:**
        - Location: `/CATS_DOGS/test/`
        - Subfolders: `CAT/` for cat images, `DOG/` for dog images.

- For Homer_Bart:
    - **Training Set:** 
        - Location: `/homer_bart_2/train_set`
        - Subfolders: `bart/` for bart images, `homer/` for homer images.
    - **Testing Set:**
        - Location: `/homer_bart_2/test_set`
        - Subfolders: `bart/` for bart images, `homer/` for homer images.

These images are used to train and evaluate the CNN model to distinguish between cats-dogs and homer-bart.

## Practical Implementation

The notebook includes the following key steps:

1. **Dataset Loading:** Define paths to the training and testing folders, and load the images.
2. **Data Preprocessing:** Normalize the images and prepare them for input into the CNN.
3. **Model Design:** Build a CNN using convolutional layers, max-pooling layers, and fully connected layers to extract features from the images.
4. **Model Compilation:** Compile the CNN using an optimizer and loss function.
5. **Model Training:** Train the CNN using the training dataset and backpropagation.

![Screenshot 2024-09-30 192648](https://github.com/user-attachments/assets/45f376eb-7b85-4d60-ae08-7927cf1a5cce)

6. **Evaluation:** Evaluate the trained model's performance on the test dataset.
7. **Result Analysis:** Visualize the model's training and validation accuracy and loss using Matplotlib plots.

![Screenshot 2024-09-30 192708](https://github.com/user-attachments/assets/1a453984-557d-4d64-a5b4-9b8e68b011b4)

## CNN Architecture

The CNN architecture used in the notebook consists of the following components:
- **Convolutional Layers:** Extract spatial features from the images.
- **Pooling Layers:** Reduce the dimensionality and computational complexity while retaining essential information.
- **Fully Connected Layers:** Classify the images by learning non-linear combinations of features extracted by the convolutional layers.

![image](https://github.com/user-attachments/assets/61779bab-a98d-4583-9417-603aa6e6565a)

## Requirements
- **Python Version:** 3.x
- **Libraries:**
    - NumPy
    - OpenCV
    - Matplotlib
    - TensorFlow
    - Keras (provided by TensorFlow)

## Usage

To run this notebook:

1. **Clone the repository:**
    ```bash
    git clone https://github.com/PriyanshuLathi/Computer-Vision.git
    ```

2. **Install the required libraries:**
    ```bash
    pip install numpy opencv-python matplotlib tensorflow
    ```

3. **Open the notebook in Jupyter.**

4. **Run the cells** to train the CNN and visualize the model’s performance.

## Conclusion

This notebook provides a complete guide to building a CNN model for classifying images of cats-dogs and homer-bart. It walks through the entire process of loading the dataset, preprocessing the images, building the CNN, and evaluating its performance. This project serves as an excellent example of image classification using deep learning.

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/PriyanshuLathi/Computer-Vision/blob/main/LICENSE) file for details.

## Contact

For any questions or feedback:

- LinkedIn: [Priyanshu Lathi](https://www.linkedin.com/in/priyanshu-lathi)
- GitHub: [Priyanshu Lathi](https://github.com/PriyanshuLathi)

Contributions are welcome! Fork this repository and submit a pull request for review.

## Authors

- Priyanshu Lathi

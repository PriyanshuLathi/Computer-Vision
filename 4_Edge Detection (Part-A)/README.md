# Edge Detection (Part-A)

## Overview

This Jupyter Notebook demonstrates fundamental edge detection techniques in image processing using Python libraries such as OpenCV and matplotlib. The purpose is to provide a hands-on understanding of how edge detection works using Roberts, Prewitt, and Sobel operators, which are commonly used to detect edges in images for various computer vision applications.

## Aim

The notebook introduces the theoretical background of the following edge detection techniques:

- **Roberts Operator:** Applies a pair of 2x2 convolution kernels to approximate the gradient of an image. It is sensitive to noise but effective in detecting fine edges.
- **Prewitt Operator:** Uses two 3x3 convolution kernels to detect vertical and horizontal edges. It is a basic edge detector that emphasizes changes in intensity.
- **Sobel Operator:** An enhanced version of the Prewitt operator, using 3x3 kernels with a larger emphasis on the central pixels, providing smoother and more robust edge detection.

## Practical Implementation

The notebook includes the following tasks:

1. Load and display an image using OpenCV.
2. Convert the image to grayscale for edge detection.
3. Apply the **Roberts** operator to detect edges.
4. Use the **Prewitt** operator to identify horizontal and vertical edges.
5. Implement the **Sobel** operator to detect edges in both directions with greater accuracy.
6. Visualize and compare the results of different edge detection methods.

## Requirements

- **Python Version:** 3.x
- **Libraries:**
    - NumPy
    - OpenCV
    - Matplotlib
    - PIL (Python Imaging Library)


## Usage

To run this notebook:

1. **Clone the repository:**
    ```bash
    git clone https://github.com/PriyanshuLathi/Computer-Vision.git
    ```

2. **Install the required libraries:**
    ```bash
    pip install numpy opencv-python matplotlib pillow
    ```

3. **Open the notebook in Jupyter.**

4. **Run each cell** to perform the described operations and observe the results.

## Conclusion

This notebook provides a practical introduction to edge detection using the Roberts, Prewitt, and Sobel operators, enabling users to understand and apply these techniques effectively in computer vision tasks.

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/PriyanshuLathi/Computer-Vision/blob/main/LICENSE) file for details.

## Contact

For questions or feedback:

- LinkedIn: [Priyanshu Lathi](https://www.linkedin.com/in/priyanshu-lathi)
- GitHub: [Priyanshu Lathi](https://github.com/PriyanshuLathi)

## Authors

- Priyanshu Lathi

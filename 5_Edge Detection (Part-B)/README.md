# Edge Detection (Part-B)

## Overview

This Jupyter Notebook extends the exploration of edge detection techniques in image processing, focusing on more advanced methods using Python libraries such as OpenCV and matplotlib. It provides a practical understanding of how edge detection works using the Scharr, Canny, and Laplacian operators, which offer enhanced performance and accuracy for various computer vision applications.

## Aim

The notebook introduces the theoretical background of the following edge detection techniques:

- **Scharr Operator:** An improvement over the Sobel operator, using larger convolution kernels to provide even more precise edge detection by emphasizing the edges' intensity changes.
- **Canny Operator:** A multi-stage edge detection algorithm that combines noise reduction, gradient calculation, non-maximum suppression, and edge tracking by hysteresis to produce robust and accurate edges.
- **Laplacian Operator:** Uses the second derivative to detect edges, highlighting regions where the intensity changes rapidly, and is particularly effective for detecting fine details and noise.

## Practical Implementation

The notebook includes the following tasks:

1. Load and display an image using OpenCV.
2. Convert the image to grayscale for edge detection.
3. Apply the **Scharr** operator for more accurate edge detection.
4. Use the **Canny** operator to detect edges using a multi-stage algorithm.
5. Implement the **Laplacian** operator to find edges using the second derivative.
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

This notebook provides an in-depth understanding of advanced edge detection techniques using the Scharr, Canny, and Laplacian operators, enabling users to apply these methods for more precise and effective computer vision tasks.

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/PriyanshuLathi/Computer-Vision/blob/main/LICENSE) file for details.

## Contact

For questions or feedback:

- LinkedIn: [Priyanshu Lathi](https://www.linkedin.com/in/priyanshu-lathi)
- GitHub: [Priyanshu Lathi](https://github.com/PriyanshuLathi)

## Authors

- Priyanshu Lathi

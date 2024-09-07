# Basic Operations on Image Data (Part-B)

## Overview

This Jupyter Notebook covers basic image processing techniques, including thresholding, blending, and pasting images using Python libraries such as OpenCV and matplotlib. The aim is to demonstrate how these techniques can be used to manipulate image data for various applications in computer vision.

## Aim

To perform and understand the following basic operations on image data:
- **Thresholding:** Separating an image into foreground and background using different thresholding techniques.
- **Blending:** Combining two images to create a composite image with transparency effects.
- **Pasting:** Inserting one image onto a specific region of another image.

## Theory

The notebook introduces the theoretical background of the following image processing techniques:

- **Thresholding:** Used to separate an image into foreground and background by comparing pixel intensity values to a predefined threshold. Techniques covered include Binary Thresholding, Binary Inverse Thresholding, Truncate Thresholding, To Zero Thresholding, and To Zero Inverse Thresholding.
- **Blending:** Combining two or more images to create a composite image, often using linear blending with OpenCV's `cv2.addWeighted()` function.
- **Pasting:** Inserting one image onto a specific region of another image, useful for tasks like adding watermarks or creating collages.

## Practical Implementation

The notebook includes the following tasks:

1. Download and import an RGB image using OpenCV.
2. Check the shape of the image and visualize it using the matplotlib library.
3. Convert the RGB image to a grayscale image and display it.
4. Apply different thresholding techniques to the grayscale image, including binary and inverse thresholding.
5. Create an image with a white background and add text.
6. Resize images and perform blending operations.
7. Paste a smaller image onto a larger one in the upper left corner.

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

This notebook provides a hands-on introduction to fundamental image processing operations, offering practical experience with techniques that are widely used in computer vision applications.

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/PriyanshuLathi/Computer-Vision/blob/main/LICENSE) file for details.

## Contact

For questions or feedback:

- LinkedIn: [Priyanshu Lathi](https://www.linkedin.com/in/priyanshu-lathi)
- GitHub: [Priyanshu Lathi](https://github.com/PriyanshuLathi)

## Authors

- Priyanshu Lathi
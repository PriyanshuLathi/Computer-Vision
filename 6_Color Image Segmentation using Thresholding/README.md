# Color Image Segmentation using Thresholding

## Overview

This Jupyter Notebook demonstrates color image segmentation using various thresholding techniques. It provides an introduction to the principles and methods of image segmentation, focusing on how thresholding can be applied to isolate different regions in an image based on their color properties. The notebook utilizes Python libraries such as OpenCV, PIL, and matplotlib to implement these techniques.

## Aim

The notebook covers the following thresholding techniques:

- **Global Thresholding:** A single threshold value is applied across the entire image to separate foreground and background.
- **Adaptive Thresholding:** The threshold value is determined locally for different regions of the image, making it effective in cases where illumination or contrast varies.
- **Multi-level Thresholding:** Multiple thresholds are used to segment an image into more than two classes, allowing for finer distinctions between objects with varying intensities or colors.
- **Color Thresholding:** Thresholding is applied to each color channel (Red, Green, Blue) or in an alternative color space (such as HSV), enabling more precise segmentation based on color properties.

## Practical Implementation

The notebook includes the following steps:

1. **Read the Image:** Load the color image into the Python environment.
2. **Convert to Grayscale:** Transform the color image to grayscale to simplify the thresholding process.
3. **Convert to Different Color Spaces:** Utilize RGB and HSV color spaces for segmentation.
4. **Apply Thresholding:**
   - Use global, adaptive, and multi-level thresholding techniques.
   - Perform thresholding on individual color channels or alternative color spaces.
5. **Refine Segmentation Results:** Use morphological operations (erosion, dilation, opening, and closing) to enhance the segmented output.
6. **Visualize Results:** Display the original image alongside the segmented images for comparison.

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

In this experiment, we explored color image segmentation using the thresholding technique. We learned how to:

- Load and visualize color images.
- Convert images to different color spaces (RGB and HSV).
- Apply thresholding to segment objects based on color ranges.
- Use morphological operations (erosion, dilation, opening, and closing) to refine segmentation results.

We observed that thresholding is a simple yet effective method for segmenting objects in color images, especially when the objects have distinct color characteristics. However, the choice of appropriate threshold values and the use of morphological operations can significantly impact the quality of segmentation.

By experimenting with different threshold values and morphological operations, we were able to achieve satisfactory segmentation results for both the "fruit.png" and "Thresh_segmentation.png" images.

This experiment highlights the practical applications of color image segmentation in various fields, including object detection, medical imaging, remote sensing, and industrial inspection.

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/PriyanshuLathi/Computer-Vision/blob/main/LICENSE) file for details.

## Contact

For questions or feedback:

- LinkedIn: [Priyanshu Lathi](https://www.linkedin.com/in/priyanshu-lathi)
- GitHub: [Priyanshu Lathi](https://github.com/PriyanshuLathi)

## Authors

- Priyanshu Lathi

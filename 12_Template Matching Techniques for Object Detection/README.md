# Template Matching Techniques for Object Detection

## Overview
This Jupyter Notebook demonstrates the implementation of template matching techniques to detect objects within images. Template matching is a simple yet powerful approach for locating a sub-image (template) within a larger image. This notebook utilizes OpenCV to apply various template matching techniques and visualize the results.

## Aim
The primary objectives of this notebook include:

- **Data Loading and Preprocessing:** Load target images and template images for detection tasks.
- **Template Matching Techniques:** Implement multiple techniques such as normalized cross-correlation for effective object detection.
- **Result Visualization:** Display the matching results with bounding boxes around detected objects.

## Dataset Description
This project uses sample images provided within the notebook, including target images containing objects of interest and template images representing those objects. 

- **Target Image:** 
    - This image contains the scene or area where object detection is performed.
- **Template Image:** 
    - This is the object image we aim to locate within the target image.
  
## Practical Implementation

The notebook is organized as follows:

1. **Dataset Loading:** Load the target and template images.
2. **Template Matching Techniques:** Implement techniques using OpenCV, including normalized cross-correlation for locating template matches within the target image.
3. **Matching Analysis:** Determine the best match locations and apply bounding boxes to highlight detected regions.
4. **Result Visualization:** Display images showing bounding boxes around detected objects to illustrate successful matches.

## Template Matching Techniques

The implemented techniques include:

- **Normalized Cross-Correlation:** Calculate similarity between the template and sub-regions of the target image, identifying the best match by the highest correlation values.
- **Result Localization:** Once a match is found, apply bounding boxes to mark the matched region on the target image.

## Requirements
- **Python Version:** 3.x
- **Libraries:**
    - OpenCV
    - NumPy
    - Matplotlib

## Usage

To run this notebook:

1. **Clone the repository:**
    ```bash
    git clone https://github.com/PriyanshuLathi/Computer-Vision.git
    ```

2. **Install the required libraries:**
    ```bash
    pip install numpy opencv-python matplotlib
    ```

3. **Open the notebook in Jupyter.**

4. **Run the cells** to apply template matching and visualize results.

## Conclusion

This notebook provides a complete guide to implementing template matching techniques for object detection. It covers the process of loading images, applying template matching, and visualizing the results, making it an effective reference for object detection using classical computer vision techniques.

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/PriyanshuLathi/Computer-Vision/blob/main/LICENSE) file for details.

## Contact

For any questions or feedback:

- LinkedIn: [Priyanshu Lathi](https://www.linkedin.com/in/priyanshu-lathi)
- GitHub: [Priyanshu Lathi](https://github.com/PriyanshuLathi)

Contributions are welcome! Fork this repository and submit a pull request for review.

## Authors

- Priyanshu Lathi
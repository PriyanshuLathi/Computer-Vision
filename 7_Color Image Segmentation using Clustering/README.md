# Color Image Segmentation using Clustering

## Overview

This Jupyter Notebook demonstrates color image segmentation using clustering techniques. It provides an introduction to the principles of image segmentation and how clustering algorithms can be applied to group pixels into meaningful regions based on their features. The notebook utilizes Python libraries such as OpenCV, NumPy, and Matplotlib to implement these techniques.

## Aim

The notebook covers the following clustering techniques for image segmentation:

- **K-Means Clustering:** A widely used algorithm that partitions image pixels into K clusters based on their color or intensity features.
- **Mean Shift Clustering:** A non-parametric clustering algorithm that does not require the number of clusters to be predefined.
- **Hierarchical Clustering:** Builds a hierarchy of clusters using agglomerative (bottom-up) or divisive (top-down) approaches.

## Practical Implementation

The notebook includes the following steps:

1. **Preprocessing:** Load the image and prepare it for clustering by converting it into a suitable format such as a NumPy array.
2. **Feature Extraction:** Extract relevant features from each pixel, such as color components or texture information.
3. **Clustering:** Apply clustering algorithms (K-Means, Mean Shift, or Hierarchical) to group pixels with similar features.
4. **Label Assignment:** Assign unique labels to each cluster to distinguish the segmented regions.
5. **Visualization:** Display the segmented images by mapping each cluster label to a distinct color.

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

4. **Run each cell** to perform the described operations and observe the segmentation results.

## Conclusion

In this experiment, we explored color image segmentation using clustering techniques. We learned how to:

- Load and visualize images.
- Extract features from image pixels.
- Apply clustering algorithms to segment images into distinct regions based on color or intensity.
- Visualize segmented results with unique labels assigned to each cluster.

Clustering-based segmentation is effective in various applications, including object recognition, medical imaging, and image editing. Experimenting with different clustering techniques and parameters can significantly impact the quality and accuracy of segmentation.

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/PriyanshuLathi/Computer-Vision/blob/main/LICENSE) file for details.

## Contact

For questions or feedback:

- LinkedIn: [Priyanshu Lathi](https://www.linkedin.com/in/priyanshu-lathi)
- GitHub: [Priyanshu Lathi](https://github.com/PriyanshuLathi)

## Authors

- Priyanshu Lathi
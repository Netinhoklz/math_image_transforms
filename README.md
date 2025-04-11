# math-image-transforms

This repository contains a master's level assignment for the Computer Vision course. The project demonstrates the application of several mathematical transformations on images, showcasing their effects on both grayscale and RGB images.

## Overview

In this activity, we explore how different mathematical functions can transform the pixel intensities of digital images. The implemented functions include:

- **Linear Transformation**
- **Logarithmic Transformation**
- **Exponential Transformation**
- **Quadratic Transformation**
- **Square Root Transformation**

Each transformation is applied to both grayscale and color images, allowing for a comprehensive analysis of how these operations modify image characteristics such as brightness and contrast.

## Objectives

- **Explore Mathematical Functions:** Gain insight into the behavior of linear and non-linear transformations on image intensities.
- **Compare Effects:** Evaluate the differences in applying these functions to grayscale versus RGB images.
- **Visual Analysis:** Provide visual examples that illustrate the impact of each transformation.
- **Educational Insight:** Lay the foundation for further studies and applications in digital image processing and computer vision.

## Transformation Details

- **Linear Transformation:** Adjusts the overall brightness by scaling pixel values uniformly.
- **Logarithmic Transformation:** Enhances dark regions by compressing the dynamic range, making details in shadows more visible.
- **Exponential Transformation:** Increases contrast in the brighter regions, leading to a more pronounced intensity difference.
- **Quadratic Transformation:** Alters the mid-tones to enhance specific details through a gamma correction-like effect.
- **Square Root Transformation:** Relieves high intensity saturation, offering a lighter transformation compared to the exponential function.

## Methodology

1. **Image Acquisition:** Select sample images in both grayscale and RGB.
2. **Function Implementation:** Code each transformation function using Python.
3. **Application:** Apply these functions to the selected images.
4. **Visualization:** Display and compare original versus transformed images using plots.

## Requirements

- Python 3.x
- [OpenCV](https://opencv.org/)
- [NumPy](https://numpy.org/)
- [Matplotlib](https://matplotlib.org/)

You can install the required Python packages using:

```bash
pip install opencv-python numpy matplotlib

# TP1: Image Processing - Image Manipulation and Point Operations

## Overview
This notebook, "Computer vision TP1.ipynb," is a comprehensive guide to basic image processing techniques. It covers manipulation of images, grayscale level transformations, and histogram operations. The focus is on understanding the fundamental concepts of image manipulation and point operations in the context of Data Science and Artificial Intelligence.

## Authors
- Ahmed Abdelmounaim BELKHOUMALI
- Sarah BOUARABA

## Specialization
Data Science & Artificial Intelligence

---

### Manipulation 01: Understanding Digital Images
- **Objective**: Understand digital images as matrices and explore grayscale levels.
- **Key Concepts**: Digital images as matrices, 8-bit grayscale levels, pixel representation.
- **Operations**:
  - Generation of matrices to represent images.
  - Visualization of grayscale images.
  - Understanding the range of grayscale levels from 0 (black) to 255 (white).

---

### Manipulation 02: RGB Channels and Grayscale Conversion
- **Objective**: Explore RGB color space and convert images to grayscale.
- **Key Concepts**: RGB image type, color channels, grayscale conversion.
- **Operations**:
  - Loading and visualization of RGB images.
  - Separation and visualization of RGB channels.
  - Analysis of image types and data types (uint8).
  - Conversion of RGB to grayscale using both a predefined formula and Python's built-in functions.
  - Comparative analysis of the two grayscale conversion methods.

---

### Manipulation 03: Image Resampling and Quantization
- **Objective**: Learn about image resampling (sub-sampling) and quantization.
- **Key Concepts**: Sub-sampling, quantization, image degradation, and optimal image quality.
- **Operations**:
  - Implementation of image sub-sampling and analysis of image degradation.
  - Quantization to reduce grayscale levels and its impact on image quality.
  - Comparative study of original, sub-sampled, and quantized images.

---

### Manipulation 04: Histogram Operations and Contrast Enhancement
- **Objective**: Explore histogram operations for contrast enhancement.
- **Key Concepts**: Histogram equalization, histogram matching, contrast adjustment.
- **Operations**:
  - Histogram plotting and normalization.
  - Histogram equalization and its effect on image contrast.
  - Contrast enhancement using histogram matching.
  - Entropy calculation for different histogram methods.
  - Visual and statistical comparison of original and enhanced images.

---

## Tools and Libraries Used
- Python
- OpenCV (cv2)
- Matplotlib
- NumPy
- skimage.measure

## Installation and Usage
Ensure that Python is installed along with the required libraries. The notebook can be run cell by cell to observe each manipulation's outcome.

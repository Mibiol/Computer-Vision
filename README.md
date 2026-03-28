# Computer-Vision
Collection of simple computer vision experiments using Python, OpenCV, and NumPy.
# Edge Detection using OpenCV

A comprehensive implementation of classical **edge detection techniques** using **OpenCV in Python**, developed in a Jupyter/Colab environment. This project demonstrates how different algorithms extract structural information from images across multiple domains.

---

## Table of Contents
- [Overview](#overview)
- [Objectives](#objectives)
- [Tech Stack](#tech-stack)
- [Methodology](#methodology)
- [Edge Detection Techniques](#edge-detection-techniques)
- [Results](#results)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Applications](#applications)
- [Future Work](#future-work)
- [Author](#author)
- [License](#license)

---

## Overview

Edge detection plays a critical role in **computer vision** by identifying object boundaries and significant transitions in pixel intensity. This project explores and compares three fundamental edge detection techniques:

- Sobel Operator  
- Prewitt Operator  
- Canny Edge Detector  

The implementation is designed for clarity, visualization, and educational purposes.

---

## Objectives

- Implement classical edge detection algorithms from scratch and using OpenCV  
- Compare performance across different image types  
- Visualize outputs for better interpretability  
- Build a reusable foundation for advanced computer vision tasks  

---

## Tech Stack

| Category     | Tools Used                      |
|--------------|--------------------------------|
| Language     | Python 3.x                     |
| Libraries    | OpenCV, NumPy, Matplotlib      |
| Environment  | Jupyter Notebook / Google Colab|

---

## Methodology

The workflow followed in the notebook:

1. Image Acquisition  
   - Upload images via Google Colab interface  

2. Preprocessing  
   - Convert to grayscale  
   - Apply Gaussian Blur (noise reduction)  

3. Edge Detection  
   - Apply Sobel, Prewitt, and Canny algorithms  

4. Visualization  
   - Display original and processed images side-by-side  

---

## Edge Detection Techniques

### 1. Sobel Operator
- Computes gradients in horizontal and vertical directions  
- Highlights intensity changes  

### 2. Prewitt Operator
- Uses convolution kernels for edge approximation  
- Simpler alternative to Sobel  

### 3. Canny Edge Detector
A multi-stage algorithm:
- Noise reduction (Gaussian filter)  
- Gradient calculation  
- Non-maximum suppression  
- Double thresholding and edge tracking  

---

## Results

The notebook provides visual outputs for each technique:
- Original Image  
- Grayscale Image  
- Edge-detected Results  

This enables clear comparison of:
- Edge sharpness  
- Noise sensitivity  
- Detection accuracy  

---

## Project Structure


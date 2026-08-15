# 👁️ Computer Vision with OpenCV — Google Colab

A hands-on collection of **Computer Vision and Digital Image Processing experiments** implemented in **Python, OpenCV, NumPy, and Matplotlib** using **Google Colab**.

This repository documents my progression from **beginner-level image processing** to **intermediate and slightly challenging computer vision operations**, with practical implementations and visual outputs.

> **Learning by doing — from pixels to computer vision.**

---

## 🚀 Overview

This repository contains practical Computer Vision experiments organized by difficulty:

| Level                   | Focus                                                                         |
| ----------------------- | ----------------------------------------------------------------------------- |
| 🟢 Beginner             | Fundamental image handling and basic OpenCV operations                        |
| 🟡 Intermediate         | Image transformations, noise, histograms and enhancement                      |
| 🟠 Slightly Challenging | Morphological operations, object detection, segmentation and image arithmetic |

All experiments are designed to run directly in **Google Colab**, making the notebooks easy to execute without requiring a local OpenCV installation.

---

## 🛠️ Technologies Used

* 🐍 Python
* 👁️ OpenCV
* 🔢 NumPy
* 📊 Matplotlib
* ☁️ Google Colab
* 🖼️ Digital Image Processing

---

# 📚 Experiments

## 🟢 Beginner Level

The Beginner section introduces the basic concepts required to work with images using Python and OpenCV.

### Topics

* Loading and displaying images
* Image properties and dimensions
* Color-space basics
* Grayscale conversion
* Basic image manipulation
* Fundamental OpenCV operations

📂 **Directory:** `Beginner/`

> The Beginner-level PDF/notebook is not included in the files currently available to me. It can be added to this section once provided.

---

# 🟡 Intermediate Level

The Intermediate section focuses on fundamental image transformations and enhancement techniques.

### Experiments

#### 1. Resize an Image Using Different Interpolation Methods

Comparison of:

* Nearest Neighbor
* Bilinear / Linear interpolation
* Bicubic interpolation

The experiment demonstrates how different interpolation algorithms affect image resizing.

#### 2. Rotate an Image by Different Angles

Image rotation using geometric transformations around the image center, including different rotation angles.

#### 3. Add Noise to an Image

Generation of noise on an image to study image degradation and noise-processing concepts.

#### 4. Image Processing Operations

Additional intermediate-level image-processing operations included in the provided assignment.

#### 5. Image Analysis

Practical image-analysis operations using OpenCV.

#### 6. Histogram Calculation and Visualization

Calculation and visualization of the grayscale intensity distribution from `0–255` using an image histogram.

#### 7. Histogram Equalization

Improving global image contrast using histogram equalization.

📂 **Directory:** `Intermediate/`

---

# 🟠 Slightly Challenging Level

This section moves from basic image manipulation toward practical computer-vision operations.

### Experiments

#### 1. Image Addition and Subtraction

Performs element-wise addition and subtraction between two images while handling pixel-value saturation.

#### 2. Image Blending

Combines two images using weighted addition to produce a blended output.

#### 3. Erosion and Dilation

Implementation of fundamental morphological operations:

* Erosion
* Dilation

These operations demonstrate how structural elements can shrink or expand foreground regions.

#### 4. Morphological / Image Processing Operations

Further image-processing operations using OpenCV morphological techniques.

#### 5. Detect and Count Objects Using Contours

Uses thresholding and contour detection to identify structural boundaries and count detected objects.

#### 6. Segment an Object Based on Color

Uses the **HSV color space** and a color mask to isolate objects based on their color characteristics.

📂 **Directory:** `Slightly-Challenging/`

---

# ☁️ Running the Notebooks

The notebooks are designed for **Google Colab**.

### Option 1 — Open from GitHub

After the notebooks are uploaded to GitHub:

1. Open the required `.ipynb` file.
2. Select **Open in Colab**.
3. Upload the required input image when prompted.
4. Run the cells sequentially.
5. Observe the generated image-processing results.

### Option 2 — Open Directly in Google Colab

Use:

```text
https://colab.research.google.com/
```

Then select:

**File → Open notebook → GitHub**

and enter this repository.

---

# 🎯 Learning Objectives

Through these experiments, I am building practical understanding of:

* Image representation
* Pixel-level operations
* Image resizing
* Interpolation techniques
* Geometric transformations
* Image noise
* Histograms
* Contrast enhancement
* Image arithmetic
* Morphological image processing
* Thresholding
* Contour detection
* Object counting
* Color-based segmentation
* HSV color space

---

# 📈 Learning Progression

```text
Image Fundamentals
        ↓
Basic OpenCV
        ↓
Image Transformations
        ↓
Noise & Histograms
        ↓
Image Enhancement
        ↓
Morphological Processing
        ↓
Contour Detection
        ↓
Object Counting
        ↓
Color Segmentation
        ↓
Computer Vision
```

---

# 💡 Key Takeaways

These experiments helped me understand how Computer Vision systems process images at different levels — from manipulating individual pixels to extracting meaningful objects and regions.

The progression also provides a foundation for more advanced topics such as:

* Object detection
* Feature extraction
* Image classification
* Face detection
* Machine Learning for Computer Vision
* Deep Learning
* CNN-based image recognition

---

## 👨‍💻 Author

**Chinmay Yalawatti**

Electronics & Communication Engineering

Interested in:

`Embedded Systems` • `Computer Vision` • `AI/ML` • `IoT` • `FPGA/VLSI`

---

## ⭐ Repository Goal

This repository is part of my continuous learning journey in **Python, Computer Vision, AI/ML, and practical engineering**.

More experiments and projects will be added as I progress.

⭐ If you find this repository useful, consider giving it a star.

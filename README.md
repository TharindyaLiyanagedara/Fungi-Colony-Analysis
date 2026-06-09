# 🍄 Fungal Colony Detection and Growth Analysis

## 📖 Overview

This project focuses on the detection and analysis of fungal colony growth using digital image processing techniques. A series of fungal colony images captured at different growth stages are processed to isolate the colony region from the background, enabling automated monitoring and analysis of colony expansion over time.

The system utilizes image preprocessing, segmentation, thresholding, and binary image generation techniques to accurately identify fungal growth regions and support quantitative growth assessment.

## 🎯 Objectives

* Detect fungal colonies from digital images.
* Separate fungal regions from the background.
* Generate binary masks for colony identification.
* Track fungal colony growth over time.
* Support automated biological image analysis.

## 🔬 Methodology

### 1. Image Acquisition

A sequence of fungal colony images was collected at different stages of growth.

### 2. Image Preprocessing

The images undergo several preprocessing steps, including:

* Image loading
* Noise reduction
* Color space conversion
* Contrast enhancement

### 3. Segmentation

Image segmentation techniques are applied to separate the fungal colony from the background.

### 4. Binary Mask Generation

A binary image is generated where:

* White pixels represent fungal colony regions.
* Black pixels represent the background.

### 5. Growth Analysis

The extracted colony regions can be used to:

* Measure colony area
* Compare growth progression
* Monitor fungal expansion over time

## 📊 Sample Results

### Original Images

* Sequential fungal colony growth images
* Visible increase in colony size over time

### Processed Images

* Binary segmented masks
* Colony region successfully isolated from the background

## 🛠 Technologies Used

* Python
* OpenCV
* NumPy
* Matplotlib
* Scikit-Image
* Jupyter Notebook

## Retinal Blood Vessel Segmentation for Early Diabetic Retinopathy Detection
### BMEN 623- Group 1
#### Kennedy Connors
#### Regan Kane 
#### Sepehr Akhiani

## Overview  
This project aims to develop a practical methodology for retinal blood vessel segmentation to facilitate the early detection of diabetic retinopathy. By utilizing fundamental image processing techniques such as contrast enhancement, noise reduction, and targeted segmentation, this work seeks to improve the accuracy and reliability of identifying vascular structures in fundus images.

## Objectives  

### **Aim 1: Develop a preprocessing pipeline for retinal fundus images**  
This aim focuses on enhancing image quality through conversion to grayscale, applying Contrast Limited Adaptive Histogram Equalization (CLAHE) for contrast enhancement, and implementing noise reduction techniques such as Gaussian filtering to improve vessel visibility while preserving other critical structures. Additionally, optic disc localization and removal using anisotropic diffusion filtering, thresholding, and morphological operations will be performed in this preprocessing stage to prevent false vessel detection. Preprocessing effectiveness will be evaluated by comparing segmentation performance (Dice coefficient, accuracy) between grayscale and green channel extraction methods.

### **Aim 2: Implement and refine blood vessel segmentation techniques**  
To accurately extract retinal vascular networks, we will apply edge detection methods, such as Sobel and Canny filters, and adaptive thresholding, complemented by morphological operations to enhance segmentation performance. Segmentation outcomes will be quantitatively assessed using the Dice coefficient and accuracy metrics.


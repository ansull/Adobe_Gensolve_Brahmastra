# Adobe_Gensolve_Brahmastra

# CURVETOPIA: A Deep Dive into Curves

## Overview

CURVETOPIA is an innovative project that aims to revolutionize the way curves are represented in digital art. By leveraging advanced algorithms, the project seeks to regularize, detect symmetry, and complete curves, transforming raster line art into a series of connected cubic Bezier curves. This initiative promises to enhance the precision and aesthetic quality of digital artworks.

## Goals

The core objectives of CURVETOPIA are:

- **Curve Regularization:** Convert diverse sets of curves into standardized geometric forms.
- **Symmetry Detection:** Identify and enhance reflective symmetries within closed shapes.
- **Curve Completion:** Restore interrupted or occluded curves to their original, smooth forms.

## Methodology

CURVETOPIA's approach is divided into three main challenges:

1. **Regularizing Curves:** Detect and refine specific shapes (e.g., lines, circles) based on predefined geometric properties using K-Means clustering.
2. **Symmetry Exploration:** Utilize convolutional neural networks (CNNs) to detect and enhance symmetry in curves.
3. **Curve Completion:** Employ Generative Adversarial Networks (GANs) to reconstruct missing segments of curves.

## Implementation

### Data Handling

Data is sourced from CSV files containing sets of curves represented by their x and y coordinates. The data is preprocessed to facilitate regularization, symmetry analysis, and curve completion.

### Curve Regularization

K-Means clustering is used to classify and regularize curves into specific geometric shapes, streamlining their form.

### Symmetry Detection

A CNN model is trained to identify symmetrical patterns in curves, enhancing the visual harmony of the artwork.

### Curve Completion

GANs are employed to fill in gaps within interrupted curves, ensuring a smooth, continuous shape.

## Experiments and Results

- **Visualization:** Curves are visualized using matplotlib, showcasing their structure before and after processing.
- **Feature Extraction:** Evaluates the effectiveness of K-Means in regularizing curves.
- **Symmetry Analysis:** Tests the CNN model on various shapes, assessing its accuracy.
- **Completion:** Demonstrates the GAN model's ability to reconstruct incomplete curves.

## Conclusion

CURVETOPIA introduces a novel method for converting line art into structured, regularized curves. The project addresses critical challenges in curve regularization, symmetry detection, and completion, offering valuable tools for digital artists and designers.

## Usage

To get started with CURVETOPIA, clone the repository and follow the installation instructions. Detailed examples are provided in the `examples` directory to help you understand how to use the various functions and models.

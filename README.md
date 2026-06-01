# MRI Segmentation using MedSAM under K-Space Subsampling

## Overview

This project investigates the impact of k-space subsampling on magnetic resonance imaging (MRI) quality and its effect on automatic medical image segmentation using MedSAM.

The objective is to evaluate how reducing the amount of acquired MRI data affects segmentation performance, image quality and the reliability of AI-assisted medical image analysis.

The study combines concepts from medical imaging, image reconstruction and deep learning-based segmentation.

---

## Objectives

* Analyze the effect of k-space subsampling on MRI reconstruction quality.
* Evaluate segmentation performance under different sampling rates.
* Measure the robustness of MedSAM when working with degraded MRI data.
* Compare segmentation results across multiple reconstruction scenarios.
* Identify the trade-off between acquisition efficiency and segmentation accuracy.

---

## Technologies

* Python
* MedSAM
* NumPy
* OpenCV
* Medical Imaging
* Deep Learning
* MRI Reconstruction

---

## Methodology

The project follows the following workflow:

1. Acquisition of MRI images.
2. Simulation of different k-space subsampling levels.
3. Image reconstruction from subsampled data.
4. Automatic segmentation using MedSAM.
5. Evaluation and comparison of segmentation performance.

Different subsampling configurations are analyzed to quantify their impact on image quality and segmentation accuracy.

---

## Experimental Setup

The experiments evaluate multiple reconstruction scenarios generated from different sampling ratios.

For each configuration:

* MRI images are reconstructed.
* MedSAM performs automatic segmentation.
* Segmentation quality metrics are computed.
* Results are compared against reference images.

---

## Repository Structure

```text
dataset/        -> MRI datasets and image samples
src/            -> Source code
results/        -> Segmentation outputs and evaluation metrics
docs/           -> Project report and supporting material
```

---

## Results

The experiments show how image degradation caused by k-space subsampling influences the performance of AI-based segmentation systems.

Key findings include:

* Relationship between sampling rate and image quality.
* Impact of reconstruction quality on segmentation accuracy.
* Robustness limits of MedSAM under degraded imaging conditions.
* Trade-off between acquisition speed and diagnostic information preservation.

---

## Skills Demonstrated

* Medical Image Analysis
* Computer Vision
* Deep Learning
* AI-assisted Segmentation
* Experimental Design
* Data Analysis
* Scientific Research
* Python Development

---

## Future Work

Potential improvements include:

* Evaluation using additional segmentation models.
* Testing alternative reconstruction techniques.
* Extension to larger and more diverse MRI datasets.
* Comparison with fully supervised segmentation approaches.

---

## Author

**Mauro Martínez Cazaux**

Data Engineering Student – Universidad Politécnica de Cartagena (UPCT)

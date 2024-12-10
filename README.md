# FRINT - Frame Interpolation Model

## Overview
FRINT (FRame-INTerpolation) is a model designed for frame interpolation using advanced deep learning techniques. The model leverages optical flow estimation, self-attention mechanisms, and multi-scale feature extraction to achieve high-quality interpolated frames.

## Requirements
- Python 3.6 or higher
- TensorFlow 2.x
- TensorFlow Addons
- NumPy
- Matplotlib

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Dedeep007/FRINT-FRame-INTerpolation-model.git
   cd FRINT-FRame-INTerpolation-model
   pip install tensorflow tensorflow-addons numpy matplotlib

## Model Components
### WarpLayer
A custom layer to handle dense image warping using optical flow.

### Self-Attention Block
Implements self-attention mechanism with dense layers for capturing dependencies.

### Residual Block
Uses depthwise separable convolutions and squeeze-and-excitation for enhanced feature extraction.

### Feature Extractor
Extracts multi-scale features using depthwise convolutions.

### Optical Flow Estimation
Estimates optical flow between input frames and warps frames accordingly.

## Colab Link:
https://colab.research.google.com/drive/1my3ju-hEG_yfeLsISJKtyE05_EXlFcvk?usp=sharing

## Dataset:
It is provided as a zip.
Alternatively, you can decompose a video into individual frames, categorize them into three distinct groups, preprocess the frames by converting them into normalized vectors, and store these vectors using frame splitter mentioned in the notebook.

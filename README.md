# Crowd Density Estimation

This project implements a deep learning-based crowd density estimation system using a convolutional neural network. The objective is to analyze video or image frames and estimate the number of people in crowded scenes.

## Features

- Uses a pre-trained CSRNet model for density map generation.
- Processes image frames to estimate crowd counts.
- Visualizes density maps alongside original input images.
- Supports evaluation using ground truth counts.

## Requirements

- Python 3.8+
- PyTorch
- OpenCV
- NumPy
- Matplotlib
- PIL (Pillow)
- tqdm

## Dataset
This project is compatible with public datasets such as:

- ShanghaiTech Part A & B
- UCF_CC_50

Ensure your dataset is structured correctly as expected in the notebook.

## Output

- Estimated count per frame.
- Visualized density map.

# The Illusion of Accuracy: Auditing CNN Shortcut Learning

## Overview
Deep learning models often achieve high accuracy by memorizing background correlations rather than learning the actual target concept—a phenomenon known as the "Clever Hans" effect. This project provides a hands-on toolkit for auditing Convolutional Neural Networks (CNNs) to expose these hidden contextual biases. 

By utilizing Gradient-weighted Class Activation Mapping (Grad-CAM) and Occlusion Sensitivity Testing, this project visualizes network attention, stress-tests spatial resilience, and exposes contextual hallucinations in pre-trained models. It prioritizes universal accessibility by utilizing perceptually uniform colormaps and geometric dual-coding for all visual outputs.

## What to Install
To execute the project, you will need a Python environment with the following standard machine learning and computer vision libraries installed:
* PyTorch
* Torchvision
* OpenCV (opencv-python)
* Pillow
* Matplotlib
* NumPy
* Requests

You can install these packages via your preferred Python package manager.

## How to Run
1. Download or clone this repository to your local machine.
2. Open your terminal or command line interface and navigate into the project folder.
3. Ensure your Python environment is active and all required libraries are successfully installed.
4. Launch your preferred interactive Python environment or notebook editor and open the main project document.
5. Execute the cells sequentially from top to bottom. The script will automatically initialize the pre-trained model, generate the synthetic or fetched test images, and output the side-by-side diagnostic heatmaps.

## License
This project is licensed under the MIT License. You are free to use, modify, and distribute this software under the terms of the license.

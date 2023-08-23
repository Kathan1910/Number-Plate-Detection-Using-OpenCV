# Number Plate Detection Using OpenCV and EasyOCR

Welcome to the documentation of the Number Plate Detection project. This project focuses on implementing a simple yet effective method to detect and extract number plates from images using OpenCV and the EasyOCR library. In this documentation, we'll provide an overview of the project, steps taken, and instructions on how to use it.

## Table of Contents

- [Introduction](#introduction)
- [Problem Statement](#problem-statement)
- [Project Architecture](#project-architecture)
- [Usage](#usage)
- [License](#license)

## Introduction

Number Plate Detection is a computer vision project aimed at automatically locating and extracting license plate information from images. This project uses the power of OpenCV for image processing and EasyOCR for optical character recognition, allowing for efficient number plate extraction and text recognition.

## Problem Statement

The primary objective of the Number Plate Detection project is to develop a reliable method to detect and extract license plate information from images. This involves several challenges, including:
- Accurate identification of license plate regions in images.
- Handling variations in license plate appearance due to lighting conditions, angles, and vehicle types.
- Efficiently recognizing and extracting alphanumeric characters from the detected plates.

## Project Architecture

The Number Plate Detection project consists of the following key steps:

1. Image Preprocessing:
   - Loading images using OpenCV.
   - Converting images to grayscale.
   - Applying image transformations (blurring, thresholding, etc.) to enhance plate visibility.

2. License Plate Detection:
   - Utilizing the Haarcascade classifier in OpenCV to detect potential plate regions.
   - Applying filters and techniques to refine the detected regions.

3. Optical Character Recognition (OCR):
   - Using the EasyOCR library for text recognition on the detected plates.
   - Extracting alphanumeric characters from the recognized text.

4. Displaying Results:
   - Visualizing the detected plates and the extracted text on the original images.

## Usage

1. Prepare the input images containing vehicles with visible number plates.
2. Execute the project script for number plate detection and recognition.
3. View the output images with detected plates and extracted text.

For detailed code examples and usage instructions, please refer to the [documentation](docs/README.md).


## License

This project is licensed under the [MIT License](LICENSE).

---

Thank you for exploring the Number Plate Detection Using OpenCV and EasyOCR documentation. We hope this project proves useful in automatically extracting license plate information from images. If you have any questions or feedback, please feel free to reach out.

Safe driving!

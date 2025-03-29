# Number Plate Recognition System

A Python-based application for recognizing number plates from images using **EasyOCR**. This system leverages computer vision techniques for image preprocessing and Optical Character Recognition (OCR) to extract text from number plates.

## Features
- Image preprocessing (grayscale conversion, blurring) to enhance OCR accuracy.
- Number plate text extraction using the EasyOCR library.
- Display of the original image with the recognized text as the title.
- Simple interpretation of the recognized text as a potential number plate.
- Supports processing of uploaded image files.
- Includes a Colab-specific implementation for capturing images directly from a webcam.

## Tech Stack
- **Python** - Programming language.
- **EasyOCR** - Library for Optical Character Recognition.
- **OpenCV (cv2)** - Library for image processing.
- **Matplotlib (pyplot)** - Library for displaying images.
- **Google Colab Specific:**
    - `google.colab.files` for file uploading.
    - `IPython.display` and `google.colab.output.eval_js` for webcam interaction.
    - `base64` and `numpy` for handling image data from the webcam.

## Installation (for local setup)

1. **Install Python** (if not already installed).

2. **Install required libraries:**
   ```sh
   pip install easyocr opencv-python matplotlib

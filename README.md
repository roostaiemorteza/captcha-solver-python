# CAPTCHA Solver with Python, Selenium & OCR

A Python automation project that uses Selenium, OpenCV, and Tesseract OCR to detect and read simple image-based CAPTCHA challenges.

## Overview

The script automates a browser workflow, captures a CAPTCHA image, applies image preprocessing, and uses OCR to extract the CAPTCHA text.

This project is intended for automation experiments and development with simple CAPTCHA implementations.

## Features

- Selenium browser automation
- Firefox WebDriver support
- CAPTCHA screenshot capture
- OpenCV image preprocessing
- Tesseract OCR integration
- Multiple OCR configurations for improved recognition
- Automatic CAPTCHA text entry into a web form

## Workflow

1. Open the target webpage with Selenium.
2. Locate the CAPTCHA image.
3. Capture the CAPTCHA as an image.
4. Convert and preprocess the image using OpenCV.
5. Run Tesseract OCR with multiple configurations.
6. Validate the extracted text.
7. Enter the recognized CAPTCHA into the target form.

## Requirements

Python 3.x and the following packages are required:

```bash
pip install selenium
pip install pillow
pip install pytesseract
pip install opencv-python
pip install numpy
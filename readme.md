# OCR Web Application with Tesseract and Streamlit

This project is an Optical Character Recognition (OCR) web application built using Python, Tesseract, and Streamlit. It extracts text from images in multiple languages (English and Hindi) using Tesseract's OCR capabilities and displays the results in a user-friendly interface.

## Table of Contents
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Troubleshooting](#troubleshooting)
- [Technologies](#technologies)
- [Contributing](#contributing)
- [License](#license)

## Features
- Extracts text from uploaded images.
- Supports multiple languages (English + Hindi).
- Displays recognized text in real-time.
- Streamlit-based interface for ease of use.

## Prerequisites
Before running this project, ensure you have the following installed:
- [Python 3.x](https://www.python.org/downloads/)
- [Tesseract OCR](https://github.com/tesseract-ocr/tesseract) (Install Tesseract for your OS)
  - Make sure to set the `TESSDATA_PREFIX` environment variable to the location of the `tessdata` folder in the Tesseract installation.
- [Streamlit](https://docs.streamlit.io/library/get-started/installation)

### Installing Tesseract on Windows
1. Download and install Tesseract from [here](https://github.com/tesseract-ocr/tesseract).
2. Set the `TESSDATA_PREFIX` environment variable:
   - Right-click on `This PC` or `My Computer`, select `Properties` → `Advanced system settings` → `Environment Variables`.
   - Create a new environment variable:
     - Variable name: `TESSDATA_PREFIX`
     - Variable value: `C:\Program Files\Tesseract-OCR\`



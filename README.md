# ComputerVisionProject
How to Run the Project (Google Colab)

Open Google Colab

Upload the notebook file ProjectCV.ipynb

Run the installation cell:

!sudo apt install tesseract-ocr
!pip install pytesseract opencv-python-headless numpy


Upload any image:

from google.colab import files
uploaded = files.upload()


Run the OCR function:

run_ocr("your_image_name.jpg")

Project Structure
ProjectCV.ipynb   → Main OCR code (Google Colab notebook)
README.md         → Project documentation

Main Dependencies

Python 3

OpenCV

NumPy

pytesseract

Tesseract OCR Engine

Google Colab environment

Features

Upload any image from your device

Automatic preprocessing (resize, grayscale, sharpen, threshold)

OCR text extraction using Tesseract

Displays original and processed images

Outputs recognized text

# ComputerVisionProject
How to run the project

1-Open Google Colab

2-Upload the .ipynb file

3-Run the installation for ocr:
!sudo apt install tesseract-ocr
!pip install pytesseract opencv-python-headless numpy

4-Upload the image:
from google.colab import files
uploaded = files.upload()


5-Run the OCR function:
run_ocr("imageName.jpg/png")

Core dependencies	
-Python 3
-OpenCV
-NumPy
-pytesseract
-Tesseract OCR Engine
-Google Colab environment

Features:
Upload any image from your device
Automatic preprocessing (resize, grayscale, sharpen, threshold)
OCR text extraction using Tesseract
Displays original and processed images
Outputs recognized text

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

Core dependencies:
-Python 3
-OpenCV
-NumPy
-pytesseract
-Tesseract OCR Engine

Features:
Upload any image
preprocessing: resize, grayscale, sharpen, and threshold
OCR text extraction
Display both original and processed image
Output the extracted text

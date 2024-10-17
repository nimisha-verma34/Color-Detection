# Color-Detection
Color Detection using Open CV 
Overview
This project involves building a color detection system using Python, OpenCV, Pandas, and NumPy. The program identifies colors from an image by reading pixel values and matching them with a predefined dataset of colors.

Features
Detects and identifies colors from any image.
Real-time color detection through user-provided images.
Interactive interface that displays the name of the detected color when hovering over an image pixel.
Technologies Used
Python: For the main logic and implementation.
OpenCV: For image processing and pixel color extraction.
Pandas: To handle the color dataset in CSV format.
NumPy: For efficient numerical operations.
How It Works
The program reads an input image using OpenCV.
When the user clicks on a pixel in the image, the program retrieves the RGB value of the pixel.
The RGB value is then compared against a CSV file containing color names and RGB values to find the closest match.
The name of the detected color is displayed in the output.

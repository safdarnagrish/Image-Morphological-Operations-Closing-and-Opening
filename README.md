# Image Morphological Operations: Closing and Opening

## University Project

This repository contains a Python project demonstrating the application of morphological operations, specifically closing and opening, on a grayscale image using the OpenCV library. This project is part of a university assignment focusing on digital image processing techniques.

## Project Overview

Morphological operations are fundamental image-processing techniques used to extract and manipulate the structure of objects within an image.

- **Closing Operation**: This operation is a dilation followed by an erosion. It is useful for closing small holes inside foreground objects or eliminating small black points on the object.

- **Opening Operation**: This operation is an erosion followed by a dilation. It is effective for removing small objects from the foreground (typically noise).

This project demonstrates these operations on an input image and displays the original, closed, and opened images side by side.

## Features


- Input Image: The project reads an image in grayscale mode.
- Closing Operation: Fills small holes and removes small dark spots from the foreground.
- Opening Operation: Removes small objects or noise from the foreground.
- Visualization: Uses Matplotlib to display the original, closed, and opened images.

## Getting Started
### Prerequisites
Make sure you have the following packages installed:

Python 3.x
OpenCV (cv2)
NumPy
Matplotlib
You can install the required packages using pip:

Copy code
```
pip install opencv-python numpy matplotlib
```
### Running the Project
1. Clone the repository:

Copy code
```
git clone https://github.com/safdarnagrish/morphological-operations.git
cd morphological-operations
```
2. Place your input image (e.g., beauty.jpg) in the project directory.

3. Run the Python script:

Copy code
```
python morphological_operations.py
```
4. The script will display the original image, the result of the closing operation, and the result of the opening operation side by side.

### Project Structure

- morphological_operations.py: The main script that reads the image, applies the closing and opening operations, and displays the results.
- README.md: This file, provides an overview of the project and instructions for use.
- beauty.jpg: The input image used for demonstration (you can replace this with your own image)
  
### Example Output

After running the script, you should see a window displaying three images:

- Original Image: The unprocessed grayscale image.
- Closing Operation: The image after applying the closing operation.
- Opening Operation: The image after applying the opening operation.
  
### Usage

This project can serve as a foundation for more advanced image-processing tasks. You can modify the kernel size or apply these operations to different images to observe their effects.

### License

This project is open-source and available under the MIT License. Feel free to modify and use the code as needed.

### Acknowledgments
- This project was developed as part of a university course on Digital Image Processing.
- The morphological operations implemented here are based on standard techniques in image processing, using the OpenCV library.

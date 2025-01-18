# Exercise 1: Image Inspector

## Objective
Create a program that loads an image and reports its key properties. This will help understand how images are represented in OpenCV and NumPy.

## Requirements
1. Create a function that takes an image path as input
2. The function should return or display:
   - Image dimensions (height, width)
   - Number of color channels
   - Data type of pixel values
   - Size in memory (KB/MB)
   - Minimum and maximum pixel values for each channel
   - Mean and standard deviation of pixel values

## Steps to Complete
1. Write code to load an image using OpenCV
2. Extract basic properties using NumPy array attributes
3. Calculate additional statistics using NumPy functions
4. Format the output in a clear, readable way
5. Add error handling for:
   - File not found
   - Invalid image format
   - Corrupted image files

## Extension Challenges
- Add visualization of pixel value distribution (histogram)
- Support for both color and grayscale images
- Memory usage comparison between different image formats
- Option to display results both in terminal and as saved text file

## Tips
- Use cv2.imread() for loading images
- Remember OpenCV loads images in BGR format
- Look into .shape, .dtype, and .size attributes of NumPy arrays
- Consider using try/except blocks for error handling

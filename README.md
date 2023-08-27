Assignment: Image Processing Techniques

This repository contains code and explanations for various image processing techniques. The assignment involves implementing and demonstrating concepts such as histogram equalization, vibrance enhancement, filtering with Sobel operators, foreground histogram equalization, and image zooming with nearest-neighbor and bilinear interpolation.

Contents
Vibrance Enhancement:
Implemented an intensity transformation to enhance vibrance.
Split the image into hue, saturation, and value planes.
Applied the intensity transformation to the saturation plane.
Fine-tuned parameter 'a' for desired visual enhancement.
Recombined the planes and displayed results.
Histogram Equalization:
Created a custom function for histogram equalization.
Applied the function using numpy and OpenCV.
Plotted histograms before and after equalization for comparison.
Zooming Images:
Developed a program to zoom images by a given factor.
Implemented nearest-neighbor and bilinear interpolation methods.
Organized code into separate functions for each method.
Sobel Filtering:
Utilized filter2D to apply Sobel filter for gradient computation.
Implemented custom Sobel filtering code for edge detection.
Demonstrated convolution with sepFilter2D using Sobel kernel.
Foreground Histogram Equalization:
Equalized the histogram of the foreground in an image.
Extracted foreground using masks and bitwise operations.
Calculated histograms and cumulative sums for the foreground.
Employed formulas to equalize the histogram and recombine the image.
Images and Outputs:
Included input images for various parts of the assignment.
Provided output images showcasing the results of each operation.
Displayed plots and histograms to visualize the transformations.
Instructions
Clone the repository to your local machine.
Navigate to specific directories for each technique.
Run the provided scripts using your preferred Python interpreter.
Review the generated images and plots for the results.
Experiment with parameters and images to further explore the techniques.
Dependencies
Python 3.x
OpenCV
Numpy
Matplotlib
Contributions
Contributions to this repository are welcome! If you have any improvements or additional techniques to share, feel free to submit a pull request.

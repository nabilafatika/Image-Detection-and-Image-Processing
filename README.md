# Image Detection with Python
Object detection is a technology that falls under the broader domain of Computer Vision. This method is concerned with identifying and tracking objects present in images and videos. Object detection has many applications such as face detection, vehicle detection, pedestrian counting, autonomous vehicles, security systems, etc.

The two main objectives of object detection include: • To identify all objects present in an image • Filtering objects

# Image Processing with Python
Contains several mandatory modules used in this notebook: numpy, pandas, cv2, skimage, PIL, matplotlib. 
<ul> • Numpy is a library for array manipulation, used for linear algebra, Fourier transformations, and random number capabilities.</ul>
<ul> • Pandas is a library for data manipulation and data analysis. </ul>
<ul> • CV2 is a library for computer vision tasks.</ul>
<ul> • Skimage is a library that supports image processing applications in Python.</ul>
<ul> • Matplotlib is a library that generates images and provides a graphical user interface toolkit.</ul>

# Read Image from Device
We will read an image from a device and display it using OpenCV. Note the difference when reading images in RGB and BGR formats. The default color channel input format for OpenCV is BGR.

# Read the Image from The URL and Display It
Search for an image on Google, then use the URL address of that image to perform the operations below by uncommenting the code.

# Generating a Histogram for Color and Grayscale Images
Sometimes you want to enhance the contrast in an image or expand the contrast in a specific region while sacrificing details in less varied or less important colors. A good tool to identify regions of interest is the histogram. To create a histogram from our image data, we use the matplotlib.pylab hist() function. Displaying the histogram of all pixels in a color image.

# Find The Contours of The Image from The Grayscale Image
Method 1: Use matplotlib.contour
Method 2: Use the OpenCV library

# Grayscale Transformation
Provides some examples of performing mathematical transformations on grayscale images.

# Histogram Equalization
Demonstrates histogram equalization on a dark image. This transformation equalizes the grayscale histogram so that all intensities become as uniform as possible. The transformation function is the cumulative distribution function (CDF) of pixel values in the image (normalized to map the range of pixel values to the desired range). This example uses image 4 (im4).

# Fourier Transformation of Grayscale Image
Fourier transformation is used to find the frequency domain of an image. You can think of an image as a signal sampled in two directions. So taking the Fourier transformation in both the X and Y directions gives you a representation of the image's frequency. For sinusoidal signals, if the amplitude changes very rapidly over a short period of time, it can be said that it is a high-frequency signal. If it varies slowly, it is a low-frequency signal. Edges and noise are high-frequency content in the image because they change drastically in the image.

# Finding Edges with Highpass Filtering in FFT
Demonstrates performing a high-pass filter to remove low-frequency components, thus resulting in a sharp image containing its edges.


This project is part of my coursework for the Artificial Intelligence class during my college years. It focuses on advanced topics in Machine Learning, particularly Image Detection and Image Processing. 
<p>Nabila Fatika - 2024</p>

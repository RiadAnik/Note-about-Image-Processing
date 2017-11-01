# 1. What is Filtering in Image Processing?

At first we should what is filter means in image processing. Filtering is a technique for modifying or enhancing an image. 
For example, you can filter an image to emphasize certain features or remove other features. Image processing operations implemented with filtering include smoothing, sharpening, and edge enhancement.

# 2. What is the functionality of Gabor Filter?

Gabor filters are generally used in texture analysis, edge detection, feature extraction, disparity estimation (in stereo vision), etc. Gabor filters are special classes of bandpass filters, i.e., they allow a certain ‘band’ of frequencies and reject the others.


# 3.My purpose of learning Gabor Filter

My project is to detect road detection by using voting scheme based vanishing point detection algorithm. So, I have determined texture orientation of each pixel by using Gabor Filter. Now we should know what do it means by texture Orientation.
It is nothing but gradient image. Now What is gradient of an Iamge?

An image gradient is a directional change in the intensity or color in an image. The gradient of the image is one of the fundamental building blocks in image processing. For example the Canny edge detector uses image gradient for edge detection.

![gradient2 svg](https://user-images.githubusercontent.com/21199518/32272286-ab436f90-bf27-11e7-867c-682276ef88a5.png)


In the above two images, the values of the function are represented in black and white, black representing higher values, and its corresponding gradient is represented by blue arrows.

Now, i have found the directional response of each pixel and this is going to be necessary for voting method to identify the vanishing point.

# Learn more about Gabor Filter from below links:


1.https://cvtuts.wordpress.com/2014/04/27/gabor-filters-a-practical-overview/


2.https://en.wikipedia.org/wiki/Gabor_filter


3.https://www.youtube.com/watch?v=-NZakhhB_Do


4.https://stackoverflow.com/questions/20608458/gabor-feature-extraction


5.https://stackoverflow.com/questions/7419409/image-processing-using-gabor-filter

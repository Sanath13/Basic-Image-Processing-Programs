# Basic-Image-Processing-Programs

Basic Image Processing programs made easier to understand

**1. Smoothing**

Average smoothing  is done by convolving the image with a normalized box filter. It simply takes the average of all the pixels under kernel area and replaces the central element with this average.

**2. Histogram**

Histogram is considered as a graph or plot which is related to frequency of pixels in an Gray Scale Image with pixel values (ranging from 0 to 255). Grayscale image is an image in which the value of each pixel is a single sample, that is, it carries only intensity information where pixel value varies from 0 to 255. Images of this sort, also known as black-and-white, are composed exclusively of shades of gray, varying from black at the weakest intensity to white at the strongest where Pixel can be considered as a every point in an image.

In this program, we have manually calculated histogram of an image by using dictionaries and compared the results with opencv's in-built function cv2.calcHist()

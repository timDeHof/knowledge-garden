---
id: evaavg2uywbq035g3910aj9
title: Image Processing
desc: ""
updated: 1666798573846
created: 1666796396592
---

Image processing allows us to transform and manipulate thousands of images at a time and extract useful insights from them. It has a wide range of applications in almost every field.

[more Information](https://neptune.ai/blog/image-processing-python#:~:text=Image%20processing%20allows%20us%20to,programming%20languages%20for%20this%20purpose.)

## Image processing tools

1.  OpenCV
    : Openc Source Computer Vision Library

    ### ways you can use opencv in image processing:

    - Converting images from one color space to another i.e. like between BGR and HSV, BGR and gray etc.
    - Performing thresholding on images, like, simple thresholding, adaptive thresholding etc.
    - Smoothing of images, like, applying custom filters to images and blurring of images.
    - Performing morphological operations on images.
    - Building image pyramids.
    - Extracting foreground from images using GrabCut algorithm.
    - Image segmentation using watershed algorithm.

    Refer to [this link](https://opencv.org/) for more details.

2.  Scikit-image
    : an open-source library used for image preprocessing

    ### some operations that can be done using scikit image:

    - To implement thresholding operations use try_all_threshold() method on the image. It will use seven global thresholding algorithms. This is in the filters module.
    - To implement edge detection use sobel() method in the filters module. This method requires a 2D grayscale image as an input, so we need to convert the image to grayscale.
    - To implement gaussian smoothing use gaussian() method in the filters module.
    - To apply histogram equalization, use exposure module, to apply normal histogram equalization to the original image, use equalize_hist() method and to apply adaptive equalization, use equalize_adapthist() method.
    - To rotate the image use rotate() function under the transform module.
    - To rescale the image use rescale() function from the transform module.
    - To apply morphological operations use binary_erosion() and binary_dilation() function under the morphology module.

3.  PIL/pillow

    : stands for Python Image Library

    : To carry out manipulation operations there is a module in this library called Image.

    ### ways to carry out manipulation operations

    - To load an image use the open() method.
    - To display an image use show() method.
    - To know the file format use format attribute
    - To know the size of the image use size attribute
    - To know about the pixel format use mode attribute.
    - To save the image file after desired processing, use save() method. Pillow saves the image file in png format.
    - To resize the image use resize() method that takes two arguments as width and height.
    - To crop the image, use crop() method that takes one argument as a box tuple that defines position and size of the cropped region.
    - To rotate the image use rotate() method that takes one argument as an integer or float number representing the degree of rotation.
    - To flip the image use transform() method that take one argument among the following: Image.FLIP_LEFT_RIGHT, Image.FLIP_TOP_BOTTOM, Image.ROTATE_90, Image.ROTATE_180, Image.ROTATE_270.

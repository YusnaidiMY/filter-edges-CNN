# filter-edges-CNN
A Python program using OpenCV to demonstrate the use of a CNN filter to extract edge information from an input image. The image size is specified (using a resizing function) while the filter size is 3 x 3 with one channel.

The original file is located at
    https://colab.research.google.com/drive/136NtHZ-itJLIRu1AGOUl1BOh3kK1hJX_
    
This program demonstrates the use of a CNN filter to extract edge information from an image. 
The program allows the user to resize the input image to any pixel size, like 320 x 320, 128 x 128, etc. 
A filter of a 3 x 3 with one channel size is convoluted to the input image of the feature image to 
generate the feature map output, showing the edges of objects detected in the image. 
The original input image and the resulting feature map are shown using Matplotlib's 
subplot which is shown side by side for easy interpretation. Experiment with the edge detection quality 
by applying normalization and compare it without applying normalization.

Authors: Yusnaidi Md Yusof / yusnaidi.kl@utm.my, 
         Azizul Azizan / azizulazizan@utm.my
Date: 7.1.2024
Copyright RFTI@UTM 2024.

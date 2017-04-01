# ComputerVision
Computer Vision projects.
A program change the color of the image based on a histogram computed from a window in the image.
The window is specified in terms of the normalized coordinates w1 h1 w2 h2, where the window upper left
point is (w1,h1), and its lower right point is (w2,h2). For example, w1=0,h1=0,w2=1,h2=1 is the entire
image, and w1=0.3,h1=0.3,w2=0.7,h2=0.7 is is window in the center of the image. The provided example
program proj1b.cpp shows how to go over the pixels of this window.
The scaling is to be performed in the xyY domain. The
scaling should stretch only the luminance (Y) values.I applied linear scaling that would map
the smallest Y value in the specified window and all values below it to 0, and the largest Y value in the
specified window and all values above it to 1.

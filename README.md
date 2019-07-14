# Environement Perception for Self Driving Cars

An Implementation of Environment Perception for a Self Driving Car for the Course Introduction to Self-Driving Cars (Coursera)

DESCRIPTION:
===========

Implemention of Drivable Surface Estimation, Lane estimation and 2D object and obstacle detection using the output of semantic segementation implemented using a convolutional neural network

- Input to the system is semantic segmentation output and depth map for every pixel in the images.

  The inputs are automatically imported and could be used through the following functions:

   DatasetHandler().rgb: a camera RGB image 
   DatasetHandler().depth: a depth image containing the depth in meters for every pixel.
   DatasetHandler().segmentation: an image containing the output of a semantic segmentation neural network as the category per pixel.
   DatasetHandler().object_detection: a numpy array containing the output of an object detection network.

- Output is as follows:
  1) Drivable surface plane parameters
  2) Lane boundary equations for the drivable surface
  3) minimum distance to the obstacles in 3D cordinates


SOLUTION :
---------

DRIVABLE SURFACE SHOWN IN YELLOW:
--------------------------------
![download](https://user-images.githubusercontent.com/32943733/61184746-c0a08400-a66a-11e9-9c1c-043efff0c2ad.png)

LANE MARKINGS FOR DRIVABLE SURFACE:
----------------------------------
![download (1)](https://user-images.githubusercontent.com/32943733/61184764-e29a0680-a66a-11e9-91d4-b123067a77d7.png)

LOCATION AND DISTANCE TO OBSTACLE:
-----------------------------------
![download (2)](https://user-images.githubusercontent.com/32943733/61184781-078e7980-a66b-11e9-8a98-d7adfb26f923.png)


Dependencies:
=============

- Jupyter Notebook
- Python 3.5 or 3.6

Running Autonomous Control:
==========================

# -Real-Time-AI-Face-Detection-with-Python-

**Face Detection with Python using OpenCV**

Face detection is a computer technology that determines the
locations and sizes of human faces in arbitrary (digital)
images. It detects facial features and ignores anything else,
such as buildings, trees and bodies. Human face perception is
currently an active research area in the computer vision
community. Human face localization and detection is often the
first step in applications such as video surveillance, human
computer interface, face recognition and image database
management. Locating and tracking human faces is a
prerequisite for face recognition and/or facial expressions
analysis, although it is often assumed that a normalized face
image is available.In this paper we intend to implement the
Haar-Classifier for Face detection and tracking based on the
HaarFeatures.


**Approach used for Implementation**
 

This project uses LBPH (Local Binary Patterns Histograms) Algorithm to detect faces. It labels the pixels of an image by thresholding the neighborhood of each pixel and considers the result as a binary number.
LBPH uses 4 parameters : 
(i) Radius: the radius is used to build the circular local binary pattern and represents the radius around the 
central pixel. 
(ii) Neighbors : the number of sample points to build the circular local binary pattern. 
(iii) Grid X : the number of cells in the horizontal direction. 
(iv) Grid Y : the number of cells in the vertical direction.
The model built is trained with the faces with tag given to them, and later on, the machine is given a test data and machine decides the correct label for it.

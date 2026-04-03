# NVIDIA-Image-Processing-
Aim
To convert an RGB pixel into grayscale using the luminance formula.
General Objective
To understand digital image representation and the process of colour-to-grayscale conversion as a fundamental preprocessing step in robotic vision systems.
Specific Objective
To compute grayscale intensity using:
G
r
a
y
=
0.3
R
+
0.59
G
+
0.11
B
Gray=0.3R+0.59G+0.11B
Given:
R
=
120
R=120
G
=
150
G=150
B
=
200
B=200
Dataset
CIFAR-10 Dataset
Source: University of Toronto
Procedure
Input RGB values
Apply grayscale formula
Multiply each channel with weights
Add the results
Display grayscale value
Algorithm
Start
Input values 
R
,
G
,
B
R,G,B
Apply formula
Compute grayscale value
Display result
Stop
Code Logic
gray = 0.3*R + 0.59*G + 0.11*B

The grayscale intensity of the given RGB pixel is:
Gray = 151
Industry Application
Grayscale conversion is used in:
Image preprocessing
Object detection
Face recognition
Autonomous systems
Companies like NVIDIA use this in:
Vision AI
Deep learning pipelines
GPU-accelerated image processing
Conclusion
The RGB to grayscale conversion simplifies image data while preserving important intensity information, making it essential for computer vision tasks.

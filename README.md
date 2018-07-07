# People-Counter
2nd Year Project
Summary: A system that tracks the number of people in a building. Dual authentication system: light gate (laser setup) and computer vision. I worked on the computer vision system using OpenCV in Python. 

## CV Algorithm
Capture image from camera → Apply background reduction → Image processing/medianblur → Find contours and centroids → Track movement of centroids → Update counter when centroid crosses line

## Directory content
Autonomous People Counter Final Report.pdf --> Full report

Computer_Vision.py --> Python code for computer vision system

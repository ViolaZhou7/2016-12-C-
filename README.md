# 2016-12-C-
Personal C++ projects

NOTE: right now, the code is not in a good coding convention, and there can be few improvements:
1. speed estimation - probably should apply optical flow
2. more verification needed
3. read input from video and store video frames in sequence
4. ...

Vehicle Detection and Speed Estimation

Abstract
In this project, we are going to simulate the road traffic and implement traffic management techniques by mainly applying OpenCV library. Fortunately, OpenCV is quite functional in computer vision field for its library.
Another notable feature is OpenCV is cross-platform, which is applicable in Windows, Linux and MacOS with different programming languages like C++, Python and Java.
OpenCV has large collection of computer vision computation algorithm, what we have done are background subtraction, finding contours, calculating optical flow and more.


Objectives
To evaluate and assess the ability of OpenCV libraries in traffic monitoring system and combine it with our own contribution.
To read images in sequence or a video from cameras as input data and apply operations on them.
To detect moving vehicles in a specified area, track them by finding contours and output them on screen.
To estimate the speed of vehicles to find speeding ones.


Methodology
To apply background subtraction to detect moving vehicles.
To apply perspective transformation on frames to map 3D points to 2D plane.
To apply contours detection to find contours of moving vehicles and edit threshold to reduce noise.
*To bound contours by rectangles or circles to find centers of contours for tracking purpose. 
*To apply sparse optical flow to find path of each moving object.
To use the transformed frame and reference area to assume the distance and calculate the speed

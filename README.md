# Mouse-free

# Overview / Usage
A python script developed here, detects a face and finds the landmarks for mouth and eyes. These landmarks are used as a mouse. Every angle and distance these landmarks move is used as a factor to control various mouse functions like scrolling, left click, right click. Apart from that, the person's hand is used as gesture to control various applications embedded in your PC.

# Methodology / Approach
It is built using dlib facial landmarks detector on OpenCV using python. It first finds all the landmarks and the distance and angles between them. Now every change in distance and angles between these points is recorded and functionality has been assigned.

# Technologies Used
OpenCV, dlib library: Facial landmark detector, python gui

# Key functions
1. Left wink: left click
2. Right wink: right click
3. Squinting eyes: turn on/off scrolling
4. Open Mouth: Activate/Deactivate cursor
5. Head Movement: Cursor movement/Scrolling
6. One finger: Brightness control
7. Two fingers: Screenshot
8. Three (or) Four (or) Five finger: Open respective applications 

# To Run Code
Run merge.py file

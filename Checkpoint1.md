# Goal

## Build a system that can:

1) Access webcam feed
2) Detect motion in the room
3) Draw bounding boxes around moving objects
4) Trigger simple alerts when movement occurs

## Topics to Learn

### OpenCV Basics

Understand:

1) Reading webcam feed
2) Displaying frames
3) Converting frames to grayscale
4) Gaussian blur
5) Frame differencing
6) Thresholding
7) Contours


## Recommended Resources
YouTube

1) [[Motion Detection Tutorial using OpenCV | Python Hackers Realm](https://www.youtube.com/watch?v=T-7OSD5a-88)] 

2) [[“OpenCV Python Tutorial for Beginners” by Murtaza Hassan](https://www.bing.com/videos/riverview/relatedvideo?q=%e2%80%9cOpenCV+Python+Tutorial+for+Beginners%e2%80%9d+by+Murtaza+Hassan&&mid=5208D39E081E57F5CA155208D39E081E57F5CA15&churl=https%3a%2f%2fwww.youtube.com%2fchannel%2fUCYUjYU5FveRAscQ8V21w81A&FORM=VAMGZC)]


## Documentation

1) [[OpenCV Tutorial](https://www.geeksforgeeks.org/python/opencv-python-tutorial/)]


## Mini Tasks

1) Show webcam feed
2) Show grayscale feed
3) Detect movement of hand
4) Ignore small movements/noise
5) Print “Motion Detected”

## Expected Output

1) A working webcam window where moving objects are highlighted with rectangles.
2) Write a small report of your work

## Suggestions

1) Dont perform everything in a single jupyter notebook, write modular python files and call them in main.py 

Suggested folder structure

```
.
├── main.py                          # Main integrated system
├── intruder_conversation.py         # Intruder detection & escalation
├── face_recognition_module.py       # Face enrollment & verification
├── voice_activator.py               # Voice command processing
├── test_webcam.py                   # Webcam test utility
├── test_mic_sounddevice.py          # Microphone test utility
├── enrollments/                     # Enrolled faces database
│   ├── people.json
│   └── <name>_emb.npy
└── assets/
    └── alarm.wav                    # Default alarm sound
```
2) Go throught the first video carefully


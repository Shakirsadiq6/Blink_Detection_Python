# Eye Blink Detection using MediaPipe and OpenCV
### Overview
This Python script utilizes the MediaPipe library and OpenCV to detect and count eye blinks in real-time using facial landmarks. The facial landmarks are obtained through the MediaPipe FaceMesh model, and specific landmarks for the left and right eyes are used to calculate the blink ratio. The script counts the total number of blinks and displays it on the screen.

### Description
The script captures video from the default camera (usually the webcam).<br>
It uses the MediaPipe FaceMesh model to detect facial landmarks.<br>
Specific landmarks corresponding to the left and right eyes are used to calculate the blink ratio.<br>
The blink ratio is then compared to a threshold to determine if a blink has occurred.<br>
The total number of blinks is continuously updated and displayed on the screen.<br>
The application provides a visual cue instructing the user to blink their eyes.<br>

### Dependencies
OpenCV: Open Source Computer Vision library.<br>
MediaPipe: A framework for building multimodal applied machine learning pipelines.<br>

### How to Clone
Make sure you have Python installed on your system.<br>
Clone the repository using the following command:<br>
```https://github.com/Shakirsadiq6/Blink_Detection_Python.git```
Navigate to the project directory:<br>
```cd Blink_Detection_Python```

### Usage
Install the required libraries:<br>
pip install opencv-python mediapipe

### Run the script:
```python main.py```

A window will open showing the live video feed with blink detection.<br>
Follow the on-screen instructions to blink your eyes, and the total blink count will be displayed.<br>

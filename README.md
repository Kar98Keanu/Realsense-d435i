# Realsense-d435i

To Set Up:
Open Command Prompt
Download Dependancies:
pip install opencv-python
pip install realsense2
pip install pyrealsense2 numpy opencv-python ultralytics

For python Realsense.py:

CV Model Used: Yolov8

Controls:
    q  — quit
    d  — toggle depth colormap overlay
    c  — cycle YOLO confidence threshold to be shown (0.3 → 0.5 → 0.7)

Parameters:
    Object, Distance(m), H+, V+
    H: Horizontal angle, + value = Right of the Centre, - value = Left of the centre
    V: Vertical angle, + value = Below Centre, - value = Above Centre
    H & V values are obtained by finding the centre of the object and the screen and measuring the pixels to get the H & V values

If pip is not recognised as an internal or external command:
Download Python
Run in command prompt: python -m pip
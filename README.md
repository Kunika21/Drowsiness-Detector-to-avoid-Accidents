# Drowsiness-Detector-to-avoid-accidents

This is a project implementing Computer Vision concepts to detect drowsiness of a driver and generates alert if drowsy.

**Real Time Application**

This detector can be used to abolish Drivers from driving vehicles for a longer period of time(exceeding 10hrs or more which may cause fatigue and drowsiness).

**Dependencies**

* OpenCV
* immutils
* dlib
* scipy

**Algorithm**

Each eye is represented by 6 (x, y)-coordinates, starting at the left-corner of the eye (as if you were looking at the person), and then working clockwise around the eye:.

<img src="https://github.com/Kunika21/Drowsiness-Detector-to-avoid-accidents/eye1.jpg">

**Condition**

It checks 20 consecutive frames and if the Eye Aspect ratio is lesst than 0.25, Alert is generated.

**Relationship**

<img src="https://github.com/Kunika21/Drowsiness-Detector-to-avoid-accidents/eye2.png">

**Conclusion**

<img src="https://github.com/Kunika21/Drowsiness-Detector-to-avoid-accidents/eye3.jpg">


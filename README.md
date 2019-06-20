Android Gesture Detectors Framework
===================================
Different type of Gesture Detector in Android:-

### RotateGestureDetector

Helps finding out the rotation angle between the line of two fingers (with the 
normal or previous finger positions)

### MoveGestureDetector

Convenience gesture detector to keep it easy moving an object around with one 
ore more fingers without losing the clean usage of the gesture detector pattern.

### ShoveGestureDetector

Detects a vertical two-finger shove. (If you place two fingers on screen with less than a 20 degree angle between them,
this will detact movement on the Y-axis.)

### ScaleGestureDetector (default Android)

This one is NOT in this framework, but is gesture detector that resides in the 
Android API since API level 8 (2.2).

### BaseGestureDetector (abstract)

Abstract class that every new gesture detector class should extend.

### TwoFingerGestureDetector (abstract)

Abstract class that extends the BaseGestureDetector and that every new gesture 
detector class for two finger operations should extend.

License
-------
This project is licensed with the 2-clause BSD license.

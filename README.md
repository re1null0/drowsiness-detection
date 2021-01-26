# Drowsiness detection with Firebase

## Description
The given code was the part of my SafeDrive project. This embedded system detects drowsiness of drivers. 
Given Python code works with external camera and Raspberry Pi and sends any case of detected drowsiness to the Firebase Database system. 
Feel free to (re)use the code in any way you wish, but bare in mind that the source code is provided "as-is". It is on your own risk and you are solely responsible for whatever happens then.

## Dependencies

- scipy
- imutils
- threading
- numpy
- playsound
- argparse
- dlib
- cv2
- pyrebase

## How to set up? 

1. Make sure to clone this repository and install dependencies
2. Change all paths to corresponding ones
3. Refer to following arguments in order to tune cascades for facial landmarks and sound
```
python detect_drowsiness.py --shape-predictor shape_predictor_68_face_landmarks.dat
python detect_drowsiness.py --shape-predictor shape_predictor_68_face_landmarks.dat --alarm alarm.wav
```


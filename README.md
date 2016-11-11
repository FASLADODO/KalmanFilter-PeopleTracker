# KalmanFilter-PeopleTracker

## Description

Implementation of the Kalman Filter in order to track people in a sequence of frames (video).

It can be seen in the video:
* A green box which contains the position where the HOG detector has detected a person
* A yellow box which contains the position where the KF predicts the position of a person
* A blue ellipse which indicates the uncertainty of the KF prediction, i.e. the error the KF could take in its prediction. If the KF has no measures from the HOG detector this uncertainty will increase more and more.

## Author

[Marcos Canales Mayo](https://github.com/MarcosCM)

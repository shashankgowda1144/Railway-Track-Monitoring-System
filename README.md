# Railway-Track-Monitoring-System

The railway analysis performed by this program (in Python 2.7, using OpenCV 3.3) addresses the following tasks:

Detection of the turn markings and kilometer signs (Italian Railway) thanks to the HAAR cascade classifiers previously trained using OpenCV.
Rail lines detection and tracking using HoughLines together with an iterative Template matching process.
Focus Of Expansion coordinates determined by computing the intersection between the straight line approximation of the rails. Moreover the optical flow within the bounding box enclosing the detected turn markings is assessed to the same aim.
Wrongly matched keypoints filtering, thanks to the Focus Of Expansion tracking, evaluating their optical flow direction, displayed in white for the complete scenario.

https://raw.githubusercontent.com/federicafioretti/railway-detection/master/image-readme/execution.png

![Alt Text](https://raw.githubusercontent.com/federicafioretti/railway-detection/master/image-readme/execution.png)

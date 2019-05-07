# arUco track demo

## HOW TO RUN:
1. Install anaconda if you don't have it yet.
2. Create a Conda environment:
```
conda create --name aruco
```
3. Open the project folder in terminal, then install the opencv package:
```
pip install opencv-contrib-python
```
4. Install whatever Conda says is missing.
5. From the proj folder, run:
```
pythonw marker_detect.py
```


## intro
this is a demo of aruco tracking.

## steps

1. take 15 to 20 pictures of the calibration chessboard. The chessboard img is in the cam_calib folder.
2. put the photos in the cam_calib/calib folder.
3. run marker_detect.py


## credits
Zander Mao coded (with tutorials help)
Rodolfo Cossovich refined the measurement of distances

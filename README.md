# facial-landmark-annotation-tools
A python GUI implementation for faster annotation with keyboard shortcuts. It is referenced from original repo (https://github.com/laoreja/facial-landmark-annotation-tools)

It is a very simple GUI facial landmark annotation tool using python and OpenCV.

This version helps you manually annotate a bounding box and 5 points: left eye, right eye, nose, leftmost mouth, rightmost mouth .

## How to use

To run this demo:

python key_point_5pts.py ./image/

## GUI

Sample output annotated file format:
1.jpg 139 264 195 325 160 288 179 288 169 296 161 303 177 302

[image_file, TL, BR, LE, RE, NO, LM, RM]

## References



## To DO
1. modify tool to add 35 points ladnamrks

2. modify it to annotate multiple faces in same image
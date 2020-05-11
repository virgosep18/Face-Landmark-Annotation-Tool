## Facial Landmarks Detection
==============================
Steps to find 68 points facial landmarks using OpenCV :

1. First read image frame from disk
2. Create face detector object (please read below notes for more details)
3. Find faces from frame using face detector object
4. Find facial landmarks on faces using 'shape_predictor_68_face_landmarks.dat'

Here I have tried below face detectors for finding landmarks:

1. Dlib's get_frontal_face : based on HOG + SVM classifier
2. Dlib's cnn_face_detection_model_v1 : CNN architecture trained model mmod_human_face_detector.dat
3. OpenCV's DNN module : Pre-trained deep learning caffe model with SSD method 



# To find facial landmarks with different methods

 1. First, change input image dir , output image dir and output landmarks file path in detect_keypoints.py
 2. Run one of below commands to get facial landmarks:

    $ python detect_keypoints.py -l hog
    $ python detect_keypoints.py -l cnn
    $ python detect_keypoints.py -l dl


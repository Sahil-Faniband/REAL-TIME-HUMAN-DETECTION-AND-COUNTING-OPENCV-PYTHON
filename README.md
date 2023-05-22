# REAL-TIME-HUMAN-DETECTION-AND-COUNTING-OPENCV-PYTHON

Python Open CV Project for Human Detection and Counting System Utilizing a Camera or a Video or an Image.

##Human Detection using OpenCV

This Python script detects humans in images, videos, or through the webcam using OpenCV and the Histograms of Oriented Gradients (HOG) object detector.

##Prerequisites

-Make sure you have the following libraries installed:

-OpenCV (cv2)
-imutils
-numpy
-argparse



 ##Requirements:
  -1.pip install opencv-python 
  -2.pip install imutils 
  -3.pip install numpy
  -4.opencv-python~=4.6.0.66
  -5.imutils~=0.5.4
  -6.numpy~=1.23.3
  
  ##Usage

##Detecting Humans in Images
To detect humans in an image, use the following command:
-python human_detector.py -i path/to/image.jpg -o path/to/output.jpg
Replace path/to/image.jpg with the path to your input image and path/to/output.jpg with the desired output path for the annotated image.

##Detecting Humans in Videos
To detect humans in a video file, use the following command:
-python human_detector.py -v path/to/video.mp4 -o path/to/output.avi
Replace path/to/video.mp4 with the path to your input video and path/to/output.avi with the desired output path for the annotated video.

##Detecting Humans through Webcam
To detect humans through your webcam, use the following command:
-python human_detector.py -c true
This will open a new window showing the webcam feed with human detections in real-time. Press 'q' to quit the program.

##Options

-v, --video: Path to the input video file.
-i, --image: Path to the input image file.
-c, --camera: Set to true if you want to use the webcam for real-time human detection.
-o, --output: Path to the optional output video or image file.
##Acknowledgements

This project is based on the OpenCV library and utilizes the Histograms of Oriented Gradients (HOG) object detector.

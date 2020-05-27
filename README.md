# Face Mask Detection 

Face Mask Detection Using DNN and TensorFlow with Trained Model With Low Computational power required for Image Processing,Object Detection and Computer Vision

This project is based on face mask detection it provides five depths of pytorch, tensorflow, caffe, keras, mxnet Learn the forward inference of the framework, detect faces and determine whether a mask is worn. In this project, the dnn module in opencv is used to do deep learning forward inference,In this project, only four libraries, opencv, numpy, PIL, and argparse, are needed to complete the deep learning task of face mask detection, and no additional deep learning framework is required. 


## How to Install

### 1. Download Or Clone Repository：
```
$ git clone AbhiGandhi/FaceMaskDetection
```
### 2 Install the packages From requirements.txt file
```
$ pip install -requirements
```
## How to Use:

on image：
```
python3 MaskDetector.py --img-path /path/to/your/img
```
on video：
```
python3 MaskDetector.py --img-mode 0 --video-path /path/to/video  
# If you want to run with camera video, set  video_path to be 0
```

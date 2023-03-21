# real-time-face-detection
real time face detection
# Face Detection with OpenCV and Deep Learning

A fast and accurate face detection with OpenCV using a pre-trained deep learning face detector model shipped with the library.
Two files are required for using OpenCV's deep neural network module with Caffe models.
- The .prototxt file (define the model architecture i.e., the layers themselves)
- The .caffemodel file (which contains the weights for the actual layers)

You can find Caffe-based face detector prototxt files in the ```face_detector``` sub-directory of the [dnn samples](https://github.com/opencv/opencv/tree/master/samples/dnn/face_detector).

## Getting Started

How to use
```    
git clone https://github.com/aakashjhawar/face-detection.git
cd face-detection
```
To detect face from photos:
```
python3 detect_faces_image.py <path/to/input_image>
```
To detect face from videos:
```
python3 detect_faces_video.py
```

## Prerequisites

- Python 
- OpenCV
```
sudo apt-get install python-opencv
```

## Results

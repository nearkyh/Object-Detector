# Object Detector
A Real-time object detector using [Tensorflow Object Detection API](https://github.com/tensorflow/models/tree/master/research/object_detection) and [OpenCV](http://opencv.org/).


## Requirements
- Ubuntu 16.04
- Python 3.5
- [Tensorflow 1.8](http://yongyong-e.tistory.com/10)
- [OpenCV 3.4](http://yongyong-e.tistory.com/41)


## Getting Started
Creating virtualenv
1. `cd Object-Detector`
2. `virtualenv env --python=python3.5`
3. `source env/bin/activate`

Install Dependencies
- `pip install -r requirements.txt`

Apply Trained Model
- `unzip object_detection/ssd_mobilenet_v1_coco_11_06_2017.zip -d object_detection/`

Run
- `python object_detector.py`

<div align='center'>
  <img src='object_detection/g3doc/img/demo.gif' width='600px'>
</div></br>

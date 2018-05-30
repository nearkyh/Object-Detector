# Object Detector
A Real-time object detector using [Tensorflow Object Detection API](https://github.com/tensorflow/models/tree/master/research/object_detection) and [OpenCV](http://opencv.org/).


## Requirements
- Ubuntu 16.04
- Python 3.5
- [Tensorflow 1.8](http://yongyong-e.tistory.com/10)
- [OpenCV 3.4](http://yongyong-e.tistory.com/41)


## Getting Started
Creating virtualenv
```bash
$ cd Object-Detector
$ virtualenv env --python=python3.5
$ source env/bin/activate
```

Install Dependencies
```bash
$ pip install -r requirements.txt
```

Apply Trained Model
```bash
$ unzip object_detection/ssd_mobilenet_v1_coco_11_06_2017.zip -d object_detection/
```

Run
```bash
$ python object_detector.py \
    --input_cam=your_cam_num
```

<div align='center'>
  <img src='object_detection/g3doc/img/demo.gif' width='600px'>
</div></br>

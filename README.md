# PPE-Object-Detection
A PPE Object Detection application that uses the YOLO v5 architechture to detect if construction workers are wearing safety helemts and vests or not

# **Acknowledgment**
Contents of Yolov5 forked from https://github.com/ultralytics/yolov5 \
Dataset 1 (PPE): https://www.kaggle.com/datasets/snehilsanyal/construction-site-safety-image-dataset-roboflow \
Dataset 2: https://www.kaggle.com/datasets/andrewmvd/hard-hat-detection

# changes made to yolov5
- Added PPE.yaml
- Added Dataset2.yaml
- used hyp_evovlved.yaml from evolve folder instead of default hyp.yaml from evolve folder
- Modified Detect.py

# steps for running
- no need to run any of pre-processing code since datasets folder contains pre-processed data
- cd into yolov5
- install requirments.txt
- run the command `python  detect.py --weights ./runs/Final/weights/best.pt --source 0 ` , which will run our weights using the camera, you can replace 0 by path for any folder containing image or url where results will be stored in ./runs/detect


**Note:** Refer to original Yolov5 for detaile instructions on running/setting up the enviroment

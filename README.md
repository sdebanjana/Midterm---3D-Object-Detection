# Midterm : 3D Object Detection
##
📦project

┣ 📂dataset --> contains the Waymo Open Dataset sequences

┃

┣ 📂misc

┃ ┣ 📜helpers.py --> misc. helper functions, e.g. for loading / saving binary files
┃ ┗ 📜objdet_tools.py --> object detection functions without student tasks
┃
┣ 📂results --> binary files with pre-computed intermediate results
┃
┣ 📂student
┃ ┣ 📜association.py
┃ ┣ 📜filter.py
┃ ┣ 📜measurements.py		
┃ ┣ 📜objdet_detect.py --> model-based object detection incl. student tasks
┃ ┣ 📜objdet_eval.py --> performance assessment for object detection incl. student tasks
┃ ┣ 📜objdet_pcl.py --> point-cloud functions, e.g. for birds-eye view incl. student tasks
┃ ┗ 📜trackmanagement.py
┃
┣ 📂tools --> external tools
┃ ┣ 📂objdet_models --> models for object detection
┃ ┃ ┃
┃ ┃ ┣ 📂darknet
┃ ┃ ┃ ┣ 📂config
┃ ┃ ┃ ┣ 📂models --> darknet / yolo model class and tools
┃ ┃ ┃ ┣ 📂pretrained --> copy pre-trained model file here
┃ ┃ ┃ ┃ ┗ 📜complex_yolov4_mse_loss.pth
┃ ┃ ┃ ┣ 📂utils --> various helper functions
┃ ┃ ┃
┃ ┃ ┗ 📂resnet
┃ ┃ ┃ ┣ 📂models --> fpn_resnet model class and tools
┃ ┃ ┃ ┣ 📂pretrained --> copy pre-trained model file here
┃ ┃ ┃ ┃ ┗ 📜fpn_resnet_18_epoch_300.pth
┃ ┃ ┃ ┣ 📂utils --> various helper functions
┃ ┃ ┃
┃ ┗ 📂waymo_reader --> functions for light-weight loading of Waymo sequences
┃
┣ 📜basic_loop.py
┣ 📜loop_over_dataset.py
 

# License-Plate-Detection-using-YOLOv8
Our project is to detect Indian vehicle license plates as a representation of vehicle presence in an image. We have utilized You Only Look Once version 8 (YOLOv8) to detect the plates inside an input image. The method has the advantages of high accuracy and real-time performance, thanks to YOLOv8 architecture. The presented system receives a series of vehicle images and produces the processed image with added bounding-boxes containing the vehicles' license plates. This project can be used in parking area to keep track of every vehicle and make parking process easier.

Built with:

•	Python

•	YOLO

•	Easyocr

•	Roboflow

Step 1: Clone the github repository
!git clone https://github.com/MuhammadMoinFaisal/Automatic_Number_Plate_Detection_Recognition_YOLOv8.git

Step 2: Install the dependencies
!pip install -e '.[dev]'

Step 3: Preparing a custom dataset for YOLOv8 and export it using Roboflow apikey
	Steps in Roboflow:
•	Create project
•	Upload your images
•	Label your images
•	Generate a new version of your dataset
•	Export dataset

Step 4: Setting the directory
%cd   /content/Automatic_Number_Plate_Detection_Recognition_YOLOv8/ultralytics/yolo/v8/detect

Step 5: Custom training

Step 6: Validate custom model

Step 7: Test custom model


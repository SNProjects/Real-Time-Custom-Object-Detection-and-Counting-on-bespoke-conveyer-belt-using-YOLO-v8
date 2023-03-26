<h1 align="center">Custom Object detection and counting on a conveyer belt</h1>

<div align= "center"> <h4>Training a Deep Learning neural network to detect and count custom objects on a bespoke conveyer belt using YOLO-V8.</h4>

 
</div>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;

## :innocent: About the Project
Training a deep neural network using the latest version of YOLO (You Only Look Once), i.e., YOLO-V8 to detect custom objects on a conveyer belt. The model also counts objects of each category as they pass on along the conveyer belt. 

## :warning: TechStack/framework used

- [OpenCV](https://opencv.org/)
- [YOLO](https://github.com/ultralytics/ultralytics)
- [Python](https://www.python.org/)


## Use cases of the project
This project can be used for custom object detection and counting in any manufacturing unit using just a functioning camera and a conveyer belt. By training the model on the manufactured products, a given number of products belonging to a specific category can be packaged together. This would make the product counting and packaging tasks in an industry more efficient and robust. 

## Working
## Making the conveyer belt:
The conveyer belt used in this project is made at home using spare parts like an old spare motor, a broken headphone's headband, a bed table and some empty medicine bottles for the wheels of the conveyer belt.

## Training the model on custom dataset:
To train the model, run the file train_yolo_model.ipynb, and download the trained model.

## testing and counting objects on the conveyer belt:
To count objects, run the file objdet.py and start the conveyer belt. The category of object and its count starts appearing on screen as the object moves on the conveyer belt.








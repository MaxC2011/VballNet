# VballNet
This project recognizes volleyball actions performed in a picture using ImageNet
Vball Net
This project recognizes the different volleyball actions happening in an image.

Overview
Volleyball teams have a hard time analyzing opponents due to the lacking technology. Since the sport is to keep the ball up in the air, the complicated and confusing patterns and rotations a team plays is hard to recognize. However, with a volleyball action recognizer, coaches and teams will be able to analyze what a player is doing in game and see the possibilities of performing a certain action. This will help coaches and analytics to be able to analyze data and plays of other teams more efficiently and conveniently.

Output
Installation
Install my-project with npm

  npm install my-project
  cd my-project
```To Train The Model (yolo task=classify mode=train model=yolov8n-cls.pt
data=datasetepochs=50 imgsz=224)  ​

To Classify The Model (yolo task=classify mode=predict
model=runs/classify/train/weights/best.ptsourc=0)​

To Test The Model (yolo task=classify mode=val
model=runs/classify/train/weights/best.pt
data=/home/nvidia10/Final_Project/dataset)​

To Export The Model (yolo export model=runs/classify/train/weights/best.pt
format=onnx  # or format=torchscript, openvino, etc.)
    

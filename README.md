# road_object_detection


Deep Learning based autonomous road traffic and drivable area detection

Download weights using the following link to a new folder name it bin:
https://pjreddie.com/darknet/yolov2/

To load the model use command:
flow --model ./cfg/yolo.cfg --load ./bin/yolo.weights

For running the road detection script :
python Road_Detection.py

# Results

<img src="results/objects.png" width="500" height="250">

<img src="results/12.png" width="500" height="250">

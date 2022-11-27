# simple-yolo
<a href="#"><img src="https://img.shields.io/badge/yolo /></a>
Simple yolo is a project that aims to use the same architecture as yolo v7 to detect only the center of objects instead of detecting a box.
The objective is to accelerate the execution speed by 4 for applications based on yolo and which just need the center of the object (prour tracked or just have the presence of an object ....). Thus in the prediction phase, the model takes an image as input and outputs a point (x,y) representing the center of the object

# Yolo_v_3
Simplest, easiset implementation of Yolov3 from scratch.

 
To run the detector on sample directory:

- clone this repository
- save your images in the imgs folder
- download the yolov3 weights using command given below
- run the command ``python3 detect.py`` 
- result will be present in the det folder

Command to download Pretrained weights for yolov3:-
``wget https://pjreddie.com/media/files/yolov3.weights``



Showing the sample results after the detection (in det folder) on the images (in imgs folder):

Time taken (in seconds) for detection :
``

Reading addresses        : 0.000

Loading batch            : 0.091

Detection (10 images)    : 2.541

Output Processing        : 0.000

Drawing Boxes            : 0.102

Average time_per_img     : 0.273
``


pallete : This is a pickled file that contains many colors to randomly choose from









Source code:- `https://blog.paperspace.com/how-to-implement-a-yolo-object-detector-in-pytorch/`
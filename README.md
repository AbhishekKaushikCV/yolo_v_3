# Yolo_v_3
Simplest, easiset implementation of Yolov3 from scratch.

 
To run the detector on sample directory:

- clone this repository
- save your images in the imgs folder
- download the yolov3 weights using command given below
- run the command ``python3 detect.py`` in the terminal
- result will be present in the det folder

To run the detection on video file:

- save your video file in the current directory
- download the yolov3 weights using command given below
- run the command ``python3 video.py`` in the terminal

To run the detection on webcam:
- change the code (Cooment the line 94 and Uncomment the line 96) in the video.py
- download the yolov3 weights using command given below
- run the command ``python3 video.py`` in the terminal

Command to download Pretrained weights for yolov3:-
``wget https://pjreddie.com/media/files/yolov3.weights``


## Results:

Experiment on the thermanl image (flir1.jpeg) from the FLIR thermal image dataset. Detection is present in the det folder (det_flir1.jpeg).

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


pallete :  For the bounding box of different objects in a image we need different color of bounding boxe.For this we use this pickle file that contains many colors to randomly choose from.









Source code:- `https://blog.paperspace.com/how-to-implement-a-yolo-object-detector-in-pytorch/`
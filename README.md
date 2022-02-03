# Deep-Learning-Abnomal-Neural-Cell-detection
* Detect and delineate distinct objects of interest in biological images depicting neuronal cell types commonly used in the study of neurological disorders.
* Unfortunately, segmenting individual neuronal cells in microscopic images can be challenging and time-intensive
* Accurate instance segmentation of these cells—with the help of computer vision—could lead to new and effective drug discoveries to treat the millions of people with these disorders

## Why is segmenting individual neuronal cells difficult ?
* To develop cell instance segmentation models, the neuroblastoma cell line SH-SY5Y consistently exhibits the lowest precision scores out of eight different cancer cell types tested. 
* This could be because neuronal cells have a very unique, irregular and concave morphology associated with them, making them challenging to segment with commonly used mask heads.

## Visualizing Dataset

![image](https://user-images.githubusercontent.com/78380617/152316352-a6c0cf1a-00b3-40cc-8c53-0b46c693057a.png)

![image](https://user-images.githubusercontent.com/78380617/152316504-eabd6513-8cce-4961-b68d-0f3653a4b883.png)

![image](https://user-images.githubusercontent.com/78380617/152316569-331226ba-6fa0-40bd-8416-825b037eae82.png)

## Modelling technique
We have used Detectron2 library by Facebook AI Research for object detection and segmentation.
** The Detectron2 model used, is based on the concept of maskR-CNN benchmark. 
** To input into the model, The images are augmented by changing the brightness, random flipping etc. 
** The Detectron2 uses a predefined instance segmentation architecture to train on the given annotated image dataset. 
** The predictor is then able to identify masks and delineate distinct objects of interest depicting neuronal cell types commonly used in the study of neurological disorders.


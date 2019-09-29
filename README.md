# Virtual-Machine-for-YOLO
[It is a Virtual Machine for run the YOLO (You Only Look Once)](https://drive.google.com/drive/u/4/folders/1hjfmpTuctrJNz1gPnWLkfYX7a78OXP2K)

YOLO it is a system for real time object detection. YOLO use the data set COCO default for detect approximately 80 objects. You can find more information in the official page [YOLO](https://pjreddie.com/darknet/yolo/)            

I attached the link for the Virtual Machine (VM) because you can use this for experiment, avoiding install all the components for run YOLO. This VM is easy to use, and it allows decide if use this system or not. Also, you can use this VM to know and demonstrate the functionalities of the YOLO. 
You only need run the commands for obtain the results for the object detection in real time.
This Virtual Machine is on Ubuntu 18.04. The password is "1234"

This is a [guide](https://revistas.ulatina.ac.cr/index.php/tecnologiavital/article/download/250/260) to start in Machine Learning with YOLO.

The follow instructions and commands is for run the program in the terminal. 

**cd darknet**

For detect a imagen by command line, execute this command 
**./darknet detect cfg/yolov3.cfg yolov3.weights.1 bici.jpg**

For detect in real time, execute this command with webcam
**./darknet detector demo cfg/coco.data cfg/yolov3.cfg yolov3.weights**




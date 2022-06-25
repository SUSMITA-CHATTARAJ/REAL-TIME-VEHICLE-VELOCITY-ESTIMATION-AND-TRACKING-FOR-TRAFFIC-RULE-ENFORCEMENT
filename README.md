# REAL-TIME-VEHICLE-VELOCITY-ESTIMATION-AND-TRACKING-FOR-TRAFFIC-RULE-ENFORCEMENT

 AIM: 
 
“ To detect and track fast moving vehicles in a real time traffic stream, and subsequently estimate its velocity.”

OBJECTIVE:

To transfer learn YOLO v5 DL model for image classification.

To tune the model for optimum performance. 

Target : 95% > PREC, FPS >30.

To deploy the model in edge devices.

WHAT

“ The objective of this project is to detect vehicles  (pertinent to indian roads) in real-time with precision above 95%.”

CNN MATRIX MULTIPLICATION

 We have divided the the whole  window  into 5*5 matrix .
 
 If the feature is present it will be denoted as ‘1’ and if not present it will be denoted as ‘0’.
 
 Now we will take a 3*3 matrix from this and multiple it with the filter matrix

After the extraction is done for all the features then we will only take the blocks containing 1 or ~1

RESULT

Maximum FPS - 10FPS

Precision - 88%

Confidence threshold - 0.25

Opencv screen size - 640 * 480

FUTURE ASPECTS

Since we are executing  Yolo v5 in CPU(Ryzen 5000 series) it provides use a very low fps maximum of 10 Fps. However, the intention is to deploy the model on an edge device , like low performance .

We have to increase the FPS by multiprocessing and multithreading.

For speed detection and tracking of the vehicle can be done using optical flow. 

After the Empirical study  is done, we can apply ALPR(Automatic License Plate Recognition).

CONCLUSION

To wrap up, we have learned what object detection is, its applications, and its implementation.

We have also tackled the YOLO object detection algorithm (YOLO v5 particularly) which we used to perform our own object detection by setting up the environment to detect images and videos.



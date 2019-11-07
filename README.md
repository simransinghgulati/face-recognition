# face-recognition

## training 
* run **trainer.py** : enter name and click '*c*' while in the webcam frame to add (capture) your face to the training data
* with each key-press (c) the console displays remaining number of faces to be clicked
* once 10 pictures are clicked, those images are loaded on to the face_data.npy
* and the webcam automatically shuts down returning total number of rows and their features in npy file

## testing
* run **predict.py** and test with faces stored in the training step
* press '*q*' (in the webcam frame) to stop & exit the program

#### to change web-cam :
try changing id in cv2.VideoCapture(0) to some other integer, by default 0 points towards the in-built camera

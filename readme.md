# Driver drowsiness detection system 

A countless number of people drive on the highway day and night.
Taxi drivers, bus drivers, truck drivers and people travelling long-distance suffer from lack of sleep.
Due to this it becomes very dangerous to drive when feeling sleepy.
The majority of accidents happen due to the drowsiness of the driver.
So, to prevent these accidents we will build a system using Python, OpenCV, and Dlib which will alert the driver when he feels sleepy.
Drowsiness detection is a safety technology that can prevent accidents that are caused by drivers who fall asleep while driving.
The objective of this intermediate Python project is to build a drowsiness detection system that will detect that a person’s eyes are closed for a few seconds.
This system will alert the driver when drowsiness is detected.

- The requirement for this Python project is a webcam through which we will capture images. You need to have Python (updated version) installed on your system, then using pip, you can install the necessary packages.
1. OpenCV – pip install opencv-python (Face and eye detection).
2. Imutils – pip install imutils (To get landmarks of eye).
3. Scipy – pip install scipy (To calculate distance between eye landmarks).
4. Pygame – pip install pygame (To play alarm sound).
5. Dlib - pip install dlib  (Provides functionality for detecting facial landmarks, One common use case of dlib is face detection. You can use the dlib.get_frontal_face_detector() function to create a face detector object, which you can 
                            then use to detect faces in images.)

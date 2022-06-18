# Head Pose Estimation:
        Simply, head pose estimation means detecting the position of a human in the image by detecting the  heads **Euler angles**; Pitch,yaw and roll,They define the object's rotation in 3D environment.
        
# Objective of the project:
   
   Train 3 supervised-machine learning models each to predict one of the Euler angles(Pitch,yaw and roll) and projecting the axes on images/Frames

# Dataset Explanation:
				
        "AFLW2000" contains 2000 images of human faces with different rotations and poses.

# Libraries used:
    
    1.MediaPipe: used to extract 468*468 features from each face
    2.openCV: for image and video processing
    3.Sklearn: for processing, training and evaluating the machine learning models
        
				
				

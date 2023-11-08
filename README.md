
# Object-Detection-for-Traffic-Management-System-using-YOLO using mini dataset

* The MiniTask.ipynb notebook contains the working code for the Object Detection for the Traffic Management Systems.
* The model used for this task is YOLO.
# Steps involved
* Installing Libraries
* Data Preparation
* Custom training YOLO model
* Validating Custom Model
* Inference with Custom Model
* Visualization of the model's predictions on Test images
# Installing Libraries
* Install the required libraries for the task like ultralytics, YOLO, Image
# Data Preparation
* The data is prepared for the YOLO Model training as per requirement. The dataset must consist of the train, test and val folders within each folder the images 
  and labels folder is present.
* Each image has it's own corresponding label in the label folder.
* The name.yaml file contains the components that are to  be detected in the images.
# Custom training YOLO model
* The YOLO model is used for the object detection task.
* There are 3 modes of the YOLO model -
  1. Train
  2. val
  3. predict
* And the tasks that can be performed are -
  1. Detect
  2. Segment
  3. Classify
* YOLO, short for "You Only Look Once", is a popular real-time object detection system in computer vision. It's an algorithm that can detect and locate multiple 
  objects in an image or a video frame, providing both the class labels and the bounding box coordinates for the detected objects.
* During the custom training, the name.yaml file is fed to the YOLO Model and is trained.
* During modelling a runs folder is created by default which contains the detect folder and the train folder.
* The train folder contains all the performance reports of the training set like R_curve, PR_curve, F1_curve and results.
#  Validating Custom Model
* We now validate the model using the validation set.
* A seperate folder consisting the performance reports of validation set is created.
# Inference with Custom Model
* We now predict the model against the test data.
# Visualization of the model's predictions on Test images
* We now can visualize the F1-Confidence Curves and Precision-Confidence Curves and many more.

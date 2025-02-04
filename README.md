# automotive_surveillance
A Deep-Learning-based car identification model to identify the car's make, color, and number plate of a car moving on the road.

**• OBJECTIVE**:

Design a DL-based car identification model to identify the car's make, color, and number plate of a car moving on the road.

**• DATA DESCRIPTION:**

* The dataset contains 16,185 images of 196 classes of cars. The data is split into 8,144 training images and 8,041 testing images, where each class has been split roughly in a 50-50 split.


* Annotation consists of bounding box region for training images.


* Link to the dataset: https://www.kaggle.com/jutrera/stanford-car-dataset-by-classes-folder


**• Steps and Tasks:**

* Import the data

* Map training and testing images to their classes.

* Map training and testing images to their annotations.

*  Display images with bounding box
* Images mapped to its class and annotation ready to be used for deep learning
* Design, train, and test CNN models to classify the car
* Models used 
  1. CNN with hyper-parameter tuning
  2. CNN with transfer learning(RESNET 50)
  3. RCNN
  4. YOLO
  5. MobilnetV2


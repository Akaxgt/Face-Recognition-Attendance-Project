# Face-Recognition-Attendance-Project

Face Recognition using CNN and OpenCV

Libraries and Frameworks used:

1. OpenCV
2. Python Numpy
3. Python OS Module
4. Pythhon Face Recognition Library
5. Python Datetime Module

Code Working:

1. Reads the image from directory and encodes facial features to be detected and compared later.
2. Reads the image from Web-Cam, and matches the facial encodings with those stored in the database.
3. Marks and tracks attendance along with timestamp (if match is found).

Steps involved in Face Recognition:

1.Face Detection: Locate the face, note the coordinates of each face located and draw  a bounding box around every faces.
2.Face Alignments. Normalize the faces in order to attain fast training.
3.Feature Extraction. Local feature extraction from facial pictures for training, this step is performed differently by different algorithms.
4.Face Recognition. Match the input face with one or more known faces in our dataset.   

Convolutional Neural Networks:

ConvNet/CNN is a Deep Learning algorithm that can take in an input image, assign importance (learnable weights and biases) to various aspects/objects in the image, and be able to differentiate one from the other.
The objective of the Convolution Operation is to extract the high-level features such as edges, from the input image. Conventionally, the first ConvLayer is responsible for capturing the Low-Level features such as edges, color, gradient orientation, etc. With added layers, the architecture adapts to the High-Level features as well, giving us a network that has a wholesome understanding of images in the dataset, similar to how we would.

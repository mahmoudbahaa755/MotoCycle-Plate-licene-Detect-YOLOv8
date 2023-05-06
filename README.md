Motorcycle License Plate Detection using YOLOv8
This is a repository for training and deploying a YOLOv8 object detection model for detecting motorcycle license plates in images. The model is trained on a custom dataset of motorcycle license plates

Dataset
The custom dataset used for training the model consists of images of motorcycles with license plates. The images are annotated using the YOLO format, with each annotation containing the coordinates of the license plate region in the image.
data link:
https://universe.roboflow.com/toto-fj9hq/egyptian-license-plate-recognition-in-vehicles-and-motorcycles
Model
The YOLOv8 object detection model architecture is used to train the model on the custom dataset. The model is trained using transfer learning, with the pre-trained weights of the YOLOv8 model as the starting point. The model is trained to output bounding boxes around the detected license plates.

Requirements
roboflow
ultralytics



Credits
This project was created by Mahmoud Bahaa. The YOLOv8 model is based on the work of Alexey Bochkovskiy, Chien-Yao Wang, and Hong-Yuan Mark Liao. The custom dataset used for training the model was created by Mahmoud Bahaa.

License
This project is licensed under the MIT License. See the LICENSE file for details.

**Object Detection**
This project demonstrates real-time object detection using MobileNet-SSD (Single Shot MultiBox Detector) and OpenCV's deep learning module (cv2.dnn).
The application processes live video streams and detects objects by drawing bounding boxes around them with labels.

**Features**
Real-time object detection using a pre-trained MobileNet-SSD model.
Capable of detecting 21 object classes, such as persons, vehicles, animals, and more.
Lightweight and optimized for live processing using OpenCV.
Displays bounding boxes and confidence scores for detected objects.

**Working**
Model: The project uses the MobileNet-SSD pre-trained model, optimized for real-time applications.
Classes Detected: The model recognizes 21 object categories, including:
Aeroplane, Bicycle, Bird, Boat, Bottle, Bus, Car, Cat, Chair, Cow, Dining Table, Dog, Horse, Motorbike, Person, Potted Plant, Sheep, Sofa, Train, TV Monitor.
**Processing:**
Each video frame is resized and converted into a blob format using cv2.dnn.blobFromImage.
The blob is passed through the network, and predictions are filtered based on a confidence threshold.
Detected objects are highlighted with bounding boxes and labeled with class names and confidence scores.

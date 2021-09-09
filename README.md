# Object Detection
#### Using MobileNEts and Single shot Detectors(SSD) to get super fast real-time object detection

Simply, Object Detection tells us the information about what is in the Image as well as the placement in the image with a bounding box.

- The MobileNet SSD used here was trained on COCO dataset, which has 20 classes like Dogs, Birds, Bottles etc.,
- The `dnn` Module in the OpenCV helps to build our Object detector.
- The static files `MobileNetSSD_deploy.caffemodel` and `MobileNetSSD_deploy.prototxt.txt` are the pre-trianed model with weights and the text file with Classes respectively.

#### The implemented object detector is applied on the input images and also tested in the real time to obtain the bounding box.
It detects only the objects which includes in the text file.















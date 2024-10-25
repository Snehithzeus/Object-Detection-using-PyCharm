To begin with object detection using YOLO, you'll need to install the necessary dependencies. 
Ensure you have opencv and numpy installed by running the command pip install numpy opencv-python.
Once your environment is set up, download the pre-trained YOLO v3 weights file from the official website at https://pjreddie.com/media/files/yolov3.weights,
or use the terminal command wget https://pjreddie.com/media/files/yolov3.weights to download it directly.
Along with the weights, you will also need the configuration file yolov3.cfg and the class names file yolov3.txt, which can be obtained from the YOLO repository on GitHub.

After placing all these files in your current directory, you can run the object detection on an image (for instance, dog.jpg).
Use the following command format: python yolo_opencv.py --image dog.jpg --config yolov3.cfg --weights yolov3.weights --classes yolov3.txt. 
This command will process the specified image and apply the YOLO detection algorithm.

Once you execute the command, the script will output an image with detected objects highlighted, 
allowing you to visualize the results. If you want a more simplified implementation, 
consider using the cvlib library, which enables object detection with a single function call,
such as detect_common_objects(). This concise guide covers the essential steps to get started with object detection using YOLO in OpenCV,
and you can look forward to more examples for SSD and Faster R-CNN in the future.

before processing
![image2](https://github.com/user-attachments/assets/590188e0-fe1d-47d3-b89b-2b18fcaca7ca)
after processing 
![object-detection](https://github.com/user-attachments/assets/e8fa0f20-eec6-46bf-8083-e116c2c535f1)




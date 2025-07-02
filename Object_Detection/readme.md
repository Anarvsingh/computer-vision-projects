# Object Detection using YOLOv3

This repository contains code for object detection using the YOLOv3 algorithm. YOLOv3 is a popular real-time object detection algorithm known for its speed and accuracy. This implementation provides a robust framework for integrating computer vision capabilities into Python-based applications.

## Prerequisites

- Python 3
- OpenCV
- NumPy
- Matplotlib

## Download YOLOv3 Weights and Configuration

To run the object detection, you need to download the YOLOv3 pre-trained weights and configuration files. Run the following commands:

download_url = "https://pjreddie.com/media/files/yolov3.weights"
desired_path = "/content/yolov3.weights"
!wget {download_url} -O {desired_path}

download_url = "https://github.com/pjreddie/darknet/raw/master/cfg/yolov3.cfg"
desired_path = "/content/yolov3.cfg"
!wget {download_url} -O {desired_path}

download_url = "https://github.com/pjreddie/darknet/blob/master/data/coco.names"
desired_path = "/content/coco.names"
!wget {download_url} -O {desired_path}

## Results

![Image 1 Image](results/image1.png)

![Image 2 Image](results/image2.png)

![Image 3 Image](results/image3.png)

![Image 4 Image](results/image4.png)

## Customization

You can modify the confidence threshold and Non-Maximum Suppression (NMS) parameters in the code for different detection sensitivity. To detect a different specific object, you can change the class_id according to the COCO labels.

## About the Developer

This project is maintained by Anarv Singh, a Software Engineer with over 5 years of experience in backend development and distributed systems. With expertise in Python, Java, and cloud-based architectures, Anarv focuses on building scalable, high-performance applications and implementing efficient engineering solutions.

- GitHub: https://github.com/Anarvsingh
- LinkedIn: https://www.linkedin.com/in/anarv-s-91811a173/
- Email: anarvsingh@gmail.com
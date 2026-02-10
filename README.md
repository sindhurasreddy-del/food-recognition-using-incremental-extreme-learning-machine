# Real-Time Food Detection Using YOLOv3 and OpenCV DNN

## Introduction
Food detection is a fundamental computer vision task with applications in nutrition tracking, smart kitchens, and automated food analysis systems.  
This project presents a **real-time food detection system** implemented using **YOLOv3 (You Only Look Once)** and **OpenCV’s Deep Neural Network (DNN) module**.

The system processes both **static images and live webcam video streams**, detects **food-related objects**, and visualizes results using bounding boxes, class labels, and confidence scores.

---

##  Project Objectives
- Detect food items in images and live video streams  
- Achieve real-time performance using YOLOv3  
- Apply Non-Maximum Suppression to improve detection accuracy  
- Display detection confidence and FPS for performance evaluation  
- Build a lightweight and modular computer vision pipeline  

---

##  System Architecture
1. Input image or webcam frame
2. Image preprocessing and blob creation
3. Forward pass through YOLOv3 network
4. Food-related class filtering
5. Confidence thresholding
6. Non-Maximum Suppression (NMS)
7. Visualization of results and FPS calculation

---

##  Key Functionalities
- **Food Object Detection:** Identifies food-related objects using YOLOv3 trained on the COCO dataset  
- **Real-Time Processing:** Supports live webcam detection  
- **Confidence-Based Filtering:** Removes weak predictions  
- **Non-Maximum Suppression:** Eliminates duplicate detections  
- **Performance Monitoring:** Displays real-time FPS  
- **Modular Design:** Easy to extend or retrain for food-only datasets  

---

##  Technologies and Tools
- Python  
- OpenCV (DNN Module)  
- YOLOv3 Deep Learning Model  
- NumPy  
- Computer Vision  

---



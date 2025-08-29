# FastSCNN-and-OrientedRCNN-for-ObjectDetection

# Neural Networks & Deep Learning — Homework 3  

**Note:** The full project instructions and reports are written in **Persian**.  
An **English version can be provided on request**.  

## Overview  
This homework consists of two main tasks:  
 
1. **Urban Scene Segmentation (Fast-SCNN)**  
   - Implemented **Fast-SCNN** for semantic segmentation using the **CamVid dataset**.  
   - Covered preprocessing, model implementation, training, and evaluation using metrics like **IoU**, **Dice Coefficient**, and **Accuracy**.  
   - Results show that the model performs well on large, well-defined classes (road, building, sky) but struggles with smaller or complex objects (pedestrians, poles, fences).  

2. **Object Detection with Oriented R-CNN**  
   - Studied and implemented **Oriented R-CNN** for rotated object detection on the **HRSC2016 dataset**.  
   - The project included both theoretical analysis (architecture, rotated RoI Align, loss functions) and practical implementation (training, evaluation, and visualizing predictions).  
   - The model showed strong performance on detecting large objects (ships, airplanes) but had limitations with small or heavily rotated targets.  

## Key Takeaways  
- **Fast-SCNN** provides an efficient real-time approach to segmentation, with balanced trade-offs between accuracy and computational cost.  
- **Oriented R-CNN** extends standard object detection by handling rotated bounding boxes, making it highly useful in aerial image analysis and similar domains.  

---

# OBJECT-RECOGNIZATION-SYSTEM-USING-IMAGE-PROCESSING-

## **OBJECT RECOGNITION SYSTEM USING IMAGE PROCESSING**
---

### **Abstract**  
An object recognition system using image processing is a computer vision technology designed to automatically **identify and classify objects** within digital images or video streams.  

**Stages involved in the system include:**  
- **Image Acquisition:** Capturing digital images or video frames.  
- **Preprocessing:** Enhancing and normalizing images for better quality.  
- **Feature Extraction:** Extracting relevant features from images.  
- **Object Detection:** Identifying object locations using techniques like edge detection.  
- **Classification:** Categorizing objects into predefined groups based on features.  

This system has applications in **robotics, surveillance, and autonomous vehicles**.

---

### **Aim**  
- **Objective:** To extract relevant features from images/videos and match them with predefined categories.

---

### **Literature Review**  
- Bootstrapped simple images and progressively applied **neural networks** for detection.  
- Detected multiple objects of varying shapes and colors, but accuracy for complex objects was limited.  

---

### **Methodology**  
- Detect and recognize objects in both **structured** and **unstructured** environments.  
- Utilized a **single-lens webcam** for real-time obstacle detection.  
- Adaptive system capable of learning during operation.  
- Tested in various environments, suitable for indoor and outdoor applications.  

---

### **Tools Required**  

#### **Hardware:**  
- Raspberry Pi  
- SD Card  
- Drone  
- 12V Battery  
- Minimum 4GB RAM  
- Windows OS PC (64-bit)  

#### **Software:**  
- Python IDLE  
- OpenCV  
- NumPy  
- Deep Learning using CNN (Convolutional Neural Networks)  

---

### **Block Diagrams**  

#### **Hardware Block Diagram:**  
- SD Card  
- Webcam  
- Raspberry Pi  
- Deep Learning Dataset  
- Drone  

#### **Software Block Diagram:**  
- Camera captures object.  
- Detect object pattern from the scene.  
- Extract features and match them with predefined patterns.  
- Store results in cloud storage.

---

### **Flowchart**  
1. **Camera Captures Object**  
2. **Detection of Object Pattern**  
3. **Feature Extraction**  
4. **Object Detection**  
5. **Matching Process:**  
   - If **YES:** Produce audio output of recognized object.  
   - If **NO:** Store in the cloud database.  

---

### **Raspberry Pi Specifications**  
- Broadcom BCM2837B0 chipset  
- 1.4GHz Quad-Core ARM Cortex-A53  
- 1GB RAM  
- Gigabit Ethernet  
- Micro SD socket  
- HDMI, USB 2.0 ports  

---

### **Algorithm and Modules**  

#### **Preprocessing:**  
- Improves image quality and suppresses distortions.  

#### **Feature Extraction:**  
- Techniques like binarization, thresholding, resizing, and normalization are applied to extract critical features.  

#### **CNN (Convolutional Neural Networks):**  
- Specialized for image recognition and pixel data processing.  

#### **Blob Detection:**  
- Identifies regions in images differing in brightness or color compared to surrounding areas.  

---

### **Advantages**  
- **High Accuracy**  
- **Fast Object Detection (using YOLO)**  
- **Low Processing Time**  

---

### **Result**  
- Implemented YOLO and RCNN algorithms for **fast and accurate detection** using Raspberry Pi.  
- Limited computing power caused slower inference and reduced detection accuracy.  

---

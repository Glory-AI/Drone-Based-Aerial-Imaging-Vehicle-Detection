# Drone-Based-Aerial-Imaging-Vehicle-Detection

## Project Overview

The project focused on developing a computer vision dataset for colored vehicle detection and classification using aerial imagery captured with a DJI Mini drone. The aim was to gather over 5,000 images of vehicles with different colors from parking areas within the university campus and develop a well-annotated dataset suitable for object detection and machine learning research.

The project was intended to support computer vision applications such as intelligent transportation systems, autonomous surveillance, smart parking management, and aerial vehicle monitoring. The final goal was to produce a publishable and presentable dataset for research and model training purposes.

## Technical Workflow

1. **Data Acquisition**

   A DJI Mini drone was used to capture aerial images and videos of parked vehicles across different campus parking lots.
    Images were collected under varying lighting conditions, camera angles, and altitudes to improve dataset diversity and robustness.

2. **Dataset Preparation**

   Extracted and organized over 5,000 vehicle images from the captured aerial footage.
   Categorized images based on visible vehicle colors and scene quality.

3. **Annotation Process**

   Used Label Studio for image annotation and labeling.
   Bounding boxes were created around vehicles, with labels assigned according to vehicle color categories.

4. **Model Development**

   YOLO (You Only Look Once) object detection architecture was used for training and testing the dataset.
   The annotated dataset was converted into YOLO-compatible format for model training.

5. **Evaluation and Validation**

   The trained model was evaluated for object detection accuracy and color classification performance.
   Detection results were validated using test images from unseen parking locations.

## Tools and Technologies Used

* DJI Mini Drone
* Label Studio
* YOLO Object Detection Model
* Python
* OpenCV
* Google Colab / Jupyter Notebook
* Git/GitHub for version control


## Project Outcome

* Successfully collected and organized a large aerial image dataset containing over 5,000 vehicle samples.
* Developed a structured and annotated colored vehicle dataset for object detection tasks.
* Trained a YOLO-based computer vision model capable of detecting and classifying vehicles from aerial imagery.
* Aiming to produce a research-oriented dataset suitable for publication, further AI research, and intelligent transportation applications.
* Improved understanding of UAV-based data acquisition, computer vision workflows, and machine learning model development.

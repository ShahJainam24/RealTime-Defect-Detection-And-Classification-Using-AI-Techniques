# Project Overview

<p align="left"> 
<a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue" alt="python" width="120" height="30"/> </a>
<a href="https://code.visualstudio.com/" target="_blank" rel="noreferrer"> <img src="https://img.shields.io/badge/VSCode-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white" alt="vscode" width="120" height="30"/> </a> 
<a href="https://www.json.org/json-en.html" target="_blank" rel="noreferrer"> <img src="https://img.shields.io/badge/json-5E5C5C?style=for-the-badge&logo=json&logoColor=white" alt="Json" width="120" height="30"/> </a> 
<a href="https://www.javascript.com/" target="_blank" rel="noreferrer"> <img src="https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E" alt="JavaScript" width="120" height="30"/> </a> 
<a href="https://www.mongodb.com/" target="_blank" rel="noreferrer"> <img src="https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB" width="120" height="30"/> </a> 
</p>

Visual inspection of an object by a person, in most cases not possible because of the error in eyesight and precision to recognize an object properly. In recent times, only video monitors and video recorders have been used where a person can check on-line or taped video sequences for defects. In this way, only small parts of an object i.e. top or bottom side are viewed.

Additionally, this visual inspection is subjective and dependent on a large number of human factors such as the problems of working longer hours, attention being drawn to other events, subjectivity in terms of defect severity assessment. Developing automatic detection and classification of surface defects of objects has been really a challenging problem. An automatic detection and classification system require knowledge of data concerning the current state of the objects, and a methodology to integrate various types of information into decision-making process of evaluating the quality of the product. The need for surface detection technologies for surface defect classification has long been recognized. Real time image processing typically involves the application of high-speed camera, which may give the defect images in real time. The large amount of information is gathered during this process in the form of images. Human experts evaluate this information and give the level of defects, types of defects of the objects. 

The main focus of this project is to utilize the perfect image of an object with proper dimensions and make effective use of this data in the development of successful application using various new technologies.

# Process Model

![image](https://github.com/ShahJainam24/RealTime-Defect-Detection-And-Classification-Using-AI-Techniques/assets/49012105/1e219c73-63ad-4067-ae6f-27231a5de5ae)

# Implementation Details

### 1 Data Gathering

#### 1.1 Data Gathering for Prototype Model

-   Multiple websites were explored to collect images of various objects like pistons, hot strips, fabrics, metal plates, etc., to build a neural network for defect detection and classification.
-   The collected images represented different examples for training and testing the model.

#### 1.2 Data Creation for Implementing Defect Detection Model

-   A saucer dataset was created specifically for defect detection and classification.
-   Videos of different saucers were recorded, and these videos were converted into individual image frames.
-   These image frames were then categorized into three categories: defect1 (minor defects like design or dents), defect2 (broken or chipped saucer), and normal (perfect saucer).

### 2 Data Understanding

#### 2.1 Data for Prototype Model Building (Pistons Dataset)

-   The dataset contained images of pistons classified into three categories: normal pistons, pistons with Defect Type 1, and pistons with Defect Type 2.
-   These images were used to build a neural network for object classification.

#### 2.2 Data for Building Defect Detection Model (Saucer Dataset)

-   The saucer dataset comprised images of saucers falling into three categories: defect1, defect2, and normal saucers.
-   The dataset was created by converting video frames of saucers into images for defect detection model building.

### 3 Building Neural Network and Implementing Defect Detection

#### 3.1 Model Building for Pistons Dataset

-   A Sequential Neural Network was built for the pistons dataset with layers for image classification.
-   The model was trained and optimized using the Adam optimizer with accuracy metrics.

#### 3.2 Data Preparation and Pre-processing on Saucer Data

-   The saucer dataset was prepared by capturing videos of saucers and converting them into image frames.
-   These images were divided into training, testing, and validation datasets for model training.

#### 3.3 Model Building for Saucer Dataset

-   Similar to the pistons dataset, a Sequential Neural Network was built for the saucer dataset.
-   The model was trained using the Adam optimizer and accuracy metrics.

### 4 Testing on Video Feed

-   The implemented models were tested on video feeds to detect and classify defects in real-time.
-   The models correctly recognized and classified defects in saucers captured from video.

### 5 Front-End Development

-   The front-end of the web application was developed using HTML, CSS, and JavaScript, integrated with Flask.
-   The application allowed users to interact with the model, either through a webcam for real-time defect detection or by uploading a demo video.

### 6 Analytics and Insights

-   Data from object detection, including object IDs and defect categories, were stored in MongoDB.
-   The MongoDB database was integrated with the Flask framework to provide insights and analytics to users.
-   Insights included the classification of saucers, the number of saucers detected over time, and graphical representations of the data.

This project implemented defect detection and classification for various objects, enhancing quality control and providing valuable insights to users through a user-friendly web application.


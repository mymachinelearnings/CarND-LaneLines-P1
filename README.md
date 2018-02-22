
# **Term 1 Project 1 : Finding Lane Lines on the Road** 

#### This Project is part of Udacity's Self-Driving Car Nanodegree Program(SDC ND) Term 1

---

## Project Overview


### **Problem Statement** <br/>
Finding Lanes in different road conditions. For this, two solid lines are to be determined - one for the left and the other for the right lane.

### **Solution** <br/>
Using various transformations(as indicated in the project writeup), two solid lines are determined and superimposed on the input images/video so that the lanes are clearly identified.

### **Summary**<br/>
This project is about finding two solid lines indicating the left & right lanes of a well-marked road. This solution works well for any properly marked road.
The following image would give you an idea on what the solution looks like. The left Image is the input and the right image is the output where you can observe solid lines superimposed on the image.

Original(RGB) Space | Image with Lane Markers
- | - 
![Original(RGB) Space](test_images_output/SolidWhiteTransformations/solidWhiteCurve.jpg) |  ![Image with Lane Markers](test_images_output/SolidWhiteTransformations/output_solidWhiteCurve.jpg)

A similar approach would be followed for marking lanes in a video. Video will be a stream of images running in sequential order. So the solution would be to process each individual frame of the video (which is an image) and apply the same logic used for processing images.

---

## Getting Started

### **Technology Stack** :
  * Python 3.6.3
  * OpenCV for Computer Vision Processing
  * numpy for array/matrices handling
  * matplotlib for Image plotting
  * moviepy for image processing
  * Jupyter Notebook as IDE
  

### **Setting up the Environment** <br/>
* Install miniconda or any package Management utility like pip
* setup a conda environment with all required packages
* activate the environment
* clone [Git Repo](https://github.com/mymachinelearnings/CarND-LaneLines-P1.git) to your local computer and open the code in Jupyter Notebook
* Run & Enjoy!
    
**Note** : This is part of Udacity's Self Driving Car Nanodegree Project 1. clear setup instructions are present [here](https://github.com/udacity/CarND-Term1-Starter-Kit/blob/master/doc/configure_via_anaconda.md)


### **Project Files** <br/>
* README.md 
    * A brief overview of the project and setup
* Term1 Prj1 Finding Lanes.ipynb 
    * Jupyter Notebook with Python code to find lane lines
* writeup_T1P1 
    * Explanation of the code and others
* test_images, test_videos 
    * Test set for this project
* test_images_output, test_videos_output 
    * Resulting Image/Videos that are processed using the code
You can ignore the rest of the files

### **Running the code** <br/>
Once the environment is setup and the repository is cloned to your local machine, start Jupyter Notebook form the project folder using <br/> `jupyter notebook` command and run each cell `Shift + Enter` and the output will be inline & written to the output folders

Note : Test set for this code is contained in test_images & test_videos, and the resulting processed images & videos are present in test_images_output & test_video_output

---

### **Authors** <br/>
* Ravi Kiran Savirigana

### **Acknowledgements** <br/>
Thanks to Udacity for providing the templates to start with. And a great community help in stackoverflow.com & github.com

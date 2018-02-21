
# **Term 1 Project 1 : Finding Lane Lines on the Road** 

#### This Project is part of Udacity's Self-Driving Car Nanodegree Program(SDC ND) Term 1

## Project Overview


### **Problem Statement** <br/>
Finding Lanes in different road conditions. For this, two solid lines are to be determined - one for the left and the other for the right lane.

### **Solution** <br/>
Using various transformations(as indicated in the project writeup), two solid lines are determined and superimposed on the input images/video so that the lanes are clearly identified.

### **Technology Stack** :
  * Python 3.6.3
  * OpenCV for Computer Vision Processing
  * numpy for array/matrices handling
  * Jupyter Notebook as IDE
  
### **Summary**<br/>
This project is about finding two solid lines for the left & right lanes of a well-marked road. This solution might not work for roads that are not properly marked.
The following image would give you an idea on what the solution looks like. The left Image is the input and the right image is the output where you can observe solid lines superimposed on the image.

A similar approach would be followed for marking lanes in a video. Video will be a stream of images running in sequential order. So the solution would be to process each individual frame of the video (which is an image) and apply the same logic used for processing images.

### **Setting up the Environment** <br/>
This project uses python libraries like numpy, opencv. For easier setup, follow the steps given below<br/>
Follow the instructions mentioned [here](https://github.com/udacity/CarND-Term1-Starter-Kit/blob/master/doc/configure_via_anaconda.md) to 
	* setup a conda environment with all required packages
	* activate the environment
**Note** : Not all packages you've installed as part of this process are required for this exercise but this is a general purpose setup for the entire term 1 of Udacity SDC ND.

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

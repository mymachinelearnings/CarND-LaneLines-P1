{
 "cells": [
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "# **Term 1 Project 1 : Finding Lane Lines on the Road** "
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "#### This Project is part of Udacity's Self-Driving Car Nanodegree Program(SDC ND) Term 1\n",
    "\n",
    "## Project Overview\n",
    "\n",
    "\n",
    "### **Problem Statement** <br/>\n",
    "Finding Lanes in different road conditions. For this, two solid lines are to be determined - one for the left and the other for the right lane.\n",
    "\n",
    "### **Solution** <br/>\n",
    "Using various transformations(as indicated in the project writeup), two solid lines are determined and superimposed on the input images/video so that the lanes are clearly identified.\n",
    "\n",
    "### **Technology Stack** :\n",
    "  * Python 3.6.3\n",
    "  * OpenCV for Computer Vision Processing\n",
    "  * numpy for array/matrices handling\n",
    "  * Jupyter Notebook as IDE\n",
    "  \n",
    "### **Summary**<br/>\n",
    "This project is about finding two solid lines for the left & right lanes of a well-marked road. This solution might not work for roads that are not properly marked.\n",
    "The following image would give you an idea on what the solution looks like. The left Image is the input and the right image is the output where you can observe solid lines superimposed on the image.\n",
    "\n",
    "A similar approach would be followed for marking lanes in a video. Video will be a stream of images running in sequential order. So the solution would be to process each individual frame of the video (which is an image) and apply the same logic used for processing images.\n",
    "\n",
    "### **Setting up the Environment** <br/>\n",
    "This project uses python libraries like numpy, opencv. For easier setup, follow the steps given below<br/>\n",
    "Follow the instructions mentioned [here](https://github.com/udacity/CarND-Term1-Starter-Kit/blob/master/doc/configure_via_anaconda.md) to \n",
    "\t* setup a conda environment with all required packages\n",
    "\t* activate the environment\n",
    "**Note** : Not all packages you've installed as part of this process are required for this exercise but this is a general purpose setup for the entire term 1 of Udacity SDC ND.\n",
    "\n",
    "### **Project Files** <br/>\n",
    "* README.md \n",
    "    * A brief overview of the project and setup\n",
    "* Term1 Prj1 Finding Lanes.ipynb \n",
    "    * Jupyter Notebook with Python code to find lane lines\n",
    "* writeup_T1P1 \n",
    "    * Explanation of the code and others\n",
    "* test_images, test_videos \n",
    "    * Test set for this project\n",
    "* test_images_output, test_videos_output \n",
    "    * Resulting Image/Videos that are processed using the code\n",
    "You can ignore the rest of the files\n",
    "\n",
    "### **Running the code** <br/>\n",
    "Once the environment is setup and the repository is cloned to your local machine, start Jupyter Notebook form the project folder using <br/> `jupyter notebook` command and run each cell `Shift + Enter` and the output will be inline & written to the output folders"
   ]
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.5.2"
  },
  "widgets": {
   "state": {},
   "version": "1.1.2"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 2
}

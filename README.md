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
    "---\n",
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
    "### **Summary**<br/>\n",
    "This project is about finding two solid lines indicating the left & right lanes of a well-marked road. This solution works well for any properly marked road.\n",
    "The following image would give you an idea on what the solution looks like. The left Image is the input and the right image is the output where you can observe solid lines superimposed on the image.\n",
    "\n",
    "Original(RGB) Space | Image with Lane Markers\n",
    "- | - \n",
    "![Original(RGB) Space](test_images_output/SolidWhiteTransformations/solidWhiteCurve.jpg) |  ![Image with Lane Markers](test_images_output/SolidWhiteTransformations/output_solidWhiteCurve.jpg)\n",
    "\n",
    "A similar approach would be followed for marking lanes in a video. Video will be a stream of images running in sequential order. So the solution would be to process each individual frame of the video (which is an image) and apply the same logic used for processing images.\n",
    "\n",
    "---\n",
    "\n",
    "## Getting Started\n",
    "\n",
    "### **Technology Stack** :\n",
    "  * Python 3.6.3\n",
    "  * OpenCV for Computer Vision Processing\n",
    "  * numpy for array/matrices handling\n",
    "  * matplotlib for Image plotting\n",
    "  * moviepy for image processing\n",
    "  * Jupyter Notebook as IDE\n",
    "  \n",
    "\n",
    "### **Setting up the Environment** <br/>\n",
    "* Install miniconda or any package Management utility like pip\n",
    "* setup a conda environment with all required packages\n",
    "* activate the environment\n",
    "* clone [Git Repo](https://github.com/mymachinelearnings/CarND-LaneLines-P1.git) to your local computer and open the code in Jupyter Notebook\n",
    "* Run & Enjoy!\n",
    "    \n",
    "**Note** : This is part of Udacity's Self Driving Car Nanodegree Project 1. clear setup instructions are present [here](https://github.com/udacity/CarND-Term1-Starter-Kit/blob/master/doc/configure_via_anaconda.md)\n",
    "\n",
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
    "Once the environment is setup and the repository is cloned to your local machine, start Jupyter Notebook form the project folder using <br/> `jupyter notebook` command and run each cell `Shift + Enter` and the output will be inline & written to the output folders\n",
    "\n",
    "Note : Test set for this code is contained in test_images & test_videos, and the resulting processed images & videos are present in test_images_output & test_video_output\n",
    "\n",
    "---\n",
    "\n",
    "### **Authors** <br/>\n",
    "* Ravi Kiran Savirigana\n",
    "\n",
    "### **Acknowledgements** <br/>\n",
    "Thanks to Udacity for providing the templates to start with. And a great community help in stackoverflow.com & github.com"
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

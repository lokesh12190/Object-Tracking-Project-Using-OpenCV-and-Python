# Object-Tracking-Project-Using-OpenCV-and-Python
Single and Multi object Tracking
## OBJECT TRACKING
Object tracking is an application of computer vision where an object is detected in a video, otherwise interpreted as a set of frames, and the object’s trajectory is estimated.

## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. 


## Understanding Project Structure
```
objectTrackingOpencv
|-- InputFiles
    -- car_driving.mp4
    -- chaplin.mp4
    -- horse_riding.mp4 
    -- run.mp4
|-- SourceFolder
    -- CentroidTracking.py
    -- SingleObjectTracking.py
    -- MultiObjectTracking.py
|-- README.MD
 -- Engine.py
 -- requirements.txt
```

## Prerequisites
* Python3.X


## Installing
* To activate Virtual Environment
    * First install Virtual Environment for python3 using this command in your terminal\
           `pip install virtualenv`
   
    * Create a new Virtual Env\
            `python3 -m venv task_env`
        
    * In the current working directory i.e **objectTrackingOpencv**, activate the virtualenv\
            `source task_env/bin/activate`
            
* run this command in command line to install needed dependencies\
     `pip install -r requirements.txt`


### NOTE
You can download the GOTURN caffemodel and prototxt files located at: https://github.com/spmallick/goturn-files
1. You need the goturn.caffemodel file and goturn protxtxt for running the goturn model - these must be downloaded from the above link and stored in the ML_Pipeline folder
2. You need the res10_300x300_ssd_iter_140000.caffemodel and deploy.prototxt file for executing the CentroidTracking.py file - these must be present in the ML_Pipeline folder.
     
For concatenating the goturn model;
1) git clone 

2) on unix

cd goturn-files

cat goturn.caffemodel.zip* > goturn.caffemodel.zip

unzip goturn.caffemodel.zip

3) on windows

type goturn.caffemodel.zip* > goturn.caffemodel.zip

Extract the zip with any unzipping libra

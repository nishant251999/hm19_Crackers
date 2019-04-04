# hm19_Crackers

College name- Bharati Vidyapeeth's College of Engineering

Team Leader name- Nishant Jain
Team member 1- Itisha Goyal
Team member 2- Harshit Mittal

PLAN OF ACTION :

-The prototype is all software based for now.
-It takes any camera feed in input and returns the speed and type of vehicle(with help of ML).
-Speed limits are then set and an image of vehicles breaching that limit is captured.
-Multiple images are captured to ensure the best possible view of the vehicle’s number plate.
-Through OCR, the number plate can be read.
-Date, time and location can easily be found with the help of image saved in computer and location of the auto rickshaw (use of GPS).
-The time, location and vehicle’s number are then mailed to concerned authorities with the help of a python script.

INSTRUCTIONS TO RUN :

Download the zip file from the given link in Source Code file. 
Unzip the source code folder.

Python packages to be installed

Tensorflow (Tensorflow-gpu if you have Nvidia GPU)
openCV
imutils
Pillow
numpy
tkinter
urllib
openALPR api
Download openalpr API from this link: https://github.com/openalpr/cloudapi/tree/master/python/openalpr_api

Run the project by the command python3 VehicleMonitor.py


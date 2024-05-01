# Design and Implementation of a Surveillance and Security System Using OpenCV and YOLO8

This Flask application streams video from a webcam and performs real-time object detection using YOLO model from Ultralytics. It also captures images of intruders at regular intervals and applies various image processing techniques.

## Installation steps

1. Clone this repository to your local machine.
2. Install the required dependencies by running: pip install -r requirements.txt


# Note before Run: 
1.Download the weights file from google drive link: "https://drive.google.com/file/d/1KJqIL7Za1daESKxrADMK_knqfw7pEdCO/view?usp=share_link"
2.You have to run the command from terminal only.
3.Before every Run Delete the 'runs' folder from the same directory where these files are located.Continue if you don't have this folder.
4.Delete all the folders ends with '_images' present in same directory to avoid browser caching.
5.Make sure you have only app.py, iptechniques.py, best15.pt, requirements.txt, Readme.md, templates and logo folders in this directory.
6.This trained model can identify only 4 classes(Arun, Ali, Kaushik and Intruder). If any person(other than Arun, Ali, Kaushik) comes before the camera, model identifies them as intruder.

## Usage

1. Run the Flask application from terminal: python app.py
2. Open your web browser and go to `localhost ip address visible in terminal` to view the video stream and access the image processing functionalities.

## Features

- Real-time video streaming from webcam.
- Object detection using YOLO model.
- Image capture at regular intervals.
- Various image processing techniques such as histogram equalization, edge detection, and thresholding.

## Authors

Arun Sai Teja Medisetty,
Girish Kumar Reddy Boreddy,
Akshitha Reddy Thokala, 
Ali Abbasi Maleki, 
Nupoor Vijay Kumbhar, 
Rachana Jinukula, 
Sree Sai Preetham Nandamuri, 
Venkata Achyuth Kumar Sanagapalli,
Venkata Kaushik Belusonti, 
Vishnu Sai Inakollu

# Invisibility-Cloak
Hello Everyone, Watching Harry Potter was one of the most fascinating things we saw during our childhood and something which still fascinates us!  One of the eye-catching part of the movie is Harry and Ron's hideout at Hagrid's. Inspired by this I have come up with an Invisible Cloak that makes you invisble. You could also use this to scare your friends and colleagues as this also draws inspiration from the movie Hollow Man.

Fascinated by it I have come with up this project which makes use of Color Detection and Object Segmentation.
My project makes use of a video input where it detects red colour being given a threshold of a range of values.

Initially all things containing every color is detected as our python file is so programmed. Then only those things which are not Red are detected.

Then these two are given as inputs to another variable which will NAND both the inputs.
Therefore our live video stream will not be able to detect anything that is red in colour. Also if you are behind any red object you are invisible too!

This can be executed for any colour by specifying the required color thresholds and RGb Values.

Purpose:
This project is aimed at Color Segmentation and Object Detection. This can be used for various entertainment purposes as well as automated machines which need to detect a specific color or any object.

Pre-Requisites:
Python3
Numpy Libraries
'pip install opencv-python' to import cv2

Contact:
GitHUB : https://github.com/ADITYA1720
E-MAIl : adityadjadhav17@gmail.com

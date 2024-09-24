color-detection-and-tracker
color-detection-and-tracker is a python application to detect color from images and track colors & objects in realtime using HSV object detection method. It uses basic computer vision tools to achieve this and is deployed using tkinter.

Packages used:
numpy, requests, pandas, opencv-python, Pillow(PIL), tkinter

Features:
Detect Color : This feature detects color from the selected picture. Import an image and clicking anywhere on it gives you the color name.

Track objects from image : This feature allows you to track colors from a imported image. Choose an image and click detect, in the next screen adjust HSV values to track colors.

Track objects in realtime : You can track objects in realtime using this feature. Select track objects in realtime and you can tract objects using your pc camera or using your android camera ( IP Webcam required). If choosen pc camera, pass 0 as your camera id and on choosing stream/android pass the local stream url from IP Webcam, and again on the next screen adjust hsv values to detect objects.

About packages:
*Requests---*Requests module is used to send HTTP/1.1 requests easily. The requests.get(url) method sends a GET request to the specified url.

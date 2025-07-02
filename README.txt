🔍 Project Description
🚦 Anomaly Detection in Road Traffic for Safe Transportation
This project aims to enhance road safety by detecting speeding vehicles in traffic footage using computer vision and machine learning techniques. Leveraging OpenCV and Dlib libraries, it identifies cars in real-time, tracks their movement, and calculates their speed. If a vehicle exceeds the defined speed threshold (e.g., 55 km/h), it flags the vehicle as "OverSpeed".

🔧 Technologies Used
Python
OpenCV
Dlib
Haar Cascade Classifier
Computer Vision
XML (for trained car detection classifier)

🎯 Key Features
Real-time car detection using Haar Cascades.
Vehicle tracking with Dlib correlation trackers.
Speed estimation based on pixel movement and frame rate.
Overspeed warning annotations.
Outputs video with bounding boxes and speed overlays.

📂 Files Included
car_speed.py: Main Python script for car tracking and speed estimation.
vech.xml: Haar cascade XML file for vehicle detection.
car_speed.mp4 (or carsVid.mp4): Input video file (you can rename accordingly).
outNew.avi: Output video with annotations (generated during execution).

🚀 How It Works
Reads frames from input video.
Detects cars every 10 frames using Haar classifier.
Tracks each car using a correlation tracker.
Estimates speed based on pixel displacement.
Annotates frames with speed and alerts for overspeeding.
Saves and displays the annotated output video.


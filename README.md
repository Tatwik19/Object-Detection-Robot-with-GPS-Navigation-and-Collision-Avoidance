# Object Detection/Tracking Robot with GPS Navigation and Collision Avoidance using YOLOv5
GPS Guided Autonomous Robot with vision based Obstacle Avoidance

The entire project is written in Python and performed on NVIDIA JetBot with Jetson nano

Components used:
MPU 9250 (For magnetometer)  
Ublox NEO 6M (GPS module)  
Rasbery Pi Camera V2.1
  
INTRODUCTION  
The goal of this project is to create an autonomous robot that detects objects of interest and uses GPS navigation. Image processing is employed to avoid collisions. A self-navigating unmanned vehicle travels to user-specified destination coordinates wirelessly. The navigation of the unmanned vehicle uses GPS and magnetometer, and a vision-based collision avoidance system is being used. Utilizing image processing from the camera feed of the vehicle's front view to prevent collisions. The research uses YOLOv5 (You Only Look Once), which is a real-time object detection system to detect and track the object of interest. In this paper, Sai Srinivas Tatwik presents the design and implementation of the autonomous vehicle’s algorithm. The created algorithm may be extended to a number of tasks, such as monitoring, research, and navigating to areas that may be unsafe for people.

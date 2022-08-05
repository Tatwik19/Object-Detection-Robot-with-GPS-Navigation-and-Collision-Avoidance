# Object Detection/Tracking Robot with GPS Navigation and Collision Avoidance using YOLOv5
GPS Guided Autonomous Robot with vision based Obstacle Avoidance

The entire project is written in Python and performed on NVIDIA JetBot with Jetson nano

Components used:
MPU 9250 (For magnetometer)  
Ublox NEO 6M (GPS module)  
Rasbery Pi Camera V2.1
  
## INTRODUCTION  
The goal of this project is to create an autonomous robot that detects objects of interest and uses GPS navigation. Image processing is employed to avoid collisions. A self-navigating unmanned vehicle travels to user-specified destination coordinates wirelessly. The navigation of the unmanned vehicle uses GPS and magnetometer, and a vision-based collision avoidance system is being used. Utilizing image processing from the camera feed of the vehicle's front view to prevent collisions. The research uses YOLOv5 (You Only Look Once), which is a real-time object detection system to detect and track the object of interest. In this paper, Sai Srinivas Tatwik presents the design and implementation of the autonomous vehicle’s algorithm. The created algorithm may be extended to a number of tasks, such as monitoring, research, and navigating to areas that may be unsafe for people.
  
  
## SOFTWARE DESIGN

Main Loop flowchart  
![NSTL Software design Main Routine drawio](https://user-images.githubusercontent.com/96451759/183043685-bbbe597f-4e4a-4933-a9d1-8974e868d2db.png)

Flowchart for System Initialization  
![NSTL Software design Initialize System drawio](https://user-images.githubusercontent.com/96451759/183044472-cb777bee-e900-4ee6-b257-64f4055b51b8.png)

Subroutine for Object Detection  
![NSTL Software design Object Detection Routine drawio](https://user-images.githubusercontent.com/96451759/183044605-23339116-9e30-4c54-958c-3a9f79ced40f.png)

Subroutine for Collision Avoidance  
![NSTL Software design Collison Avoidance drawio](https://user-images.githubusercontent.com/96451759/183044810-4ab7a294-ab32-4972-8149-7edefbf2c5f0.png)

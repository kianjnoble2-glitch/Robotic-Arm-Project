# Robotic-Arm-Project (Co-developer)

This project is now complete, the following is what it achieved:

Made use of YOLO object detection and ESP32 camera to detect and sort objects based on visual characteristics (colour of the object in this case).

Moved objects from the pick up point to different positions based on the detected colour of the object.

Custom blazer mobile app that gave users the ability to start and stop the sorting process (uses an express server with a REST API to connect the app and the robot arm together). Custom blazer mobile app also gives users status updates about the mobile app and the robot (connected or not connected).
obile app also tells users what the robot arm is currently doing (currently sorting or on standby).

Robot is able to move to all designated positions and pick up and place down objects (see below youtube video link). 
Link of demonstration : https://youtu.be/SiDiiW4zKR8
Robot is able to differentiate between different colours and sort accordingly: 
Link of demonstration: https://www.youtube.com/watch?v=NX4PpT_mN6E

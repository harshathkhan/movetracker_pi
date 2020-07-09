# MOVE TRACKER
# MOTION - DETECTION SECURITY SYSTEM
The main idea of the project is to alert with any uncommon movements in the house when the housemates are away. Nowadays robbery is very common even in our busy cities. 
So to take a step to prevent and protect ourselves,the project is made. 
Its security system with raspberry pi, and motion sensor and a pi cam to record the motion.
We used raspberry pi 4 along with PIR motion sensor. Rasbian buster lite is the OS used . 
python is the language used for coding. Initially OS was installed and we have to configure our wifi network. 
Then camera module is also attached to the pi.We use PIR motion sensor as it senses the motion around 120 degree vertically so if we keep the sensor at a corner of our room then we can cover the complete dimension. 
The python program works in the way that it starts scanning the PIR sensor’s output. When the motion is detected ,the output of PIR sensor is 1 and the code checks for the camera to be enabled The camera captures a video of 5-6 seconds and then convert it from h264 raw format to mp4 format .
The video is sent to the given email. So the user can check the video and if anything suspicious, he could make an alarm through his phone.
PIR passive infrared sensor which have high sensitivity range. 
Raspberry pi is chosen as it is very user friendly and supports python and has many USB ports and SD card can be inserted.

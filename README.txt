Team Size: 5
Language and tools-Python, hSenid API, raspberry pi, arduino, wide angle motion detection sensor and
web cam
Contribution-Implement USSD and SMS section using hSenid API
we did this project for tadHack hackerthon organized by hSenid mobile and and got selected into the final
15 teams out of 100. In this project, we built a home security device with IoT to help home owners. This
device supports: Movement detection through web cam, Human detection using OpenCV, Gas detection
through MQ2 gas sensor, Uploading photos of intruders to user’s google drive account, Sending alert
text messages to user’s mobile phone through a dongle connected to device Sensors were attached to an
Arduino UNO board. Arduino board, web cam and the 3g dongle attached to a raspberry pi B+.Oauth
2.0 has been used to authenticate devices to user’s google drive. Sending and receiving text messages
to device was achieved by serial communication. Human detection was achieved using openCV 2.4.10.
Devices operate on voice commands. They track user’s location to give maximum security to household.
We used hSenid APIs like SMS and USSD to transfer that massages to owners. Underlying codes are
written in Python.

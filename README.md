# Mediapipe_ROS_Project
Piloting a mobile base robot with gesture recognition allows by mediapipe

My thesis subject of my 6 months internship at UNIMORE University of Modena,Italia constited in creating a informatic program to catch position of the user with a webcam, detect what kind of position the user is making and depending on that, move the UR10E Robot. As we say, 'one picture worth a thousand words', you can check the final test video here : https://drive.google.com/file/d/1w5VgjV3_ha-61Da7t3WNPMw6gN6Anj2m/view

- Step 1 : Catching the data of the position that the user is making on the webcam screen using mediapipe (https://mediapipe.dev/) and OpenCV.
- Step 2 : Create a loop to build the training dataset with the coordinates of the dots showing on the webcam screen of the user.
- Step 3 : Build an Machine learning model to predict the futur position that the user will make on the screen. And evaluate the accurancy of it.
- Step 4 : Create a ROS node to define what kind of mouvement the robot will make (Go straight, turn right...) for each position setted up before.
- Step 5 : Enjoy piloting a robot by distance only with gesture recognition ;)

In this Repository you gonna have only the Python Script, but to connect it with the robot you have to build your folder and your project regarding on the ROS documentation (https://www.ros.org/).
That's why you can download the complete project with the zip file.

<picture>

 <img alt="Test du pilotage du robot UR10E" src="C:\Users\User\Desktop\Test pilotage robot.png">
</picture>

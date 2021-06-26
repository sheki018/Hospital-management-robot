# Hospital management robot

This is a hospital management robot which transports all needed medicines and food to the patients thereby avoiding physical contact. It can be used at home as well.

This repository contains a "nodemcu_robot.ino" file which contains the code for the microprocessor. All actions of the robot are defined here. There is another apk file which contains the android application where we can control the actions of robot. Instructions to use this application is provided below.

UNDER THE HOOD:

HARDWARE:

It is made up of 4 major components.

1.NODE MCU – We have got this so that it can work wirelessly

2.L2393D H BRIDGE MOTOR DRIVER

3.50 RPM GEARED MOTOR – we have limited its speed to obtain maximum stability and to make sure that everything is transported in shape

4.TWO 6V, 4.5A BATTERY – just a little bit of juice to power up the robot but you can power up the robot for 2 hours on a single charge whereas it will take one hour to fully charge the battery depending upon the usage.

SOFTWARE:

Right now, we have programmed the nodemcu to do to basic operations like moving forward, back and the sides using Arduino IDE and then we took the complex part like voice recognition to the app we created via MIT app inventor. Now coming back to the codes! We have used C++ for programming the nodemcu (INO file) and we have used Java in programming the Application that we created. The application is secure as it keeps track of the IP address.

INSTRUCTIONS TO USE:

1.Install and open the APK file in your android device.

2.In the home screen choose your choice of control either manual or voice control.

Manual control:

3.Use the arrow buttons to control the direction of robot’s travel and the stop button to stop the movement of the robot.

4.Use the slider below to control the speed of the robot.

5.Press the “Switch to Voice Control” button to switch to the screen where the actions of the robot can be controlled by voice commands.

Voice control:

6.Press the microphone button and allow permissions to use device’s microphone.

7.Press the “How to use” instruction button to check out all the valid commands to control the actions of the robot.

8.Speak commands such as “go forward”, “turn right”, turn left” and “go back” to control the robot’s actions.

9.Press the “Switch to Manual Control” button to return back to the original screen.

10.Close the app.

# ABOUT THE PROJECT
------------------------------------------------------------
The purpose of this image is to give you a jump start to 
programming your robot with Android Studio. 
------------------------------------------------------------

PREREQUISITES
------------------------------------------------------------
1) USB WIFI stick - such as the WUSB6300 or similar cheap one
2) Access to a non-DoDEA internet connection  
3) A Github account for every programmer
------------------------------------------------------------

SPECIAL NOTE ABOUT MOTORS AND SERVOS
------------------------------------------------------------
1) The Rev Control Hub - https://www.revrobotics.com/rev-31-1595/
	a) up to 4 DC motors such as https://www.revrobotics.com/rev-41-1600/
	b) up to 6 Servos such as https://www.revrobotics.com/rev-41-1097/
	
2) If your robot requires more than 4 DC motors, you can use
   a) REV expansion hub - https://www.revrobotics.com/rev-31-1153/
      which gives you an additional 4 DC motors and 6 servo ports
   OR
   b) Use a servo port to control a Sparkmini https://www.revrobotics.com/rev-31-1230/
      Any use of a Sparkmini will require the availibity of a XT30 power port. To add more
      power ports, you can use https://www.revrobotics.com/rev-31-1293/
   OR
   c) there is a new part that can remove the need for the expansion hub
      our team will test it this year. https://www.revrobotics.com/rev-11-1855/ 
      this gives an additional 6 servo ports. See option b.	
------------------------------------------------------------	  

SPECIAL NOTE ABOUT THE DRIVE CHASSIS AND ODOMETRY
------------------------------------------------------------
1) The start kits come with a tank drive system https://xiaoxiae.github.io/Robotics-Simplified-Website/drivetrain-control/tank-drive/ which DOES NOT WORK WELL in FTC. Instead, I recommend you use a mecanum drive. I Strongly recommend https://www.gobilda.com/strafer-chassis-kit-104mm-gripforce-mecanum-wheels/
2) To run autonomous, you need to use odometry to track the robots location on the field. I strongly recommend the following https://www.gobilda.com/odometry. This requires 2 odometry pods and 1 computer.
------------------------------------------------------------

GETTING STARTED
------------------------------------------------------------
1) Update your control hub - https://docs.revrobotics.com/rev-hardware-client/duo/control-hub
2) Update your driver hub - https://docs.revrobotics.com/rev-hardware-client/duo/driver-hub

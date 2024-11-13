# ABOUT THE PROJECT
------------------------------------------------------------
The purpose of this image is to give you a jump start to programming your robot ideally with Android Studio. 
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
	
3) If your robot requires more than 4 DC motors, you can use  
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
3) Plug in you USB WIFI stick and connect to the virtual machine.
4) Connect the virtual machine to your robot using WIFI
5) Choose how you are going to program the robot https://ftc-docs.firstinspires.org/en/latest/programming_resources/shared/choosing_program_lang/choosing-program-lang.html
6) To get the most out of the robot, you will need to use Android Studio.
------------------------------------------------------------

GETTING STARTED with Android Studio
------------------------------------------------------------
*some of these steps may already be done in the released image for the 2024-25 FTC season
1) read and complete only this page: https://ftc-docs.firstinspires.org/en/latest/programming_resources/tutorial_specific/android_studio/installing_android_studio/Installing-Android-Studio.html
2) Github integration
   	a) only read the following page: https://ftc-docs.firstinspires.org/en/latest/programming_resources/tutorial_specific/android_studio/fork_and_clone_github_repository/Fork-and-Clone-From-GitHub.html
   	b) log into Github
   	c) Paste the URL to the DoDEA FTC 2024-25 base code: [https://github.com/team3011/2025FTC_BaseCode](https://github.com/team3011/2025_BaseCode)<br>
    	d) Click on Fork. This will take you to the “Create a new fork” page, and will auto-fill the “Owner” and “Repository name” fields. I would rename the repository to your team number following by an 'a'. Just enter a description (optional), leave the “Copy the master branch only” option checked, and click the green “Create fork” button.
4) Importing the base project from GitHub<br>
	a) If this is your first time opening a project click on Get from VCS otherwise click File -> New -> Project from Version Control<br>
	b) Install Git if you have not already<br>
 	c) Paste the URL your forked project<br>
  	d) Click clone (this will take a while to pull everything in, be patient)<br>
   	e) If prompted, do NOT update the Android Gradle plugin!!!!!!!!!!!<br>
   	f) The base project includes FTCLib and RoadRunner<br>
5) Pushing test code to the robot with a USB cable<br>
	a) Open the Subsystem_Test.java program and read the comments<br>
	b) Turn on the robot<br>
	c) plug the usb cable into the control hub<br>
	d) plug the usb cable into the computer<br>
	e) The top bar of Andriod Studio should now show the control hub connected to the left of TeamCode. If it is not there, check to make sure the control hub is connected to the VM. On the VM bar click Devices -> USB, make sure there is a check mark next to the control hub. If the check mark is not there, click on the device.<br>
	f) To push code, click on the green triangle next to Teamcode.<br>
6) 

#Fuzzy Logic Project

##CONTENTS

<ol>
<li>SETUP</li>
<li>ABSTRACT</li>
</ol>

##1. SETUP

###1.1 DOWNLOAD JAVA SE JDK
GO TO: http://www.oracle.com/technetwork/java/javase/downloads/jdk7-downloads-1880260.html
DOWNLOAD JDK FOR YOUR OS. FOLLOW ON SCREEN INSTRUCTIONS WHEN INSTALLING THE JDK.

###1.2 GET THE CODE
THE CODE IS BEING HOSTED ON GITHUB. MAKE AN ACCOUNT WITH GITHUB - MSG ME REGARDING WRITE ACCESS.
IF YOU ARE NEW TO USING GIT, SUGGEST USING: http://windows.github.com/ - TO PROVIDE EASY GUI LAYOUT FOR USING GIT REPO SYSTEM.
CLONE REPO TO LOCAL DIRECTORY.

###1.3 SET UP IDE
THIS IS ONLY FOR ECLIPSE RIGHT NOW. ECLIPSE CAN BE DOWNLOADED FROM http://www.eclipse.org/downloads/packages/eclipse-classic-422/junosr2.
SELECT YOUR OS FROM THE DOWNLOAD LINKS PANEL ON THE RIGHTSIDE, DOWNLOAD - UNZIP. NO INSTALLATION REQUIRED, RUN "eclipse.exe" IN EXTRACTED FOLDER.
CHOOSE A WORKSPACE - ANY FOLDER SHOULD WORK (DON'T SELECT THE CLONED FOLDER OR ANY FOLDER INSIDE IT FROM SECTION 1.2)
IMPORT PROJECT TO ECLIPSE BY ACCESSING "FILE>IMPORT..." SELECT "GENERAL>EXISTING PROJECTS TO WORKSPACE". CLICK "NEXT". 
SELECT "BROWSE" ON THE NEXT SCREEN FOR THE ROOT OF THE PROJECT. SELECT THE CLONED FOLDER FROM STEP 2. A PROJECT SURE APPEAR, IN THE SPACE BELOW.
MAKE SURE THE CHECKBOX NEXT TO THE PROJECT NAME IS TICKED AND DO NOT COPY THE PROJECT TO YOUR WORKSPACE.

##2. ABSTRACT

ADDED ABSTRACT FOR REFERENCE.

The automobile has become the main means of transportation in the modern world, with the amount of cars on the roads steadily growing on a yearly basis. This leads to people being increasingly vulnerable to car accidents. Transport Canada reports that there were 125,141 automotive collisions in Canada in 2010 [1]. While all modern cars pack a number of passive and active safety systems such as carefully engineered crumple zones, airbags and seatbelts with pretensioners, intelligent accident-avoidance systems continue to be very rare and limited in their functionality. Many accidents happen due to driver mistakes, or because drivers cannot react quickly enough. These types of accidents could be easily avoided if such systems were more prevalent and effective. 

The goal of this project is to build a system that utilizes fuzzy logic to best assist the driver in the safe operation of their vehicle. The system will measure information such as speed, location, behavior of neighbouring cars, conditions of the road surface as well as the laws and obstacles on the given stretch of the road [2]. These inputs and observations will allow the system to make the best decision in regards to the car�s speed, and the lane the car should be occupying. 

Some major actions required for typical highway driving include cruise control and lane changes. These maneuvers have been well researched and estimated in the fuzzy domain. Cruise control for highway driving must consider the legal speed limit and the lead car�s speed and distance ahead. If the leading car is fluctuating speeds the preceding car must be able to adjust accordingly [3]. Additionally, if a car wishes to merge lanes it must consider the available space to merge as well as the space remaining to make a safe merge [4]. 

One focus will be to establish when another driver is behaving in an unsafe manner such as tailgating or making sporadic movements. In these situations the system should apply the driving techniques to properly avoid and mediate the risk of the dangerous driver. Poor road conditions and slower traffic in a specific lane would also indicate a situation in which action should be taken. The final major situation to be considered is the potential of surrounding vehicles attempting to merge into the lane the assisted vehicle is in. As before, lane merging or speed control can be used to adhere to the conduct of the road.

The project will be implemented as a computer simulation rather than in hardware.

##References

[1] Transport Canada, "Canadian Motor Vehicle Traffic Collision Statistics: 2010," 24 October 2010. [Online]. Available: http://www.tc.gc.ca/eng/roadsafety/tp-1317.htm. [Accessed 12 Feburary 2013].

[2] Z. Zhao, S. Zechang and Y. Zhuoping, "Research On Fuzzy Road Surface Identification and Logic Control for Anti-lock Braking System," in Vehicular Electronics and Safety, Beijing, 2006. 

[3] R. Muller, S. A. Daimler-Benz and G. Nocker, "Intelligent Cruise Control with Fuzzy Logic," in Intelligent Vehicles '92 Symposium., Detroit, 1992. 

[4] Y. Hou, P. Edara and C. Sun, "A Genetic Fuzzy System for Modeling Mandatory Lane Changing," in 15th International IEEE Conference on Intelligent Transportation Systems, Anchorage, 2012. 

 

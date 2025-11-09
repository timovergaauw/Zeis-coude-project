# Zeis coudé project for observatory Halley.
# NOTE : the folder OnstepX-main is the Giga project the Onstepx-main zip file is the origin base files from OnstepX

OnstepX based project for Zeis coudé.
initial scope of project:
build on an Arduino Giga with touchscreen.
project is running  servo motors with encoders.
both axis have renishaw encoder rings.
needs an RTC.
optional gps
4 end stops
controlled maximum rotation angle per axis.
uses the onstep user library for fixed vieuw points of like church tower incase its clouded.
uses ascom to control Dome via Nina or Stellarium

Done list:
1. Base Onstep project converted to Arduino Giga R1 including PINNMAP and  HAL file
2. 
TODO list:
1. make the pinnmap for the Arduino Giga R1 compleet
2. upload to the Giga and check wifi acces.
3. test stepper 4890 drivers with motors.
4. read endtsop signals on pins
5. add RTC
6. add servo control part to the project
7. test add gps module
8. add user and observatory related io if theres and extra need
9. dry run test system before mounting on telescope.
10. full assambly on telescoop
11. calibrate the system and make first run
12. public happy to see it work :-)
13. optional stuff manuals e.d

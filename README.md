# UTS-Capstone-ML-IMU-Gait-Analysis
UTS Capstone utilizing machine learning to classify gait pattern

## PLATFORM
Construct IMU Platform (to test and place on body = IMU + battery)
Three Calibration Modes:
- Sitting/Standing
- Walking
- Running
	
##	WIRELESS IMPLEMENTATION
Implement using LabView wirelessly via Bluetooth
Using K means clustering
- Organise data plots
- - Each individual gait test e.g. walking
	
##	TESTING ENVIRONMENT
Perform test in an environment of constant temperature
No external factors such as: wind, air con, heater
###	Placement of Gait Sensor
- Since utilizing 3-axis accelerometers only, will require that sensor to be placed where the swing occurs during gait as walking and running have a very distinct acceleration during the gait.
- Ankle
- Base of foot #1

###	Build Platform
	
##	CALIBRATION
Use auto-calibration of output of IMU in LabVIEW
- K-means clustering to filter outputs
- - If/For statements to determine which movement is occurring i.e. walking, running or standing.
- - Each mode has a separate screen to display activity OR
- - One screen and multiple plots (Walking, Running, Standing

### Walking Calibration
- Set a threshold value i.e. a certain magnitude of acceleration specific to walking (repeat for running)
- Code that all other samples to be Stationary/Standing/Sitting

## MISC
- How to read IMU data from LabVIEW
- How to export data to LabVIEW 

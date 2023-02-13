# Human_Gait_Analysis_LMPS-B2

This project utilisizes the LP-Research Motion Sensor Bluetooth version 2(LPMS-B2) series which is a 9-axis Bluetooth IMU(inertial measurement unit)/attitude and heading reference system(AHRS). Through the use of three different MEMS sensors (3-axis gyroscope, 3-axis accelerometer and 3-axis magnetometer) drift-free, high-speed orientation data around all three axes is achieved. However, For this project we will use Euler anlges read from the sesnor to analyzing the data.

The LPMS-B2 is operated using OpenZen library python API. This python API allows the sensor to stream data in to machine. The binary release of OpenZen includes support for Python 3.8. 

So with the help of LPMS-B2 sensor and OpenZen python API, sensor data is accuired and stored in .csv file extention which will be further filtered using low-pass filtering technique to be able read this data efficiently and plot a clean graph for gait analysis.

Steps for getting started:

We will be requiring the Binary Releasee of Openzen for our code to support the openzen library. You can download the following file from: https://bitbucket.org/lpresearch/openzen/downloads/ 

After downloading the binary file please place these files into the same folder you run your Python script from and the OpenZen module can be imported. 

- Packages required importing:
  - openzen
  - os
  - sys
  - time
  - csv


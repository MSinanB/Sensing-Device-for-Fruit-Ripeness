# Sensing-Device-for-Fruit-Ripeness
University Project completed with a team of 3 including myself

## Project Overview 
This project proposes a way to determine the ripeness of fruit by utilizing an Arduino Nano microcontroller, a KNN classifier for data classification and verification and MQ-135, MQ-3 and MQ-2 gas sensors, which can all be considered easily accessible and cheap electronics to help consumers detect the ripeness of fruit and reduce the negative impacts of wasting food. 

## Hardware
The system consists of a pre-wired control board with multiple sensors attached, an Arduino Nano microcontroller and 3 different MOS gas sensors (MQ135, MQ2, MQ3). 
The MQ135 sensor is mostly used to detect the air quality of the environment. MQ2 and MQ3 sensors are selected based on research, since none of the presented MQ sensors can directly measure ethylene.

## Software
The algorithm includes a data acquisition section, data classification and verification section and an output display section.
Data acquisition algorithm done with Arduino software 
Classification algorithm done with Python through google colaboratory 
Classification process would be done based on quantitatively finding out the amount of ethylene released. Due to the fact that none of the gas sensors are capable of specifically distinguishing ethylene from other gases.






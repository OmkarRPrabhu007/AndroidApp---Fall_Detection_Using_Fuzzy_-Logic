# Android Application for Fall Detection and Alert system Using Fuzzy Logic (_Simulink_)
This project implements a fall detection mechanism using fuzzy logic concepts in Simulink (MATLAB). It simulates an Android application with the following features :


## Features
### 1. Monitor Accelerometer Data
- Monitor the accelerometer data of your phone when the app is running.
- Detect if there is a fall based on the accelerometer readings.

### 2. Record Audio and Measure Sound Level
- Automatically switch on the microphone of the phone if a fall is detected.
- Measure the sound level of the recorded audio.

### 3. Estimate Danger Level Using Fuzzy Logic
- Use fuzzy sound levels (Low, Medium, High) and fuzzy accelerometer levels (Low, Medium, High).
- Estimate the level of danger (Low, Medium, High) based on the fuzzy inputs.

### 4. Send Alert with Audio and Location
- If the danger level is High, send an alert to another phone using TCP/IP or UDP network.
- Transmit the recorded sound from Step 2 and the GPS location of the current phone.

### 5. Play Buzzer Sound
- Play a buzzer sound (alarm type) on the current phone if the danger level is Medium or High.
- The sound level of the buzzer is proportional to the estimated danger level.


## Course 
This project was completed as part of the Control Systems course at the Indian Institute of Technology Gandhinagar (IIT Gandhinagar) under the guidance of [Prof. Nithin V. George](https://www.iitgn.ac.in/faculty/ee/fac-nithin).

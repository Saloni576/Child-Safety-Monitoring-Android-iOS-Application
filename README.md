# Child Safety Monitoring App
This project involves creating an Android/iOS application that helps parents monitor their child's safety while cycling. The app uses the phone's built-in sensors (GPS, accelerometer, and gyroscope) to track the child's activity and provide alerts to the parents. This app was made as an assignment in the Signal Systems and Random Processes course at IITGN.

## Problem Statement
Design and deploy an Android/iOS app for a smart bicycle to help parents monitor their child’s safety.
The smart bicycle has embedded hardware sensors and systems such as a gyroscope, accelerometer, GPS, microphone, and antenna. For this problem statement, assume that your Android/iOS mobile phone (Phone A)  behaves as the smart IoT embedded system and you are riding a (sensorless old-fashioned) bicycle. It should be able to transmit the data to your partner's device (parents’ Android/iOS mobile hereafter referred to as Phone B for warning.
The child-monitoring Android/iOS app (during cycling) should be able to do the following:

1. Continuously monitor the GPS, accelerometer, and gyroscope data of your phone to determine the following
Over speed
Fall detection
Boundary crossing (define some geographical coordinates on campus)
Note: Your device should detect actual falls and avoid false detection like bumps or braking.

2. If the cycle goes beyond a particular perimeter, or over speeds, your device should do the following:
Play a beep alarm sound on your device (Phone A) and parent's device (Phone B).

3. If the cycle falls, your device should do the following:
Play a beep alarm sound on your device (Phone A), with an option to switch OFF the alarm. Also play beep alarm on phone B.

## Tech used
MATLAB (for the backend - converted to C)\

Simulink (for building the UI)

TCP IP Protocols (for real time data transfer)

## Demonstration video link
https://youtu.be/vlIEVO4WqkI?si=77t1nux4Qdj3Dk5y



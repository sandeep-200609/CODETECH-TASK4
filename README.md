Name:SANDEEP S
Company:CODETECH IT SOLUTIONS
ID:CT06DG25
Domain:EMBEDDED SYSTEM
Duration:June 10th to July 25th

Project Title:
Speech Recognition-Based Device Control System using Arduino
 Project Objective:
To design a system that allows users to control electrical devices (like lights or fans) using voice commands. This is achieved through speech recognition on an Android smartphone, which sends commands to an Arduino via Bluetooth to switch devices ON or OFF.

 How It Works (Concept):
The user speaks a command (e.g., "Light on") into an Android app.

The app converts voice to text, then sends a corresponding control signal ('1', '0', etc.) to the Arduino over Bluetooth (via HC-05 module).

The Arduino receives the command, interprets it, and controls a relay, which turns an electrical device ON or OFF.

 Key Components:
Component	Purpose
Arduino UNO/Nano	Controls the relay and processes input
HC-05 Bluetooth Module	Communicates with Android device
Relay Module (5V)	Switches electrical devices ON/OFF
Android Smartphone	Captures and sends voice commands
Android App	Converts speech to control commands

 System Features:
Wireless control via Bluetooth

Voice-activated switching of appliances

Simple and scalable for multiple devices

Cost-effective and beginner-friendly

No need for internet or cloud service

 Inputs and Outputs:
Voice Command	Arduino Input	Device Action
"Light on"	'1'	Turns ON relay/device
"Light off"	'0'	Turns OFF relay/device

 Software Involved:
Arduino IDE – to program the Arduino

Android Voice App – to capture and send voice commands

Examples: Arduino Voice Control, Bluetooth Terminal with Google Voice Typing

Optional: MIT App Inventor – to create your own app

 Communication Method:
Bluetooth (HC-05) handles the wireless communication between Android and Arduino.

 Applications:
Smart home automation

Touchless device control (useful for elderly or disabled)

Classroom/lab automation

Voice-controlled lighting/fans

# Fingerprint-Enrollment-and-Authentication-System

*This project implements a fingerprint enrollment and authentication system using an Arduino and an R305 fingerprint sensor. The system allows users to enroll their fingerprints and authenticate their identity based on the enrolled fingerprints.*

Installation:

  To get started with the project, ensure you have the necessary libraries installed. The primary libraries used in this project are *Adafruit_Fingerprint* and *SoftwareSerial*. These can be installed via the Arduino Library Manager.

Hardware Requirements:

  Arduino board (e.g., Arduino Uno)
  R305 fingerprint sensor
  Connecting wires
  
Project Structure:

  The project consists of the following files:

  Enrollment.cpp: Contains the code for enrolling fingerprints.
  Authentication.cpp: Contains the code for authenticating fingerprints.
  Template_Extraction.cpp: Contains the code for extracting fingerprint templates.
  
Libraries:

The following libraries are used in this project:

    #include <Adafruit_Fingerprint.h>
    #include <SoftwareSerial.h>
    
Usage:

Set up Arduino: Connect the R305 fingerprint sensor to the Arduino board using the appropriate pins.

Enroll Fingerprints: Upload Enrollment.cpp to the Arduino to enroll new fingerprints. Follow the instructions provided by the serial monitor to complete the  enrollment process.

Authenticate Fingerprints: Upload Authentication.cpp to the Arduino to authenticate fingerprints. Place a finger on the sensor to verify if it matches any    enrolled fingerprints.

Extract Fingerprint Templates: Use Template_Extraction.cpp if you need to extract and manage fingerprint templates for further processing or storage.

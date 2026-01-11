# 📏 Distance Measurement System

## 📌 Project Overview

This project is a **Touch-Activated Ultrasonic Distance Measurement System** built using **Arduino Uno**.  
The system measures the distance of an object **only when the user touches a touch sensor**, and displays the measured distance on a **16×2 LCD**.

This approach avoids continuous sensing, saves power, and provides a **modern, user-friendly interface**.

----------

## 📝 Project Description

The project uses an **ultrasonic sensor (HC-SR04)** to measure the distance of nearby objects by transmitting and receiving ultrasonic sound waves.  
A **touch sensor (TTP223)** is used as an input trigger, allowing the user to initiate distance measurement manually.  
The calculated distance is displayed on a **16×2 LCD**, making the system easy to use and understand.

This project demonstrates **sensor interfacing, embedded system control, and real-time data display** using Arduino.

----------

## 🎯 Features

-   Touch-based activation (no physical button)
    
-   Accurate distance measurement using ultrasonic sensor
    
-   Real-time distance display on LCD
    
-   Power-efficient (on-demand measurement)
    
-   Simple and scalable design. 

----------

## 🧰 Components Used

-   Arduino Uno
    
-   Ultrasonic Sensor (HC-SR04)
    
-   Touch Sensor (TTP223)
    
-   16×2 LCD Display
    
-   Breadboard
    
-   Jumper Wires
    

----------

## 💻 Software & Tools Used

-   Arduino IDE
    
-   Embedded C / Arduino Programming Language
    
-   USB Cable (for programming Arduino)
    
-   GitHub (for version control and documentation)
    

----------

## ⚙️ Working Principle

1.  The system remains idle and displays **“Touch to Start”** on the LCD.
    
2.  When the user touches the touch sensor:
    
    -   Arduino activates the ultrasonic sensor.
        
    -   Ultrasonic waves are transmitted and received.
        
    -   The time taken for the echo is measured.
        
3.  Distance is calculated using the time delay.
    
4.  The calculated distance is displayed on the LCD.
    

----------

## 🧠 Algorithm

1.  Start the system
    
2.  Initialize LCD, ultrasonic sensor, and touch sensor
    
3.  Display **“Touch to Start”** on LCD
    
4.  Wait for touch sensor input
    
5.  If touch detected:
    
    -   Trigger ultrasonic sensor
        
    -   Measure echo duration
        
    -   Calculate distance
        
    -   Display distance on LCD
        
6.  Return to idle state
    
7.  Repeat
   

----------

## ▶️ How to Run the Project

1.  Connect all components according to the circuit diagram
    
2.  Open Arduino IDE
    
3.  Select **Arduino Uno** and correct COM port
    
4.  Upload the provided Arduino code
    
5.  Power the Arduino
    
6.  Touch the touch sensor to measure distance
    
7.  View the distance on the LCD
    

----------


## 🎯 Expected Outcomes

-   Accurate measurement of object distance in centimeters
    
-   User-controlled distance sensing using touch input
    
-   Reduced unnecessary sensor operation
    
-   Improved understanding of Arduino sensor interfacing

----------

## 🏫 Applications

-   Digital distance meter
    
-   Object detection system
    
-   Parking assistance system
    
-   Robotics obstacle measurement
    
-   Smart sensing devices
    

----------

## ✅ Advantages

-   Touch-based user control
    
-   Power-efficient operation
    
-   Accurate distance measurement
    
-   Clear LCD display output
    
-   Simple and low-cost design

-----

## 🚀 Future Improvements

-   Add buzzer or LED for distance alerts
    
-   Multiple measurement modes using long/short touch
    
-   Bluetooth-based distance monitoring
    
-   Battery-powered portable version
    

----------

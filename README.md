# Inventory 360 – Smart Kitchen Inventory Control using IoT (ESP8266)

An IoT-based embedded system designed to monitor grocery stock levels and humidity inside storage containers using sensors and WiFi-enabled communication.

This project solves a real-life problem of unnoticed grocery depletion and food spoilage due to humidity by implementing real-time monitoring and automated email alerts.

# Problem Statement

In homes and commercial kitchens, groceries often run out without notice and food items get spoiled due to excess humidity inside containers. Manual checking leads to poor inventory planning, food waste, and unnecessary expenses.


## Oposed Solution

A smart kitchen inventory system using:

-Load Cell + HX711 to measure grocery quantity
- DHT11 to monitor humidity inside container
- ESP8266 for processing and WiFi communication
- Threshold logic to detect understock and humidity rise
- Automated email alerts to notify users

## System Architecture

The system consists of two sensor-equipped containers continuously sending data to ESP8266. When sensor readings cross predefined thresholds, alerts are triggered via email.

##  Hardware Components

 ESP8266 : WiFi-enabled microcontroller 
 HX711: Load cell amplifier 
 Load Cell:Weight measurement
 DHT11 : Humidity sensing 

## Software Used

- Arduino IDE
- Embedded C++
- ESP8266 WiFi libraries
- Sensor interfacing libraries

##  Key Features

- Real-time grocery weight monitoring
- Humidity monitoring to prevent spoilage
- Threshold-based automation
- IoT email alert system
- Low-cost implementation (₹1140)


##  Applications

- Smart homes
- Restaurants and commercial kitchens
- Food storage monitoring

## Learning Outcomes

- Sensor interfacing with ESP8266
- Handling real-time sensor data
- Implementing threshold logic
- IoT communication using WiFi
- Practical embedded system design for real-world problems

##  Future Improvements

- Mobile app notifications
- Cloud data logging
- Monitoring multiple containers
- Predictive inventory analysis


##  Author

Ritika Milind Gawade  
B.Tech ENTC | Embedded Systems & IoT
